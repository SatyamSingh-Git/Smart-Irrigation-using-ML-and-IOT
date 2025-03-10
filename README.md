# 🌱 Smart Irrigation System Using Machine Learning & IoT

## 📌 Project Overview
This project implements a **smart irrigation system** that uses **Machine Learning (ML) and IoT** to predict the optimal time for activating the water pump based on **temperature, humidity, soil moisture, and crop type**. 

The system helps in **water conservation** and **efficient farming** by ensuring crops receive the right amount of water at the right time.

## 🚀 Features
- **Automated Irrigation**: Predicts when to turn the pump ON/OFF based on real-time sensor data.
- **Machine Learning Model**: Utilizes **K-Nearest Neighbors (KNN), Decision Tree (DT), and Support Vector Machine (SVM)** for classification.
- **Real-time Monitoring**: Displays sensor data and irrigation status on a web interface.
- **IoT Integration**: Uses ESP8266 microcontroller, DHT11 temperature/humidity sensor, and soil moisture sensor.
- **Data Logging**: Stores sensor readings for historical analysis and optimization.

## 🔧 Tech Stack
- **Programming Language**: Python
- **Machine Learning**: Scikit-learn, Pandas, NumPy
- **IoT Components**: ESP8266, DHT11, Soil Moisture Sensor
- **Web Interface**: PHP, MySQL
- **Visualization**: Matplotlib, Seaborn

## 📊 Machine Learning Model
The ML model predicts whether irrigation is required using the following classifiers:

| Algorithm        | Accuracy |
|-----------------|----------|
| K-Nearest Neighbors (KNN) | 99% |
| Decision Tree (DT) | 100% |
| Support Vector Machine (SVM) | 64% |

## 📌 System Architecture
1. **Data Collection**: Sensors capture **temperature, humidity, and soil moisture** data.
2. **Data Processing**: Collected data is preprocessed and stored in a database.
3. **ML Prediction**: The model predicts if irrigation is needed.
4. **Irrigation Control**: The **water pump** is turned ON/OFF based on ML predictions.
5. **Real-time Monitoring**: Users can view live data and irrigation status via a web interface.

## 📜 Installation & Setup
### 🔹 Hardware Requirements
- ESP8266 Microcontroller
- DHT11 Temperature & Humidity Sensor
- Soil Moisture Sensor
- Water Pump with Relay

### 🔹 Software Requirements
- Python 3.x
- Scikit-learn, Pandas, NumPy, Matplotlib
- PHP & MySQL for web-based monitoring
- Arduino IDE for ESP8266 programming

### 🔹 Steps to Run the Project
1. Clone the repository:
   ```sh
   git clone https://github.com/your-username/smart-irrigation-ml.git
   cd smart-irrigation-ml
   ```
2. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```
3. Upload the ESP8266 firmware using **Arduino IDE**.
4. Start the Python ML script:
   ```sh
   python irrigation_ml.py
   ```
5. Launch the web interface (PHP & MySQL setup required).

## 📌 Future Enhancements
- **Enhance ML Model**: Incorporate deep learning for better accuracy.
- **Mobile App**: Develop an app for remote irrigation control.
- **Fertilizer Prediction**: Extend the model to recommend fertilizers based on crop conditions.

## 🛠 Contributing
Contributions are welcome! Feel free to submit issues or create pull requests.

## 📜 License
This project is licensed under the **MIT License**.

---

💡 *Empowering sustainable agriculture with AI & IoT!* 🌾
