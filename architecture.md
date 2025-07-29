
---

## 🧰 Tech Stack

| Layer         | Technology                 |
|---------------|-----------------------------|
| Frontend      | React.js, Tailwind CSS      |
| Backend       | Spring Boot (Java)          |
| Database      | MySQL                       |
| Auth (opt)    | JWT (JSON Web Tokens)       |
| Container     | Docker, Docker Compose      |
| CI/CD         | GitHub Actions (planned)    |
| Deployment    | Localhost / Cloud (planned) |

---

## 📦 Folder Structure

```plaintext
recipe-app/
├── client/                # React frontend
│   ├── public/
│   └── src/
│       ├── pages/
│       ├── components/
│       ├── services/
│       └── App.jsx
├── server/                # Spring Boot backend
│   └── src/main/java/...
├── docs/                  # Documentation files
│   ├── architecture.md
│   ├── api-specs.md
│   └── product-vision.md
├── docker-compose.yml
├── README.md
└── .gitignore
```

## ⚙️ Component Responsibilities

### 🖥️ Frontend (React + Tailwind)

- Handles UI and UX
- Interacts with the backend via REST APIs
- Key pages: Home, Recipe List, Recipe Detail, Upload Recipe, Login/Register
- Uses Axios/Fetch for API calls

---

### 🔧 Backend (Spring Boot)

- Exposes secure REST endpoints
- Handles recipe CRUD, authentication, and user management
- Validates requests and interacts with the database
- (Optional) Uses Spring Security + JWT for authentication

---

### 🗃️ Database (MySQL)

- Tables: `users`, `recipes`, `ingredients`, `favorites`
- Relationships:
  - **One-to-many**: `user → recipes`
  - **Many-to-many**: `recipes ↔ ingredients`

---

## 📡 REST API Overview

| Method | Endpoint            | Description           |
|--------|---------------------|-----------------------|
| GET    | `/api/recipes`      | List all recipes      |
| GET    | `/api/recipes/{id}` | View single recipe    |
| POST   | `/api/recipes`      | Create new recipe     |
| PUT    | `/api/recipes/{id}` | Edit recipe           |
| DELETE | `/api/recipes/{id}` | Delete recipe         |
| POST   | `/api/auth/login`   | Login user            |
| POST   | `/api/auth/register`| Register new user     |

> See [`docs/api-specs.md`](./api-specs.md) for full API documentation.

---

## 🔐 Authentication (Optional Phase)

- Users log in with email and password
- JWT token is issued upon successful login
- Token must be sent in headers for protected API routes
- Spring Security handles role-based access control

---

## 🧪 Testing

| Layer     | Tools                     |
|-----------|---------------------------|
| Frontend  | React Testing Library, Jest |
| Backend   | JUnit, Mockito            |
| Manual    | Postman collection        |

---

## 🚢 Deployment Plan

### 🔧 Local Development

```bash
docker-compose up
```


