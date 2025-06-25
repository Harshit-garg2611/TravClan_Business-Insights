# TravClan_Business-Insights
---

## 📁 Project Overview

This project analyzes travel booking data from TravClan using Python and visualizes actionable business insights through a PowerPoint presentation. The goal is to derive key patterns, identify problems, and suggest strategies to enhance sales and profitability.

---

## 🧰 Tools & Technologies Used

- **Python**: Data cleaning, analysis, and visualization  
- **Jupyter Notebook**: Interactive Python coding  
- **Libraries**: `pandas`, `matplotlib`  
- **Microsoft PowerPoint**: Visual representation of business insights  
- **Dataset**: `Dataset -2.csv`

---

## 📄 Files in This Project

| File Name                        | Description |
|----------------------------------|-------------|
| `Dataset -2.csv`                | Input dataset containing booking and transactional data |
| `TravClan.ipynb`                | Python notebook used to clean, analyze, and visualize the dataset |
| `Insights & Suggestions PPT.pptx` | Final PowerPoint presentation highlighting insights and business suggestions |
| `README.md`                     | Project documentation (you are reading it!) |

---

## 🧠 Key Insights & Suggestions

### 1. 📈 **Markup Variance**
- **Observation**: Markups range between ₹1,181 and ₹11,800 (avg: ₹6,963, SD: ₹2,860)
- **Suggestions**:
  - Use dynamic pricing algorithms
  - Optimize based on market demand and seasonal trends

![Markup Variance](extracted_images/slide3_img6.png)

---

### 2. 📱 **Channel Sales Contribution**
- **Web**: 53.41%  
- **Android App**: 31.68%  
- **iOS App**: 14.91%
- **Suggestions**:
  - Enhance mobile app UI/UX
  - Launch exclusive app-only offers and ad campaigns

![Channel Sales](extracted_images/slide5_img6.png)

---

### 3. 📆 **Monthly Booking Trends**
- **Peak**: April (6,133 bookings)
- **Low**: March and June
- **Suggestions**:
  - Offer early bird discounts
  - Run seasonal promotions

![Booking Trends](extracted_images/slide8_img6.png)

---

### 4. 🤝 **Supplier Dependence**
- High reliance on a few suppliers (IDs 5, 1, 3, 7)
- **Suggestions**:
  - Onboard diverse suppliers
  - Monitor supplier performance metrics

![Supplier Dependence](extracted_images/slide10_img6.png)

---

### 5. 💸 **Refund Patterns**
- **Refunds**: 78.37% of bookings
- **Suggestions**:
  - Clarify refund policies
  - Offer flexible rebooking or vouchers
  - Analyze and reduce refund triggers

![Refund Patterns](extracted_images/slide12_img6.png)

---

## 🚀 How to Run the Project

1. **Clone the repository or download the files**
2. Open `TravClan.ipynb` in Jupyter Notebook or VS Code with Jupyter extension
3. Make sure `pandas` and `matplotlib` are installed:
   ```bash
   pip install pandas matplotlib
