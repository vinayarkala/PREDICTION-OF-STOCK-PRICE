# PREDICTION-OF-STOCK-PRICE

# 📈 Stock Price Prediction using RNN & LSTM  

## 📌 Project Overview  
This project focuses on predicting stock prices using **Recurrent Neural Networks (RNN)** and **Long Short-Term Memory (LSTM)** models. The goal is to analyze historical stock data and forecast future price trends, helping traders and investors make informed decisions.  

## 📊 Dataset  
- **Source:** IndianBankNifty.csv (historical stock data)  
- **Features:** Open, Close, High, Low, Volume  
- **Preprocessing:** Time series formatting, normalization, and outlier handling  

## 🔍 Methodology  
### **1️⃣ Data Preprocessing**  
- Converted **date column** to datetime format for time-based analysis  
- **Split data** into training (70%) and validation (30%) sets  
- Applied **Min-Max Scaling** for feature normalization  

### **2️⃣ Model Architectures**  
#### 🟢 **Simple RNN Model**  
- **Layers:** Stacked **Simple RNN layers** with **tanh activation**  
- **Dropout layers** to prevent overfitting  
- **Dense output layer** for final price prediction  
- **Optimizer:** Adam  
- **Loss Function:** Mean Squared Error (MSE)  

#### 🔵 **LSTM Model**  
- **Layers:** Multiple **LSTM layers** for sequential pattern recognition  
- **Dense layers** for final output prediction  
- **Optimizer:** Adam  
- **Loss Function:** Mean Squared Error (MSE)  

## 📈 Evaluation Metrics  
- **Mean Squared Error (MSE)**  
- **Mean Absolute Error (MAE)**  
- **Visual comparison** of predicted vs. actual stock prices  

## 🚀 Results & Conclusion  
- Both **Simple RNN and LSTM models** effectively predict stock trends  
- **LSTM outperforms RNN** by capturing long-term dependencies in data  
- **Predictions closely follow actual trends**, making the models useful for market forecasting  

## ⚙️ Technologies Used  
- **Python**  
- **TensorFlow & Keras**  
- **NumPy & Pandas**  
- **Scikit-learn**  
- **Matplotlib for Visualization**  

## 📌 How to Run the Project  
1. **Clone this repository**  
   ```bash
   git clone https://github.com/your-repo-name.git
   cd your-repo-name
   ```  
2. **Install dependencies**  
   ```bash
   pip install tensorflow keras numpy pandas scikit-learn matplotlib
   ```  
3. **Run the model scripts**  
   ```bash
   python rnn_model.py
   python lstm_model.py
   ```  

## 📝 Future Improvements  
- **Hyperparameter tuning** for better optimization  
- **Integration of external factors** (news sentiment, financial indicators)  
- **Deployment as a real-time stock price prediction tool**  

📌 **Contributors:**  

- **Arkala Chandhra Shekar Vinay**  
