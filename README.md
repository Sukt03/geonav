# 🌐 GeoNav | Exploratory Analysis of Geo-location Data


## **🔍 Description**
GeoNav leverages geospatial data analysis and clustering techniques to provide personalized accommodation recommendations. By analyzing user preferences and apartment features, the application helps users identify suitable living options in Hyderabad.
web application developed as part of a Data Science assignment, designed to assist new residents in Hyderabad in finding the best accommodation based on their preferences for amenities, budget, and proximity.

## **✨ Features**
- **Personalized Accommodation Search:** Users can input their preferences regarding amenities, budget, and location to receive tailored accommodation suggestions.
- **Interactive Maps:** Visualize apartment locations and neighborhood details using the Folium API.
- **Clustering Analysis:** Utilizes K-Means Clustering to categorize apartments based on various features.
- **Real-time Data Rendering:** Displays dynamic graphs and visualizations to enhance user experience.
- **User-Friendly Interface:** Built with Streamlit for an intuitive and seamless user experience.

## **🛠️ Technologies Used**
- **Frontend:** Streamlit
- **Backend & Data Processing:** Python
- **Libraries & Frameworks:** 
  - **Geospatial Analysis:** GeoPandas, Shapely, Fiona, PySAL
  - **Data Visualization:** Folium API, Matplotlib, GeoPandas
  - **Machine Learning:** K-Means Clustering
- **APIs:** Foursquare API for location-based data retrieval
- **Other Tools:** Git/GitHub for version control

## **📈 Data Source**
The dataset `food_coded.csv` was retrieved from Kaggle:
- [Food Choices Data Exploration Analysis](https://www.kaggle.com/code/rafalpanasiuk/food-choices-data-exploration-analysis)

## Demo

![gif](https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExdzIxdG9ucGN6Zm9oZmFqNnAybmN4c2V5NHVsajZpcW0wNWVudjQ5YyZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/lSDhrBSoDX3cbvce34/giphy.gif)



## Installation Guide

1) Clone this repo

```bash
  git clone https://github.com/dr-pandit-69/geolocational_data_analysis
```

2) Create a Virtual Environment (Highly Recommended)
```bash
  pipenv shell
```

3) Enter the Virtual Environment (Highly Recommended)
```bash
  pipenv shell
```

4) Install all the requirements

```bash
  pip install -r requirements.txt
```

5) Run the Project

```bash
  streamlit run Hello.py
```

