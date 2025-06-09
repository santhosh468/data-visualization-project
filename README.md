# 🎬 Netflix Content Dashboard

An interactive and visually appealing data dashboard built using Streamlit and Plotly to explore and analyze Netflix's movies and TV shows dataset.

## 📊 Features

* 📁 Upload Your Own Dataset
    Option to upload a custom CSV file with similar structure to the Netflix dataset.
  
* 🔍 Smart Filtering
    * Filter by content type (Movie or TV Show)
    * Select release year range using a slider
      
* 📈 Visualizations
    * Pie chart of Movies vs TV Shows
    * Line chart of content released over time
    * Bar chart of top countries
    * Rating distribution and content by decade
    * Top genres chart
      
* 📄 Summary Statistics & Insights
    Total titles, average release year, top country, common ratings, etc.
  
* 💾 Downloadable Data
    * Export filtered dataset as CSV
    * Download summary statistics as CSV

## 📂 Dataset

By default, the app uses the publicly available Netflix Movies and TV Shows Dataset from [Kaggle](https://www.kaggle.com/datasets/shivamb/netflix-shows).

Expected columns:
```
show_id, type, title, director, cast, country, date_added,
release_year, rating, duration, listed_in, description
```
## 🚀 How to Run

#### 🔧 Prerequisites
Make sure you have Python 3.7+ and pip installed. Then install the required libraries:
```
pip install streamlit pandas plotly
```

#### ▶️ Run the App

```
streamlit run app.py
```

The app will launch in your default browser at `http://localhost:8501/`.

### 🧾 File Structure

```
.
├── app.py             # Main Streamlit application
├── netflix_titles.csv # Default Netflix dataset
└── README.md          # Project readme file
```

### 🛠 Technologies Used

- Streamlit – For building the interactive web app
- Plotly Express – For responsive and attractive charts
- Pandas – For data manipulation and analysis

### 📌 Notes

* If you upload a dataset, ensure it has a similar structure to the original Netflix dataset.
* All visualizations and metrics auto-update based on filters applied.
* The app supports download of both filtered data and descriptive statistics.

### 🧑‍💻 Author

Santhosh P
To reach out or fork the project for customization [click here](mailto:santhoshpakkiri550@gmail.com)

### 📜 License

This project is open source and available under the [MIT License](LICENSE).
