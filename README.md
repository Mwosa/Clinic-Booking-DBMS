# Clinic Booking System

## Project overview

The Clinic Booking System is a database solution designed to manage medical appointments, patient records, and clinic operations efficiently. This system is suitable for small to medium-sized medical clinics and doctors' offices.

## Features

- Manage patient profiles and information
- Track doctor credentials and specialties
- Schedule, modify, and cancel appointments
- Record medical diagnoses and treatments
- Manage medication prescriptions
- Find available doctors by specialty

## Database Schema

### Tables

1. patients - Stores patient information
2. doctors - Contains doctor profiles
3. specialties - Lists medical specialties
4. doctors_specialties - Maps doctors to specialties (many-to-many)
5. appointments - Records all appointment details
6. medical_records - Stores diagnoses and treatment plans
7. prescriptions - Contains medication details

## Entity Relationship Diagram (ERD)
![ERD](erd-image/clinic-erd-diagram.png)

## Setup instructions

### Option 1: Import from SQL file

Login to your MySQL server
mysql -u username -p

Create a new database
CREATE DATABASE clinic_booking;
USE clinic_booking;

Import the SQL file
source path/to/clinic_booking_system.sql

###Option 2: Using a GUI Tool (like MySQL Workbench)

Open MySQL Workbench
Connect to your MySQL server
Create a new schema named "clinic_booking"
Open the SQL file
Execute the script
