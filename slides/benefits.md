## Benefits

### Compartmentalization
* Presentation code requires different skills and knowledge to domain code.

### Maintainability
* Presentation logic and domain logic are easier to understand when separate.
* It allows extensive alteration to the presentation without affecting underlying functionality.

### Testability
* UI and Persistence (DB) can be hard to test, separation makes automated testing of Domain logic easier.
* Supports Unit Test Isolation.

### Extensibility
* You can support multiple presentations without duplicating code.
* You can easily add a programmatic API for scripting or exposed as services (E.g. Service Layer as presentation).

note:
    Put your speaker notes here.
    You can see them pressing 's'.
