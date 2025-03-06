# **Realtime Collaborative Code Editor**  

A **Realtime Collaborative Code Editor** built with **Express**, **Socket.IO**, and **React**. Multiple users can join a room, write code together, and see changes in **real-time**. The code can be executed, and the output is displayed to all users in the room.  

## **Features**  
✅ Real-time collaborative coding with multiple users  
✅ Code execution with shared output  
✅ Language selection for different programming languages  
✅ Room-based collaboration with unique session IDs  
✅ Seamless UI with a modern frontend  

---

## **Project Structure**  

```
collaborative_code_editor/
│── backend/          # Express.js server
│── frontend/         # React-based UI
│── package.json      # Backend dependencies
│── README.md         # Project documentation
```

---

## **Prerequisites**  

Ensure you have the following installed before proceeding:  

- **Node.js** (v14 or higher)  
- **npm** (v6 or higher)  

---

## **Installation**  

### **1. Clone the Repository**  
```sh
git clone https://github.com/rajneeshkabdwal4/collaborative_code_editor.git
cd collaborative_code_editor
```

### **2. Install Dependencies**  

#### Install backend dependencies:  
```sh
npm install
```

#### Install frontend dependencies:  
```sh
cd frontend
npm install
cd ..
```

---

## **Running the Project**  

### **1. Build the Frontend**  
```sh
npm run build
```

### **2. Start the Backend Server**  
```sh
npm start
```
Alternatively, start the backend server with **nodemon** for automatic restarts on file changes:  
```sh
npm run dev
```

---

## **Usage**  

1. Open your browser and navigate to **[http://localhost:5000](http://localhost:5000)**.  
2. Enter a **room ID** and your **name** to join a collaborative session.  
3. Start coding and see changes in **real-time** with other users in the same room.  
4. Use the **language selector** to switch programming languages.  
5. Click the **"Execute"** button to run the code and view the output.  

---

## **Future Scope**  

🚀 **AI Integration**: Implement AI-driven **code suggestions** and **error detection** to enhance the coding experience.  
📞 **Voice & Video Calling**: Add real-time communication features for better collaboration.  
📂 **File Sharing**: Enable users to upload and share project files within the editor.  
💾 **Version Control**: Integrate Git-based version control for tracking changes.  

---

## **License**  

This project is licensed under the **ISC License**.  
