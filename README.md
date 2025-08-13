Part 1: Coding Challenge (1 to 2 hours)
Dynamic Form Builder Application
Overview
Create an Angular application for building and managing dynamic forms with permission
controls. Please upload your code to GitHub with a README and share the repository
link with us. If any requirement proves challenging to implement within the time
constraint, document your approach and reasoning in the README.md file.
Requirements
1. Form Builder Interface
o Create a drag-and-drop interface for building forms with different field
types:
 Text input (single-line and multi-line)
 Dropdown select (with configurable options)
 Checkbox groups
 Date picker
 Radio button groups
o Each field should have configurable properties:
 Field label
 Required/optional setting
 Help text
 Validation rules (min/max length, pattern, etc.)

2. Form Management
o List view of created form templates
o Ability to edit existing templates
o Preview mode to test forms
3. Form Submission
o Form filling interface for end-users
o Validation based on the configured rules
o Submission to a mock API
o Success/error handling
o View submitted form data
4. Authorization
o Implement two user roles:
 Admin: Can create, edit, and delete form templates
 User: Can only view and fill out forms
o Authorization check on all relevant actions
o Login screen with role selection

Technical Requirements
 Angular 14+ with TypeScript

 Reactive Forms for form handling
 State management (NgRx preferred)
 Responsive design
 Unit tests for at least 2 key components
 Mock API service (no backend required)
