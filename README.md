

📚 EDA Using Python – Books Dataset.


This project performs Exploratory Data Analysis (EDA) on a books dataset to uncover trends, patterns, and insights about publishing years, genres, sales, ratings, and more. The analysis uses Python along with popular data science libraries for data cleaning, visualization, and summarization.


🗂 Dataset Overview
The dataset (Books_Data_Clean.csv) contains details about books including:

Column Name	  - Description

Publishing Year	- Year the book was published

Book Name - 	Title of the book

Author	- Author(s) of the book

language_code - 	Language code of the book

Author_Rating	-  Rating category of the author (Novice, Intermediate, etc.)

Book_average_rating	 - Average rating of the book

Book_ratings_count - 	Number of ratings received

genre - 	Genre of the book

gross sales - 	Total gross sales amount

publisher revenue - 	Revenue earned by the publisher

sale price - 	Selling price of the book

sales rank	 - Ranking based on sales

Publisher - 	Name of the publisher

units sold - 	Number of units sold


🎯 Objectives:

1)Explore the structure of the dataset and clean missing values or invalid data.

2)Visualize publishing year distribution.

3)Analyze number of books by genre.

4)Study sales vs. units sold relationships.

5)Identify top publishers by revenue.

6)Understand rating patterns across author rating categories.

7)Explore language distribution of books.

📊 Key Analysis Performed:

-Data Cleaning

-Removed books published before 1900.

-Checked for missing values and duplicates.

Visualizations:

1)Histogram of Publishing Year.

2)Bar Chart: Number of books per genre.

3)Box Plot: Ratings count by genre.

4)Scatter Plot: Sale price vs. units sold.

5)Pie Chart: Language distribution.

6)Line Chart: Units sold over publishing years.

GroupBy Aggregations:

1)Publisher revenue totals.

2)Average book ratings count by author rating category.

3)Language distribution counts.

📈 Insights:

1)Most books in the dataset were published after 1985, with peaks around the 2000s.

2)Fiction genres dominate the dataset.

3)The Intermediate author rating category has the highest average rating counts.

4)Penguin Group (USA) LLC and Random House LLC lead in publisher revenue.

5)English (eng, en-US) is the most common language, covering over 85% of the dataset.

🛠 Tools & Libraries Used:

1)Python

2)Pandas – Data cleaning and manipulation

3)Matplotlib – Visualization

4)Seaborn – Enhanced visual aesthetics

5)Jupyter Notebook


🚀 How to Run

Clone this repository:

bash
Copy
Edit
git clone https://github.com/yourusername/eda-books-dataset.git
Install dependencies:

bash
Copy
Edit
pip install pandas matplotlib seaborn
Open the Jupyter Notebook:

bash
Copy
Edit
jupyter notebook "EDA Using Python.ipynb"
Run all cells to reproduce the analysis.

This analysis was carried out as part of a data exploration learning exercise to strengthen EDA skills and visualization techniques.
