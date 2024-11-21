
# Notes Manager 📒  

A full-stack Notes Manager application built using the MERN (MongoDB, Express, React, Node.js) stack. This project enables users to manage their notes efficiently with a modern, responsive interface.

---

## ✨ Features  

- **Create Notes**: Add new notes with a title and description.  
- **Read Notes**: View a list of all your saved notes.  
- **Update Notes**: Edit the content of existing notes.  
- **Delete Notes**: Remove unwanted notes with ease.  
- **User Authentication**: Secure login and registration using JWT.  
- **Responsive Design**: Optimized for both desktop and mobile users.  

---

## 🛠️ Technologies Used  

- **Frontend**:  
  - React.js  
  - Tailwind CSS / CSS for styling  

- **Backend**:  
  - Node.js  
  - Express.js  

- **Database**:  
  - MongoDB (NoSQL database for storing notes and user information)  

- **Authentication**:  
  - JSON Web Tokens (JWT)  

---

## 🚀 Getting Started  

Follow the steps below to set up the project locally:

### Prerequisites  

- [Node.js](https://nodejs.org/)  
- [MongoDB](https://www.mongodb.com/)  
- [Git](https://git-scm.com/)  

### Installation  

1. **Clone the repository:**  
   ```bash  
   git clone https://github.com/username/notes-manager.git  
   cd notes-manager  
   ```  

2. **Install backend dependencies:**  
   ```bash  
   cd back-end-notes-manager 
   npm install  
   ```  

3. **Install frontend dependencies:**  
   ```bash  
   cd ../frontend-notes-manager  
   npm install  
   ```  

4. **Set up environment variables:**  
   - Create a `.env` file in the `backend` directory with the following keys:  
     ```env  
     PORT=5000  
     MONGO_URI=your_mongodb_connection_string  
     JWT_SECRET=your_jwt_secret  
     ```  

5. **Start the backend server:**  
   ```bash  
   cd backend  
   npm start  
   ```  

6. **Start the frontend development server:**  
   ```bash  
   cd ../frontend  
   npm start  
   ```  

7. Open your browser and navigate to `http://localhost:3000`.

---

## 📝 Usage  

- Register or log in to your account.  
- Create, read, update, and delete notes from your dashboard.  

---




