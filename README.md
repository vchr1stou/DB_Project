# Cooking Competition Database Project

This repository contains the complete implementation of a database system designed for managing and organizing a popular cooking competition. Developed as part of the Database Systems course at the School of Electrical and Computer Engineering, National Technical University of Athens (NTUA), this project encompasses the following features:

* **Detailed ER and Relational Diagrams**: Clearly structured diagrams illustrating entity relationships and relational database designs, ensuring comprehensive data integrity.

* **Database Management System**: Built using MySQL/MariaDB for robust performance, the database efficiently handles recipes, ingredients, equipment, chefs, and episode details required for managing competition logistics.

* **Rich Data Structure**: Stores extensive details including cooking recipes, pastry recipes, national cuisines, difficulty levels, meal categories (e.g., brunch, quick-lunch), dietary information, preparation steps, and cooking equipment guidelines.

* **Dynamic Nutritional Calculation**: Accurately computes nutritional details such as calories per serving dynamically based on recipe ingredients.

* **User Authentication and Management**: Implements role-based access control with two user roles:

  * **Admin**: Complete access to data management, database backup, and restore functionality.
  * **Chef**: Restricted to managing assigned recipes, personal information, and adding new recipes.

* **Competition Logic**: Automates episode management by randomly selecting cuisines, chefs, judges, and recipes, ensuring fairness and compliance with competition rules.

* **SQL Queries and Index Optimization**: Includes efficient SQL queries covering various analytical tasks, such as average chef ratings, recipe tags analysis, nutritional averages, chef participation tracking, and complex data retrieval scenarios. Strategic indexing enhances query performance.

* **Extensive Data Population**: Database includes over 50 recipes, 100 ingredients, 50 chefs, and details of at least 50 episodes to ensure meaningful query results and robust testing.

## Technology Stack

* **Database**: MySQL
* **Languages**: Python, SQL

