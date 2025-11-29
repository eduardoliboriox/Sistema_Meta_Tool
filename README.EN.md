# Production Goals System

A production goal management system developed with **Python + Flask**.
Allows registering models, calculating goals adjusted per worker, and tracking production losses.
Check out the live application via the link at the end of this README.md.

---

## 🔹 Features

* Dashboard summarizing registered models, average goal/hour, and latest entries.
* Model registration (code, client, department, goal/hour, default number of workers).
* Model listing with **DataTables**.
* Edit and delete models.
* Calculation of adjusted goals per worker and time.
* Production loss calculation.
* Responsive layout with **Bootstrap 5**.

---

## 🔹 Technologies

* Python 3.11+
* Flask 2.3+
* SQLite (local database)
* HTML5, CSS3, Bootstrap 5
* DataTables (via CDN)
* JavaScript (Fetch API + AJAX)

---

## 🔹 Project Structure

```
production-goal-manager-venttos/
├─ static/
│   ├─ logo.png 
│   ├─ css/
│   │    └─ style.css  
│   ├─ js/
│        └─ main.js  
├─ templates/
│  ├─ base.html
│  ├─ cadastro.html
│  ├─ dashboard.html
│  ├─ modelos.html
│  ├─ calcular.html
│  ├─ perdas.html
├─ app.py
├─ producao.db
├─ ping.py
├─ Profile   
├─ README.md
├─ README.EN.md   
├─ requirements.txt 
```

---

## 📁 How to Run

```bash
pip install -r requirements.txt
python app.py
```

---

## 🔗 Access the System (Deployment)

The system is available online via Render:
Countermeasures are used even in the free version to prevent the page from closing due to inactivity. If it closes, wait 50 seconds and reopen.

➡️ **[https://production-goal-manager.onrender.com](https://production-goal-manager.onrender.com)**

---

## 👨‍💻 Author

* Developed by **Eduardo Libório**
* 📧 [eduardosoleno@protonmail.com](mailto:eduardosoleno@protonmail.com)

---
