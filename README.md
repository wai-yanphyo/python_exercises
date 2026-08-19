# python_exercises
Python Exercises
flowchart LR

    A["🛒 E-Commerce Source Data<br/>Products<br/>Brands<br/>Categories<br/>Orders"] 
        --> B["🥉 Bronze Layer<br/>Raw Data<br/>Delta Tables"]

    B --> C["🥈 Silver Layer<br/>Data Cleaning<br/>Deduplication<br/>Transformation<br/>Data Quality"]

    C --> D["🥇 Gold Layer<br/>Business-Ready Data<br/>Dimensions<br/>Fact Tables<br/>Aggregations"]

    D --> E["📊 Analytics<br/>SQL Queries<br/>BI Dashboards<br/>Business Insights"]

    subgraph Bronze["Bronze"]
        B
    end

    subgraph Silver["Silver"]
        C
    end

    subgraph Gold["Gold"]
        D
    end
