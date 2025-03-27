# Employee-Management-System-with-Bash-Script
This shell script implements a graphical Employee Management System using Zenity dialogs. It provides an intuitive interface for managing employee records across multiple departments, including special handling for terminated and retired employees. This system demonstrates how shell scripting can power real business applications with robust data management and user-friendly interfaces.

# Key Features
The system efficiently manages employee records across multiple departments, including Company Data, Finance, Human Resources, Operations, Marketing, and Information Technology, while also handling special categories such as fired and retired employees.

> Employee Record Options

Add Employees would auto-generate unique 5 digit IDs. Update records modifies exusting employee data while deeting employees result in removal and updating the fired.txt file. Search functionality is implemented by name or id of employee.

> HR Workflow Tools

Employees can be transferred between departments, and promotions are handled with special logic for leadership roles (e.g., "Head-of-" positions). When an employee is promoted to a head role, the system automatically processes pension details for the outgoing head and updates records accordingly.

> Technical Implementation

Data is stored in plain text files, with separate files for each department (company.txt, finance.txt, etc.), as well as archived records for terminated (fired.txt) and retired (retired.txt) employees.

> User Interface

The script includes input validation to ensure data integrity and provides a user-friendly Zenity-based GUI for all operations, making it accessible even for non-technical users.

# How to Use
To use the system, simply run the script in a Bash environment with Zenity installed. The menu-driven interface allows users to add, modify, search, and analyze employee data, while features like department-wise employee counts and promotion handling streamline HR workflows.

# Requirements
Bash shell environment.          
Zenity for dialog boxes.          
Standard Linux utilities (grep, sed, awk).          
