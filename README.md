# LEGO Amazon Analysis

This project is a **data analysis of LEGO products on Amazon**, designed for exploratory data analysis (EDA) and visualization. The notebook is beginner-friendly but also provides useful insights and charts for presentations.

---

## **Project Overview**

The main notebook `LEGO_Amazon_Analysis.ipynb`:

- Loads datasets (`geoMap.csv` and `toy-products-on-amazon-metadata.json`)  
- Performs data cleaning (handling missing values, converting price to numeric, etc.)  
- Conducts exploratory data analysis (EDA) on product and sales data  
- Generates charts and tables summarizing trends and customer reviews  
- Saves images for use in presentations

The analysis is intended for educational purposes and demonstrates data handling, visualization, and basic insights extraction.

---

## **Datasets**

1. **geoMap.csv** – Contains LEGO sales data by country.  
2. **toy-products-on-amazon-metadata.json** – Contains detailed metadata for LEGO products on Amazon, including:

- Product name and manufacturer  
- Price and stock information  
- Customer reviews and ratings  
- Product categories  

> If additional datasets are available, place them in the `data/` folder and update paths in the notebook.

---

## **Requirements**

1) You need these modules:
	> pandas
	> numpy
	> matplotlib
	Note: To install this, you can open cmd and run this code "install pandas numpy matplotlib"

2) Use python 3.14.0
	> You can download it from here https://www.python.org/downloads/release/python-3140/

---

## **How to setup**

1) Create a folder on your desktop and name it "extracted"
2) Create 2 subfolders named:
	"datasets"
	"Python_code"
3) On the datasets folder, extract all of the dataset in there.
4) On the Python_code, extract these python codes:
	"analysis.py"
	"app.py"
	"cleaning.py"
	"data_loader.py"
	"utils.py"
	"visuals.py"

5) Edit app.py
	> modify the BASE_DATA_PATH
	Note: You have to specify here the location path of datasets folder.
		ex. BASE_DATA_PATH = Path(r"C:\Users\<username>\Desktop\extracted\datasets")

   
---

## **Example Outputs**

The code produces:

- Price distribution charts  
- Average customer ratings per category  
- Number of reviews and answered questions  
- Insights into customer purchasing patterns  


---

## **How to execute the codes**

1) Open CMD
2) Type in "python C:\Users\username\Desktop\extracted\Python_code\app.py"
3) You have to choose 1 first to load the datasets.
4) You have to choose 2 to clean the datasets.
5) Choose either 3 or 4 depending on what you want to do.

---

## **Author**

Pragatighai
