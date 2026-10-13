# Library Management System Requirements

## 1. Purpose

The Library Management System is a desktop application designed to manage library operations, including books, members, users, borrowing, returns, and reports.

The application is being developed as a Visual Programming course unit project.

## 2. User Roles

The system will support the following roles:

### Administrator
- Manage system users.
- Manage books and book copies.
- Register and manage library members.
- View borrowing and return records.
- Manage fines and library settings.
- Generate reports.

### Librarian
- Register and update members.
- Manage book records where authorized.
- Issue books to members.
- Process returned books.
- View borrowing records.
- Search library information.

### Member
- View available books where the interface permits.
- Search the library catalogue.
- View personal borrowing records where implemented.

Access must be restricted according to each user's assigned permissions.

## 3. Functional Requirements

### Authentication
- Users must log in using valid credentials.
- Users must be able to log out.
- Passwords must not be stored as plain text.
- Invalid login attempts must be handled safely.

### Book Management
- Add new books.
- Update book information.
- View and search books.
- Track individual book copies.
- Track whether copies are available or borrowed.

### Member Management
- Register library members.
- View member details.
- Update member information.
- Search for members.
- Prevent invalid or incomplete records.

### Borrowing
- Record book loans.
- Associate each loan with a member and a book copy.
- Record borrowing and due dates.
- Prevent unavailable copies from being issued.

### Returns
- Record returned books.
- Update copy availability.
- Identify overdue returns.
- Calculate fines according to approved library rules, if fines are enabled.

### Reports
- Display borrowing and return records.
- Show available and borrowed copies.
- Provide useful library summaries.
- Support printing or exporting reports where implemented.

## 4. Non-Functional Requirements

### Security
- Use secure password hashing.
- Validate user input.
- Use parameterized SQL queries.
- Enforce authorization checks.
- Protect database credentials.

### Reliability
- Handle database errors gracefully.
- Avoid inconsistent borrowing and return records.
- Validate data before saving it.

### Usability
- Provide a clear login screen.
- Use consistent forms and navigation.
- Display understandable validation messages.
- Make common library operations easy to perform.

### Maintainability
- Separate the user interface from business logic and database access.
- Use clear naming conventions.
- Document important implementation decisions.
- Test features before integration.

## 5. Technology Stack

- Language: VB.NET
- User Interface: Windows Forms
- Backend: VB.NET Class Library
- Database: MySQL
- Version Control: Git and GitHub

## 6. Acceptance Criteria

The project will be considered functionally complete when the agreed features have been implemented and tested.

The team should demonstrate:
- Successful authentication.
- Correct book and member management.
- Accurate borrowing and return records.
- Correct availability tracking.
- Appropriate permissions for different user roles.
- Reliable database operations.
- Useful reports.
- Clear documentation and a successful demonstration.

## 7. Scope Management

The team should agree on the final feature set before implementing additional functionality.

Any changes to these requirements should be discussed, documented, and coordinated with the team leader.