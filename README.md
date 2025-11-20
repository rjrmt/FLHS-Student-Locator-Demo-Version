## FLHS Student Locator – Testing Tools

**FLHS Student Locator** is a lightweight web application designed to help Fort Lauderdale High School quickly locate students and manage classroom changes during testing windows.  
It is optimized for fast lookups, simple deployment, and ease of use by teachers, proctors, and administrators.

---

### Features

- **Student Room Locator**  
  Look up a student and instantly see their assigned testing room using the locator page.

- **Room Change Dashboard**  
  View classroom relocations and updated testing locations on a dedicated room-changes page.

- **CSV-Driven Data**  
  Student and room assignments are sourced from a CSV file (`data/demo-data.csv`), making it easy to update schedules without touching the code.

- **Simple Static Deployment**  
  The project runs as a static site (HTML, CSS, JavaScript) and can be hosted on any static host (e.g. Netlify, GitHub Pages, school web server).

---

### Tech Stack

- **Frontend**: HTML5, CSS3, vanilla JavaScript  
- **Data**: CSV file for student and room data  
- **Tooling**: `live-server` for local development

---

### Project Structure

- `index.html` – Landing page / entry point  
- `pages/locator.html` – Student locator interface  
- `pages/room-changes.html` – Classroom relocation / room changes view  
- `data/demo-data.csv` – Sample data for testing and demonstration  
- `assets/logo.png` – Fort Lauderdale High School branding asset  
- `_headers` – Optional configuration for static hosting platforms (e.g. Netlify)  
- `LICENSE` – MIT license for this project  
- `package.json` – Project metadata and development scripts

---

### Getting Started (Local Development)

**Prerequisites**

- Node.js and npm installed on your machine

**Install dependencies**

```bash
npm install
```

**Run the project locally**

```bash
npm start
```

This will start `live-server` on port `8080` and open `index.html` in your browser.

---

### Usage Notes

- Replace `data/demo-data.csv` with real testing data before deployment.  
- Ensure that student information is handled in accordance with **school and district privacy policies**.  
- This repository is intended as a **demo and portfolio project**; adapt it to your production environment and security requirements.

---

### About the Author

Created by **RJ Ramautar** as a practical tool for Fort Lauderdale High School testing operations and as a professional portfolio project.  

If you found this helpful or would like to collaborate, feel free to connect with me on LinkedIn and reference this repository.

---

### License

This project is licensed under the **MIT License**. See the `LICENSE` file for details.

