# Hospital Database Assessment (HPDM206Z)
- University of Exeter - MSc Health Data Science
- Computing Skills and Python
- Assessment 1: Hospital Database Project

## Project Overview

This repository contains the full contents to be submitted for Assessment 1 in the Computing Skills and Python module. The assignment involved designing, implementing, and querying a relational database in MySQL. The documents uploaded in this repository demonstrate the development of skills including use of GitHub, code planning using pseudocode and Entity Relationship Diagrams (ERDs), creation of MySQL databases, and writing MySQL queries to retrieve data from databases.

The hospital database I have created is streamlined to ensure that only relevant data is included and the final schema includes four tables: Hospital, Doctors, Patients, Prescriptions. All planning documents and SQL queries have been included in the repository.

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

Tables:
- Hospital: HospitalID, Name, Beds, Accreditation
- Doctors: DoctorID, Name, HospitalID
- Patients: PatientID, Name, DOB, DoctorID
- Prescriptions: PrescriptionID, DoctorID, PatientID, DrugName, DateIssued

## Pseudocode

Location: /hospital-database-assessment/planning_docs/Pseudocode.pdf


The pseudocode used in this assignment has been documented within Microsoft Word and exported as a PDF file. It reflects the final database schema and aligns perfectly with the final ERD and MySQL implementation. I decided to amend the pseudocode following its implementation in MySQL as the outcomes change in light of new information. A narrative around those changes is available to read in the Short Report document.

Contents:
- Database Creation
- Table Definitions
- Data Loading from CSV Files
- Logical Steps for SQL Queries

## SQL Queries

Location: /hospital-database-assessment/SQL/SQL Queries.pdf


The SQL Queries document has been created using Microsoft Word and exported as a PDF file. The SQL queries I have created meet each of the six tasks set out within assessment 1 guidance. All queries tested in MySQL have utilised the finalised database scheme. These include:

- All doctors who work a particular hospital.
- A list of prescriptions for a particular patient.
- A list of all prescriptions prescribed by a particular doctor.
- Adding a new patient to the database and registering with a doctor.
- Identifying which doctor made the most prescriptions.
- A list of doctors who work at the hospital with the most beds.

All SQL queries were tested in MySQL and outputs are included in the document.

## References

Location: /hospital-database-assessment/planning_docs/Reference List.pdf


The Reference List document contains a list of all resources used in the completion of the assignment, including those materials most pertinent to my learning in preparation for this assignment. This includes MySQL documentation, GitHub documentation, University of Exeter guidance, and a citation Microsoft Co-Pilot AI software which was used to support learning and completion of the assignment. All sources have been formatted in the Harvard referencing style.

## Use of Artificial Intelligence (Disclaimer)

Artificial intelligence was used in the completion of this assignment in accordance with University of Exeter guidance on use of generative AI. Microsoft co-pilot was used to aid learning, troubleshoot errors, develop ideas, aid understanding, provide feedback on my work, and assist with the planning and structure of this assignment.

Note: Copilot does not provide exportable or shareable links to AI outputs. All AI‑assisted outputs are incorporated directly into the submitted assignment documents in accordance with University of Exeter guidance.

## Author
- James Kelly
- Student Number: 760072671
- MSc Health Data Science
- University of Exeter


### GitHub Repository Link
https://github.com/jk861-healthdata/hospital-database-assessment/
