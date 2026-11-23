
# Power BI Portfolio

V tomto repozitáři jsou dva menší projekty, na kterých jsem si vyzkoušel práci s Power BI.

S Power BI jsem se poprvé setkal ve škole, kde jsem si vyzkoušel jeho základní funkce. První projekt jsem zaměřil na esport, konkrétně na League of Legends, který mě osobně zajímá.

Druhý projekt jsem vytvořil jako další praktickou ukázku svých dosavadních zkušeností s Power BI. Chtěl jsem si vyzkoušet něco, co je bližší reálnému využití Business Intelligence ve firmách, a zároveň si procvičit práci s datovým modelem, DAX a vizualizacemi.

---

## 1. LCK 2026 – ADC Scouting Analytics

**Zdroj dat:** Oracle's Elixir

Tento projekt navazuje na moje první zkušenosti s Power BI ve škole. Jelikož se zajímám o profesionální League of Legends, rozhodl jsem se pracovat se statistikami hráčů z korejské ligy LCK.

Cílem bylo vytvořit jednoduchý analytický report, který umožňuje porovnávat výkonnost jednotlivých ADC hráčů.

### ADC Overview

První stránka slouží k celkovému porovnání hráčů.

Zaměřil jsem se především na:

- Win Rate – úspěšnost hráče.
- KDA – poměr killů a asistencí ke smrtím.
- DPM – způsobené poškození za minutu.

Zajímalo mě také, jestli existuje vztah mezi KDA a Win Rate. Proto jsem vytvořil bodový graf s regresní přímkou.

### ADC Scouting Profile

Druhá stránka funguje jako jednoduchý scouting report. Uživatel si může vybrat konkrétního hráče a zobrazit jeho statistiky.

Report obsahuje:

- Win Rate, KDA a DPM.
- Počet odehraných her.
- Gold Difference v 15. minutě (GD@15).
- CS Difference v 15. minutě (CSD@15).
- XP Difference v 15. minutě (XPD@15).
- Damage Share a Kill Participation.
- Přehled odehraných šampionů.

Při práci jsem využil Power Query pro filtrování a úpravu dat a DAX pro výpočty jednotlivých metrik.

Je potřeba brát v úvahu, že samotné statistiky nemusí objektivně vypovídat o kvalitě hráče, protože je ovlivňuje také síla týmu, výběr šampionů nebo herní styl.

Analýza se vztahuje k vybraným zápasům LCK Cup 2026, nikoliv k celé sezoně LCK.



## 2. Sales Performance Dashboard

**Zdroj dat:** Microsoft AdventureWorks

Druhý projekt jsem vytvořil jako praktickou ukázku práce s obchodními daty.

Chtěl jsem si vyzkoušet, jak by mohl vypadat jednoduchý dashboard pro sledování obchodních výsledků společnosti.

Pracoval jsem s ukázkovým datasetem AdventureWorks od Microsoftu.

### Datový model

Nejdříve jsem si prošel strukturu dat a jejich vzájemné vztahy.

Pracoval jsem s faktovou tabulkou Sales, která obsahuje informace o prodejích, a dimenzionálními tabulkami, například Product, Customer, Date nebo SalesTerritory.

Pomocí relací jsem propojil časovou dimenzi s prodejními daty, abych mohl sledovat obchodní výsledky podle jednotlivých období.

### DAX metriky

Pro analýzu jsem vytvořil tyto metriky:

- Total Revenue – celkové tržby.
- Total Cost – náklady na prodané produkty.
- Gross Profit – hrubý zisk.
- Gross Margin – hrubá marže v procentech.

### Sales Dashboard

Dashboard umožňuje:

- Sledovat celkové tržby, náklady a ziskovost společnosti.
- Filtrovat výsledky podle fiskálního roku a měsíce.
- Porovnávat měsíční vývoj tržeb.
- Sledovat denní tržby ve vybraném období.
- Analyzovat tržby podle produktových kategorií.
- Porovnávat tržby mezi jednotlivými zeměmi.

Na tomto projektu jsem si chtěl především procvičit práci s datovým modelem, relacemi mezi tabulkami a jejich vlivem na filtrování jednotlivých vizualizací.



## 3. Použité technologie

- **Power BI Desktop** – tvorba reportů a vizualizací.
- **Power Query** – načítání, filtrování a úprava dat.
- **DAX** – výpočty analytických metrik.
- **Datové modelování** – práce s faktovými a dimenzionálními tabulkami.
- **GitHub** – uložení a sdílení projektů.



## 4. Jak otevřít projekty

Oba projekty jsou uložené ve formátu `.pbix`.Jednotlivé soubory je možné stáhnout přímo z tohoto repozitáře a otevřít v Power BI Desktop.


---
## 5. Zdroje dat

- [Microsoft AdventureWorks – Power BI Samples](https://github.com/microsoft/powerbi-desktop-samples)
- [Oracle's Elixir – Esports Data](https://oracleselixir.com/)


## Závěrem

Oba projekty beru především jako praktické procvičení Power BI.

Jsem stále ve fázi učení, ale chtěl jsem si vyzkoušet práci s různými typy dat a vytvořit reporty, které mají konkrétní analytický účel.

První projekt se zaměřuje na oblast, která mě osobně zajímá, zatímco druhý na využití Business Intelligence při vyhodnocování obchodních výsledků.

