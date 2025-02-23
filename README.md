# Apriori Suggestion

This project implements the Apriori algorithm for market basket analysis using Python. It identifies relationships between items frequently bought together, using a dataset from BigBasket.

## Features
- Reads transactional data from `BigBasket.csv`.
- Applies the Apriori algorithm to find item associations.
- Filters results based on minimum support, confidence, and lift.
- Displays the top 10 strongest item pairs.

## Installation
 Install dependencies:
 pip install numpy 
 pip install pandas 
 pip install matplotlib 
 pip install apyori

python apriori_suggestion.py



---

### **Netflix Suggestion ECLAT README**

# Netflix Movie Suggestion (ECLAT Algorithm)

This project applies the ECLAT algorithm to identify frequent movie-watching patterns using transactional data from Netflix.

## Features
- Reads `Netflix.csv`, handling encoding errors.
- Uses the Apriori-based approach to find frequent movie pairings.
- Displays the top 10 most frequently watched movie pairs.

## Installation
1. Install dependencies:
   pip install numpy
   pip install pandas
   pip install matplotlib
   pip install apyori

python netflix_suggestion_eclat.py

