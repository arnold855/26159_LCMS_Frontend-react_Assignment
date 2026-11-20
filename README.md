# Legal Case Management System - LCMS

A Frontend web application for managing legal cases between lawyers and clients. Built with **React** (frontend) with data persisted in local JSON files.

---

##  Features

- **User Authentication** — Register and log in as a Lawyer or Client
- **Lawyer Dashboard** — Create and manage cases, update case statuses, view assigned clients
- **Client Dashboard** — View personal cases and their current status
- **Case Management** — Supports Civil, Criminal, Labour, and Corporate case types
- **Legal Tip Banner** — Rotating legal tips displayed across the app
- **Responsive UI** — Clean layout with Navbar, Footer, and Back-to-Top button

---

##  Project Structure

```
legal-case-management-system/
├── data/
│   ├── cases.json          # Persisted case records
│   └── users.json          # Persisted user records
├── public/
│   └── index.html
├── server/
│   └── server.js           # Express REST API (port 5001)
├── src/
│   ├── components/
│   │   ├── BackToTop.jsx
│   │   ├── Footer.jsx
│   │   ├── LegalTipBanner.jsx
│   │   └── Navbar.jsx
│   ├── pages/
│   │   ├── About.jsx
│   │   ├── Contact.jsx
│   │   ├── DashboardClient.jsx
│   │   ├── DashboardLawyer.jsx
│   │   ├── Home.jsx
│   │   ├── Login.jsx
│   │   └── Register.jsx
│   ├── styles/
│   │   └── GlobalStyles.jsx
│   ├── utils/
│   │   ├── api.jsx
│   │   ├── session.jsx
│   │   └── stats.jsx
│   ├── App.jsx
│   └── index.jsx
├── package.json
└── README.md
```

---

##  Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) (v16 or higher)
- npm

### Installation

1. Install dependencies:
   ```bash
   npm install
   ```

3. Start the app (runs both server and client):
   ```bash
   npm start
   ```

- React app runs on: `http://localhost:3000`
- Express API runs on: `http://localhost:5001`

---

##  Tech Stack

| Layer | Technology |
|-------|------------|
| Frontend | React 18, React Router v6 |
| Data Storage | Local JSON files (`data/`) |
| Dev Tools | concurrently |

---

## Author

**Arnold**
- GitHub: [@arnold855](https://github.com/arnold855)

---
