
# Car Price Prediction ML Web App 🚗💰

This project is a **Car Price Prediction web application** built using **Machine Learning algorithms and deployed using Streamlit**.  
It allows users to input car details and get the predicted resale price of the car in India.

---

## 🚀 Features

- Predict car price using ML model based on car attributes.
- User-friendly web interface using **Streamlit**.
- Trained model is loaded using **Pickle**.
- Inputs like brand, year, kms driven, fuel type, and others are used for predictions.
- Custom preprocessing is done inside the app before prediction.

---

## 📂 Project Structure

```
SAMCPP/
├── Cardetails.csv             # Dataset used for feature extraction and inputs
├── model.pkl                  # Trained ML model (Pickle format)
├── app.py                     # Main Streamlit application code
└── requirements.txt           # Required Python packages
```

---

## 🧪 Technologies Used

| Technology  | Purpose                               |
|-------------|---------------------------------------|
| Python      | Core programming language             |
| Pandas      | Data manipulation and handling        |
| NumPy       | Numerical operations                  |
| Streamlit   | Web interface for ML deployment       |
| Pickle      | Model serialization                   |
| Scikit-learn (assumed) | Model training (offline) |

---

## ⚙ Setup and Installation

### Prerequisites
Ensure you have:
- Python 3.8 or higher installed.
- `pip` package manager.

### Clone the repository
```bash
git clone https://github.com/yourusername/SAMCPP.git
cd SAMCPP
```

### Create a virtual environment (recommended)
```bash
python -m venv venv
source venv/bin/activate  # Linux/Mac
venv\Scripts\activate     # Windows
```

### Install the dependencies
```bash
pip install -r requirements.txt
```

---

## 📊 Running the Application Locally

```bash
streamlit run app.py
```

Then open the URL provided by Streamlit in your browser (`http://localhost:8501`).

---

## 🎯 Model Overview

- The model is pre-trained and saved as `model.pkl`.
- The ML model uses features such as:
  - Brand
  - Year
  - KMs Driven
  - Fuel type
  - Seller type
  - Transmission type
  - Owner type
  - Mileage
  - Engine capacity
  - Max Power
  - Seats

### Data preprocessing inside the app includes:
- Converting categorical variables to numerical (manual mapping).
- Handling user inputs into model-ready formats.

---

## 🔧 Deployment on Cloud (Optional)

### Deploy on Streamlit Cloud
1. Push your project to a public GitHub repository.
2. Visit [Streamlit Cloud](https://share.streamlit.io/).
3. Click **New App**.
4. Connect to your GitHub repo and deploy.
5. Ensure `app.py`, `model.pkl`, and `Cardetails.csv` are all present.

---

## 📦 Packages Used (from `requirements.txt`)

| Package      | Purpose                          |
|--------------|----------------------------------|
| pandas       | Data manipulation                |
| numpy        | Numerical computing              |
| streamlit    | Web app framework                |
| pickle (standard) | Model loading               |
| altair, pydeck, pyarrow | Streamlit visualization support |
| scikit-learn (assumed) | Model training (offline) |

*Full list of dependencies can be found in `requirements.txt`.*

---

## 💡 Notes

- **Model Training is not included inside this repository.**  
  You can use your own dataset and retrain the model.
- **Ensure `model.pkl` and `Cardetails.csv` are in the same directory as `app.py` for correct functioning.**

---

## 📜 License

This project is for educational and demonstration purposes.

---

## 🤝 Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

---

## ✨ Author

Made by **Abdul Mannaan**  
LinkedIn: [abdulmannaan](https://www.linkedin.com/in/abdulmannaan/)  
GitHub: [abdulmannaan502](https://github.com/abdulmannaan502)
