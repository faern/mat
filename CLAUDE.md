# Cooklang recipe repository

Recipes are written in cooklang. See [agent/cooklang-spec.md](agent/cooklang-spec.md) for the language specification.

## Validation

After editing any `.cook` file, run `./cook doctor` to verify correctness.

## Web server

Run `./cook server` to start the web UI at http://127.0.0.1:9080. Use it to visually verify changes like images and formatting.

## Cooklang pitfalls

- `~` is timer syntax in cooklang. Never use it to mean "ungefär/approximately". Use "ca" instead (e.g. "ca 1 cm" not "~1 cm").

## Taggar

När du skapar ett nytt recept från instruktioner/länk från användaren. Fråga alltid användaren "Gillade Blake denna mat?" med alternativen "Ja", "Nej" och "Vet inte". Om användaren svarar "Ja": Lägg till taggen "blakekompatibel" på receptet.
