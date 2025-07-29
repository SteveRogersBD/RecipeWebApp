
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
