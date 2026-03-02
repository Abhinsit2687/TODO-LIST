# 📝 Simple Todo List Web App

A clean and modern **Todo List Web Application** built using **HTML, CSS, and JavaScript**.  
This project allows users to add, edit, delete, and mark tasks as completed — with data saved in the browser using localStorage.

---

## 🚀 Features

- ➕ Add new todos  
- ⌨️ Press **Enter** to quickly add tasks  
- ✅ Mark tasks as completed (strike-through effect)  
- ✏️ Double-click to edit a todo  
- 🗑️ Delete todos  
- 💾 Persistent storage using localStorage  
- 🎨 Modern responsive UI with smooth animations  

---

## 🛠️ Technologies Used

- HTML5 – Structure of the web page  
- CSS3 – Styling, animations, and responsive design  
- JavaScript (ES6) – Application logic and DOM manipulation  
- Local Storage API – Data persistence  

---

## 📂 Project Structure

TodoList/
│
├── index.html      # Main HTML file  
├── style.css       # Styling file  
└── script.js       # JavaScript logic  

---

## ⚙️ How It Works

### 1️⃣ Adding a Todo
- User enters text in the input field.
- Clicks **Add** button or presses **Enter**.
- Todo is added to the list and saved to localStorage.

### 2️⃣ Mark as Completed
- Clicking the checkbox updates the completed status.
- The text gets a strike-through effect.
- Changes are saved automatically.

### 3️⃣ Edit Todo
- Double-click on the todo text.
- A prompt appears to update the text.
- Changes are saved instantly.

### 4️⃣ Delete Todo
- Click the Delete button.
- The todo is removed from the array and UI updates.

---

## 💾 Data Persistence

Todos are stored in the browser using:

```javascript
localStorage.setItem('todos', JSON.stringify(todos));
```

When the page reloads:
- Data is retrieved using localStorage.getItem()
- Todos are re-rendered automatically.

---

## 📱 Responsive Design

- Fully responsive layout
- Works on desktop and mobile devices
- Adjusted input and list width for smaller screens

---

## ▶️ How to Run

1. Download or clone the repository.
2. Open `index.html` in your browser.
3. Start adding your todos!

No additional setup or installation required.

---

## 🎯 Learning Outcomes

Through this project, you will understand:

- DOM manipulation  
- Event handling  
- JavaScript array operations  
- localStorage usage  
- Dynamic UI rendering  
- Clean UI design using CSS  

---

## 🔮 Future Improvements

- Add due dates
- Add priority levels
- Add drag & drop reordering
- Add dark/light theme toggle
- Replace prompt edit with inline editing
- Add filter (All / Completed / Pending)

---

## 👨‍💻 Author

Abhishek Gupta
