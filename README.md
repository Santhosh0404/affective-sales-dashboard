# affective-sales-dashboard

#Project Overview

This project presents an emotionally designed smart dashboard that combines AI-powered forecasting models and affective visualization principles. It aims to not only predict future sales using powerful machine learning techniques but also to present insights in a way that is intuitive, interactive, and engaging for business users.

🔍 Key Objectives

    Predict future monthly sales using three AI models: XGBoost, Prophet, and LSTM.

    Compare actual vs predicted sales in a Power BI dashboard.

    Provide model performance evaluation using MAE, RMSE, and R² Score.

    Enable story-driven visualizations using affective design.

    Build a unified, filterable, KPI-driven interface for business insights.


🗂️ Project Structure

Affective-Sales-Dashboard/
│
├── data/                 # Contains cleaned_sales_data.csv and forecasted outputs
├── notebooks/            # Jupyter Notebooks for each model (XGBoost, LSTM, Prophet)
├── dashboard/            # Power BI .pbix files and screenshots
├── report/               # Project Report, IEEE Paper Draft, PPT
├── requirements.txt      # Python dependencies for models
├── .gitignore            # Git ignore settings
└── README.md             # This file


🧪 Models Used

| Model   | Description                              | MAE      | RMSE     | R² Score   |
| ------- | ---------------------------------------- | -------- | -------- | ---------- |
| XGBoost | Gradient boosting for tabular prediction | \~4.07   | \~5.46   | **1.0000** |
| Prophet | Time-series forecasting by Facebook      | \~265104 | \~318306 | 0.5332     |
| LSTM    | Recurrent Neural Network for sequences   | \~514335 | \~571016 | -0.1655    |


📊 Dashboard Pages (Power BI)

    Forecast Comparison – Line chart comparing Actual vs Predicted (all models)

    Model Metrics – KPI Cards for MAE, RMSE, R² by model

    Sales Explorer – Visual breakdown by ProductLine, Region, Gender

    Narrative Page – Smart insights and interactive storytelling

🛠️ Technologies Used

    Python: Data Preprocessing, Model Building

    Power BI: Visualization and Interactive Dashboard

    Pandas, XGBoost, Prophet, TensorFlow/Keras: Forecasting

    Matplotlib, Seaborn: Evaluation graphs

📦 How to Run

    Clone this repository

    Install dependencies:pip install -r requirements.txt
    Run Jupyter notebooks inside notebooks/ folder.
    Open .pbix files inside Power BI Desktop to view dashboard.

📌 Future Enhancements

    Add employee-wise performance forecast.

    Integrate real-time sales data pipeline.

    Add customer sentiment integration from Amazon reviews.

    Deploy dashboard to Power BI Service or web.
📄 License

This project is for educational and research purposes only.
Contact Santhosh G
Email: sandyofficial0404@gmail.com for collaborations.
