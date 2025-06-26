# Small Backend Project

This is a simple backend project built with **Node.js**, **Express.js**, and **EJS** (Embedded JavaScript).  
It demonstrates:

- How to set up an Express server
- How to render HTML using EJS
- How to create dynamic routes
- How to serve static files (like CSS)

---

## 🛠️ Tech Stack
- Node.js
- Express.js
- EJS (view engine)
- HTML/CSS

---

## 🚀 Features
- `GET /`  
  → Renders a page that shows `Hey 11` (the result of 8 + 3 using EJS)

- `GET /profile/:username`  
  → Displays a message like `Welcome, Koushik` dynamically

- Serves static files from the `public` folder (e.g., CSS)

---

## 📦 Prerequisites
- Node.js (v14 or later)
- npm (comes with Node.js)

---

## 🧑‍💻 How to Run Locally

### 1. Clone the repository
bash
git clone https://github.com/bkoushik11/Small-backend-project.git
cd Small-backend-project
### 2. Install dependencies
bash
Copy
Edit
npm install
### 3. Start the server
bash
Copy
Edit
node index.js
### 4. Open in your browser
http://localhost:3000 → shows "Hey 11"

http://localhost:3000/profile/YourName → shows "Welcome, YourName"

Dynamic route that greets the user
