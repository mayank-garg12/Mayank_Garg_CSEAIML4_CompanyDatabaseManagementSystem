
# Company Management Dashboard

## 👥 Team Members

- **Mayank Garg** — Roll No: 2301730272  
- **Aarav Kumar** — Roll No: 2301730271  
- **Aditya Goyal** — Roll No: 2301730252

## 📄 Project Description

This is a browser-based **Company Management Dashboard** designed to manage and visualize data related to Employees, Machines, Projects, and Vehicles. The frontend provides CRUD (Create, Read, Update, Delete) capabilities with support for dynamic column addition/removal. It's structured to simulate basic database management system functionality without requiring a backend.

## 🎥 Video Explanation

[Watch the project explanation here](https://drive.google.com/file/d/1IrQYEQ3Am4MvN2wSCu-Wn6PWrL2Esrov/view?usp=drivesdk)

## 🛠️ Technologies Used

- **HTML5**
- **CSS3**
- **JavaScript (Vanilla)**

## ▶️ How to Run the Project

1. Download or clone this repository.
2. Locate the `FrontEnd_CDBMS.html` file.
3. Open the file in any modern web browser (e.g., Chrome, Firefox).
4. You will be prompted with a login screen. Use any numeric username and password (no validation is enforced).
5. Navigate through the sections using the sidebar:  
   - Dashboard  
   - Employees  
   - Machines  
   - Projects  
   - Vehicles

Each section allows you to:
- Add new entries (rows)
- Edit existing data
- Delete entries
- Add or remove columns dynamically

---

## ⚙️ Suggested Backend Integration (Optional/Future Scope)

If you wish to extend this project with backend functionality, follow these guidelines:

### 1. Stack Recommendation
- **Backend Framework:** Node.js with Express.js (or Python Flask/Django)
- **Database:** MongoDB (NoSQL) or MySQL/PostgreSQL (Relational)
- **Authentication:** JWT-based login for user validation

### 2. Proposed API Endpoints

| Method | Endpoint           | Description                  |
|--------|--------------------|------------------------------|
| POST   | `/login`           | Authenticate user credentials|
| GET    | `/employees`       | Fetch employee records       |
| POST   | `/employees`       | Add new employee             |
| PUT    | `/employees/:id`   | Update employee by ID        |
| DELETE | `/employees/:id`   | Delete employee by ID        |

> Repeat similarly for machines, projects, and vehicles.

### 3. Frontend Integration Tips

- Replace the current in-memory `data` and `columns` variables with API calls using `fetch()` or Axios.
- On page load, call `/employees` to populate the employee table.
- When adding or editing data, send POST/PUT requests accordingly.

---
