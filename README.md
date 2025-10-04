# Supermarket Sales – Exploratory Data Analysis (EDA)

## Project Description
This project presents an in-depth Exploratory Data Analysis (EDA) of the **Supermarket Sales** dataset. The goal is to uncover insights about sales trends, customer behavior, product performance, and revenue drivers using data visualization and statistical techniques.

---

## Project Details

### 1. Data Cleaning & Preprocessing
- Loaded and inspected the dataset for missing values and data types.
- Cleaned the data by removing null values and rounding numerical columns for clarity.
- Encoded categorical variables (e.g., gender) for consistency.

### 2. Feature Analysis
- Segregated numerical and categorical features for targeted analysis.
- Performed descriptive statistics to summarize the dataset.

### 3. Visualization & Insights
- Created visualizations to analyze:
  - **COGS (Cost of Goods Sold)** by branch, quantity, product line, city, payment method, and customer type.
  - **Gross Income** by the same categorical variables.
- Saved key plots as `EDA1.png` (COGS) and `EDA2.png` (Gross Income).

### 4. Dataset Overview
- 1,000 sales records with 17 features, including invoice details, branch, city, product line, pricing, customer type, gender, payment method, gross income, tax, and purchase time/date.

---

## Tech Stack
- **Python**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Jupyter Notebook**

---

## Getting Started

1. **Clone the repository:**
   ```bash
   git clone https://github.com/DCode-v05/Supermarket-Sales.git
   cd Supermarket-Sales
   ```
2. **Install dependencies:**
   ```bash
   pip install pandas numpy matplotlib
   ```
3. **Open the notebook:**
   ```bash
   jupyter notebook "EDA of Supermarket Sales.ipynb"
   ```

---

## Usage
- Run the notebook cells sequentially to reproduce the analysis and visualizations.
- The dataset (`supermarket_sales.csv`) is included for convenience.
- Visual outputs are saved as `EDA1.png` and `EDA2.png` in the project root.

---

## Project Structure
```
Supermarket-Sales/
│
├── EDA of Supermarket Sales.ipynb   # Main analysis notebook
├── supermarket_sales.csv            # Dataset
├── EDA1.png                        # COGS analysis visualization
├── EDA2.png                        # Gross income analysis visualization
└── README.md                       # Project documentation
```

---

## Contributing

Contributions are welcome! To contribute:
1. Fork the repository
2. Create a new branch:
   ```bash
   git checkout -b feature/your-feature
   ```
3. Commit your changes:
   ```bash
   git commit -m "Add your feature"
   ```
4. Push to your branch:
   ```bash
   git push origin feature/your-feature
   ```
5. Open a pull request describing your changes.

---

## Contact
- **GitHub:** [DCode-v05](https://github.com/DCode-v05)
- **Email:** denistanb05@gmail.com
