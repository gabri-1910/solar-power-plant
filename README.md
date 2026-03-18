Great — now that I’ve actually read your notebook, I can build a **100% accurate README** tailored to your project (not a generic one).

Here’s your complete, polished README 👇

---

# 🌞 Solar Power Plant – Brazil Irradiation Analysis

This project analyzes **solar irradiation across Brazil** to identify the best location for installing a **solar power plant**. It combines geospatial data, energy metrics, and visualization techniques to support strategic decision-making.

---

## 📌 Project Objective

The goal of this project is to answer a real-world question:

> *Where is the best location in Brazil to install a solar power plant?*

To achieve this, the project:

* Analyzes **solar irradiation data**
* Maps geographic distribution across Brazil
* Evaluates seasonal variation
* Considers **infrastructure constraints** (power grid)
* Narrows down optimal regions and cities

---

## 📊 Key Features

* ☀️ Solar irradiation analysis (monthly averages)
* 🗺️ Geospatial mapping using shapefiles
* 📍 Identification of high-potential regions
* 📈 Seasonal trend visualization
* ⚡ Integration with power grid data
* 🌐 Interactive map visualization with Folium

---

## 🛠️ Technologies Used

* **Python 3**
* **Pandas** – data manipulation
* **GeoPandas** – geospatial analysis
* **Shapely** – geometry handling
* **Matplotlib** – data visualization
* **Folium** – interactive maps

---

## 📂 Project Structure

```bash
solar-power-plant/
│
├── brazil-solar-irradiation-per-state.ipynb   # Main analysis notebook
├── data/                                      # (Kaggle datasets - external)
├── shapefiles/                                # Geographic data (states, cities)
└── README.md
```

> ⚠️ Note: The datasets used in this project are loaded from Kaggle input paths (`../input/...`), so they are not included in the repository.

---

## 📥 Data Sources

The project uses multiple datasets, including:

* Solar irradiation data (monthly averages)
* Brazilian states shapefile
* City-level geographic data
* Power grid transmission lines

These datasets are typically sourced from **Kaggle** and public GIS repositories.

---

## 🔎 Methodology

### 1. Data Loading

* Import solar irradiation dataset
* Load shapefiles for Brazil regions

### 2. Data Transformation

* Convert latitude and longitude into geometry points
* Build a `GeoDataFrame` for spatial analysis

### 3. National Analysis

* Plot irradiation levels across Brazil
* Identify regions with highest solar potential

### 4. Seasonal Analysis

* Visualize irradiation trends over months
* Understand variability throughout the year

### 5. Regional Focus (Bahia)

* Zoom into a high-potential state
* Analyze cities and subregions

### 6. Infrastructure Consideration

* Overlay **power grid distribution lines**
* Evaluate feasibility of energy transmission

### 7. Final Visualization

* Combine:

  * Irradiation data
  * Cities
  * Power grid
* Generate an **interactive map using Folium**

---

## ▶️ How to Run the Project

### 1. Clone the repository

```bash
git clone https://github.com/gabri-1910/solar-power-plant.git
cd solar-power-plant
```

---

### 2. Install dependencies

```bash
pip install pandas geopandas shapely matplotlib folium
```

---

### 3. Run the notebook

```bash
jupyter notebook
```

Open:

```
brazil-solar-irradiation-per-state.ipynb
```

---

## 📈 Example Insights

From the analysis, you can:

* Identify regions with **highest solar irradiation**
* Compare **seasonal stability**
* Select cities with:

  * High solar potential ☀️
  * Proximity to power grid ⚡
  * Geographic feasibility 🗺️

---

## 🌍 Use Cases

* Renewable energy planning
* Government energy policy analysis
* Solar farm site selection
* Academic research in energy & geography
* Data science portfolio project

---

## 🔮 Future Improvements

* 🤖 Add machine learning for energy prediction
* 📡 Integrate real-time weather data
* 🧭 Multi-criteria decision model (cost, terrain, etc.)
* 📊 Dashboard (Streamlit or Power BI)
* 🌎 Expand analysis to all Latin America

---

## ⚠️ Limitations

* Data sourced externally (not included in repo)
* Analysis depends on dataset quality
* Does not include economic cost modeling
* Infrastructure analysis is simplified

---

## 👨‍💻 Author

**Gabriel da Silva Araújo**

* GitHub: [https://github.com/gabri-1910](https://github.com/gabri-1910)
* Location: Pará, Brazil 🇧🇷

---

## 🌱 Final Thoughts

This project demonstrates how **data analysis + geospatial intelligence** can be applied to solve real-world energy problems.

It’s a strong example of:

* Data science applied to sustainability
* Practical use of GeoPandas
* Decision-making with real datasets

---

## ⭐ If you like this project

Give it a star on GitHub and feel free to contribute!

---
* Or even a **business idea for solar in your region** ⚡
