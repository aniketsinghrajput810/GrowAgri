# 🌱🚜 GrowAgri 🚜🌱

GrowAgri is a data-driven crop recommendation system designed to support farmers by providing personalized crop suggestions based on various environmental parameters. This project leverages machine learning and web technologies to offer an intuitive and effective solution for optimizing agricultural yields.

## 🚀 Features

- 📊 **Data Collection**: Integration with Kaggle datasets and direct user inputs.
- 🔧 **Data Preprocessing**: Handling missing values, outliers, and ensuring data consistency.
- 📈 **Exploratory Data Analysis**: Visualizing data trends and patterns.
- 🤖 **Machine Learning Model**: Random Forest classifier for accurate crop predictions.
- 🌐 **Web Application**: Django-based backend with an intuitive frontend using HTML, CSS, and JavaScript.

## 🛠️ Technologies Used

- 🐍 **Programming Language**: Python
- 🌐 **Web Framework**: Django
- 🖌️ **Frontend Technologies**: HTML, CSS, JavaScript
- 📚 **Data Analysis Libraries**: Pandas, NumPy, Matplotlib, seaborn, scikit-learn
- 💾 **Model Persistence**: pickle
- 🛠️ **Development Tools**: Jupyter Notebook, VS Code

## 📋 Data Collection and Preprocessing

- 📥 **Data Sources**: Kaggle datasets and user inputs.
- 🔧 **Preprocessing Steps**:
  - Handling missing values
  - Removing outliers
  - Ensuring data consistency
  - Data splitting into training, validation, and test sets

## 📊 Exploratory Data Analysis (EDA)

- 📊 **Descriptive Statistics**: Summary statistics of the dataset.
- 📈 **Data Visualization**: Using Matplotlib and seaborn for visual insights.
- 🔍 **Outlier Detection**: Identifying and handling outliers.

## 🧠 Model Building

- 🧩 **Algorithm Used**: Random Forest classifier from scikit-learn.
- 🏋️‍♂️ **Model Training**: Trained on preprocessed data.
- 📊 **Model Evaluation**: Evaluated using accuracy metrics and validation sets.

## 🚀 Model Deployment

- 💾 **Model Persistence**: Saved the trained model using pickle.
- 🌐 **Django App**: Integrated the model into a Django web application.
- 🖥️ **Frontend**: Developed an intuitive user interface with HTML, CSS, and JavaScript.

## 🛠️ Installation

To set up the GrowAgri project locally, follow these steps:

1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/GrowAgri.git
    cd GrowAgri
    ```

2. Create a virtual environment and activate it:
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

4. Run the Django development server:
    ```bash
    python manage.py runserver
    ```

## 🚀 Usage

1. Open your web browser and navigate to `http://127.0.0.1:8000/`.
2. Input the environmental parameters (N, P, K, temperature, humidity, pH, and rainfall).
3. Get crop recommendations based on the input parameters.

## 🤝 Contributing

Contributions are welcome! Please follow these steps to contribute:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes and commit them (`git commit -m 'Add new feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Open a pull request.

Feel free to customize and expand this README file to suit the specific details and requirements of your project.

🎉🌱🚀
