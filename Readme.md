# Student Result Portal

This is a learning project to understand how a web browser fetches data using HTTP.

The project demonstrates why a local server is required instead of opening HTML files directly, and how JavaScript can fetch data from a JSON file when served over HTTP.

---

## Current Implementation

- Static website built using **HTML** and **JavaScript**
- Student result data stored in a **JSON file**
- Files are **served locally** using Python’s built-in HTTP server
- JavaScript uses `fetch()` to read JSON data and display results

---

## Project Structure
student-result-portal/
├── index.html
├── results.json


---

## How to Run the Project Locally

### Prerequisites
- Python installed on your system

### Steps
1. Clone the repository
2. Open a terminal / PowerShell in the project folder
3. Run the following command:python -m http.server 
4. Open your browser and go to: http://localhost:8000

## Purpose of This Project

This project is built step by step to understand:
- Difference between `file://` and `http://`
- Why browsers require a server for data fetching
- How static websites work
- Basics of frontend development without frameworks

---

## Planned Improvements

- Add multiple students
- Display subject-wise marks
- Improve UI to resemble a real marksheet
- Convert PDF result data into JSON
- Add backend and database in later stages

---

## Note

This is a learning-focused project. The repository will evolve as new concepts are added and understood.



