# Hospital Database Assessment (HPDM206Z)
- University of Exeter - MSc Health Data Science
- Computing Skills and Python
- Assessment 1: Hospital Database Project

## Project Overview

This repository contains the full contents to be submitted for Assessment 1 in the Computing Skills and Python module. The assignment involved designing, implementing, and querying a relational database in MySQL. The documents uploaded in this repository demonstrate the development of skills including use of GitHub, code planning using pseudocode and Entity Relationship Diagrams (ERDs), creation of MySQL databases, and writing MySQL queries to retrieve data from databases.

The hospital database I have created is streamlined to ensure that only relevant data is included and the tables I have created include 'Hospital', 'Doctors', 'Patients', and 'Prescriptions.' All planning documents and SQL queries have been included in the repository.

## Repository Structure

- hospital-database-assessment/
  - planning_docs/
    - Entity Relationship Diagram.xlsx
    - Pseudocode.pdf
    - Reference List.pdf

  - SQL/
    - SQL Queries.pdf

  - README.md
  
## Entity Relationship Diagram (ERD)

Location: /hospital-database-assessment/planning_docs/Entity Relationship Diagram.xlsx


The Entity Relationship Diagram for this assignment has been created using Microsoft Excel. It reflects the final database schema used in MySQL and aligns with all SQL queries used in the assignment. It evidences my understanding of the relationships between data contained within different tables and my awareness of the importance of removing unnecessary data.

Key Relationships:
- One Hospital < Many Doctors
- One Doctor < Many Patients
- One Doctor < Many Prescriptions
- One Patient < Many Prescriptions

## Pseudocode

Location: /hospital-database-assessment/planning_docs/Pseudocode.pdf


The pseudocode used in this assignment has been documented within Microsoft Word and exported as a PDF file. It reflects the final database schema and SQL query logic implemented in MySQL. I decided to amend the pseudocode following its implementation in MySQL as the outcomes change in light of new information. A narrative around those changes is available to read in the Short Report document.

Contents:
- Database Creation
- Table Definitions
- Data Loading from CSV Files
- Logical Steps for SQL Queries

## SQL Queries

Location: /hospital-database-assessment/SQL/SQL Queries.pdf


The SQL Queries document has been created using Microsoft Word and exported as a PDF file. This represents the finalised SQL queries used to extract the data required by the assignment. These include:

- All doctors who work a particular hospital.
- A list of prescriptions for a particular patient.
- A list of all prescriptions prescribed by a particular doctor.
- Adding a new patient to the database and registering with a doctor.
- Identifying which doctor made the most prescriptions.
- A list of doctors who work at the hospital with the most beds.

All SQL queries were tested in MySQL and outputs are included in the document.

## Use of Artificial Intelligence (Disclaimer)

Artificial intelligence was used in the completion of this assignment in accordance with University of Exeter guidance on use of generative AI. Microsoft co-pilot was used to aid learning, troubleshoot errors, develop ideas, aid understanding, provide feedback on my work, and assist with the planning and structure of this assignment. Hyperlinks to the main chat used to generate ideas is included in the reference list found in the planning_docs folder.

## Author
- James Kelly
- MSc Health Data Science
- University of Exeter
