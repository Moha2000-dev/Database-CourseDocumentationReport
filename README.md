#  Database Course Documentation

This repository contains a comprehensive report and visual mind map for a database documentation task,
developed as part of a course assignment. It covers fundamental database concepts, comparisons, roles,
and modern technologies in database systems.

---
##  Contents
- `Database_Report.md` – The main detailed report.
- `DBMS_MindMap.png` – Mind map illustrating the advantages of DBMS.
---
##  Topics Covered

- Flat File Systems vs Relational Databases
- DBMS Advantages (Mind Map)
- Roles in a Database System
- Types of Databases (Relational, Non-Relational, Cloud, etc.)
- Cloud Storage and Database Integration
- Database Engines and Query Languages
- Cross-Engine Database Migration
- Logical vs Physical Database Schemas

---



/////////////////////////////////////////////////////////////////////////////////////////////////////second file /////////////////////////////////////////////////////////
# How Big Data Systems Work

This document explores how modern big data systems operate, focusing on the types of databases used by major companies, video games, military applications, e-commerce platforms, and banking institutions.

---

## 1. Databases Used by Popular Companies

| Company     | SQL Database      | NoSQL Database     |
|-------------|-------------------|--------------------|
| Instagram   | PostgreSQL        | Cassandra          |
| Uber        | MySQL             | MongoDB, Redis     |
| Amazon      | Aurora (SQL)      | DynamoDB           |

### Why Hybrid Database Structures?
- **SQL**: Great for structured data like user profiles, transactions.
- **NoSQL**: Best for high-volume, unstructured or real-time data.

---

## 2. Use of SQL Server in Industry

**Example:**  
- **Microsoft** uses SQL Server heavily, especially within Azure.
- **Banks and Government Agencies** prefer SQL Server for:
  - Security
  - Integration with Microsoft tools
  - Robust transaction handling

---

## 3. Databases in Video Games

### Database Use in Games:
- **SQL**: For structured data like player accounts, rankings.
- **NoSQL**: For unstructured, fast-changing data like chat, events.

**Example:**  
- **League of Legends** uses **MySQL** to manage player stats and match history.

---

## 4. Offline Database Systems

### Where Used?
- Military bases
- Submarines
- Airplanes

### Offline Databases:
- **SQLite**
- **SQL Server**
- **Oracle**

**Features**: Fully offline-capable, secure, and reliable for operational tasks.

---

## 5. SQL Server Offline Capabilities

- **Can SQL Server work offline?** Yes.
- Functions without internet access for all essential tasks.
- Internet only required for:
  - Cloud integration
  - Remote backups
  - Updates

---

## 6. Data Organization in E-commerce (Amazon/Noon)

### Techniques Used:
- **Indexing**
- **Caching**
- **Partitioning**
- **Metadata-based Search**

### Types of Databases:
- **SQL (e.g., MySQL, PostgreSQL)** for structured data
- **NoSQL (e.g., DynamoDB, Cassandra)** for user behavior, reviews

### Challenges:
- Speed with massive data
- Data duplication
- Scalability
- Secure and consistent checkout

---

## 7. Databases in Banking

### How Banks Use Databases:
- Store sensitive info: account data, balances, transaction history
- Deployed on secure, private servers

### Key Features:
- **RBAC** (Role-Based Access Control)
- **Encryption**
- **Audit logs**
- **ACID Compliance**

**Examples**:
- **Oracle**: Used by Bank of America
- **SQL Server**: Used by Emirates NBD (Middle East)

---

## 8. Architecture Layers of a Big Data System

1. **Client (User Interface)**:  
   Browser or app interface that sends user input to the server.

2. **Application Server (Logic Layer)**:  
   Handles business logic, processes requests, connects to the database.

3. **Database Server (Data Layer)**:  
   Stores and retrieves structured/unstructured data.

---

## Summary

Big data systems rely on a mix of SQL and NoSQL technologies tailored to their domain needs. From gaming to e-commerce to defense, the key is choosing the right tools for performance, security, and scalability.

