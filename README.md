This project have following features.
Add new employees
List all employees
Edit employee details
Delete employees
Build a simple Employee Management System where you can:
Search & filter employees based on name or role
Sort employees based on name, age, or role
Tech Stack & Concepts
Frontend: AngularJS, Bootstrap for UI
Data Handling: AngularJS Services (to manage employee data)
Two-Way Data Binding: Use ng-model
Directives: ng-repeat, ng-click, ng-if, ng-show, ng-hide
Requirements
1. Employee List Page
Display a table of employees with the following columns:
Name
Age
Role (e.g., Developer, Designer, QA, Manager)
Actions (Edit, Delete)
Provide a search bar to filter employees by name or role
Provide a sorting option to sort employees by name, age, or role
2. Add/Edit Employee Page
A form with input fields for:
Name
Age
Role (Dropdown: Developer, Designer, QA, Manager)
Save Button: Add new employee or update existing one
Cancel Button: Redirect to employee list
3. Delete Employee
Clicking "Delete" should show a confirmation before removing the employee
4. Use a Service to Manage Employee Data
Create an EmployeeService to handle data storage (store in an array)
Fetch, Add, Update, and Delete employees using this service
Bonus (Optional Enhancements)
Local Storage: Store employees in localStorage so data persists on refresh
Custom Directive: Create a custom directive for the employee form
Expected Outcome
By completing this task, you'll gain hands-on experience with:
✔ Controllers & Services
✔ Data binding & event handling
✔ Using filters, sorting, and search in AngularJS
