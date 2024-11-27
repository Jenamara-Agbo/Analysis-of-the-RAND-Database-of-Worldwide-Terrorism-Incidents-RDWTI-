# Analysis of the RAND Database of Worldwide Terrorism Incidents (RDWTI)

This repository contains a comprehensive analysis of the RAND Database of Worldwide Terrorism Incidents (RDWTI), a dataset spanning terrorism incidents from 1968 to 2009. The analysis explores patterns, trends, and significant findings related to terrorism incidents globally, leveraging Python-based data processing and visualization techniques.

## Dataset Overview

The RDWTI is a legacy RAND project that documents over **40,000 terrorism incidents** with detailed information on:
- **Date, Location, and Perpetrators**
- **Weapons, Injuries, and Fatalities**
- **Incident Descriptions**

The data was downloaded from [RAND's official website](https://www.rand.org/nsrd/projects/terrorism-incidents.html) and processed into a **CSV file** for analysis.

## Key Analyses and Findings

### 1. **Top 5 Countries with the Most Terrorism Incidents**
- Iraq recorded the **highest number of incidents** with over 10,000 attacks.
- Other hotspots included **West Bank/Gaza**, **Afghanistan**, **Thailand**, and **Colombia**.

#### Visualization:
![Bar Chart](assets/top5_countries.png)

### 2. **Top 10 Most Deadly Attacks**
- The deadliest incident occurred in the **United States**, with **2,749 fatalities** (likely referencing the 9/11 attacks).
- Other major incidents took place in **Iraq**, **Algeria**, **Russia**, and **India**.

#### Visualization:
![Horizontal Bar Chart](assets/top10_deadly_attacks.png)

### 3. **Kidnapping-Related Incidents**
- Over **4,291 incidents** mentioned terms like "kidnap," "abduction," or "hostage."
- **33% of kidnapping-related incidents resulted in fatalities.**

#### Top Countries for Kidnapping Mentions:
1. Iraq
2. Colombia
3. Afghanistan
4. Lebanon
5. Kashmir

#### Visualization:
![Stacked Bar Chart](assets/kidnapping_mentions_by_country.png)

### 4. **Incidents Involving Ransom**
- Only **4.33%** of kidnapping-related incidents mentioned the word "ransom."
- Top countries for ransom-related incidents include **Iraq** and **Colombia.**

#### Visualization:
![Pie Chart](assets/ransom_mentions_pie.png)

### 5. **"Students" as Perpetrators**
- "Students" were mentioned as perpetrators in **6 incidents** (~0.01% of the total).

#### Visualization:
![Donut Chart](assets/student_involvement_donut.png)

### 6. **First Incident Mentioning a "Suicide Bomber"**
- The **first mention** of a suicide bomber occurred in **1985 in Lebanon**, involving a car-bomb attack on Israeli soldiers.

### 7. **Mentions of "Priests" or "Clergy"**
- Terms like "priests" or "clergy" appeared in **23 incidents.**

#### Visualization:
![Donut Chart](assets/priests_mentions_donut.png)

### 8. **Women as Terrorists**
- The dataset did not identify any incidents where **women** were explicitly named as perpetrators.

## Installation and Usage

To replicate the analysis, follow these steps:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-username/RDWTI-Terrorism-Analysis.git
   cd RDWTI-Terrorism-Analysis
