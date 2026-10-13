# Team Development Workflow

## 1. Main Branch

The `main` branch contains reviewed, stable code.

Do not commit directly to `main` during normal feature development.

## 2. Feature Branches

Each developer should work on a separate branch.

Branch naming examples:

- `feature/login-form`
- `feature/book-management`
- `feature/member-management`
- `feature/borrowing`
- `feature/database-schema`
- `feature/reporting`

## 3. Daily Workflow

1. Pull the latest changes.
2. Create a branch for your assigned task.
3. Implement your changes.
4. Test your work.
5. Commit using a descriptive message.
6. Push your branch to GitHub.
7. Open a pull request.
8. Request a review before merging.

## 4. Collaboration Rules

- Coordinate changes to shared files.
- Do not commit passwords or database credentials.
- Do not commit bin, obj, or .vs folders.
- Communicate blockers early.
- Do not merge untested changes.
- The team leader coordinates task assignments and integration.

## 5. Pull Requests

Each pull request should explain:
- What was changed.
- Why the change was necessary.
- How the change was tested.

## 6. Team Communication

Each member must know their assigned task, expected files, and dependencies before starting implementation.