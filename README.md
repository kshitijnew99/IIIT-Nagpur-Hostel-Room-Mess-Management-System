IIIT Nagpur Hostel Room & Mess Management System

DBMS project made using MySQL to manage hostel room allocations, student details, mess attendance, monthly billing, and late entry logs at IIIT Nagpur.
The system tracks real-time room occupancy, prevents double allocations, records daily meals, and auto-generates mess bills for each student.

Screenshots of the query outputs:https://docs.google.com/document/d/1nqgf8VXeMj4c-bbCYqn2_Rzy0dn981Bmr2dkXtMip20/edit?usp=sharing

📁 Database Overview
Tables:

departments

students

rooms

staff

room_allocation

mess_attendance

mess_bill

late_entry

Extras:

Trigger: Automatically updates room occupancy when a student is allocated or vacates.

Procedure:

sp_allocate_room – Allocates a student only if the room has vacancy.

sp_generate_mess_bills – Generates monthly mess bills based on meals consumed.

View:

vw_monthly_mess_summary – Shows total meals per student for each month.

⚙️ How to Run

Open MySQL Workbench.

Run the schema.sql file to create all tables, triggers, procedures, and sample data.

Execute the queries at the bottom to view outputs.

🧠 Sample Queries

List rooms with capacity and current occupancy

Students with their active room allocation

Rooms that are fully occupied

Students not allocated any room

Mess attendance between two dates

Monthly mess summary for a given month

View all generated mess bills

Recent late entry logs

Rooms with vacancy

Department-wise student count

Author: Kshitij Rao Ranjan
B.Tech, IIIT Nagpur — DBMS Lab Project (2025)

Repo Name: iiitn-hostel-mess-management
