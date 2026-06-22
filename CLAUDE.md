# Cooklang-receptarkiv

Recept skrivs i cooklang. Se [agent/cooklang-spec.md](agent/cooklang-spec.md) för språkspecifikationen.

## Validering

Efter att du redigerat en `.cook`-fil, kör `./cook doctor` för att verifiera att den är korrekt.

## Webbserver

Kör `./cook server` för att starta webbgränssnittet på http://127.0.0.1:9080. Använd det för att visuellt verifiera ändringar som bilder och formatering.

## Cooklang-fallgropar

- `~` är timer-syntax i cooklang. Använd det aldrig för att mena "ungefär". Använd "ca" istället (t.ex. "ca 1 cm" inte "~1 cm").

## Taggar

När du skapar ett nytt recept från instruktioner/länk från användaren. Fråga alltid användaren "Gillade Blake denna mat?" med alternativen "Ja", "Nej" och "Vet inte". Om användaren svarar "Ja": Lägg till taggen "blakekompatibel" på receptet.
