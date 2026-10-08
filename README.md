# Day 7 Git Project
## Project Structure

- `README.md` - Project documentation
- `app.txt` - Application information
- `status.txt` - Application status
- `health.txt` - Health check result
- `.gitignore` - Files ignored by Git

## Git Workflow

1. Created the project repository.
2. Created meaningful commits.
3. Created feature branches for changes.
4. Tested changes locally.
5. Pushed feature branches to GitHub.
6. Created Pull Requests.
7. Reviewed the changes.
8. Merged approved Pull Requests into `main`.
9. Pulled the latest changes locally.

## Production Incident Practice

A simulated Nginx 502 Bad Gateway incident was investigated using port checks, curl, Nginx status, and Nginx error logs. The issue was caused by the Python application being stopped. The application was restarted on port 3000 and verified through Nginx.

## Learning Outcome

This project demonstrates practical Git and GitHub workflow, including branching, commits, Pull Requests, code review, merging, and basic production troubleshooting.
