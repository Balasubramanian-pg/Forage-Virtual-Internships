### **Part 1: Data Analysis in Excel**  

#### **Step 1: Download & Prepare the Dataset**  
- Open the provided **Excel file** containing Everqlo’s order data.  
- Ensure data cleanliness (check for missing values, duplicates).  

#### **Step 2: Create Age Groups**  
1. **Add a new column** titled **"Age Group"**.  
2. **Use grouping settings**:  
   - **Minimum value**: 18  
   - **Maximum value**: 50  
   - **Interval size**: 5  
   - Resulting groups: **18-22, 23-27, 28-32, 33-37, 38-42, 43-47, 48-50**  

#### **Step 3: Build Pivot Tables for Each Question**  

**1. Age Group Adoption of BNPL**  
- **Rows**: Age Group  
- **Values**: Count of BNPL transactions (filter for BNPL payment method)  
- **Output**: Shows which age group uses BNPL the most.  

**2. BNPL’s Share of Total Transactions**  
- **Rows**: Payment Method  
- **Values**: Count of transactions (or sum of order value)  
- **Calculation**: Add a calculated field to show BNPL as % of total transactions.  

**3. Average Age of BNPL Users**  
- Filter for BNPL transactions only.  
- **Values**: Average of Age  

---

### **Part 2: PowerPoint Slide Creation**  

#### **Slide Structure**  
**Title**: *"BNPL Adoption Trends by Age Group"*  

**Key Observation**:  
*"Customers aged **23-27** use BNPL the most, accounting for **XX%** of transactions in their age group."*  

**Bar Chart Requirements**:  
- **X-axis**: Age Groups (18-22, 23-27, ..., 48-50)  
- **Y-axis**: % of BNPL transactions (**per age group**, not overall)  
- **Chart Type**: Clustered Bar Chart  

**Supporting Comments**:  
1. *"BNPL is **most popular with younger shoppers**, with adoption decreasing after age 30."*  
2. *"The **23-27 age group** has **2X higher BNPL usage** than the 38-42 group."*  

#### **Example Visualization**  
(Insert a **bar chart** here with age groups on the left and % BNPL usage on the bottom.)  

---

### **Final Checks**  
✔ **Pivot Tables**: Correctly grouped age ranges, filtered BNPL transactions.  
✔ **Chart**: Clearly labeled, percentage-based (not raw counts).  
✔ **Slide**: One clear takeaway, minimal text, visually clean.  

