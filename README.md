
# 🍽️ Zomato Data Analysis Project

## 📊 Project Overview
This project focuses on **analyzing restaurant data from Zomato** to uncover trends and insights about restaurant types, ratings, costs, and online order preferences.  
The analysis is performed using **Python (Pandas, Matplotlib, Seaborn)** and visualized using various plots.

---

## 🧠 Objective
The main goal of this analysis is to:
- Understand the relationship between **restaurant type**, **ratings**, and **approximate cost**.
- Analyze **customer preferences** for **online ordering** and **table booking**.
- Visualize **data distributions** and correlations between important factors.

---

## 🗂️ Dataset Information

|           Column Name         |                 Description                      |
|-------------------------------|--------------------------------------------------|
| `name`                        | Name of the restaurant                           |
| `online_order`                | Whether online order is available (Yes/No)       |
| `book_table`                  | Whether table booking is available (Yes/No)      |
| `rate`                        | Average rating of the restaurant                 |
| `votes`                       | Number of customer votes                         |
| `approx_cost(for two people)` | Approximate cost for two people                  |
| `listed_in(type)`             | Type of restaurant (Buffet, Cafes, Dining, etc.) |

---

## 🗂️ Outputs 

<img width="694" height="305" alt="Screenshot (15)" src="https://github.com/user-attachments/assets/6d39f70e-5a6e-4e83-ac26-060d4a1a9d33" />
<img width="665" height="328" alt="Screenshot (16)" src="https://github.com/user-attachments/assets/6b3a6a07-d53f-4f95-9f25-74fe273149c1" />
<img width="709" height="346" alt="Screenshot (17)" src="https://github.com/user-attachments/assets/e1435785-cb7b-4350-96c9-babd597987a4" />
<img width="542" height="245" alt="Screenshot (18)" src="https://github.com/user-attachments/assets/186ed897-9cc9-45e4-acea-cb2a9c705aa4" />
<img width="868" height="106" alt="Screenshot (21)" src="https://github.com/user-attachments/assets/3a3a9ebf-6c13-4666-b6e9-fbf3d2bca505" />

---

## 📈 Visualizations & Insights

### 1️⃣ Distribution of Approximate Cost
<img width="699" height="534" alt="Screenshot (24)" src="https://github.com/user-attachments/assets/990cbe67-e412-42f9-8e3a-77d4ca031dce" />

- Most restaurants have an approximate cost between **200–400 INR** for two people.
- High-cost restaurants are less frequent.

---

### 2️⃣ Online Order vs Rating
<img width="676" height="649" alt="Screenshot (25)" src="https://github.com/user-attachments/assets/61f65ec6-7e35-4071-a785-dd7058d15e2a" />
- Restaurants offering **online orders** tend to have **higher ratings**.
- This indicates customers prefer and rate online-order-enabled restaurants better.

---

### 3️⃣ Heatmap: Restaurant Type vs Online Order
<img width="665" height="555" alt="Screenshot (26)" src="https://github.com/user-attachments/assets/e03267be-18cd-4767-90dd-7d745fb93a8d" />


- **Dining** is the most common restaurant type.
- A majority of **Dining** restaurants **do not offer online orders**, while **Cafes** tend to offer them more frequently.

---

### 4️⃣ Restaurant Type Distribution
<img width="712" height="538" alt="Screenshot (19)" src="https://github.com/user-attachments/assets/556f8822-695d-4153-832c-1b8ddd5c4ccf" />
- The dataset is dominated by **Dining** restaurants.
- **Cafes** and **Buffets** are less common.

---

### 5️⃣ Type of Restaurant vs Votes
<img width="748" height="550" alt="Screenshot (20)" src="https://github.com/user-attachments/assets/94758474-e74d-4123-9645-78f3a21f6055" />
- **Dining** restaurants receive the highest number of votes.
- This indicates they attract more customers and engagement.

<img width="677" height="536" alt="Screenshot (23)" src="https://github.com/user-attachments/assets/0cd4e6a9-d7ef-4f89-b257-b2ba80ac8a0c" />

<img width="699" height="525" alt="Screenshot (22)" src="https://github.com/user-attachments/assets/7ae2088d-59d6-4cf6-973b-b1907f80e40f" />

---

## 💡 Key Findings
- **Online ordering** is correlated with **higher ratings**.
- **Dining** type restaurants dominate the dataset and receive the most **votes**.
- **Approximate cost** for two people is generally under **₹400**, making mid-range restaurants more popular.
- **Cafes** and **Buffets** are niche but have steady customer bases.

---

## 🧰 Tools & Technologies Used
- **Python**
  - Pandas 🐼
  - Matplotlib 📊
  - Seaborn 🎨
- **Jupyter Notebook / Google Colab**
- **Data Cleaning, EDA & Visualization**

---
