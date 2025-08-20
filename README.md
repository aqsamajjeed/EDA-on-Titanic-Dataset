# 🚢 Titanic Dataset - Exploratory Data Analysis (EDA)

This project performs **Exploratory Data Analysis (EDA)** on the famous Titanic dataset from Kaggle.

The aim of this project is to analyze passenger survival rates based on demographic and socio-economic factors such as gender, age, class, fare, and family size.

---

## 📂 Project Structure
- `Titanic Dataset.csv` → Dataset used in this analysis.
- `titanic_eda.ipynb` → Jupyter Notebook with full code and analysis.
- `README.md` → Project documentation.

---

## 🔧 Tools & Libraries
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn

---

## 🧹 Data Cleaning
- Handled missing values:
  - `Age` filled with median
  - `Embarked` filled with mode
  - `Cabin` simplified (first letter, unknowns marked as `U`)
- Dropped unnecessary columns: `Name`, `Ticket`
- Encoded categorical variables (`Sex`, `Embarked`, `Cabin`)

---

## 📊 Analysis & Visualizations
1. **Survival by Gender**
   - Females: ~74% survived
   - Males: ~19% survived  

2. **Survival by Passenger Class**
   - 1st Class: ~63% survival  
   - 3rd Class: ~24% survival  

3. **Age Distribution by Survival**
   - Children had the best survival chances
   - Elderly (50+) had the lowest survival

4. **Fare vs Survival**
   - Survivors paid significantly higher fares → higher-class passengers had better chances  

5. **Family Size vs Survival**
   - Small families (2–4 members) had higher survival
   - Solo travelers & large families fared worse  

6. **Correlation Heatmap (Key Features)**
   - Survival strongly correlated with `Sex`, `Pclass`, and `Fare`

7. **Class + Gender Interaction**
   - 1st & 2nd class females had the highest survival  
   - 3rd class males had the lowest  

8. **Heatmap of Survival (Gender vs Class)**
   - Confirms “women and children first” and survival inequalities by class

---

## 📌 Key Insights
- **Gender mattered most**: Females had much higher survival chances.
- **Class determined fate**: Wealthier (1st-class) passengers survived more.
- **Children were prioritized**, while elderly survival was poor.
- **Fare strongly linked** to survival (economic privilege).
- **Family size mattered**: medium-sized families had advantages.

---

## 🏁 Executive Summary
This analysis highlights the **social and economic inequalities** in Titanic survival rates.  
Survival was shaped by **gender, class, and age**, with women, children, and wealthy passengers enjoying the highest chances of survival, while 3rd-class men had the worst odds.

---

## 📌 How to Run
1. Clone this repository  
   ```bash
   git clone https://github.com/yourusername/titanic-eda.git
   cd titanic-eda
