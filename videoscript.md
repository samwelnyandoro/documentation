# 🎤 AT2 Data Analytics Video Script

---

## **[INTRO — 20 seconds]**

Hi, my name is **[Your Name]**.  
In this video, I'll be walking through my AT2 data analytics submission.

I've chosen the **University Students Performance and Study Habits 2026** dataset from Kaggle, which explores how factors like study hours, sleep, stress, and AI tool usage relate to student academic performance.

---

## **[DATASET OVERVIEW — 35 seconds]**

Here’s the dataset on Kaggle.

It contains **10,000 student records** and over **15 attributes**, covering:
- Numerical variables like GPA, study hours, and sleep duration  
- Categorical variables like gender and field of study  

It also contains **missing values across several columns**, which gave me the opportunity to apply real data cleaning as part of the task.

---

## **[LOADING THE DATA — 35 seconds]**

Moving into the notebook:

The first thing I did was load the dataset into a **Pandas DataFrame** using `read_csv`.

I then:
- Displayed the first and last five rows to verify it loaded correctly  
- Used `df.info()` to check data types and non-null counts  

As you can see, the dataset has a mix of:
- Float  
- Integer  
- Object columns  

There are also a small number of missing values in certain fields.

---

## **[VARIABLE SELECTION — 25 seconds]**

Next, I selected the variables relevant to my analysis.

I:
- Dropped the **student ID column** since it has no analytical value  
- Removed columns with more than **40% missing data** to avoid bias  

The remaining variables include:
- GPA  
- Study hours  
- Sleep  
- Stress level  
- AI usage  
- Social media hours  
- Attendance  

These were retained because they directly relate to my research objective.

---

## **[EDA — 60 seconds]**

For the exploratory data analysis:

I used:
- **Pandas** for descriptive statistics  
- **Seaborn** and **Matplotlib** for visualisations  

### Key insights:
- GPA is approximately **normally distributed** with a slight left skew  
- Study hours show **high variability** (under 5 to over 30 hours/week)  
- Sleep duration is **right-skewed**, meaning many students sleep fewer than 6 hours  

### Visual findings:
- Histograms confirm these patterns  
- Bar charts show:
  - Balanced gender distribution  
  - Representation across multiple fields  
- Box plots reveal:
  - A few outliers in study hours  
  - Outliers in social media usage  

---

## **[CORRELATION ANALYSIS — 55 seconds]**

Now for the correlation matrix:

I computed **Pearson correlation coefficients** and visualised them using a heatmap:
- **Red = positive relationships**  
- **Blue = negative relationships**

### Key findings:
- Study hours vs GPA → **~ +0.6 (moderate positive)**  
- Attendance vs GPA → **~ +0.6 (moderate positive)**  
- Stress vs GPA → **~ –0.52 (moderate negative)**  
- Sleep vs GPA → **~ +0.45 (moderate positive)**  

### Interesting insight:
AI tool usage shows a **weak positive correlation overall**, but:
- Moderate users perform best  
- Very low or very high usage performs worse  

This suggests **over-reliance may be counterproductive**.

---

## **[GROUP-BASED CORRELATION — 40 seconds]**

To go deeper, I segmented the data by:
- Gender  
- Field of study  

### Findings:
- Stress vs GPA:
  - Female students → **~ –0.61 (stronger negative)**  
  - Male students → **~ –0.43**  

- Sleep vs GPA:
  - Stronger for **STEM students**  
  - Weaker for **humanities students**  

This may reflect the **higher cognitive demands** of STEM coursework.

---

## **[CLOSING — 20 seconds]**

To summarise:

- **Positive predictors of performance:**
  - Study hours  
  - Attendance  
  - Sleep  

- **Negative predictor:**
  - Stress  

Group-based analysis shows these relationships **vary across gender and field of study**, adding deeper insight to the findings.

**Thanks for watching.**

---

## ⏱️ **Total Time**
Approximately **4 to 4.5 minutes** at a natural speaking pace.

💡 *Tip:* Do one practice run before recording so transitions between notebook sections feel smooth.