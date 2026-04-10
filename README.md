Here’s your **clean, professional, recruiter-level README.md** (polished, structured, and GitHub-ready):

---

````markdown
# 🚀 CivicResolve 🤝  
### Empowering Communities to Build Better Cities

Welcome to **CivicResolve** — a platform designed to bridge the gap between citizens and local authorities.

We believe that better cities are built through active citizen participation. CivicResolve makes it simple to report, track, and resolve civic issues like potholes, broken streetlights, and water leaks — all from one place.

---

## 🌐 Live Demo

- 🔗 **Frontend (Vercel):** https://civic-resolve-nx9n.vercel.app  
- 🔗 **Backend API (Render):** https://civicresole-backend-api.onrender.com  

> Note: Backend URL is the base API. Use valid endpoints to test functionality.

---

## 🌟 Key Features

### 👤 For Citizens
- Report issues with title, description, and category  
- Upload images as proof  
- Pinpoint location using interactive maps 📍  
- Track issue status in real-time  
- Provide feedback after resolution  
- Secure login (Email/Password + Google OAuth)  

---

### 🛡️ For Administrators
- Central dashboard to monitor all issues  
- Approve or reject reports  
- Assign tasks to contractors (based on location)  
- Manage users (citizens & contractors)  
- View analytics and reports  

---

### 👷 For Contractors
- View assigned issues  
- Update issue status (In Progress → Resolved)  
- Upload "after" images as proof  
- Manage profile and service areas  

---

## ⚙️ Tech Stack

### 🧠 Backend
- Java 21  
- Spring Boot 3  
- Spring Data JPA (Hibernate)  
- Spring Security + JWT Authentication  
- MySQL  
- Java Mail Sender  

---

### 🎨 Frontend
- React (Vite)  
- React Bootstrap  
- Framer Motion  
- Leaflet & React-Leaflet (Maps)  
- Chart.js  
- Google OAuth  

---

## 🛠️ Getting Started

### 📌 Prerequisites
- Java 21  
- Node.js 18+  
- MySQL  

---

### 🔧 Backend Setup

```bash
cd Backend/civicresolve-backend
````

1. Create MySQL database:

```
civicresolve
```

2. Configure:

```
src/main/resources/application.properties
```

Update:

```
spring.datasource.username=your_username
spring.datasource.password=your_password
```

3. Run:

```bash
./mvnw spring-boot:run
```

---

### 💻 Frontend Setup

```bash
cd Frontend/civicresolve-frontend
```

1. Install dependencies:

```bash
npm install
```

(If error:)

```bash
npm install --legacy-peer-deps
```

2. Create `.env` file:

```
VITE_GOOGLE_CLIENT_ID=your_google_client_id
```

3. Run app:

```bash
npm run dev
```

Open 👉 [http://localhost:5173](http://localhost:5173)

---

## 🔒 Security

* Passwords hashed using BCrypt
* JWT-based authentication
* Role-Based Access Control (RBAC)
* Environment variables for sensitive data

---

## 📸 Screenshots

> Add screenshots here:

* Dashboard
* Issue Map
* Login Page

---

## 📌 Future Enhancements

* Real-time notifications
* Mobile app version
* AI-based issue categorization
* Advanced analytics dashboard

---

## 🤝 Contributing

Contributions are welcome! Feel free to fork the repo and submit a pull request.

---

## 👨‍💻 Author

**Mahi Rusia**

* GitHub: [https://github.com/mahirusia123](https://github.com/mahirusia123)
* LinkedIn: [https://www.linkedin.com/in/mahirusia/](https://www.linkedin.com/in/mahirusia/)

---

## ⭐ Support

If you like this project, give it a ⭐ on GitHub!

---

### ✨ Happy Coding!

```

---

## 🔥 Why this README is 🔝 (important for you)
- Clean structure (recruiter-friendly)
- Proper sections (projects look professional)
- Shows **real-world skills**
- ATS + GitHub portfolio optimized

---

If you want next level:
✅ Add **badges (build, tech stack)**  
✅ Add **architecture diagram**  
✅ Make it **top 1% GitHub project**
```
