# 🚀 Project Dashboard

A simple and clean **Project Dashboard** built using:
- HTML
- CSS
- JavaScript

It helps you organize and access all your mini projects in one place.

---

## 📁 Folder Structure

```
Project-Dashboard/
  │
  ├── index.html
  ├── style.css
  ├── script.js
  │
  └── projects/
      ├── todo/
      │ └── index.html
      │
      ├── calculator/
      │ └── index.html
      │
      ├── weather/
      │ └── index.html
      │
      └── quiz/
      └── index.html

```
---

## 🌟 Features

- 📌 Central dashboard for all projects  
- 🔍 Search projects instantly  
- 🟢 Auto status detection (Completed / In Progress)  
- 📱 Responsive layout  
- 🎨 Clean UI with CSS styling  
- ⚡ Easy to add new projects  

---

## ➕ How to Add a New Project

### 1. Create Project Folder

Inside `/projects`, create a new folder:


/projects/new-project/


---

### 2. Add Your Project File


/projects/new-project/index.html


---

### 3. Add Project Card in `index.html`

Copy an existing project card inside your dashboard and modify it.

Update:
- `<h2>` → Project name  
- `data-name` → search keyword  
- `href` → project path  

---

### Example Card

```html
<!-- Calculator -->
<div class="card glass rounded-3xl p-5 transition hover:-translate-y-2 duration-300"
     data-name="calculator">

    <div class="flex justify-between items-center mb-4">
        <div class="text-5xl">🧮</div>
        <span class="status-badge"></span>
    </div>

    <h2 class="text-xl font-bold mb-2">
        Calculator
    </h2>

    <p class="text-gray-300 mb-5">
        Perform arithmetic calculations instantly.
    </p>

    <a href="projects/calculator/index.html"
       target="_blank"
       class="inline-block bg-fuchsia-500 hover:bg-fuchsia-400 px-5 py-2 rounded-xl font-semibold transition">
        View Project
    </a>

</div>
```
### Note: In your Project `index.html`

Copy this and paste it in your project index.html in <body> tag at first it help to return back to dashboard:

```html
<a href="/index.html" class="back-btn">← Back to Dashboard</a>

```
and add this style to <style> tag

```
.back-btn{
    position:fixed;
    top:20px;
    left:20px;
    z-index:1000;

    padding:10px 18px;
    background:#00d4ff;
    color:#000;
    text-decoration:none;
    border-radius:8px;
    font-weight:bold;
    transition:0.3s;
}

.back-btn:hover{
    background:#fff;
    transform:translateY(-2px);
}

```



## 👤 Author

- **Pranav Waghmare**
