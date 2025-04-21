# 🏎️ F1 Lap Time Prediction (Monaco 2023)

This project uses real telemetry data from the **2023 Monaco Grand Prix** to train an LSTM model that predicts lap times for Formula 1 drivers. It combines cutting-edge machine learning techniques with interactive tools for simulation and visualization.

---

## 🔍 Project Highlights

- **Real F1 Telemetry** using `FastF1` for Monaco GP
- **Feature Engineering** on sector speeds and tire data
- **LSTM Model** trained to predict next lap time from previous 10 laps
- **Race Simulation** for each driver (predicted vs actual totals)
- **SHAP Explainability** with XGBoost baseline
- **Interactive Gradio App** for:
  - Selecting drivers
  - Viewing lap data
  - Predicting next lap time
  - Simulating pit stop effects

---

## 📁 File Overview

| File | Description |
|------|-------------|
| `f1_prediction_gradio_deployment.ipynb` | Main notebook with training, evaluation, simulation, and Gradio app |
| `README.md` | This file (overview, instructions, and goals) |

---

## 📊 Technologies Used (2025-Ready)

- `FastF1` – Race telemetry & timing data
- `PyTorch` – Deep learning (LSTM)
- `XGBoost` – Baseline model + SHAP explainability
- `Gradio` – Interactive web app in Colab
- `scikit-learn`, `matplotlib`, `pandas`, `shap`

---

## 🚀 Try It Yourself (in Colab)

> ⚡ [Run the notebook in Google Colab](https://colab.research.google.com/)

You can:
- Predict laps for any 2023 Monaco driver
- Add pit stop penalties
- See lap-by-lap data used for the model

---

## 📈 Example Output
Predicted: 77.95s | Actual: 78.24s
Predicted: 78.01s | Actual: 78.03s
Predicted: 77.96s | Actual: 78.00s
![image](https://github.com/user-attachments/assets/74e57e09-3234-415a-af99-3aae1f13cfa6)
![image](https://github.com/user-attachments/assets/962a4754-e1b3-422b-97d9-ed321cb0afb5)


---

## 💡 Future Ideas

- Deploy on Hugging Face Spaces
- Add CrewAI agents for strategy simulation
- Predict tire degradation trends
- Multi-track race prediction (e.g., Spa, Silverstone)

---

## 🙌 Author

Built by Vinayak Maharaj – passionate about ML, F1, and building awesome AI-powered tools.
