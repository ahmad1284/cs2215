```mermaid
erDiagram
    MTEJA |O--|| ORDER : places
    ORDER ||--|{ LINE-ITEM : contains
    MTEJA }|..|{ DELIVERY-ADDRESS : uses
```