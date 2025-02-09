# 📺 Netflix Originals Data Exploration and Analysis

## 📌 Project Overview
This project analyzes the **Netflix Originals dataset** to uncover insights about **movie genres, runtime, IMDb scores, and premiere dates**. The goal is to **identify patterns, filter data efficiently, and generate meaningful reports** using advanced **SQL queries**.

## 🎯 Problem Statement
The dataset holds valuable information regarding the content **Netflix produces**, and understanding these attributes can help identify **trends and business opportunities**. The aim is to:
- Perform **complex filtering, aggregation, and sorting** using **MySQL**.
- Extract key insights into **genre popularity, IMDb ratings, and release trends**.
- Implement **data constraints** for validation.

## 🛠️ Technologies Used
- **Database:** MySQL
- **Querying Techniques:** CTEs, Views, Stored Procedures, Subqueries, Window Functions
- **Tools:** SQL Workbench, MySQL CLI

---

## 📂 Dataset Information
| Column Name     | Description |
|----------------|-------------|
| **Title**         | The title of the Netflix Original  |
| **GenreID**       | Genre ID of the movie/show  |
| **Runtime**       | Duration of the movie/show in minutes  |
| **IMDBScore**     | IMDb score of the movie/show  |
| **Language**      | Language in which the movie/show is available  |
| **Premiere_Date** | The date the movie/show premiered  |

---

## 🚀 SQL Query Objectives

### **1️⃣ Filter Movies Based on IMDb Score, Runtime, and Language**
Retrieve all **Netflix Originals** where:
- **IMDb score > 7**
- **Runtime > 100 minutes**
- **Language is English or Spanish**

### **2️⃣ Count Netflix Originals Per Language (With Minimum Threshold)**
Find total **Netflix Originals** in each **language**, but only show those languages **with more than 5 titles**.

### **3️⃣ Top 3 Longest Hindi Movies (Sorted by IMDb Score)**
Retrieve the **top 3 longest-running** Hindi-language movies **sorted by IMDb score** in **descending order**.

### **4️⃣ Filter Titles Containing 'House'**
Retrieve all titles that **contain 'House'** and have an **IMDb score > 6**.

### **5️⃣ Filter Movies Released Between 2018-2020**
Find **Netflix Originals** released between **2018 and 2020** in **English, Spanish, or Hindi**.

### **6️⃣ Find Short Runtime or Low IMDb Score Movies**
Retrieve all movies that:
- Have **runtime < 60 minutes** OR
- Have **IMDb score < 5**
- Sorted by **Premiere Date**

### **7️⃣ Calculate Average IMDb Score Per Genre**
Get the **average IMDb score** for each **genre**, but only if the genre **has at least 10 movies**.

### **8️⃣ Find the Top 5 Most Common Runtimes**
Retrieve the **top 5 most common runtimes** for Netflix Originals.

### **9️⃣ Group Netflix Originals by Language for 2020**
List all **Netflix Originals released in 2020**, grouped by **language**, and display the **total count of titles per language**.

### **🔟 Create a Table with IMDb & Runtime Constraints**
Create a new **table** that:
- **IMDb score must be between 0 and 10**
- **Runtime must be greater than 30 minutes**

---

## 🚀 How to Use
1. **Clone the repository**:
   ```sh
   git clone https://github.com/yourusername/Netflix-Originals-Analysis.git
   ```
2. **Import the dataset** into **MySQL**.
3. **Run the SQL scripts** to execute queries and analyze trends.
4. **Modify constraints and stored procedures** for custom insights.

---

## 📈 Expected Insights
- **Top-performing genres & movies**
- **Popular runtimes & language trends**
- **Automated filtering & ranking using SQL queries**
- **Understanding of movie releases over time**

---

📌 **Author:** P Rohith Raveendran  
🔗 [GitHub Profile](https://github.com/rohithr2511) | 🔗 [LinkedIn Profile](https://www.linkedin.com/in/p-rohith-raveendran-dataanalyst/)  

