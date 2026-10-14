# BRÅ – samlad och standardiserad statistik

Statistik från Brottsförebyggande rådet i lättillgängliga format, sammanställd av NordicIntel.

**250 färdigställda dataset.** [Fillista med namn, format och nedladdningslänkar](manifest.csv) · [Bläddra efter tabell](KATALOG.md).

## Hämta data

| Format | Nedladdning |
|---|---|
| JSON-stat, samtliga dataset | [ZIP](https://github.com/nordicintel/BRA-samlad-och-standardiserad-statistik/releases/download/data-2026-10-15/jsonstat-datasets.zip) |
| CSV med kategorikoder, samtliga dataset inklusive SOL | Uppladdning pågår – se [fillistan](manifest.csv) |
| CSV med läsbara kategorietiketter, samtliga dataset inklusive SOL | Uppladdning pågår – se [fillistan](manifest.csv) |
| Parquet, enskilda tabeller | [Hugging Face](https://huggingface.co/datasets/nordicintel/BRA-samlad-och-standardiserad-statistik) |
| Källkopplingar, cellbeslut och granskningsresultat | [Proveniens, ZIP](https://github.com/nordicintel/BRA-samlad-och-standardiserad-statistik/releases/download/data-2026-10-15/provenance.zip) |

[Om värden och korrigeringar](DATA.md).

## Originalfiler

De insamlade originalfilerna finns i [källfilsutgåvan](https://github.com/nordicintel/BRA-samlad-och-standardiserad-statistik/releases/tag/kallfiler-2026-10-14):

| Material | Nedladdning | Källadresser |
|---|---|---|
| 3 875 arbetsböcker | [ZIP, 166 MB](https://github.com/nordicintel/BRA-samlad-och-standardiserad-statistik/releases/download/kallfiler-2026-10-14/bra-source-workbooks.zip) | [Filmanifest](https://github.com/nordicintel/BRA-samlad-och-standardiserad-statistik/releases/download/kallfiler-2026-10-14/sources-manifest.json) |

Arbetsboksarkivet innehåller också sitt källmanifest. [SOL:s källadresser och frågeurval](https://github.com/nordicintel/BRA-samlad-och-standardiserad-statistik/releases/download/kallfiler-2026-10-14/sol-source-manifest.jsonl.gz) bevaras; råa SOL-svar distribueras inte.

## Innehåll

Statistik om brott, misstänkta personer, lagföring, kriminalvård och återfall samt Brås statistiska undersökningar. Materialet omfattar de insamlade källtabellerna och de tidsserier som ingår i dem.

Tabeller sammanförs utifrån Brås presentationer. Dimensioner och kategorier standardiseras med hänsyn till mått, population och statistisk betydelse. Saknade värden och felmarkeringar i källorna bevaras uttryckligen.

## Källa och användning

Källa: [Brottsförebyggande rådet (Brå)](https://bra.se/statistik). Detta är en oberoende bearbetning av NordicIntel, inte en officiell publicering från Brå.

Brås löpande publicerade statistik får vidareutnyttjas fritt, utan avgifter eller villkor. Läs [Brås information om vidareutnyttjande](https://bra.se/om-bra/om-webbplatsen/data-fran-bra).

