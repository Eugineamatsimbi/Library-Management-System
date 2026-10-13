# System Architecture

## 1. Overview

The Library Management System uses a three-layer architecture.

## 2. Presentation Layer

Project: `src/Library Management system/`

Technology: VB.NET Windows Forms.

Responsibilities:
- Login and Dashboard forms.
- Book and member management forms.
- Borrowing and return forms.
- Displaying information and validation messages.
- Collecting user input.

The frontend must not contain complex database operations.

## 3. Business Logic Layer

Project: `src/LibraryManagement.Core/`

Technology: VB.NET Class Library.

Responsibilities:
- Authentication and authorization logic.
- Book and member management rules.
- Borrowing and return validation.
- Fine calculations where applicable.
- Coordination between the frontend and database access code.

## 4. Database Layer

Location: `database/`

Technology: MySQL.

Responsibilities:
- Store users and roles.
- Store books and individual book copies.
- Store library members.
- Store borrowing and return records.
- Store fines and settings where applicable.

## 5. Application Flow

1. The user interacts with a Windows Forms screen.
2. The frontend calls the appropriate backend service.
3. The backend validates the requested operation.
4. The database layer executes parameterized SQL queries.
5. MySQL returns the result.
6. The backend returns a result to the frontend.
7. The frontend displays the outcome.

## 6. Development Rules

- Keep UI code separate from business logic.
- Keep database access in a dedicated component.
- Use parameterized SQL queries.
- Handle errors appropriately.
- Coordinate interface changes between frontend and backend developers.
- Test changes before merging them into the main branch.