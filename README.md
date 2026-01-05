# Dubai Real Estate Goldmine: Rental Market Analysis
**Exploratory Data Analysis and Real Estate Insights**

## Introduction
The UAE real estate market, particularly in Dubai and Abu Dhabi, is a global hub for investment and residency. This project analyzes a comprehensive dataset of over 73,000 rental listings to understand pricing dynamics, property distributions, and the factors driving rental costs in these major cities.

## Data Overview
The analysis uses a dataset containing 17 columns of information for each property listing, including:
* **Pricing:** Total rent, rent per sqft, and rent category (Low, Medium, High).
* **Property Features:** Type (Apartment, Villa, Penthouse, etc.), number of beds, baths, and area in square feet.
* **Location:** Address, city, latitude, longitude, and specific neighborhood.
* **Listing Status:** Posting date, age of listing, and furnishing status (Furnished/Unfurnished).

## Methodology
The project follows a standard data science workflow:
1. **Data Loading:** Importing libraries (`pandas`, `seaborn`, `matplotlib`) and the rental dataset.
2. **EDA (Exploratory Data Analysis):**
   * Investigating data types and handling missing values (e.g., latitude/longitude).
   * Analyzing the distribution of rental prices and property types.
3. **Statistical Modeling:** Calculating metrics like R2 Score and Mean Squared Error to evaluate prediction accuracy.

## Technical Stack
* **Language:** Python
* **Key Libraries:** `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`

## Results
The preliminary analysis provides a clear picture of the rental landscape, categorizing properties by price and location to highlight market trends. Initial model evaluations show an R2 Score of approximately 0.46, indicating a baseline for predicting rental prices based on property features.
