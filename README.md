Employee Management System

🌐URL = https://melodious-frangollo-6993a8.netlify.app/

⚙️ 1. UML Diagram Symbols (Standard Software Symbols)

  Symbol              	 Meaning	Example                       Use
  ----------------------------------------------------------------------------------
  🧱 Rectangle	         Class / Entity	                      Employee, Department, Admin, Project
  -----------------------------------------------------------------------------------
  🔗 Line / Association	 Relationship between entities	      Employee → Department
  -----------------------------------------------------------------------------------
 🔺 Diamond	            Aggregation / Composition              Department has Employees
 -------------------------------------------------------------------------------------
  🟣 Oval           	Use Case (Action or Functionality)	   “Add Employee”, “View Salary”
  ---------------------------------------------------------------------------------------
  👤 Stick Figure     	Actor / User	                         Admin, Employee,HR
  -----------------------------------------------------------------------------------
  ⬛ Component Box	  Software Module	Frontend                  Backend, Database
  -----------------------------------------------------------------------------------
 📦 Cylinder          	Database	                           MySQL / MongoDB storage
 ------------------------------------------------------------------------------------------
  🡒 Arrow (→)	      Data flow or communication	           Frontend → Backend API
  ---------------------------------------------------------------------------------------
  🟩 Activity Box	   Step in workflow	                     Validate login, Fetch data


🧩 2. Entity–Relationship (ER) Diagram Symbols

  Symbol	                      Meaning	                          Example
  ---------------------------------------------------------------------------------
🟥 Rectangle	                  Entity	                        Employee, Department
----------------------------------------------------------------------------------------
🔵 Ellipse	                   Attribute	                      Emp_ID, Name, Salary
----------------------------------------------------------------------------------------
⬡ Diamond       	            Relationship	                    Works_In, Manages
------------------------------------------------------------------------------------
🔺 Underlined Text	          Primary Key	                      Emp_ID
------------------------------------------------------------------------------------
🔘 Oval with dashed line	    Derived Attribute	                Age (from DOB)
---------------------------------------------------------------------------------------
⚫ Line with crow’s foot	   One-to-many relationship	         Department → Employee


🖥️ 3. System Architecture Symbols (High-Level Design)

  Symbol	                             Description
  ------------------------------------------------------------------------------
💻 Frontend (React.js)	               User Interface – Employee Dashboard, Admin Panel
------------------------------------------------------------------------------------------
🌐 Backend (Spring Boot)	             REST APIs handling CRUD operations
-------------------------------------------------------------------------------------------
🗄️ Database (MySQL)	                   Stores employee, department, and payroll data
------------------------------------------------------------------------------------------
🔒 JWT Token	                         Used for authentication
----------------------------------------------------------------------------------------
📤 API Gateway	                      Routes frontend requests to backend
---------------------------------------------------------------------------------
🔁 REST Endpoints	                    /api/employees, /api/departments etc.


🧭 4. Common Functional Symbols

Function	   Symbol / Icon	     Description
-----------------------------------------------------
➕	            Add	             Add a new employee
---------------------------------------------------------
✏️	           Edit	             Update employee data
---------------------------------------------------------
🗑️            Delete	           Remove employee
-----------------------------------------------------------
👁️	          View	             See details
------------------------------------------------------------
🔍	          Search	           Search employees
---------------------------------------------------------------
🏢	          Department	        Manage departments
------------------------------------------------------------
💰	          Salary	            Manage payroll
--------------------------------------------------------
🔐	          Lock	              Secure login or authentication
-------------------------------------------------------------------
📊	          Report	            Generate performance reports
