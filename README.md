# Resume Analyzer with Data Visualization

## 📌 Project Overview
This project is a **Resume Analyzer** built with **Streamlit**, **Plotly**, and a **SQL database**, designed to help analyze and visualize resume data. It allows **admin users** to log in and view insights about applicants based on their resume scores, predicted fields, experience levels, and recommended skills. 

## 🚀 Features
- **User Authentication:** Secure login for admins.
- **Resume Data Upload:** Store and process resume information in a SQL database.
- **Data Visualization:** 
  - Pie charts for **Predicted Field Recommendations**.
  - Pie charts for **User Experience Levels**.
- **Downloadable Reports:** Export analyzed resume data as CSV.
- **Real-time Insights:** Interactive visualizations powered by **Plotly**.

## 🛠️ Technologies Used
- **Frontend:** Streamlit (Python-based UI framework)
- **Backend:** SQL (Database for storing resume data)
- **Data Processing:** Pandas
- **Visualization:** Plotly
- **Authentication:** Custom logic for admin login

## 📂 Project Structure
```
├── app.py                 # Main Streamlit app
├── database.py            # Database connection and queries
├── requirements.txt       # Required dependencies
├── README.md              # Project documentation
```

## 🎯 How to Run
### 1️⃣ Install Dependencies
```sh
pip install -r requirements.txt
```

### 2️⃣ Set Up the Database
Ensure your database is running and contains the **resume_data** table.

### 3️⃣ Run the App
```sh
streamlit run app.py
```

## 📊 Data Visualization
The project includes pie charts for:
- **Predicted Field Recommendations**: Shows recommended career fields based on resume skills.
- **User Experience Levels**: Displays experience levels of applicants.



## 📌 Future Enhancements
- Add **Machine Learning-based Resume Scoring**.
- Improve **Data Filtering & Search Functionality**.
- Deploy to **Cloud Services** for accessibility.
---

### 🎉 Contributing
Feel free to submit **pull requests** or **report issues** to improve the project! 🚀
