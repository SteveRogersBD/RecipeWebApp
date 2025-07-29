# 🍽️ RecipeHub — A Modern Recipe Web Application

RecipeHub is a full-stack web application that allows users to browse, search, and manage a collection of curated recipes from around the world. Designed with modern UI/UX principles and built using cutting-edge technologies, RecipeHub offers a seamless experience for both casual cooks and culinary enthusiasts.

---

## 📖 Description

RecipeHub provides an intuitive platform for discovering, sharing, and organizing recipes. The application supports user authentication, recipe categorization, and personalized recipe saving. It is built with a responsive frontend using React and a robust backend powered by Spring Boot, ensuring scalability and maintainability.

---

## ✨ Features

- 🔍 **Search Recipes:** Filter recipes by name, category, ingredients, or cuisine.
- 🍳 **Detailed Recipe View:** View step-by-step instructions, cooking time, ingredients, and images.
- 🧾 **User Authentication:** Register, log in, and manage personal accounts.
- ❤️ **Save Favorites:** Users can bookmark their favorite recipes.
- ✍️ **Add & Edit Recipes:** Authenticated users can contribute and update recipes.
- 📱 **Responsive Design:** Mobile-first UI with cross-device compatibility.
- 🌐 **API Integration:** Uses modern RESTful APIs for seamless data interaction.

---

## 🛠️ Technologies Used

### Frontend
- **React.js**
- **Tailwind CSS**
- **JavaScript (ES6+)**
- **Axios** (for API calls)
- **Vite** (development bundler)

### Backend
- **Java + Spring Boot**
- **Spring Security (JWT Authentication)**
- **Spring Data JPA**
- **MySQL** (relational database)
- **RESTful API Design**

### DevOps & Tooling
- **Docker** (optional containerization)
- **Postman** (API testing)
- **Git + GitHub** (version control)
- **Maven** (backend dependency management)

---

## ⚙️ Setup Instructions

### ✅ Prerequisites
- Node.js (v18+)
- Java 17+ (recommended: Amazon Corretto or OpenJDK)
- MySQL Server
- Maven (if not included with IDE)
- Git

---

### 1️⃣ Frontend Setup

```bash
# Clone the repository
git clone https://github.com/your-username/recipehub.git
cd recipehub/frontend

# Install dependencies
npm install

# Start the development server
npm run dev 
```

### 2️⃣ Backend Setup
```bash
# Navigate to backend folder
cd ../backend

# Configure database (application.properties or .yml)
spring.datasource.url=jdbc:mysql://localhost:3306/recipehub
spring.datasource.username=your_username
spring.datasource.password=your_password

# Run the application
./mvnw spring-boot:run
```

## 🤝 Contribution Guidelines

We welcome contributions from the community! To contribute:

1. Fork the repository  
2. Create a new branch  
   ```bash
   git checkout -b feature/your-feature
   ```
3. Commit your changes  
   ```bash
   git commit -m "Add your message"
   ```
4. Push to the branch  
   ```bash
   git push origin feature/your-feature
   ```
5. Open a **Pull Request**

---

### 🧑‍💻 Code Style

- Follow standard **Java conventions** for backend.
- Use **Prettier** + **ESLint** for consistent frontend formatting.
- Write clear, concise **commit messages**.
- Include **comments** where necessary for complex logic.

---

### 🐞 Issues & Discussions

- Use [Issues](https://github.com/your-username/recipehub/issues) to report bugs or suggest new features.
- Join the conversation in [Discussions](https://github.com/your-username/recipehub/discussions) if enabled.

---

## 📄 License

This project is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for details.

---

## 🙌 Acknowledgments

- Inspired by the joy of home cooking.
- Thanks to open-source libraries and the developer community!

