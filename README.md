# Exception Tracking System (ETS) - Hostetler Manufacturing

## Project Overview

The **Exception Tracking System (ETS)** was developed for Hostetler Manufacturing to replace their manual tracking of machine breakdowns with a computerized system. This README outlines the key components and steps involved in the project.

## Project Scope

### Objectives
1. **Create Data Entities**: Define the main entities required for the system, including their types and primary keys.
2. **Data Attribute Mapping**: Map data attributes to ensure accurate representation in the database.
3. **Entity Relationship Diagram (ERD)**: Design an ERD to illustrate the relationships between entities.
4. **Queries and Reports**:
   - Create two Query by Example (QBE) queries to generate specified reports.
   - Develop the reports based on these queries.
5. **Forms**:
   - Design two tabular forms for the entry/edit of Machine and Keyword tables.
   - Implement a QBE query and a form with a sub-form for Exception entry/edit.
6. **Menu Form**: Create a menu form for accessing all reports and forms, with an exit option for the application.

## Implementation Steps

### 1. Data Entities and Relationships
- **Entities**:
  - **Machine**: Primary Key: MachineID
  - **Exception**: Primary Key: ExceptionID
  - **Keyword**: Primary Key: KeywordID
  - **Maintenance Record**: Primary Key: RecordID
  
- **Relationships**:
  - Each Exception is linked to a specific Machine.
  - Keywords are linked to Exceptions for categorization.

### 2. Data Attribute Mapping
- Define attributes for each entity (e.g., MachineID, Description, Plant, Department for Machine; ExceptionID, Date, Description, and associated MachineID for Exception).

### 3. Entity Relationship Diagram (ERD)
- Create an ERD using a diagram tool to visualize entities and their relationships.

### 4. Queries and Reports
- **QBE Queries**:
  - **Open Exception Report**: Query for exceptions with no completion date.
  - **Machine History Report**: Query for maintenance history grouped by machine.
  
- **Reports**:
  - Generate reports based on the above QBE queries.

### 5. Forms Development
- **Tabular Forms**:
  - **Machine Table Entry Form**: For adding/editing machine information.
  - **Keyword Table Entry Form**: For adding/editing keywords.
  
- **Exception Entry/Edit**:
  - Create a QBE query for Exception entry/edit.
  - Develop a form with a sub-form for logging maintenance work associated with exceptions.

### 6. Menu Form
- Design a menu form that provides access to:
  - All reports.
  - Forms for entering/editing data.
  - An exit button to close the application.

## Conclusion
The ETS project aims to streamline Hostetler Manufacturing's exception tracking process by creating an organized, efficient system for logging and managing machine breakdowns. Through data entity mapping, report generation, and user-friendly forms, the ETS will improve operational efficiency and reduce downtime.

## Installation and Usage
- To set up the system, follow the instructions provided in the project documentation for connecting to the database and running the application.