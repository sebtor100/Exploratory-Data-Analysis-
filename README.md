# Project: FoodHub Data Analysis

## Overview

The project focuses on analyzing the data from FoodHub, a food aggregator company, to enhance customer experience and improve business strategies. The data contains information about different food orders, including order details, customer ratings, and various time-related metrics.

## Data Description

The dataset includes the following columns:

- `order_id`: Unique ID of the order
- `customer_id`: ID of the customer who ordered the food
- `restaurant_name`: Name of the restaurant
- `cuisine_type`: Cuisine ordered by the customer
- `cost_of_the_order`: Cost of the order
- `day_of_the_week`: Indicates whether the order is placed on a weekday or weekend
- `rating`: Rating given by the customer out of 5
- `food_preparation_time`: Time (in minutes) taken by the restaurant to prepare the food
- `delivery_time`: Time (in minutes) taken by the delivery person to deliver the food package

## Setup and Libraries

```python
# Import libraries for data manipulation
import numpy as np
import pandas as pd

# Import libraries for data visualization
import matplotlib.pyplot as plt
import seaborn as sns
