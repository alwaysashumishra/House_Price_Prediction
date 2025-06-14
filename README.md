
# 🏠 House Price Prediction App

This project is a simple and interactive **web application** built using **Streamlit**. It uses a trained **Machine Learning model** to predict house prices based on **10 important input features**, even if the model was trained with 512 features.

---

## 🚀 Features

- Predict house prices using a trained Random Forest model.
- Only **10 user-friendly features** are required.
- Handles the full 512-length feature vector internally.
- Interactive UI using sliders and dropdowns.
- Easy to run locally using Python and Streamlit.

---

## 📂 Project Structure

```
house-price-predictor/
│
├── app.py                  # Streamlit frontend and prediction logic
├── house_price_model.pkl   # Pre-trained ML model (Random Forest)
├── README.md               # Project description and usage
```

---

## 🧠 Input Features Used (10 Only)

| Feature Name         | Description                                |
|----------------------|--------------------------------------------|
| OverallQual          | Overall material and finish quality        |
| GrLivArea            | Above ground living area (in sq. ft)       |
| GarageCars           | Size of garage in car capacity             |
| TotalBsmtSF          | Total basement area (in sq. ft)            |
| FullBath             | Number of full bathrooms                   |
| YearBuilt            | Year house was built                       |
| KitchenQual          | Kitchen quality (Ex, Gd, TA, Fa, Po)       |
| LotFrontage          | Linear feet of street connected to property|
| Fireplaces           | Number of fireplaces                       |
| TotRmsAbvGrd         | Total rooms above ground                   |

---

## 🛠️ How to Run

### 1. 📦 Install Dependencies

```bash
pip install streamlit numpy scikit-learn
```

> Or if you use conda:
```bash
conda install -c conda-forge streamlit
```

---

### 2. ▶️ Run the App

```bash
streamlit run app.py
```

Then open the link shown in the terminal (usually http://localhost:8501) in your browser.

---

## 💡 Notes

- This app only uses 10 features out of the 512 features expected by the model.
- All other 502 features are filled with zeros to maintain the model’s input structure.
- You can modify `app.py` to add more features or change index mapping as needed.

---

## 👨‍💻 Author

**Ashutosh Mishra**  
B.Tech in AI & ML | Passionate about Data Science and Real-world AI Solutions
