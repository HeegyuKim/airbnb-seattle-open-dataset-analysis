# AirBnB Seattle Open Data Analysis
By analyzing AirBnB Seattle Open Data, We can provide valuable informations to hosts and customer.

### 1. How do seasonal costs change?
Provide seasonal costs to customer. It can be used as a reference when planning a trip

### 2. Which features are most related to homestay cost?
Correlation analysis allows hosts to see which factors have a significant impact on price. As a result of the analysis, the factors that have the greatest influence on price were in the order of number of accommodates, number of bedrooms, number of beds, number of bathrooms, and number of guests included. So, when the host decides the price, it's easier to find the right price through these five factors than other factors.

### 3. What is different between superhost and regular host?
AirBnB Superhost have more benefits than regular host. If we know what is different between superhost and regular host, It is much easier to become superhost. By the analysis, Big differences between superhost and regular host in seattle are location and number of reviews. Unexpectedly, average review scores are very similar.

<hr>

## Files
Dataset files from https://www.kaggle.com/airbnb/seattle
- calendar.csv: Calendar, including listing id and the price and availability for that day
- listings.csv: Listings, including full descriptions and average review score
- reviews.csv: Reviews, including unique id for each reviewer and detailed comments
- airbnb-analysis.ipynb: IPython Notebook for data preparation, modeling, evaluation
- requirements.txt: required packages for python

## Requirements - You must know about
- Basic Python3 
- How to use jupyter notebook
- How to use numpy, pandas, matplotlib
- Basic linear algebra, Basic statistics, graphs
- Google Map API from Google Cloud Platform

## Setup
install python3 from https://www.python.org/

install required python packages by
```python
pip install -r requirements.txt
```

If you want to draw a map, you need `Google Maps Javascript API Key` from Google Cloud Platform<br>
<br>
## Run the codes
Run jupyter

```bash
> jupyter notebook
```
Open the notebook url and open `airbnb-analysis.ipynb` in the browser.
