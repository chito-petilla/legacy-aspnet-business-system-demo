# Legacy ASP.NET Business System Demo
Sample ASP.NET Web Forms business application demonstrating accounting and management system architecture.

A sample enterprise-style business management system built using ASP.NET Web Forms, C#, and SQL Server, demonstrating how traditional enterprise applications are structured, maintained, and extended in real-world legacy environments.

This project simulates a long-running business system commonly used in accounting, customer management, and financial transaction processing systems.

## Overview
This system demonstrates a multi-module business application with core enterprise features such as:
•User and customer management 
•Financial transaction processing 
•Basic reporting capabilities 
•Audit logging for system activity 
It follows a traditional layered architecture (Presentation → Business → Data → Database) commonly used in enterprise ASP.NET Web Forms applications.

## Architecture
The system is structured into the following layers:
•Presentation Layer (ASP.NET Web Forms) 
	o User interface for business operations 
	o Handles form submissions and page rendering 
•Business Layer (C#) 
	o Contains business rules and validation logic 
	o Processes customer and transaction workflows 
•Data Access Layer (ADO.NET) 
	o Handles communication with SQL Server 
	o Executes queries and stored procedures 
•Database Layer (SQL Server) 
	o Stores structured business data 
	o Supports transactional and reporting operations

## Functional Modules
•Customer Management (Create, Read, Update, Delete) 
•Financial Transactions (Debit/Credit simulation) 
•Basic Reporting (transaction summaries) 
•Audit Logging (system activity tracking) 
•Simple user interaction via Web Forms UI 

## Technologies Used
•ASP.NET Web Forms (.NET Framework) 
•C# 
•ADO.NET 
•SQL Server 
•JavaScript 
•HTML / CSS 

## Project Structure
legacy-aspnet-business-system-demo/
│
├── README.md
│
├── docs/
│   ├── architecture-diagram.png
│   ├── database-schema.png
│   └── screenshots/
│
├── source/
│   ├── BusinessLayer/
│   ├── DataLayer/
│   ├── Models/
│   ├── Utilities/
│   └── SamplePages/
│
└── sql/
    └── legacy-business-system.sql

## Engineering Highlights
•Layered enterprise architecture (UI / Business / Data separation) 
•ADO.NET-based data access implementation 
•SQL Server relational database design 
•Separation of business logic from presentation layer 
•Maintainable structure typical of legacy enterprise systems 
•Modular design for long-term system evolution

## Database Design
The system includes core relational tables:
•Customers – stores customer information 
•Transactions – records financial operations 
•AuditLogs – tracks system actions and changes 
All database operations are designed for structured querying and transactional integrity.

## Architecture Overview
This system follows a traditional enterprise workflow:
1.User interacts with ASP.NET Web Forms UI 
2.Business Layer processes logic and validation 
3.Data Layer executes SQL operations via ADO.NET 
4.SQL Server stores and retrieves structured data 
5.Results are returned to the UI for display 

## Purpose of This Project
This project demonstrates experience in:
•Maintaining and extending legacy ASP.NET systems 
•Designing layered enterprise architectures 
•Working with SQL Server and relational data models 
•Implementing business logic in C# 
•Understanding real-world enterprise application structures

## Notes
This is a sanitized and simplified demonstration version of a legacy enterprise system. Sensitive business rules and production-specific logic have been removed to protect confidentiality while preserving architectural design and structure.


