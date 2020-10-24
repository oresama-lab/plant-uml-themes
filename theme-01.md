```puml
@startuml Sample Diagram

skinparam BackgroundColor DDDDDD
skinparam shadowing false
skinparam RoundCorner 7
skinparam ArrowColor 454645
skinparam FontColor 454645
skinparam SequenceLifeLineBorderColor 454645
skinparam SequenceGroupHeaderFontColor 454645
skinparam SequenceGroupFontColor 454645
skinparam SequenceGroupBorderColor 454645
skinparam SequenceGroupBorderThickness 1
skinparam participant {
    BackgroundColor FF6F61
    BorderColor FF6F61
    FontColor White
}
skinparam database {
    BackgroundColor 98DDDE
    BorderColor 454645
    FontColor 454645
}
skinparam entity {
    BackgroundColor FFDA29
    BorderColor 454645
    FontColor 454645
}
skinparam note {
    BackgroundColor LightGreen
    BorderColor LightGreen
    FontColor 454645
}

entity Client
participant Backend
participant Queue
database RDB
entity "External"

@enduml
```
