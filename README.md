# Oracle-Apex-Developer-Assignment-Shaukat-Khanum-Memorial-Research-Centre
Develop a Basic HR Management Module in Oracle APEX Objective: To design and implement a simple HR module to manage employees, departments, and job positions using Oracle APEX and SQL. Database Design. 1. DEPARTMENTS Table 2. JOBS Table 3. EMPLOYEES Table ER Diagram (Structure Overview)

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
Assignment Details 
Home Screen
Dashboard
Total Department
Employee Report
Employee Vacancies
Job Form
Job Report

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
Department Table

select 
 DEPT_ID,
 DEPT_NAME,
 LOCATION,
 CREATED_DATE
 from DEPARTMENTS

EPT_ID	NUMBER	22	-	-	No
DEPT_NAME	VARCHAR2	100	-	-	No
LOCATION	VARCHAR2	100	-	-	Yes
CREATED_DATE	DATE	7	-	-	Yes

Job Table

select 
 JOB_ID,
 JOB_TITLE,
 MIN_SALARY,
 MAX_SALARY
 from JOBS

JOB_ID	NUMBER	22	-	-	No
JOB_TITLE	VARCHAR2	100	-	-	No
MIN_SALARY	NUMBER	22	10	2	Yes
MAX_SALARY	NUMBER	22	10	2	Yes

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
Employee Table

select 
 EMP_ID,
 FIRST_NAME,
 LAST_NAME,
 EMAIL,
 PHONE_NUMBER,
 HIRE_DATE,
 JOB_ID,
 DEPT_ID,
 SALARY
 from EMPLOYEES
------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
MP_ID	NUMBER	22	-	-	No
FIRST_NAME	VARCHAR2	50	-	-	Yes
LAST_NAME	VARCHAR2	50	-	-	Yes
EMAIL	VARCHAR2	100	-	-	Yes
PHONE_NUMBER	VARCHAR2	15	-	-	Yes
HIRE_DATE	DATE	7	-	-	Yes
JOB_ID	NUMBER	22	-	-	Yes
DEPT_ID	NUMBER	22	-	-	Yes
SALARY	NUMBER	22	10	2	Yes

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
Project Link

Project Details 

Session Link

https://oracleapex.com/ords/r/mitp1323/skmc-rc/login?session=112587577221781

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

Email: SAADNASIR108@GMAIL.COM

SAADNASIR108@GMAIL.COM

Workshop Link

workshop id: mitp1323

Email id: SAADNASIR108@GMAIL.COM


Password: 5ws8SAbN!.Y.2e_
