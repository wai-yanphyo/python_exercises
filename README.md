# python_exercises
Python Exercises

```mermaid
flowchart TD

    A["Raw E-Commerce<br/>Data"]

    B["BRONZE<br/><br/>Raw / Ingested<br/>Data"]

    C["SILVER<br/><br/>Cleaned & Structured<br/>Data"]

    D["GOLD<br/><br/>Dimension & Fact<br/>Tables"]

    E["Dashboard /<br/>Analytics"]

    A --> B
    B -->|"Cleaning<br/>Standardisation"| C
    C -->|"Business<br/>Transformations"| D
    D --> E

    style A fill:none,stroke:#ffffff,stroke-width:1px,color:#ffffff
    style B fill:none,stroke:#ffffff,stroke-width:1px,color:#ffffff
    style C fill:none,stroke:#ffffff,stroke-width:1px,color:#ffffff
    style D fill:none,stroke:#ffffff,stroke-width:1px,color:#ffffff
    style E fill:none,stroke:#ffffff,stroke-width:1px,color:#ffffff
