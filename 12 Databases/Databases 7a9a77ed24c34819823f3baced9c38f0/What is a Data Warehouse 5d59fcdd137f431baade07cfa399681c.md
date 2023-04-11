# What is a Data Warehouse

<aside>
⚠️ A **column-oriented data-store**, designed for **analytics workloads**

</aside>

Companies have lots of data and need a way to produce analytics reports. 

Warehouses generally perform **aggregations** on columns

Warehouses are optimised around columns since they need to aggregate columns fast

![If the data comes from a compatible source, you put it in the DB, else use ✨ETL✨ to get it in the right format](What%20is%20a%20Data%20Warehouse%205d59fcdd137f431baade07cfa399681c/Untitled.png)

If the data comes from a compatible source, you put it in the DB, else use ✨ETL✨ to get it in the right format

Data warehouses are designed to be **HOT**, meaning they can return queries fast even if they have lots of data

They are **infrequently accessed** meaning they aren’t meant for real-time reporting but rather accessing once a day, once a week etc for business and user reports etc

Warehouses consume data from relational DBs regularly, but keep in mind you need to transform it first