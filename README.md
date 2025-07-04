# Task 2 – NYC Airbnb Listings Analysis (2019)

This Jupyter notebook explores and visualizes the **NYC Airbnb Open Data 2019** dataset using interactive Plotly charts and basic statistical tests. It reveals patterns in listing distribution, room‐type pricing, and neighbourhood differences to help understand the New York short‑term rental market.

---

## 📌 Objective

* **Exploratory Data Analysis (EDA)** of key features such as borough, room type, price, minimum nights, and review metrics.
* **Interactive visualisations** that communicate insights clearly (histograms, bar charts, heat‑map, box‑plots, violin plots, donut chart).
* **Statistical comparison** of average listing prices between Manhattan and Brooklyn using an independent two‐sample *t*‑test.

---

## 🧾 Dataset



*Source*: [https://www.kaggle.com/datasets/dgomonov/new-york-city-airbnb-open-data](https://www.kaggle.com/datasets/dgomonov/new-york-city-airbnb-open-data)
*File used*: **`AB_NYC_2019.csv`** (≈ 2 MB). Place it inside the `task_2/` directory or change the notebook path.

---

## 📁 Repository Structure

```
task_2/
├── task_2.ipynb        # Main Jupyter notebook
├── README.md           # Project documentation (this file)
├── requirements.txt    # Python dependencies
└── AB_NYC_2019.csv     # (Optional) Dataset file
```

---

## 📊 Visualisations & Analyses

| Chart / Test                                    | Insight Delivered                                         |
| ----------------------------------------------- | --------------------------------------------------------- |
| **Histogram** of `neighbourhood_group`          | Listing counts across the five boroughs                   |
| **Histogram** of `room_type`                    | Supply share of entire homes, private rooms, shared rooms |
| **Bar plot** of average `price` by room type    | Which room type commands the highest nightly price        |
| **Donut chart** (top borough share)             | Contribution of each borough to total listings            |
| **Correlation heat‑map** (numeric fields)       | Relationships among price, nights, reviews, availability  |
| **Violin / box plots** of `price` per borough   | Price distribution spread and outliers                    |
| **Two‑sample *t*‑test** (Manhattan vs Brooklyn) | Statistical significance of price difference              |

All plots use the **Plotly Dark** template for a modern aesthetic and include intuitive titles and annotations.

---

## 📦 Requirements

Create (optionally) a virtual environment and install dependencies:

```bash
python -m venv venv  # Windows: py -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate
pip install -r requirements.txt
```

`requirements.txt` contains (minimum versions):

```
pandas>=2.2
plotly>=5.24
scipy>=1.12
```

---

## 🚀 How to Run

```bash
git clone https://github.com/your‑username/task_2.git
cd task_2
jupyter notebook task_2.ipynb
```

Run the cells sequentially; the notebook is designed to work top‑to‑bottom with minimal configuration.

---

## ✅ Conclusion

This mini‑project showcases how to transform raw Airbnb listing data into compelling visual stories and simple statistical conclusions. It is ideal for learners practicing **EDA**, **Plotly visualisation**, and basic **hypothesis testing** in Python.

---

## 📜 License

Released under the **MIT License** – see the [LICENSE](LICENSE) file for details.
