# Zomato Data Analysis Project Using Python

## Project Overview
This project analyzes Zomato restaurant data with Python to understand customer preferences, restaurant types, and service modes. It uses visualizations and simple statistics to answer business questions about Zomato's operations.

## Objectives
The project answers these questions:
1. What type of restaurant do the majority of customers order from?
2. How many votes has each type of restaurant received from customers?
3. What are the ratings that the majority of restaurants have received?
4. What is the average spending of couples who mostly order food online?
5. Which mode (online or offline) has the maximum rating?
6. Which type of restaurants received more offline orders, so that Zomato can provide some good offers?

## Tools and Libraries Used
Python, Pandas, NumPy, Matplotlib, Seaborn, Jupyter

## How to run (step by step)

You need **Python 3.10 or newer** ([download](https://www.python.org/downloads/)). No API key is needed.

**1. Download the project**

```bash
git clone https://github.com/amitmohanty022/Zomato-Data-Analysis-Projects.git
cd Zomato-Data-Analysis-Projects
```

**2. Create a virtual environment and activate it**

```bash
python -m venv venv
# Windows
venv\Scripts\activate
# macOS / Linux
source venv/bin/activate
```

**3. Install the requirements**

```bash
pip install -r requirements.txt
```

**4. Add the dataset**

The notebook reads a file named **`Zomato data .csv`** (note the space before `.csv`) from this folder. The file is not included in the repository. Download the Zomato restaurant dataset (columns: `name, online_order, book_table, rate, votes, approx_cost(for two people), listed_in(type)`) from Kaggle by searching "Zomato data analysis dataset", and save it here with that exact name.

**5. Start Jupyter and run the notebook**

```bash
jupyter notebook Zomato_Analysis_project.ipynb
```

Choose **Run → Run All Cells**.

### Running in Google Colab instead
Open https://colab.research.google.com → **File → Upload notebook**, upload `Zomato data .csv` with the 📁 **Files** panel, then **Runtime → Run all**.

## Methodology
1. **Data Collection:** the Zomato dataset was collected and cleaned (for example, ratings such as `4.1/5` are converted to numbers).
2. **Exploratory Data Analysis (EDA):** bar charts, histograms, box plots and heatmaps.
3. **Visualization:** Seaborn and Matplotlib.

## Results and Insights
- Identified the most preferred types of restaurants among customers.
- Analyzed customer votes and average ratings for different restaurants.
- Explored spending patterns of couples ordering food online.
- Compared ratings between online and offline service modes.
- Identified restaurant types receiving higher offline orders.

## Contributing
Contributions are welcome! Feel free to submit pull requests with improvements or additional features.
