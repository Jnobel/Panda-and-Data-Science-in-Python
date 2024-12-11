# Pandas for Data Science: A Python Tutorial

Welcome to the Pandas for Data Science tutorial project! This repository demonstrates essential operations with the Pandas library in Python, including CRUD (Create, Read, Update, Delete) operations, data manipulation, and exporting results. Follow along to enhance your understanding of data science workflows.

---

## **Features**

This project includes:

- **Data Loading**: Importing datasets into Pandas DataFrames.
- **Data Exploration**: Viewing, filtering, and summarizing data.
- **Data Manipulation**: Creating, updating, and deleting columns and rows.
- **Data Exporting**: Saving results to CSV, JSON, and HTML formats.
- **Advanced Techniques**: Using `iloc`, `loc`, and applying conditional transformations.

---

## **Prerequisites**

Before starting, ensure you have the following installed:

1. Python 3.7+
2. Pandas library (`pip install pandas`)
3. Jupyter Notebook or VS Code with Jupyter support

---

## **Setup Instructions**

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/your-repository-name.git
   cd your-repository-name
   ```

2. Install required dependencies:
   ```bash
   pip install pandas
   ```

3. Open the Jupyter Notebook or `.ipynb` file in VS Code:
   ```bash
   code pandas_tutorial.ipynb
   ```

4. Download the dataset `telco_churn.csv` and place it in the project directory.

---

## **Usage**

1. Run the notebook file `pandas_tutorial.ipynb` step by step.
2. Follow the tutorial to:
   - Load and explore the dataset.
   - Filter, update, and manipulate data.
   - Export processed data to different formats.

---

## **Code Overview**

### **Key Functions Covered**

#### Data Loading:
```python
import pandas as pd
df = pd.read_csv('telco_churn.csv')
```

#### Data Exploration:
```python
# View the first few rows of the dataset
df.head()
```

#### Data Manipulation:
```python
# Create a new column
df['Total minutes'] = df['Total night minutes'] + df['Total intl minutes']
```

#### Data Export:
```python
# Export DataFrame to CSV
df.to_csv('output_telco_churn.csv', index=False)
```

---

## **Dataset**

- The dataset used in this project is `telco_churn.csv`, which contains tabular data for analyzing customer churn.

---

## **Contributing**

Contributions are welcome! To contribute:

1. Fork this repository.
2. Create a feature branch:
   ```bash
   git checkout -b feature-name
   ```
3. Commit your changes:
   ```bash
   git commit -m "Add feature-name"
   ```
4. Push to the branch:
   ```bash
   git push origin feature-name
   ```
5. Open a Pull Request.

---

## **License**

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## **Acknowledgments**

Special thanks to the tutorial creator and the open-source community for resources and guidance!
