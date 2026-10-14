# BRÅ – samlad och standardiserad statistik

Statistik från Brottsförebyggande rådet i lättillgängliga format, sammanställd av NordicIntel.

**De bearbetade dataseten valideras inför publicering.** Originalfilerna finns redan att ladda ned nedan.

## Originalfiler

De insamlade originalfilerna finns i [källfilsutgåvan](https://github.com/nordicintel/BRA-samlad-och-standardiserad-statistik/releases/tag/kallfiler-2026-10-14):

| Material | Nedladdning | Källadresser och kontrollsummor |
|---|---|---|
| 3 875 arbetsböcker | [ZIP, 166 MB](https://github.com/nordicintel/BRA-samlad-och-standardiserad-statistik/releases/download/kallfiler-2026-10-14/bra-source-workbooks.zip) | [Filmanifest](https://github.com/nordicintel/BRA-samlad-och-standardiserad-statistik/releases/download/kallfiler-2026-10-14/sources-manifest.json) |
| 39 648 SOL-svar | [ZIP, 1,04 GB](https://github.com/nordicintel/BRA-samlad-och-standardiserad-statistik/releases/download/kallfiler-2026-10-14/sol-source-responses.zip) | [Fråge- och filmanifest, JSONL.gz](https://github.com/nordicintel/BRA-samlad-och-standardiserad-statistik/releases/download/kallfiler-2026-10-14/sol-source-manifest.jsonl.gz) |

[SHA-256 för nedladdningarna](https://github.com/nordicintel/BRA-samlad-och-standardiserad-statistik/releases/download/kallfiler-2026-10-14/SOURCE-SHA256SUMS.txt). Arkiven innehåller också sina manifest. Varje manifest länkar tillbaka till Brås källadress; SOL-manifestet anger även frågeurvalet.

## Innehåll

Statistik om brott, misstänkta personer, lagföring, kriminalvård och återfall samt Brås statistiska undersökningar. Materialet omfattar de insamlade källtabellerna och de tidsserier som ingår i dem.

Tabeller sammanförs utifrån Brås presentationer. Dimensioner och kategorier standardiseras med hänsyn till mått, population och statistisk betydelse. Saknade värden och felmarkeringar i källorna bevaras uttryckligen.

## Format

- **JSON-stat:** sammanförda tabeller med kategorier, enheter och källnoter.
- **Parquet:** tabeller för analys, med tillhörande metadata.
- **Originalfiler:** källarbetsböcker och svar från Statistik On-line (SOL), med källadresser och kontrollsummor.
- **Katalog och proveniens:** beskrivningar av dataset, sammanslagningar, källversioner och undantagna celler.

Läs [om värden, korrigeringar och källor](DATA.md).

## Källa och användning

Källa: [Brottsförebyggande rådet (Brå)](https://bra.se/statistik). Detta är en oberoende bearbetning av NordicIntel, inte en officiell publicering från Brå.

Brås löpande publicerade statistik får vidareutnyttjas fritt, utan avgifter eller villkor. Läs [Brås information om vidareutnyttjande](https://bra.se/om-bra/om-webbplatsen/data-fran-bra).

