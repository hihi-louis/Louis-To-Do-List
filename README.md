# **📌 My To-Do List Web APP**

<img width="1080" alt="Screenshot 2025-02-02 at 19 24 36" src="https://github.com/user-attachments/assets/fb002295-dfcb-47d3-bfa7-b0e4d1feef15" />


A **modern, colorful, and professional** to-do list application built with **TypeScript, HTML, and CSS**, running in a **Node.js environment**.

This app allows users to **add, check, and delete tasks** with a **beautiful UI**, **smooth animations**, and **gradient-based styling**.

---

## **🚀 Features**
✔ **Add Tasks** – Quickly add new to-do items.  
✔ **Check/Uncheck Tasks** – Mark tasks as completed with a visual effect.  
✔ **Delete Tasks** – Remove tasks with a sleek animated delete button.  
✔ **Clear All Tasks** – Remove all tasks instantly with a gradient "Clear All" button.  
✔ **Professional UI** – Modern, vibrant, and animated interface.  
✔ **Fully Responsive** – Works on desktops, tablets, and mobile devices.  
✔ **Runs on Node.js** – Uses TypeScript to manage the task list logic.

---

## **📂 Project Structure**
```
/src
│── /css
│   ├── style.css      # Main styles (gradient backgrounds, animations, responsive UI)
│── /ts
│   ├── ListTemplate.ts  # Defines how the list is displayed
│   ├── ListItem.ts      # Defines the task object structure
│   ├── FullList.ts      # Manages the list logic
│── index.html         # Main HTML structure
│── server.ts          # Node.js server (optional if using a backend)
│── package.json       # Node.js dependencies
│── tsconfig.json      # TypeScript configuration
│── README.md          # Documentation (this file)
```

---

## **🛠️ Installation & Running the Project**
### **1️⃣ Prerequisites**
- Install **Node.js** (Download from [nodejs.org](https://nodejs.org/))
- Install **TypeScript** globally (if not already installed):
  ```bash
  npm install -g typescript
  ```

### **2️⃣ Clone the Repository**
```bash
git clone https://github.com/your-username/my-todo-list.git
cd my-todo-list
```

### **3️⃣ Install Dependencies**
```bash
npm install
```

### **4️⃣ Compile TypeScript**
Convert TypeScript files to JavaScript using:
```bash
tsc
```
This will generate `.js` files in the `dist/` directory.

### **5️⃣ Run the Project**
#### **Option 1: Run with Node.js**
```bash
node dist/server.js
```
Then open **`http://localhost:3000`** in your browser.

#### **Option 2: Run with a Live Server**
If using **VS Code**, install the "Live Server" extension and open `index.html`.

---

## **🎨 Styling Notes**
- The UI **uses modern gradients and animations** for a **sleek, polished look**.
- The **heading text gradient** uses `-webkit-background-clip: text;`, which is **not fully supported in Firefox**.
- To fix this, we apply:
  ```css
  background-clip: text;
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  ```
- This ensures compatibility with **Chrome, Edge, and Safari**, but **Firefox** may not support text gradients without additional techniques.

---

## **💡 Future Enhancements**
🔹 **Dark Mode** – A toggle switch for light/dark themes.  
🔹 **Task Persistence** – Save tasks in **local storage** so they remain after refresh.  
🔹 **Custom Categories** – Users can group tasks into categories.  
🔹 **Backend Integration** – Store tasks in a **database (MongoDB or Firebase)**.  

---

## **📜 License**
This project is **open-source** and available under the **MIT License**.

---

## **📬 Contact**
If you have any suggestions or need help, feel free to **open an issue** or **reach out**!

---

### **🔥 Final Thoughts**
This **README** provides clear **setup instructions for running the project with Node.js & TypeScript**. 🚀  
Let me know if you need **any refinements!** 🎨✨

