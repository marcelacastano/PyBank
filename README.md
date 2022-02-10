# PyBank 📒

- Jupyter notebook that generates a short financial summary of profit/loss data contained in a `.csv` file
- Prints out financial analysis to a `.txt` file

![Revenue](images/piggybank.jpg)
*Photo by cottonbro from [Pexels](https://www.pexels.com/)*

## How does it work? 👇

- Load a `.csv` file with the following format:

  |Date|Profit/Losses|
  |--- |--- |
  | date 1 | number 1|
  | date 2 | number 2|
  | ... | ...|

- Run the [`pybank.ipynb`](pybank.ipynb) script to obtain the following financial summary:

  - Total number of months included in the dataset.
  - Net total amount of Profit/Losses over the entire period.
  - Average of the changes in Profit/Losses over the entire period.
  - Greatest increase in profits (date and amount) over the entire period.
  - Greatest decrease in losses (date and amount) over the entire period.

## Sample Results 📈

```text
  Financial Analysis
  ---------------------------
  Total months: 86
  Total: $38,382,578.00
  Average change: $-2,315.12 
  Greatest Increase in Profits occured in Feb-2012 ($1,926,159.00)
  Greatest Decrease in Profits occured in Sep-2013 ($-2,196,167.00)
```

## Resources 🔍

* [Python Basics](https://pythonbasics.org/): Contains example materials and exercises for the Python 3 programming language.

* [Python Documentation](https://docs.python.org/3/): Official Python documentation
