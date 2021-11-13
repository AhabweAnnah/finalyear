
There are 4 types of user accounts. They include:
 
- Administrators (Super Admin & Admin)
- Coordinator
- Supervisor
- Student


**Requirements** 

Check Laravel 8 Requirements https://laravel.com/docs/8.x

**Installation**
- Install dependencies (composer install)
- Set Database Credentials & App Settings in dotenv file (.env)
- Migrate Database (php artisan migrate)
- Database seed (php artisan db:seed)

**Login Credentials**
After seeding. Login details as follows:

| Account Type  | Username             | Email | Password   |
| ------------- | --------             | ----- | --------   |
| admin         | ahabweannah@gmail.com|       |annah1234   | 
| student       | student@student.com  |       |isophel1997 |
#### **FUNCTIONS OF ACCOUNTS** 

**-- SUPER ADMIN**
- Only Super Admin can delete any record
- Create any user account
 
**-- Administrators (Super Admin & Admin)**

- Manage students courses
- Create, Edit and manage all user accounts & profiles
- Create, Edit and manage Exams & Grades
- Create, Edit and manage Subjects
- Notices are visible in calendar in dashboard
- Edit system settings
- Manages All other system users(supervisors, students)


**-- STUDENT**
- Views profile
- View own class subjects
- Views timetable
- View noticeboard and school events in calendar
- Manage own profile

**-- SUPERVISOR(not yet fully implemented)**
- Views profile
- View students progress
- Views timetable

**-- MISSING**
- student view;-being edited
- Supervisor;- view missing 
- coordinator;-interacting with all other views