# Game-App-User-Analytics-Behavioral-Revenue-Insights
Analyzed player behavior and monetization metrics in a mobile game: D1/D3/D7 retention, ARPU, session length, and level pass rates. Segmented users (high-value, skilled) to support game design optimization and revenue growth strategy.
---

##  Dataset

- **Source**: In-app player activity logs (session, payment, attempts, levels, outcomes)
- **Rows**: 3,659 sessions  
- **Unique Users**: 1,234 UserIDs  
- **Format**: Excel (.xlsx)

---

##  Key Analyses

### A. Core Metrics
1. **Retention D1, D3, D7**  
   - D1 = 35.98%, D3 = 30.88%, D7 = 34.44%

2. **ARPU D7**  
   - $12.34 per user in the first 7 days

3. **Pass Rate at Levels 1, 5, 10**  
   - Ranging from 50% to 56%, used to assess game difficulty

4. **Average Session Length per Level**  
   - From ~28 to ~36 minutes depending on level

---

### B. User Segmentation

5. **High-Value Users** (Total Payment > $5)  
   - ~38% of users, indicating strong monetization potential  
   - Fields: UserID, Country, Total Payment, Total Session

6. **Skilled Users** (Pass Rate > 80%, Avg Attempts < 2)  
   - Highest percentages in Japan and Korea  
   - Used to tailor difficulty and content by market

---

### C. Visualizations & Insights (via Tableau)

- **Retention Curve**
- **Revenue by Country**
- **Histogram of Session Length**

---

##  Key Insights & Actionable Suggestions

- Day-1 retention is highest → Enhance onboarding and day-1 rewards
- Drop in D3 retention suggests a lack of engagement → Introduce new content/events early
- High-value users should receive personalized offers and VIP packages
- Skilled users concentrated in JP/KR → Consider localized difficulty tuning
- Most sessions last 5–25 mins → Optimize content for short to medium play durations

---

## Tools Used

- **Excel**: Pivot Tables, conditional formatting, formulas
- **Python**: Data validation, cleaning

---

## Files Included

| File Name                        | Description                                      |
|----------------------------------|--------------------------------------------------|
| `game-user-analytics-data.xlsx` | Raw data and computed sheets                    |
| `game-user-analytics-report.pdf`| Step-by-step methodology and insight report     |

---

## Author

**Cao Đỗ Gia Khanh**  
Intern Data Analyst  
Email: caokhanh.gt2004@gmail.com
