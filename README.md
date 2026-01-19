# Student Performance Prediction System Using Machine Learning

A web-based application that predicts student academic performance using machine learning techniques. The system allows teachers to upload semester-wise student data and generates batch-wise analytical reports with visual insights.

---

## 📌 Features

- Secure teacher login
- Upload semester-wise student CSV data
- Machine Learning based grade prediction (A, B, C, D)
- Batch-wise storage of prediction results
- View student reports with grade distribution charts
- Clean and responsive dashboard interface

---

## 🛠️ Technologies Used

- Python 3
- Flask (Web Framework)
- Machine Learning (Scikit-learn)
- Pandas & NumPy
- SQLite Database
- HTML5, CSS3, JavaScript
- Chart.js (for visualization)

---

## 💻 System Requirements

### Hardware
- Minimum 4 GB RAM
- Any modern processor

### Software
- Windows / Linux / macOS
- Python 3.9 or above
- Web Browser (Chrome / Edge / Firefox)

---

## ⚙️ How to Run the Project

### Step 1: Clone the Repository
```bash
git clone https://github.com/YOUR_USERNAME/student-performance-prediction-system.git
cd student-performance-prediction-system
Step 2: Install Required Libraries
pip install flask pandas scikit-learn

###Step 3: Train the Machine Learning Model
python train_model.py

Step 4: Setup the Database
python db_setup.py

Step 5: Run the Application
python app.py


Open your browser and visit:

http://127.0.0.1:5000

🔐 Login Credentials (Demo)
Username: admin
Password: 1234

📂 Input CSV Format
RollNo,Name,Attendance,Internal,Assignment,StudyHours,PrevGPA
1,Ali,85,78,80,5,7.9
2,Sara,92,88,90,6,8.5

📊 Output

Predicted grade for each student

Batch-wise student performance reports

Grade distribution visualization
