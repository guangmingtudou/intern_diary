This is a place for me to keep some diary

All the contents are verified by my supervisor and are permitted to be released online.

这是我存实习日记的地方

```mermaid
graph LR
    A[history data] --> B(correlation matrix)
    
    B --> E(inference matrix)
    C[rule] --> D(expert matrix)
    D --> E
    F((alarms)) --> G[predict]
    E --> G
    I --> J[expert]
    J --> C
    H --> I((alarm tree))
    G --> H((root cause))
    B -- expert --> C
    I --> A
```