# 🎥 Movie Recommender System

A machine learning-powered system for recommending movies based on user preferences and data analysis. This repository includes both a backend recommendation engine and a frontend interface for user interaction.

## ✨ Features

- 🔮 **Recommendation Engine**: Uses machine learning models to provide personalized movie recommendations.
- 🖥️ **Streamlit Application**: A user-friendly interface for interacting with the recommendation system.
- 🌐 **Frontend**: Includes the web-based frontend to provide a better user experience.

## 📂 Project Structure

- `frontend/` - Frontend application code
- `streamlit-app/` - Streamlit application files
- `.gitattributes` - Git LFS tracking for large files
- `Recommendation System.ipynb` - Jupyter notebook for the recommendation system
- `app.py` - Main file for running the application
- `dataset.csv` - Dataset used for building recommendations
- `main.py` - Core backend logic
- `movies_list.pkl` - Serialized movie list (Pickle format)


## 🛠️ Prerequisites

To run this project, ensure you have the following installed:

- 🐍 **Python 3.8+**
- 🧰 **Streamlit**
- 📦 **Required Python libraries** (listed in `requirements.txt`)

## 🚀 Installation

1. **Clone this repository**:

   ```bash
   git clone https://github.com/Aymen016/Film-recommendation-engine.git
   cd Film-recommendation-engine
   ```

2. **Install dependencies**:

   ```bash
   pip install -r requirements.txt
   ```

3. **Set up Git LFS** for handling large files (if not already done):

   ```bash
    git lfs install
   ```

## 🏃 Usage

  ### Run the Backend:
  Start the backend logic by executing:
  
  ```bash
  python main.py
  ```

### Run the Streamlit App:
Launch the Streamlit interface:

  ```bash
  streamlit run app.py
  ```
### Access the Frontend:
Use the files in the `frontend/` folder to set up and serve the web-based frontend.

## 📊 Dataset

- 📁 The dataset (`dataset.csv`) is used for building movie recommendations.
- 🗂️ `movies_list.pkl` contains a preprocessed list of movies for faster recommendations.

## 🤝 Contributing

Contributions are welcome! Please follow these steps:

1. 🍴 Fork the repository.
2. 🌱 Create a new branch for your feature:

   ```bash
   git checkout -b feature-name
  ```


