Syntax:
==========

- Gebruik soft tabs met twee spaties i.p.v tabs. *(Dit is de enige manier om te garanderen dat de code hetzelfde word weergegeven in elke omgeving)*
- Wanneer je selectors groepeerd, hou dan elke selector bij in een enkele file.
- Voeg 1 spatie toe voordat je een declaratie opent. Dit verbeterd de leesbaarheid.
- Plaats de sluitings tekens van een declaratie op een nieuwe lijn.
- Voeg 1 spatie achter een `:` toe voor elke declaratie.
- Elke declaratie zou op in lijn nummer moete gezet worden voor een betere error melding.
- Eindig elke declaratie met een `;`
- Komma gescheiden waardes zouden een een spatie achter de waarde moete hebben.
- Include geen spatie achter komma's bij de volgende functies: `rgb()`, `rgba()`, `hsl()`, `hsla()` of `rect()` waardes
- Zorg ervoor dat dat waardes of kleur parameters die beginnen met een 0 geen 0 vanvoor bedragen.
- Gebruik geen hoofdletters in hex waardes.
- Gebruik korte hex waardes als je kan ipv van lange hex waardes.
- Quoteer alle html selectors. *(bv. `input[type=""text]`)*
- Voorkom dat je 0 waardes gaat gebruiken.

## Voorbeeld:

```css
/* Slecht voorbeeld */
.selector, .selector-secondary, .selector[type=text]
{
  padding:15px;
  margin:0px 0px 15px;
  background-color:rgba(0, 0, 0, 0.5);
  box-shadow:0px 1px 2px #CCC,inset 0 1px 0 #FFFFFF
}

/* Goed voorbeeld */
.selector,
.selector-secondary,
.selector[type="text"] {
  padding: 15px;
  margin-bottom: 15px;
  background-color: rgba(0,0,0,.5);
  box-shadow: 0 1px 2px #ccc, inset 0 1px 0 #fff;
}
```
