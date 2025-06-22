#  END-TO-END DATA SCIENCE PROJECT

COMPANY : CODTECH IT SOLUTIONS

NAME : MUZAMMIL AHMED 

INTERN ID : CT04DG2827

DOMAIN: WEB DEVELOPMENT 

DURATION : 4 WEEKS 

MWNTOR : NEELA SANTHOS 

---

This is a complete machine learning web app to predict house prices.

## 🚀 Features
- Trained regression model
- FastAPI backend
- Swagger UI and Web Form
- Deployable via Render, Railway, Heroku

## 🧠 Model
A Linear Regression model is used to fit the relationship between house features and prices.

Libraries Used:

pandas for data wrangling

scikit-learn for model training and evaluation

joblib for model serialization

---

## 📦 How to Run
```bash
pip install -r requirements.txt
uvicorn app.main:app --reload
```
Visit [http://127.0.0.1:8000/docs](http://127.0.0.1:8000/docs) for Swagger UI.

---

## 🌍 Deployment
Use `Render`, `Railway`, or `Heroku` with the included Procfile.

---

📊 Dataset
The dataset used (housing.csv) contains 20+ rows of housing data with the following features:

area: Size of the house in square feet

bedrooms: Number of bedrooms

bathrooms: Number of bathrooms

stories: Number of stories (floors)

parking: Number of parking spots

price: Target variable (house price)

---

🧩 Backend — FastAPI
/: Home page with a form UI

/predict: Accepts POST request with form or JSON data

/docs: Swagger UI for testing and exploration

Tech Stack:

FastAPI – modern, fast web framework

Pydantic – for input validation

Uvicorn – ASGI server

Jinja2 – HTML templating

---

🌐 Deployment
You can deploy the app on:

🚀 Render (easy and free for APIs)

🚂 Railway

☁️ Heroku (with Procfile)

The project is structured and documented for instant deployment.

---
🧾 Project Structure
house-price-predictor/
├── app/                # FastAPI app code
├── data/               # housing.csv
├── model/              # model.pkl
├── notebooks/          # EDA & training notebook
├── templates/          # HTML form UI
├── static/             # CSS styles
├── requirements.txt    # Dependencies
├── Procfile            # For Heroku
├── README.md           # Project guide

---

📌 Highlights

✅ Full end-to-end pipeline

✅ Easy-to-use form & API

✅ Reusable & modular code

✅ Visual appeal + professional backend

✅ Ready for GitHub & deployment


---


## OUTPUT
![Image](https://github.com/user-attachments/assets/b45dfa09-546a-4598-b898-33bac5b82513)

![Image](https://github.com/user-attachments/assets/f4b4bac1-cdbe-41b8-a9dd-e371602ccf09)

![Image](https://github.com/user-attachments/assets/0aa6704e-6d65-4372-ae64-43540ae7811a)

---
