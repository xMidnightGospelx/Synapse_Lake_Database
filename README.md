# Synapse Lake Database Repository

## Overview
This repository contains the necessary configurations, scripts, and notebooks to set up and manage the Synapse Lake Database environment. The database is named **RetailDB** and is designed to handle various retail-related data.

## Contents

### Linked Services
- `synapsea9ph7vk-WorkspaceDefaultSqlServer`: The default SQL server for the Synapse workspace.
- `synapsea9ph7vk-WorkspaceDefaultStorage`: The default storage account for the Synapse workspace.

### Integration Runtime
- `AutoResolveIntegrationRuntime`: The integration runtime used for data movement and transformation tasks.

### Database
- **RetailDB**: The main database containing all retail-related data.

### SQL Scripts
- `Create GBSales DB`: Script to create the GB Sales database.
- `GB - Query Sales CSV files`: Script to query sales data from CSV files.
- `SQL script 1`: Placeholder script.
- `Query Sales CSV files`: Another script to query sales data from CSV files.
- `GB - Create ProductSalesTotals table`: Script to create the `ProductSalesTotals` table.
- `GB - GetYearlySales`: Script to get yearly sales data.
- `XZ_script`: Custom script by user.
- `XZ_ScriptCreateTable`: Script to create a table.
- `SQLcreateTemplateScript`: Template script for SQL.
- `SQL Script SalesOrder`: Script to manage sales orders.

### Credentials
- `WorkspaceSystemIdentity`: Credential for the workspace system identity.

### Notebooks
- `OKL NoteBook SalesOrder`: Notebook for handling sales orders.
- `Notebook 1`: Placeholder notebook.

### Tables
- `Product`: Table containing product information.
- `Customer`: Table containing customer information.
- `SalesOrder`: Table containing sales order information.
- `XZGBSalesOrder`: Custom sales order table by user.

### Relationships
- `relationship-yqxghaufbw`: Relationship between two entities.
- `relationship-xmsqcykffb`: Another relationship between two entities.

## Getting Started
1. Clone the repository to your local machine.
2. Set up the linked services and integration runtime in your Synapse workspace.
3. Deploy the database and execute the SQL scripts in the given order.
4. Use the notebooks for data analysis and visualization.

## Contributing
Feel free to contribute by submitting pull requests. Please ensure your code adheres to the coding standards and includes necessary documentation.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.
