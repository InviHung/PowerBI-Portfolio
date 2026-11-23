Power BI Portfolio

V tomto repozitáři jsou dva menší projekty, na kterých jsem si vyzkoušel práci v Power BI.

S Power BI jsem se poprvé setkal ve škole, kde jsem si vyzkoušel jeho základní funkce. První projekt jsem zaměřil na esport, konkrétně na League of Legends, který mě osobně zajímá.

Druhý projekt jsem vytvořil jako další praktickou ukázku práce s Power BI. Chtěl jsem si vyzkoušet něco, co je bližší reálnému využití Business Intelligence ve firmách, a zároveň si procvičit práci s datovým modelem, DAX a vizualizacemi.

1. LCK 2026 – ADC Scouting Analytics

Zdroj dat: Oracle's Elixir

Tento projekt vznikl v rámci mého zkoušení Power BI ve škole. Jelikož se zajímám o profesionální League of Legends, rozhodl jsem se pracovat se statistikami hráčů z korejské ligy LCK.

Cílem bylo vytvořit jednoduchý analytický report, který umožňuje porovnávat výkonnost jednotlivých ADC hráčů.

Projekt obsahuje dvě stránky:

ADC Overview

Přehled hráčů podle statistik Win Rate, KDA a Damage Per Minute. Zajímalo mě také, jestli existuje vztah mezi KDA a Win Rate, proto jsem vytvořil bodový graf s regresní přímkou.

ADC Scouting Profile

Druhá stránka umožňuje vybrat konkrétního hráče a podívat se podrobněji na jeho výkonnost. Obsahuje například statistiky z úvodních 15 minut hry, podíl na týmovém poškození, účast na killech a přehled odehraných šampionů.

Při práci jsem využil Power Query k úpravě dat a DAX k výpočtu jednotlivých statistik.

Analýza vychází z vybraných zápasů LCK Cup 2026. Samotné statistiky samozřejmě nepostihují všechny faktory, které ovlivňují výkon hráče.

2. Sales Performance Dashboard

Zdroj dat: Microsoft AdventureWorks

Druhý projekt jsem vytvořil jako praktickou ukázku práce s obchodními daty.

Chtěl jsem si vyzkoušet, jak by mohl vypadat jednoduchý report pro sledování obchodních výsledků společnosti.

Pracoval jsem s ukázkovým datasetem AdventureWorks od Microsoftu.

Nejdříve jsem si prošel strukturu dat a datový model. Zaměřil jsem se především na propojení faktové tabulky Sales s dimenzemi pomocí relací.

Následně jsem pomocí DAX vytvořil metriky pro výpočet tržeb, nákladů, hrubého zisku a marže.

Dashboard umožňuje:

Sledovat tržby, náklady a ziskovost společnosti.

Filtrovat výsledky podle fiskálního roku a měsíce.

Porovnávat měsíční a denní vývoj tržeb.

Analyzovat tržby podle produktových kategorií.

Porovnávat výsledky jednotlivých zemí.

Na tomto projektu jsem si chtěl především procvičit, jak fungují relace mezi tabulkami a jak se jejich prostřednictvím promítají filtry do jednotlivých vizualizací.

Použité technologie

Power BI Desktop – tvorba reportů a vizualizací.

Power Query – načítání a úprava dat.

DAX – výpočty vlastních metrik.

Datové modelování – práce s faktovými a dimenzionálními tabulkami.

Otevření projektů

Oba projekty jsou uložené ve formátu .pbix a lze je otevřít v Microsoft Power BI Desktop.

Zdroje dat

Microsoft AdventureWorks

Oracle's Elixir

Oba projekty beru především jako praktické procvičení Power BI. Jsem stále ve fázi učení, ale chtěl jsem si vyzkoušet práci s reálnějšími daty a vytvořit reporty, které mají konkrétní analytický účel.
