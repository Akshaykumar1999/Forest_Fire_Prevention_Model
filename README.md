# 🔥 Forest Fire Prevention Web App  

This is a **Flask-based web application** that predicts the probability of a forest fire based on environmental parameters like **Temperature**, **Oxygen level**, and **Humidity**.  
The prediction is made using a pre-trained Machine Learning model.

---

## ✅ Features:
- User-friendly web interface with Materialize CSS  
- Input fields for:
  - 🌡️ Temperature (°C)
  - 💨 Oxygen (ppm)
  - 💧 Humidity (%)
- Displays fire risk probability with a safety message  
- Simple and responsive design  
- Built with Flask (Python Backend) + Materialize (Frontend)  

---

## 🛠️ Technologies Used:
- Python  
- Flask  
- Scikit-learn  
- NumPy  
- Materialize CSS  
- HTML5  

---

## 🚀 How to Run the Project Locally:

1️⃣ **Project Folder Structure:**
```
/project_folder/
├── app.py
├── log_reg_forest_prevention_model.pkl
├── templates/
│   └── Forest.html
├── README.md
```

2️⃣ **Install required Python packages:**
```bash
pip install flask numpy scikit-learn
```

3️⃣ **Run the Flask app:**
```bash
python app.py
```

4️⃣ Open your browser and go to:
```
http://localhost:5000/
```

---

## 📝 Model Used:
The project uses a trained **Logistic Regression** model (saved as `log_reg_forest_prevention_model.pkl`)  
The model predicts the probability of forest fire occurrence based on environmental input features.

---

## 🙋‍♂️ Support:
For any queries or support, feel free to contact the project owner.
