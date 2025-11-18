# Smart Forms – Signup Form Project

This project is a demonstration of a smart, accessible signup form created using **HTML**, **CSS**, and **JavaScript**.  
It includes validation, autosave with localStorage, error summaries, and phone number normalisation.

## 📁 Files
- **index.html** – Form structure and semantic markup  
- **styles.css** – Styling, accessibility cues, valid/invalid states  
- **app.js** – Validation logic, autosave, error summary, submission, phone formatting  

## ✨ Features
- Semantic HTML5 form structure  
- Field validation (name, email, password, phone, company fields)  
- Dynamic error messages and error summary box  
- Autosave + restore using `localStorage`  
- Phone number normalisation on blur  
- Honeypot field for bot detection  
- Accessible focus styles and ARIA attributes  
- Demo submission using `fetch()`  

## 🚀 Running the Project
### With VS Code Live Server:
1. Open project folder in VS Code  
2. Right-click `index.html` → **Open with Live Server**

### With Python server:
```bash
python3 -m http.server 5500

