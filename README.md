# Clinic Management Database

## Objective
This project is a **Clinic Booking System database schema** built with **MySQL**.  
It models a simple clinic with **patients, doctors, appointments, and treatments**.

---

## Schema Overview
- **Patients** → Stores patient details.  
- **Doctors** → Stores doctor details and their specialization.  
- **Appointments** → Links patients with doctors and stores booking info.  
- **Treatments** → Records treatment details for each appointment.  

### Relationships
- One patient can book many appointments.  
- One doctor can attend many appointments.  
- One appointment can have many treatments.  

---

## How to Run
1. Open MySQL Workbench or your terminal.
2. Run:
   ```sql
   SOURCE clinic_management.sql;

