# 🚦 BTS Transportation Data Analysis Project

## 📌 Project Overview

Transportation systems are crucial for the movement of goods, services, and people, and play a vital role in economic growth and public well-being. This project aims to uncover insights and inefficiencies in U.S. transportation data across multiple modes: road, rail, air, and water.

By leveraging BTS data, this project identifies patterns, trends, and actionable recommendations using the **CRISP-DM** methodology.

---

## 🛠 Tools & Technologies Used

| Tool | Description |
|------|-------------|
| **Python** | Main programming language used for data analysis |
| **Pandas / NumPy** | Data cleaning, manipulation, and statistical summaries |
| **Matplotlib / Seaborn / Plotly** | Data visualizations |
| **Visual Studio** | Interactive coding and analysis |
| **Git / GitHub** | Version control and project tracking |
| **PowerPoint / Google Slides** | Final presentation and business insights summary |

---

## 📊 Dataset

The dataset was provided by the **Bureau of Transportation Statistics** and is available in the file `data.zip`. It includes various transportation metrics across the U.S., such as:

- Passenger travel volumes  
- Freight movement statistics  
- Safety incident reports  
- Infrastructure capacities  
- Environmental impact metrics  

**📁 Dataset structure and documentation** is included in the `data/` folder.

---

## 📈 CRISP-DM Framework Implementation

### 1. **Business Understanding**
We aim to answer the following analytical questions:

1. What transportation mode contributes most to safety incidents?
2. How has passenger travel changed over the last decade?
3. Which states show the highest congestion rates?
4. What are the environmental impacts by mode of transport?
5. Is there a correlation between infrastructure quality and incident frequency?
6. How do seasonal changes affect freight movement?
7. What are the trends in air travel delays?

---

### 2. **Data Understanding & Preparation**

- Data loaded from multiple monthly reports  
- Merged and cleaned datasets for consistency  
- Missing values handled appropriately  
- Data types standardized  
- New features such as `year`, `month`, and `mode_category` created  

---

### 3. **Exploratory Data Analysis & Visualizations**

Key visualizations include:

- Trends of travel volume over time  
- Incident counts by transportation mode  
- Heatmaps showing correlations  
- Environmental emission comparisons across modes  


---

### 4. **Evaluation & Insights**

- Detailed conclusions drawn per business question  
- Limitations acknowledged (e.g., missing values, reporting inconsistencies)  
- Key performance indicators identified  

---

### 5. **Deployment / Reporting**

- All findings are summarized in the final presentation file (`presentation.pptx`)  
- This repository serves as the full documentation and analysis archive  

---

## 📁 Project Structure
├── data/ # Contains raw and processed data files (or use a download link)
├── notebooks/ # Jupyter notebooks used for data exploration and analysis
├── scripts/ # Python scripts (if applicable)
├── visualizations/ # Charts, graphs, or dashboards
├── presentation/ # Final presentation file (PDF or PowerPoint)
├── README.md # Project documentation
