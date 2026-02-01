# Be-Suspicious-Of-Online-Movie-Ratings-Especially-Fandango-s
If you are planning on going out to see a movie, how well can you trust online reviews and ratings? *Especially* if the same company showing the rating *also* makes money by selling movie tickets. Do they have a bias towards rating movies higher than they should be rated?

# Be Suspicious of Online Movie Ratings (Especially Fandango)

## 📌 Project Overview

Online movie ratings strongly influence what people choose to watch — but how trustworthy are they?

This project analyzes movie rating data with a special focus on **Fandango**, investigating whether certain platforms systematically inflate ratings compared to others. Using exploratory data analysis and statistical reasoning, the project aims to uncover **biases, inconsistencies, and suspicious patterns** in online movie ratings.

This work is inspired by real-world concerns around review manipulation and is designed as a **data analysis + ML-oriented capstone project**.


## 🎯 Objectives

* Compare movie ratings across multiple platforms
* Identify systematic rating inflation or bias
* Analyze discrepancies between critic and user ratings
* Build intuition around trustworthiness of online reviews

## 📊 Dataset

* **Source**: Publicly available movie ratings dataset
* **Platforms analyzed**:

  * Fandango
  * Rotten Tomatoes
  * Metacritic
  * IMDb
* **Features include**:

  * Movie titles
  * Critic scores
  * Audience scores
  * Normalized ratings

## 🔍 Methodology

1. **Data Cleaning & Preprocessing**

   * Handling missing values
   * Normalizing rating scales

2. **Exploratory Data Analysis (EDA)**

   * Distribution analysis
   * Platform-wise comparison
   * Visualization of rating differences

3. **Statistical Analysis**

   * Mean and variance comparison
   * Bias detection across platforms

4. **Interpretation**

   * What the numbers imply for real users
   * Why certain platforms appear more optimistic

## 📈 Key Insights

* Fandango ratings tend to skew higher than other platforms
* Variance across platforms suggests inconsistent rating standards
* Some platforms align more closely with critic consensus than others

*(Detailed plots and findings are available in the notebook)*


## 🧪 How to Run the Project

```bash
# Clone the repository
git clone <repo-url>

# Navigate to the project directory
cd Be-Suspicious-Of-Online-Movie-Ratings

# (Optional) Create a virtual environment
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Launch Jupyter Notebook
jupyter notebook
```

Open:

```
00-Capstone-Project analytics.ipynb
```

---

## 📁 Project Structure

```text
├── 00-Capstone-Project analytics.ipynb
├── README.md
├── data/
│   └── movie_ratings.csv
└── requirements.txt
```

---

## 🚀 Future Work

* Apply hypothesis testing to quantify bias
* Extend analysis to newer datasets
* Build a trust-score for rating platforms
* Deploy results as an interactive dashboard

---

## 🧠 Skills Demonstrated

* Data cleaning & EDA
* Statistical reasoning
* Python (NumPy, Pandas, Matplotlib/Seaborn)
* Analytical storytelling

---

## 📬 Contact

If you’re reviewing this project for learning, collaboration, or mentorship, feel free to reach out via GitHub.

---

⭐ If you found this project insightful, consider starring the repository!
