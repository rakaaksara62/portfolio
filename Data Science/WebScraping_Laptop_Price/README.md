# 🖥️ Web Scraping Laptop Prices  

This project scrapes **laptop price data** from Tokopedia using **BeautifulSoup** and analyzes price distribution using **Matplotlib**.

## 🚀 **Features**
✅ Web scraping for laptop price data from Tokopedia  
✅ Saves data to **CSV** format  
✅ Price distribution visualization  

## 📂 **Project Structure**
- 📂 **data-science**
  - 📂 **web-scraping-laptop**
    - 📜 **README.md** → Project description
    - 📜 **scraping.py** → Scraping script
    - 📜 **analysis.ipynb** → Jupyter Notebook for analysis
    - 📜 **requirements.txt**  → Dependencies for the project
    - 📂 **data**
      - 📜 **laptop_tokopedia.csv** → Scraped data
    - 📂 **images**
      - 📜 **price_distribution_histogram.png** → Price visualization

## 🔧 **Installation**
Ensure Python is installed, then run:
```bash
pip install -r requirements.txt
```
## 📊 How to Run

1. Run the web scraping script
```bash
   python scraping.py
```
2.Open Jupyter Notebook for analysis
```bash
    jupyter notebook
```
## 📸 **Analysis Result**
### 📊 Laptop Price Distribution  
This histogram shows the distribution of laptop prices collected from Tokopedia.  
![Laptop Price Distribution](../images/price_distribution_histogram.png)  

### 💰 Top 10 Cheapest Laptops  
| Rank | Laptop Name              | Price (IDR)  |
|------|--------------------------|--------------|
| 1    | ASUS VivoBook 14         | 5,000,000    |
| 2    | Lenovo IdeaPad 3         | 5,500,000    |
| 3    | Acer Aspire 5            | 6,000,000    |

### 🏆 Most Common Laptop Brands  
Here are the top 10 most frequently listed laptop brands.  
![Top Laptop Brands](../images/top_brands.png)  


💡 Have questions or feedback? Feel free to reach out!
📧 Email: raka.khairann@gmail.com
