# 🚴‍♂️ Bike Sales Analysis Dashboard

## 📊 Project Overview

An interactive Excel dashboard analyzing bike purchase patterns based on demographic and socioeconomic factors. This project transforms raw customer data into actionable business insights using pivot tables, data cleaning techniques, and dynamic visualizations.

---

## 🎯 Key Insights

### 1. **Income Analysis**
- Bike buyers demonstrate **higher average incomes** across both genders
- Male buyers represent the **highest-income segment**
- Clear correlation between purchasing power and bike ownership

### 2. **Commute Distance Impact**
- **0-5 miles**: Highest bike purchase rate (optimal commuting distance)
- **5+ miles**: Significant drop in purchases (cars/public transit preferred)
- **Business Opportunity**: Target customers within 5-mile radius of workplace

### 3. **Age Demographics**
- **Middle-aged customers** show peak buying interest
- Both buyer and non-buyer groups peak at middle age
- **Older demographic** shows significant purchase decline

---

## 🛠️ Technical Implementation

### Data Preparation & Cleaning

1. **Project Structure Setup**
   - Created three main tabs: Dashboard, Working Sheet, Pivot Table
   - Organized data flow for efficient analysis

2. **Data Quality**
   - Removed duplicate entries to ensure accuracy
   - Maintained data integrity throughout analysis

3. **Data Transformation**
   ```
   Marital Status: M → Married, S → Single (Ctrl+H)
   Gender: M → Male, F → Female (Ctrl+H)
   Income: Formatted as currency for readability
   ```

4. **Feature Engineering**
   - Created **Age Bracket** column for demographic segmentation
   - Applied conditional logic for age categorization:
   ```excel
   =IF(L2>54,"Old", IF(L2>=31, "Middle aged", IF(L2<31,"Adolescent","Invalid")))
   ```
   - Categories: Adolescent (<31), Middle aged (31-54), Old (>54)

### Dashboard Components

#### 📈 Pivot Table 1: Income by Gender & Purchase Status
- **Insight**: Higher average income among bike buyers
- **Variables**: Gender, Income, Purchase Status
- **Visual**: Column chart comparing income levels

#### 🚗 Pivot Table 2: Commute Distance Analysis
- **Insight**: Strong inverse correlation between distance and purchase rate
- **Variables**: Commute Distance, Purchase Status
- **Visual**: Line graph showing purchase trends by distance

#### 👥 Pivot Table 3: Age Bracket Demographics
- **Insight**: Middle-aged segment drives highest engagement
- **Variables**: Age Bracket, Purchase Status
- **Visual**: Dual-line comparison of buyers vs. non-buyers

---

## 📈 Business Recommendations

### Target Marketing Strategy

1. **Primary Audience**: Middle-aged professionals with short commutes
2. **Geographic Focus**: Areas with high concentration of 5-mile commuters
3. **Value Proposition**: 
   - Convenience and time-saving
   - Health and fitness benefits
   - Cost savings vs. driving/parking

### Implementation Tactics

- Develop marketing campaigns targeting 30-55 age group
- Partner with companies for employee bike programs
- Focus advertising in urban areas with short-distance commuters
- Emphasize environmental and economic benefits

---



---

## 🔧 Tools & Technologies

- **Microsoft Excel**: Data cleaning, analysis, and visualization
- **Pivot Tables**: Dynamic data summarization
- **Conditional Functions**: IF statements for data categorization
- **Data Validation**: Find & Replace for standardization

---

## 📊 Dataset Information

**Source**: Customer bike purchase dataset  
**Records**: 1,000+ customer entries  
**Features**: 13 variables including demographic and behavioral data

### Key Variables:
- ID, Marital Status, Gender, Income
- Children, Education, Occupation
- Home Owner, Cars, Commute Distance
- Region, Age, Purchase Status

---

## 🚀 How to Use

1. **Download** the Excel file from this repository
2. **Enable Content** if prompted (for formulas and pivot tables)
3. **Navigate to Dashboard** tab for interactive visualizations
4. **Use Slicers** (if implemented) to filter by different criteria
5. **Explore Pivot Tables** for detailed breakdowns

---

## 📸 Dashboard Preview

<img width="1058" height="631" alt="image" src="https://github.com/user-attachments/assets/e9b12e23-f02c-470e-8b3e-f7913b048579" />


---

## 🎓 Learning Outcomes

This project was completed as part of following Alex The Analyst's Excel tutorial series. Through this hands-on exercise, I developed skills in:

- Data cleaning and standardization techniques in Excel
- Advanced Excel formulas and conditional logic (nested IF statements)
- Pivot table creation, configuration, and analysis
- Dashboard design and data visualization best practices
- Translating data insights into business recommendations
- Professional project documentation and presentation

**Key Takeaway**: The project demonstrates how Excel can be used as a business intelligence tool, transforming raw data into actionable insights that drive strategic decision-making.



---

## 👤 Author

**Saniya**
- GitHub: [@saniyakhan17]
- LinkedIn: [www.linkedin.com/in/saniya--khan]

---

## 🙏 Acknowledgments

This project was completed following the Excel tutorial series by **Alex The Analyst**:
- **Tutorial**: [Excel Project: Bike Sales Dashboard](https://www.youtube.com/watch?v=opJgMj1IUrc&list=PLUaB-1hjhk8FE_XZ87vPPSfHqb6OcM0cF&index=31)
- **Instructor**: Alex The Analyst
- **YouTube Channel**: [@AlexTheAnalyst](https://www.youtube.com/@AlexTheAnalyst)
