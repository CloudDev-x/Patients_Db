# Healthcare Patient Records Management System

## Project Overview

The **HealthcarePatientDb** is a relational database designed to manage patient records efficiently within a healthcare facility. This system provides structured storage for patient information, doctor details, departments, and state data. It enables healthcare professionals to easily access and update patient records, track department and doctor assignments, and maintain accurate healthcare data.

The database is structured to store critical patient details like age, gender, doctor assignments, and location information, facilitating smooth patient management and reporting.

## Database Structure

- **Patient Table**: Stores detailed information about patients, including their ID, name, age, gender, assigned doctor, and state.
- **Doctor Table**: Contains information on healthcare professionals, their specializations, and the departments they belong to.
- **Department Table**: Keeps track of different medical departments within the hospital.
- **Statemaster Table**: Provides a reference for the states where patients and doctors are located.

## Technologies Used

- **SQL**: Database creation, management, and querying.
- **Data Analysis**: To ensure efficient handling of patient information.
- **Database Optimization**: Techniques used for effective query performance and storage management.

## Features

- Fetch patient details based on various criteria such as age, doctor, or department.
- Maintain records for multiple departments and their associated doctors.
- Built-in stored procedures to handle patient data updates and retrieval.
- Error-handling mechanisms for database operations.

## Key SQL Functionalities

- Fetch patients with the same age.
- Find the second oldest patient and their doctor and department.
- Retrieve the maximum age per department and the associated patient name.
- Doctor-wise patient count, sorted in descending order.
- Stored procedures to update patient age by department and doctor.
- A stored procedure to fetch comprehensive patient details including their doctor, department, and state.

## Use Case

This database can be used by hospitals, clinics, and other healthcare providers to manage patient records, ensure smooth operational workflows, and support data-driven healthcare decisions.

