# Architecture

```mermaid
classDiagram
    direction LR

    class Stepper {
        <<struct>>
        species: Species
        integrator: Box~dyn Integrator~
    }
```

