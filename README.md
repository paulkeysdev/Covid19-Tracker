# COVID-19 Global Data Tracker

## 📌 Project Overview
The COVID-19 pandemic has significantly impacted global health, economies, and daily life. Understanding the trends in infections, vaccinations, and mortality rates is critical for assessing responses and improving future preparedness. This project analyzes **global COVID-19 trends** with a focus on **Kenya, Uganda, and Tanzania**, leveraging the **Our World in Data (OWID) COVID-19 dataset**.

## 🚀 Objectives
- 🗂 **Import & Clean COVID-19 Data**
- 📊 **Analyze Trends in Cases, Deaths, and Vaccinations**
- 🌍 **Compare Metrics Across Countries**
- 🎨 **Visualize Trends with Charts & Maps**
- 📝 **Communicate Findings in a Jupyter Notebook or Report**

## 🛠 Tools Used
- **Python Libraries**: `pandas`, `matplotlib`, `seaborn`, `plotly.express`
- **Dataset**: [Our World in Data COVID-19](https://github.com/owid/covid-19-data)
- **Development Environment**: Jupyter Notebook

## 📂 Project Structure
Certainly! Here's a well-structured `README.md` file for your **COVID-19 Global Data Tracker** project:

```md
# COVID-19 Global Data Tracker

## 📌 Project Overview
The COVID-19 pandemic has significantly impacted global health, economies, and daily life. Understanding the trends in infections, vaccinations, and mortality rates is critical for assessing responses and improving future preparedness. This project analyzes **global COVID-19 trends** with a focus on **Kenya, Uganda, and Tanzania**, leveraging the **Our World in Data (OWID) COVID-19 dataset**.

## 🚀 Objectives
- **Import & Clean COVID-19 Data**
- **Analyze Trends in Cases, Deaths, and Vaccinations**
- **Compare Metrics Across Countries**
- **Visualize Trends with Charts & Maps**
- **Communicate Findings in a Jupyter Notebook or Report**

## 🛠 Tools Used
- **Python Libraries**: `pandas`, `matplotlib`, `seaborn`, `plotly.express`
- **Dataset**: [Our World in Data COVID-19](https://github.com/owid/covid-19-data)
- **Development Environment**: Jupyter Notebook

## 📊 Data Analysis Steps
### 1️⃣ Data Collection  
✅ Download `owid-covid-data.csv` from [Our World in Data](https://github.com/owid/covid-19-data).  
✅ Save the dataset in the `data/` folder.  

### 2️⃣ Data Loading & Exploration  
- Import the dataset using `pandas.read_csv()`.  
- Explore columns, missing values, and initial summaries.  

### 3️⃣ Data Cleaning  
- Convert `date` column to **datetime format**.  
- Filter data for Kenya, Uganda, and Tanzania.  
- Handle missing values using interpolation or `fillna()`.  

### 4️⃣ Exploratory Data Analysis (EDA)  
- Line plots for **cases & deaths over time**.  
- Bar charts for **top affected countries**.  
- Compute **death rates** using `total_deaths / total_cases`.  

### 5️⃣ Visualizing Vaccination Progress  
- Line charts showing **cumulative vaccinations**.  
- Pie charts comparing **vaccinated vs. unvaccinated populations**.  

### 6️⃣ Optional: Choropleth Map  
- Visualize **case densities** globally using `plotly.express`.  
- Geospatial plotting with `geopandas`.  

### 7️⃣ Insights & Reporting  
- Write **3-5 key insights** using Markdown cells in Jupyter Notebook.  
- Export findings to a **PDF or PowerPoint** report for presentation.  

## 🔎 Sample Insights
1️⃣ Kenya had the highest reported cases among the three countries, reflecting higher testing rates.  
2️⃣ Uganda's case trends showed distinct peaks, influenced by strict government interventions.  
3️⃣ Tanzania reported significantly fewer cases, likely due to differences in data collection and public health responses.  
4️⃣ The waves of infection align with major global variants such as **Delta and Omicron**.  
5️⃣ Vaccination rollout played a critical role in slowing down case surges in later months.  

## 💡 How to Run the Project
1. Clone this repository:  
   ```sh
   git clone https://github.com/your-username/covid19-global-data-tracker.git
   ```
2. Install dependencies:  
   ```sh
   pip install pandas matplotlib seaborn plotly
   ```
3. Open the Jupyter Notebook:  
   ```sh
   jupyter notebook notebooks/covid19_analysis.ipynb
   ```
4. Run the analysis and explore visualizations.
 
.  

## 📝 License  
This project is open-source under the MIT License.  


