# 📱 Screen Time Impact Analysis

This repository contains an exploratory data analysis (EDA) and statistical insights project investigating the **impact of screen time** on various aspects such as productivity, sleep, and health. The analysis is performed in a Jupyter Notebook (`ScreenTime_Impact.ipynb`) using Python’s data analysis and visualization libraries.

---

## 📌 Project Overview

Excessive screen time is increasingly linked to **reduced productivity, poor sleep quality, and health issues**. This project analyzes real or sample datasets to uncover:

- **Trends** in daily screen time usage  
- **Correlations** between screen time and health/productivity indicators  
- **Potential thresholds** where screen time becomes harmful  

---

## 🛠️ Tech Stack

- **Language:** Python 3.x  
- **Libraries:**
  - `pandas` – Data manipulation
  - `numpy` – Numerical operations
  - `matplotlib` / `seaborn` – Visualization
  - `scipy` – Statistical analysis
  - `sklearn` – Machine learning utilities

---

## 📊 Analysis Highlights

### 1️⃣ Screen Time Distribution
![Screen Time Distribution](plots/plot_1.png)

- Shows the spread of daily screen time usage among participants.  
- Most participants fall between **4–8 hours per day**.

---

### 2️⃣ Screen Time vs. Sleep Hours
![Screen Time vs Sleep](plots/plot_2.png)

- Clear **negative correlation** between screen time and average sleep duration.  
- High screen time often coincides with reduced sleep.

---

### 3️⃣ Weekly Trends
![Weekly Trends](plots/plot_3.png)

- Weekend spikes indicate higher entertainment usage.  
- Weekdays show more consistent work-related screen time.

---

### 4️⃣ Age Group Comparison
![Age Group Comparison](plots/plot_4.png)

- Younger participants (18–25) exhibit **higher average screen time**.  
- Older groups maintain steadier and lower usage patterns.

---

### 5️⃣ Productivity Impact
![Productivity Impact](plots/plot_5.png)

- Productivity drops sharply when screen time exceeds **8 hours**.  
- Moderate usage (4–6 hours) aligns with peak productivity.

---

## 🚀 Getting Started

### 1️⃣ Clone the repository
```bash
git clone https://github.com/<your-username>/ScreenTime_Impact.git
cd ScreenTime_Impact
```

### 2️⃣ Install dependencies
```bash
pip install -r requirements.txt
```

### 3️⃣ Run the notebook
```bash
jupyter notebook ScreenTime_Impact.ipynb
```

---

## 📌 Key Findings
- Average daily screen time exceeds **6 hours** for most participants  
- **Negative correlation** between screen time and sleep hours  
- Productivity is significantly lower beyond **8 hours/day** usage  

---

## 📜 License
This project is licensed under the **MIT License** – see the [LICENSE](LICENSE) file.

---

## 🤝 Contributing
Contributions, issues, and feature requests are welcome!  
Open a pull request or report bugs.
