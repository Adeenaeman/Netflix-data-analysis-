# 🎬 Netflix Data Analysis using Python

A complete **Exploratory Data Analysis (EDA)** project on the Netflix Movies & TV Shows dataset using **Python, Pandas, NumPy, and Matplotlib**.

This project demonstrates the complete data analysis workflow—from cleaning raw data to generating insights and creating publication-quality visualizations.

---

# 📊 Project Overview

The project explores more than **8,800 Netflix titles** to answer questions such as:

- Which country produces the most Netflix content?
- What are the most common content ratings?
- Which directors have the most titles?
- Which actors appear most frequently?
- Which year had the highest number of releases?
- What is the distribution of Movies vs TV Shows?
- Which genres are the most popular?

---

# 📁 Dataset

**Source:**  
https://www.kaggle.com/datasets/shivamb/netflix-shows

The dataset contains information about:

- Show ID
- Title
- Type (Movie / TV Show)
- Director
- Cast
- Country
- Date Added
- Release Year
- Rating
- Duration
- Genre
- Description

---

# 🛠 Libraries Used

- Python
- Pandas
- NumPy
- Matplotlib

---

# 📚 Skills Demonstrated

### Data Cleaning
- Missing value detection
- Handling null values
- Duplicate checking
- Data type conversion
- Feature engineering

### Data Analysis
- Filtering
- Sorting
- value_counts()
- groupby()
- agg()
- pivot_table()

### String Operations
- str.contains()
- str.startswith()
- str.endswith()
- str.len()

### Date & Time Operations
- to_datetime()
- Extracting year, month, weekday
- Date filtering

### NumPy
- Mean
- Median
- Standard Deviation
- Percentiles
- np.where()
- np.unique()

### Data Visualization
- Bar Charts
- Line Charts
- Pie Charts
- Histograms
- Value Annotations
- Grid Styling
- Figure Saving

---

# 📂 Project Structure

```
Netflix-data-analysis/
│
├── Netflix data analysis.ipynb
├── netflix_titles.csv
├── requirements.txt
├── README.md
│
└── graphs/
    ├── Releaseyears.png
    ├── movies&TV.png
    ├── content.png
    ├── actors.png
    ├── directors.png
    └── distributions.png
```

---

# 📈 Visualizations

### Netflix Titles Released Over the Years

<img src="graphs/Releaseyears.png" width="700">

---

### Movies vs TV Shows

<img src="graphs/movies&TV.png" width="500">

---

### Content Distribution

<img src="graphs/content.png" width="500">

---

# 🔍 Key Insights

- Movies significantly outnumber TV Shows.
- The United States has the highest number of Netflix titles.
- India is the second-largest contributor.
- TV-MA is the most common content rating.
- 2018 had the highest number of content releases.
- Rajiv Chilaka directed the most Netflix titles in the dataset.
- Netflix experienced rapid content growth between 2016–2020.

---

# ▶️ How to Run

Clone the repository:

```bash
git clone https://github.com/Adeenaeman/Netflix-data-analysis-.git
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Open:

```
Netflix data analysis.ipynb
```

Run all cells.

---

# 👩‍💻 Author

**Adeena Eman**


GitHub:
https://github.com/Adeenaeman

---

# ⭐ If you found this project useful, consider giving it a Star!
