# mlnd-p3-customer_segments
Udacity MLND Project 3 - Creating Customer Segments

This is my submission for Project 3 ('Creating Customer Segments') on Udacity's Machine Learning Engineer Nanodegree. 

The project brief asked the student to apply unsupervised learning techniques on product spending data collected for customers of a wholesale distributor in Lisbon, Portugal to identify customer segments hidden in the data. This involved data exploration, preprocessing and transformation, principal component analysis, feature selection, and clustering.

## List of files
- `customer_segments.ipynb`: completed submission file (Jupyter Notebook)
- `visuals.py`: supporting code (provided by Udacity)
- `customers.csv`: underlying data (described below)

## Data

The dataset used in this project is included as `customers.csv`. As described by [Udacity](https://github.com/udacity/machine-learning/tree/master/projects/customer_segments#data), the customer segments data is included as a selection of 440 data points collected on data found from clients of a wholesale distributor in Lisbon, Portugal. More information can be found on the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Wholesale+customers).

Note (m.u.) is shorthand for *monetary units*.

**Features**
1) `Fresh`: annual spending (m.u.) on fresh products (Continuous); 
2) `Milk`: annual spending (m.u.) on milk products (Continuous); 
3) `Grocery`: annual spending (m.u.) on grocery products (Continuous); 
4) `Frozen`: annual spending (m.u.) on frozen products (Continuous);
5) `Detergents_Paper`: annual spending (m.u.) on detergents and paper products (Continuous);
6) `Delicatessen`: annual spending (m.u.) on and delicatessen products (Continuous); 
7) `Channel`: {Hotel/Restaurant/Cafe - 1, Retail - 2} (Nominal)
8) `Region`: {Lisbon - 1, Oporto - 2, or Other - 3} (Nominal) 