# 🍽️ Restaurant Recommendation System

A machine learning-powered restaurant recommendation system that uses **Content-Based Filtering** and **Collaborative Filtering** techniques to suggest personalized restaurant choices based on user preferences, cuisine types, ratings, and reviews.

## 📋 Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Project Structure](#project-structure)
- [Installation](#installation)
- [Usage](#usage)
- [Dataset](#dataset)
- [Methodology](#methodology)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## 🔍 Overview

This project builds an intelligent restaurant recommendation engine that helps users discover restaurants tailored to their tastes. The system analyzes restaurant attributes (cuisine, location, cost, ratings) and user behavior patterns to generate accurate recommendations.

## ✨ Features

- **Content-Based Filtering** — Recommends restaurants based on similarity of features like cuisine type, cost, and location
- **Collaborative Filtering** — Leverages user-item interactions to find patterns and suggest restaurants liked by similar users
- **Exploratory Data Analysis (EDA)** — Comprehensive visualizations of restaurant distributions, rating patterns, and cuisine popularity
- **Data Preprocessing** — Handles missing values, encodes categorical features, and normalizes numerical data
- **Interactive Recommendations** — Get personalized restaurant suggestions based on input preferences

## 🛠️ Tech Stack

| Technology | Purpose |
|-----------|---------|
| Python 3.x | Core programming language |
| Pandas | Data manipulation and analysis |
| NumPy | Numerical computing |
| Scikit-learn | Machine learning algorithms |
| Matplotlib | Data visualization |
| Seaborn | Statistical data visualization |
| Jupyter Notebook | Interactive development environment |

## 📁 Project Structure

```
Restaurant-recommendation-system/
│
├── restaurant_recommendation.ipynb   # Main Jupyter notebook with all code
├── README.md                          # Project documentation
├── requirements.txt                   # Python dependencies
├── LICENSE                            # MIT License
└── .gitignore                         # Git ignore rules
```

## 🚀 Installation

### Prerequisites
- Python 3.7 or higher
- pip package manager

### Steps

1. **Clone the repository**
   ```bash
   git clone https://github.com/preetham-1332/Restaurant-recommendation-system.git
   cd Restaurant-recommendation-system
   ```

2. **Create a virtual environment** (recommended)
   ```bash
   python -m venv venv
   source venv/bin/activate   # Linux/Mac
   venv\Scripts\activate      # Windows
   ```

3. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

4. **Launch Jupyter Notebook**
   ```bash
   jupyter notebook restaurant_recommendation.ipynb
   ```

## 💡 Usage

1. Open `restaurant_recommendation.ipynb` in Jupyter Notebook or Google Colab
2. Run each cell sequentially to:
   - Load and explore the restaurant dataset
   - Preprocess and clean the data
   - Perform exploratory data analysis
   - Build the recommendation models
   - Generate restaurant recommendations

## 📊 Dataset

The project uses restaurant data with the following key features:
- **Restaurant Name** — Name of the restaurant
- **Cuisine** — Type(s) of cuisine served
- **Location/City** — Geographic location
- **Rating** — Average user rating
- **Cost** — Average cost for two people
- **Votes** — Number of user votes/reviews
- **Online Delivery** — Whether online ordering is available
- **Table Booking** — Whether table reservation is available

## 🧠 Methodology

### 1. Data Preprocessing
- Handling missing values and duplicates
- Feature encoding for categorical variables
- Data normalization and scaling

### 2. Exploratory Data Analysis
- Distribution of ratings and costs
- Popular cuisines and locations
- Correlation analysis between features

### 3. Content-Based Filtering
- TF-IDF vectorization of restaurant features
- Cosine similarity computation
- Top-N similar restaurant recommendations

### 4. Collaborative Filtering
- User-restaurant interaction modeling
- Matrix factorization techniques
- Neighborhood-based recommendations

## 📈 Results

The recommendation system provides:
- Accurate restaurant suggestions based on user preferences
- Visual insights into restaurant trends and patterns
- Scalable approach applicable to real-world restaurant platforms

## 🤝 Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/new-feature`)
3. Commit your changes (`git commit -m 'Add new feature'`)
4. Push to the branch (`git push origin feature/new-feature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License — see the [LICENSE](LICENSE) file for details.

---

⭐ **If you found this project helpful, please give it a star!**

📧 For questions or feedback, feel free to open an issue.
