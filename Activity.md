```plantuml
@startuml
(*) -up-> "Step 1"
-right-> "Step 2"
--> "Step 3"
--> "Step 4"
If "step is verbose" then
--> [Yes] "turn off verbosity"
--> "run"
else
--> "run"
Endif
-left-> (*)
@enduml
```
