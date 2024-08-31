# Databases: A Study Note

## Defining Databases

- **Databases**: Computer structures that save, organize, protect, and deliver data.
- **Database Management System (DBMS)**: A system containing and managing databases.
  
### Basic Functions
- Organize data
- Quickly add, change, and update data

## 4 Types of Databases

### Text Databases
- **Description**: Simplest form, data organized in text files (rows and columns).
- **Example**: A file with names and contact details where each row represents a record.
- **Operations**: Update (edit lines), Delete (remove lines), Add (insert lines).

### Desktop Database Programs
- **Description**: Single-user databases with more complexity.
- **Examples**: Microsoft Excel, Microsoft Access.
- **Advantages**: Faster data changes, larger storage, better performance than text databases.

### Relational Database Management Systems (RDBMS)
- **Examples**: SQL Server, Oracle Database, MySQL.
- **Advantages**: Multiple-user access, advanced security, better overall performance.
- **Structure**:
  - **Tables**: Made of rows and columns.
  - **Schema**: Set of tables.
  - **Database**: Collection of schemas.

### NoSQL and Object-Oriented Databases
- **Description**: Do not use the table/row/column approach of RDBMS.
- **Advantages**: Simplified data retrieval, denormalized storage (large chunks).
- **Use Cases**: Large-scale data storage, high-speed retrieval.

## Normalization
- **Definition**: Breaking data into the smallest possible parts.
- **Purpose**: Efficient data sorting and management.
- **Example**: Storing first name and last name in separate fields.

## Database Categorization by Logical Design

### Operational Databases
- **Purpose**: Store everyday data with fast updates.
- **Examples**: Inventory databases, product databases.
- **Key Feature**: Transaction support for data integrity.
- **Uses**: High-speed write/read operations.

### Database Warehouses
- **Purpose**: Store and track multiple versions of the same data.
- **Example**: Storing current and past names of a person.
- **Advantage**: Analyzing business trends, long-term decision making.
- **Field**: Business intelligence.

## Example: Text Database
A Linux system example, stored in `/etc/passwd` file:
```plaintext
nobody:*:-2:-2:Unprivileged User:/var/empty:/usr/bin/false
root:*:0:0:System Administrator:/var/root:/bin/sh
daemon:*:1:1:System Services:/var/root:/usr/bin/false
