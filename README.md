# Converting Between Data Types in SQL

© ExploreAI Academy

⚠️ **Important:**  
This notebook will not run on Google Colab because it cannot connect to a local database. Please ensure this notebook is executed on the same local machine as your MySQL Workbench installation and the `united_nations` database.

## 🧠 Learning Objectives

In this notebook, you will learn how to:

- Use the `CAST()` function to convert values from one data type to another.
- Understand when and why data type conversion is necessary in SQL.
- Retrieve data in a different format than how it is stored in the database schema.

## 📋 Overview

Every column in a SQL database has a data type defined by its schema. When querying the database using a `SELECT` statement, data is returned in its native type. However, there are cases where data type conversion is needed for:

- Formatting purposes  
- Mathematical operations  
- Joining fields of different types  
- Preparing data for display or export  

This notebook walks through examples of how to use the `CAST()` function effectively in SQL.

## 🗃️ Data Source

We are working with the `Access_to_Basic_Services` table from the `united_nations` database. This dataset contains various indicators related to countries, such as GDP, population estimates, and access to basic services.

## 🖥️ Requirements

- MySQL Workbench installed and running
- The `united_nations` database correctly set up on your local server
- This notebook must be executed in a local Jupyter environment (not Google Colab)

---

