# Which NYC schools have the best SAT results?

A guided DataCamp project that analyses SAT performance across New York City public high schools using Python and pandas.

## Questions answered
1. Which schools score at least 80% of the maximum (640 out of 800) in maths?
2. Which 10 schools have the best combined SAT score (maths + reading + writing)?
3. Which borough has the most variability in combined SAT scores?

## Key findings
- **10 schools** reached the 640 maths threshold. **Stuyvesant High School** was highest (754), followed by Bronx High School of Science (714) and Staten Island Technical High School (711).
- **Top 10 combined scores** were led by Stuyvesant High School (2,144), then Staten Island Technical High School and Bronx High School of Science (both 2,041).
- **Manhattan** had the widest spread of combined SAT scores (standard deviation of 230.29 across 89 schools).

## Insight
Only 10 of the 375 schools scored in the top range for maths, and many of them are science and technical schools, led by Stuyvesant High School. Results in Manhattan vary the most from school to school, with both very high and very low scorers.

## Method
- Filtered rows with boolean conditions, created a combined score column, sorted and ranked schools.
- Used `groupby` with `count`, `mean` and `std` to compare boroughs.

## Files
- `nyc_schools_analysis.ipynb`: the full analysis

## Data
`schools.csv` (375 schools: name, borough, building code, average maths, reading and writing scores, percent tested) is provided by DataCamp inside the project. Place it in the same folder as the notebook to re-run the analysis.

## Tools
Python, pandas, Jupyter

*Guided project completed on DataCamp.*
