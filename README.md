# KK1 - Dataanalys av Arsenal FC-spelare

Det här projektet är min Kunskapskontroll 1 i kursen **Artificiell Intelligens - programmering Python**.

Projektet består av en Jupyter Notebook där jag analyserar Arsenal FC-spelare från 2000-talet och framåt med hjälp av:

- pandas
- numpy
- matplotlib
- seaborn

## Dataset

Datasetet finns i:

```text
data/arsenal_squad.csv
```

Det är en egen sammanställd CSV-fil baserad på offentlig spelarstatistik, främst från Wikipedia-listan över Arsenal FC-spelare:

```text
https://en.wikipedia.org/wiki/List_of_Arsenal_F.C._players
```

Varje rad representerar en spelare. Datasetet innehåller bland annat:

- namn
- nationalitet
- positionsgrupp
- år i klubben
- starter
- inhopp
- totalt antal matcher
- mål
- om spelaren fortfarande är aktiv i Arsenal

Datasetet är ett urval och ska därför inte ses som en komplett historisk databas över alla Arsenal-spelare.

## Notebook

Analysen finns i:

```text
notebook.ipynb
```

Notebooken innehåller:

- inläsning av CSV-data
- mekanisk inspektion med `shape`, `info()` och `describe()`
- datatvätt
- filtrering med boolean masking
- gruppering med `groupby`
- enkel användning av NumPy
- fyra visualiseringar
- reflektioner kring resultaten

## Köra projektet

Projektet använder `uv` och en lokal virtuell miljö.

För att köra notebooken:

1. Öppna projektet i VS Code.
2. Öppna `notebook.ipynb`.
3. Välj kernel/miljö `kk1-python`.
4. Kör notebooken uppifrån och ner, eller välj **Restart** och sedan **Run All**.

## Syfte

Syftet är att visa grundläggande färdigheter i dataanalys med Python:

- läsa in och undersöka data
- tvätta och förbereda data
- använda pandas och NumPy
- skapa visualiseringar med matplotlib och seaborn
- skriva en tydlig och följbar notebook med reflektioner
