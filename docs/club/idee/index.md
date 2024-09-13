# Idee

Unsere Idee einfach dargestellt ;-).

# Model
``` mermaid
graph TD
    Person --->|hat|Spiel
    Event["Spiel-Event"]
    Person -->|nimmt teil an|Event
    Event -->|wird gespielt|Spiel
    Spiel -->|wird ausgeliehen an|Person
    Event -->|wird organisiert von|Person
    Organisation["Verein Spielstein"]
    Event -->|wird organisiert von|Organisation
    Location["Veranstaltungs-Ort"]
    Event -->|findet statt bei|Location
```

## Schema.org

``` mermaid
graph TD
    Person --->|hat|Spiel
    Event["Spielabend(Event)"]
    Person -->|nimmt teil an|Event
    Event -->|wird gespielt|Spiel
    Spiel -->|wird ausgeliehen an|Person
    Event -->|wird organisiert von|Person
    Organisation["Verein Spielstein"]
    Event -->|wird organisiert von|Organisation
    Location["Veranstaltungs-Ort"]
    Event -->|findet statt bei|Location
```


## Notizen von Ideen

* QR-Code Scann mit direkt Link zu den Spiel-Daten bspw. https://spielstein.ch/spiele/dorfromantik/