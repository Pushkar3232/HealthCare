# Healthcare Premium Prediction

This project is a Machine Learning application that predicts healthcare insurance premiums using regression techniques. It features a Streamlit-based frontend for user interaction.

## 📁 Project Structure

```
HEALTHCARE
|   LICENSE
|   ml_premium_prediction.ipynb
|   premiums.xlsx
|   README.md
|
+---.ipynb_checkpoints
|       ml_premium_prediction-checkpoint.ipynb
|       
|
\---app
    |   main.py
    |   prediction_helper.py
    |
    +---.idea
    |   |   .gitignore
    |   |   frontend.iml
    |   |   misc.xml
    |   |   modules.xml
    |   |   workspace.xml
    |
    |   \---inspectionProfiles
    |           profiles_settings.xml
    |           Project_Default.xml
    |
    +---artifacts
    |       model_rest.joblib
    |       model_young.joblib
    |       scaler_rest.joblib
    |       scaler_young.joblib
    |
    \---__pycache__
            prediction_helper.cpython-310.pyc
```

## 🚀 Getting Started

### Prerequisites

Ensure you have the following installed:
- Python 3.x
- pip package manager

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Pushkar3232/HealthCare.git
   ```

2. **Navigate to the project directory:**
   ```bash
   cd HealthCare
   ```

3. **(Optional) Create and activate a virtual environment:**
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

4. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

### Running the Application

To start the Streamlit app, run:
```bash
cd app
streamlit run main.py
```

## 🛠️ Usage

- Use the web interface to input required parameters for premium prediction.
- The backend processes input using pre-trained regression models stored in the `artifacts` folder.
- The results are displayed instantly through Streamlit.

## 📊 Project Details

- **Dataset:** The dataset (`premiums.xlsx`) contains historical data used for training.
- **Machine Learning Model:** Regression models predict insurance premiums based on input features.
- **Frontend:** The application uses Streamlit for an interactive user experience.

## 📜 License

This project is licensed under the terms specified in the [LICENSE](./LICENSE) file.

## 🤝 Contributing

Contributions are welcome! Feel free to fork the repository and submit a pull request with your improvements.

## 🎉 Acknowledgements

- Thanks to the open-source community for providing the tools and libraries used in this project.
- Special thanks to [Streamlit](https://streamlit.io/) for the interactive UI framework.

---
Made with ❤️ by Pushkar Shinde

