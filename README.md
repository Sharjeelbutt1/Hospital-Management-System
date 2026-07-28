# 🏥 Hospital Management System

A console-based Hospital Management System built in C++, developed to apply core object-oriented programming principles in a practical, multi-module application with persistent file storage.

## Features

**Patient Management**
- Register a new patient
- Search for a patient
- Update patient records
- Delete a patient

**Doctor Management**
- Add a doctor
- Search for a doctor
- Display all doctors

**Appointment Management**
- Book an appointment, with validation and conflict-checking
- Cancel an appointment
- View a patient's appointments

## Key Concepts Applied

- **Encapsulation** – patient, doctor, and appointment data is kept private and accessed only through controlled member functions
- **Inheritance** – shared attributes and behavior across entities are factored into a common base class
- **Polymorphism** – virtual functions allow entity-specific behavior to be overridden where needed
- **Exception Handling** – invalid input, missing records, and file errors are caught and handled at runtime
- **File Handling** – patient, doctor, and appointment records are stored in files, so data persists between runs

## Project Structure

```
Hospital-Management-System/
│
├── main.cpp
├── patient.h
├── patient.cpp
├── patientmanager.h
├── patientmanager.cpp
├── doctor.h
├── doctor.cpp
├── doctormanager.h
├── doctormanager.cpp
├── appointment.h
├── appointment.cpp
├── patient.txt
├── doctor.txt
├── appointment.txt
└── README.md
```
## Author

Sharjeel Butt

