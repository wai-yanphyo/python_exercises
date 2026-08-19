# python_exercises
Python Exercises

flowchart TD
    A["Raw E-Commerce Data<br/>CSV / Source Files"]
    
    B[" BRONZE<br/>Raw / Ingested Data<br/>Delta Tables"]
    
    C[" SILVER<br/>Cleaned & Structured Data<br/>Data Quality + Standardisation"]
    
    D[" GOLD<br/>Business-Ready Data<br/>Dimension & Fact Tables"]
    
    E[" Dashboard / Analytics<br/>Business Insights"]

    A --> B
    B -->|"Cleaning & Standardisation"| C
    C -->|"Business Transformations"| D
    D --> E
