# The "class" UML diagram type

This type is appropriate for describing program objects, their attributes, methods and the way objects (classes) interrelate to one another.

Example:

```
@startuml
class Dummy {
  +String data
  *void methods()
  ~non-void methods()
}

class Flight {
   -flightNumber : Integer
   departureTime : Date
   fly()
}
@enduml
```