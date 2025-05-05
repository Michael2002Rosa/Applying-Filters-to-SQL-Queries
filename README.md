# 🔍 SQL Security Analysis Project

## Project Description  
In my role as a security analyst, I utilized SQL queries with filters to detect potential security breaches and assist with system maintenance. This project highlights my skills in analyzing data to uncover anomalies and support IT operations through targeted database queries.

---

## Security Investigations

### 1. Retrieve After Hours Failed Login Attempts  
**Objective**: Identify suspicious login activity outside business hours.  

![ALT](https://i.imgur.com/KxEHPEa.png)

To investigate potential threats, I focused on login attempts that occurred after 6:00 PM and were unsuccessful. Using SQL filters, I queried the data to locate failed logins happening after regular working hours, combining conditions on login time and success status.

---

### 2. Retrieve Login Attempts On Specific Dates  
**Objective**: Investigate login activity related to a particular security event.

![ALT](https://i.imgur.com/Ub9ToPF.png)

I examined login attempts made on May 9, 2022, and the day before to pinpoint any unusual patterns. My approach filtered the data by specific dates to isolate activity that could be linked to the reported incident.

---

### 3. Retrieve Login Attempts Outside Of Mexico  
**Objective**: Detect potentially unauthorized access from foreign locations.  

![ALT](https://i.imgur.com/qSkG2jd.png)

This query focused on filtering out login attempts that did not originate from Mexico. I used SQL’s pattern matching to exclude entries where the location code or name indicated a Mexican origin, ensuring all other geographic login attempts were surfaced for further analysis.

---

### 4. Retrieve Employees In Marketing  
**Objective**: Identify Marketing department staff in a specific office for system updates.  

![ALT](https://i.imgur.com/PIFryzO.png)

To prepare devices for a software update, I targeted employees working in the Marketing department located in the East building. By using filters on department and office location, I generated a list of relevant personnel.

---

### 5. Retrieve Employees in Finance or Sales  
**Objective**: Find employees from either the Finance or Sales departments.  

![ALT](https://i.imgur.com/4hDPmZb.png)

For another round of system updates, I needed data on staff from both the Finance and Sales teams. The query employed logical filtering to return any employees who belonged to either of these two departments.

---

### 6. Retrieve All Employees Not in IT  
**Objective**: Isolate employees outside of the Information Technology department.  

![ALT](https://i.imgur.com/oQCt3ZW.png)

To finalize updates, I gathered information on all employees who were not part of the IT department. This required filtering the employee data to exclude entries where the department matched Information Technology.

---

## Summary  
In this project, I used SQL filtering techniques to extract critical information from login records and employee databases. I worked with multiple logical operators like AND, OR, and NOT, along with pattern matching using LIKE and wildcard symbols. These tools helped me carry out targeted data retrievals that supported security analysis and system maintenance efforts.

---

## 📜 License  
This project is part of the [Google Cybersecurity Certificate](https://www.coursera.org/professional-certificates/google-cybersecurity).  

---

