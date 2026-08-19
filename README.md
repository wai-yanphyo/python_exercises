# python_exercises
Python Exercises
## 🏗️ Medallion Architecture

The project follows the Medallion Architecture pattern, where data is progressively refined through Bronze, Silver, and Gold layers.

```mermaid
flowchart LR
    A[Source Data<br/>CSV / JSON / API] --> B[Bronze Layer<br/>Raw Data]
    B --> C[Silver Layer<br/>Cleaned & Transformed Data]
    C --> D[Gold Layer<br/>Business-Ready Data]
    D --> E[Analytics / BI<br/>Reports & Dashboards]
