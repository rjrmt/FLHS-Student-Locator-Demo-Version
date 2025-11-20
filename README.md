## FLHS Student Locator (Demo Version)

Fort Lauderdale High School Testing Tools – **demo** room locator and classroom relocation interface, sanitized for public portfolios (GitHub/LinkedIn) with no real student data.

### 📁 Project Structure

```
FLHS Student Locator (demo)/
├── index.html                      # Main landing page
├── assets/                         # Images and static assets
│   └── logo.png                    # FLHS logo
├── pages/                          # Application pages
│   ├── locator.html                # Student room locator demo
│   └── room-changes.html           # Sample room relocation information
├── data/                           # Demo data files
│   └── demo-data.csv               # Sample testing assignments (fake data)
├── package.json                    # Project configuration
├── package-lock.json              # Dependency lock file
└── node_modules/                   # Dependencies

```

### 🚀 Getting Started

### Prerequisites
- Node.js installed on your system

### Installation
```bash
npm install
```

### Running the Application
```bash
npm start
```

This will start a local server on `http://localhost:8080` and automatically open the application in your browser.

### 📋 Features

- **Test Room Locator (Demo)**: Search by demo student number (e.g., `10001`–`10005`) to see a sample testing assignment
- **Room Changes**: View a static example of classroom relocations for a test day
- **Bluebook Download**: Quick link to College Board's Bluebook application

## 📊 Data Files (Demo Only)

- `data/demo-data.csv`: Contains **fake** testing assignments with fields for:
  - Local ID (Student Number)
  - Student Name (First, Last)
  - Grade Level
  - Exam Type (FCLE)
  - Test Date and Time
  - Room Assignment

> In a real deployment, you would replace this demo file with your own secure data source and keep any real student data **out** of the public repository.

## 🎨 Design

Clean, professional interface with FLHS branding and blue color scheme.

---

**Designed by RJ Ramautar**

