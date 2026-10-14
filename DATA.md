# Om datamaterialet

Tabellerna sammanförs efter Brås presentationer och väljarfamiljer. Skillnader i population, mått, period och statistisk betydelse bevaras även när kategorier har liknande namn. SOL:s sju ämnen exporteras var för sig.

## Värden och kategorier

JSON-stat innehåller dimensionernas ordning, kategorikoder, etiketter och noter. Kategorikoder identifierar kategorier; etiketter är avsedda för visning. Följ respektive tabells mått och enheter när värden jämförs.

En saknad position i en gles tabell är inte automatiskt en observation med värdet noll. Ett uttryckligt nullvärde och dess statusmarkering ska tolkas tillsammans med tabellens källnoter. Markeringars betydelse kan skilja sig mellan källor.

## Korrigeringar

Belagda formateringsfel rättas i det publicerade materialet. Ursprunglig text, datatyp, filversion och cellkoordinat bevaras i proveniensen. Exempel är upphöjda fotnoter som fastnat i tal, dubblerade textfragment och ett källspecifikt sätt att skriva nollsiffror.

Två äldre procentceller har rättats till 1 procent med stöd av täljare, nämnare och samma avrundningsregel i resten av källtabellen. Dubbleringen `....` har rättats till källans definierade `..`-markering.

45 procentceller har divisionen 0/0 i källan och bevaras därför som odefinierade värden med markeringen `#DIV/0!`. En källcell innehåller `c` utan förklaring i källmaterialet; markeringen bevaras uttryckligen utan gissat tal.

## Källversioner och spårbarhet

Originalfilerna levereras med SHA-256-kontrollsummor och källadresser. Datasetkatalogen och proveniensen kopplar publicerade dataset till deras källfiler. För granskade publiceringsrevisioner framgår vilken version som används och vilka äldre värden som ersatts.

Cellgranskningen omfattar även rubriker, etiketter, hjälpberäkningar och tomrader med numerisk utfyllnad. Antalet granskade celler är därför inte ett mått på felaktiga observationer. Undantagna celler har källbaserade förklaringar.
