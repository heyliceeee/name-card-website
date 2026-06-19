# **Card Website**

## **Overview**
This project is a simple personal portfolio built with **Flask**.  
It serves a static HTML page that displays your profile, social links, and CV using a clean HTML5 UP template.

---

## **Tech Stack**
- **Python** + **Flask**
- **HTML5 / CSS3**
- **HTML5 UP** template
- Standard Flask folder structure

---

## **Project Structure**
```
/
├── static/
│   ├── css/
│   ├── images/
│   └── js/
├── templates/
│   └── index.html
├── app.py
└── README.md
```

---

## **Running the Project**
1. Install Flask:
   ```bash
   pip install flask
   ```
2. Start the server:
   ```bash
   export FLASK_APP=server.py
   flask run
   ```
3. Open the site:
   ```
   http://127.0.0.1:5000/
   ```

---

## **Features**
- Responsive landing page with:
  - Profile photo  
  - Name and professional title  
  - Links to **LinkedIn**, **GitHub**, and **CV**
- Lightweight Flask backend with a single route (`/`)
- Clean and minimal UI based on HTML5 UP