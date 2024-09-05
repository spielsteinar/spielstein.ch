# Idee


# Model


``` mermaid
graph TD
    Person --->|hat|Spiel
    Event["Spielabend"]
    Person -->|nimmt teil an|Event
    Event -->|wird gespielt|Spiel
    Spiel -->|wird ausgeliehen an|Person
    Event -->|wird organisiert von|Person
```