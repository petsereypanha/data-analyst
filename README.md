# Data Analyst Learning Path

A comprehensive collection of Python and SQL lessons for data analysis, covering fundamental concepts through advanced techniques.

## 📚 Repository Structure

This repository is organized into two main learning tracks:
- **Python for Data Analysis** - Data manipulation, visualization, and statistical analysis
- **SQL for Data Analysis** - Database querying, design, and data management

---

## 🐍 Python Track (`data-analyst-python/`)

### 1. Introduction to Python
**Path:** `introduction-python/`

Foundational Python programming concepts essential for data analysis.

- [`introduction.py`](data-analyst-python/introduction-python/introduction.py) - Getting started with Python
- [`data-types.py`](data-analyst-python/introduction-python/data-types.py) - Working with different data types
- [`control-flow-and-loops.py`](data-analyst-python/introduction-python/control-flow-and-loops.py) - Conditional statements and iterations

### 2. Intermediate Python
**Path:** `intermediate-python/`

Building advanced Python programming skills.

- [`function.py`](data-analyst-python/intermediate-python/function.py) - Creating and using functions
- [`lambda-functions-and-error-handling.py`](data-analyst-python/intermediate-python/lambda-functions-and-error-handling.py) - Anonymous functions and exception handling
- [`python-ecosystem.py`](data-analyst-python/intermediate-python/python-ecosystem.py) - Understanding Python packages and libraries

### 3. Joining Data with Pandas
**Path:** `joining_data_pandas/`

Master data merging and concatenation techniques in pandas.

- [`data_merging_basics.py`](data-analyst-python/joining_data_pandas/data_merging_basics.py) - Fundamental merge operations
- [`merging_tables_different_join_types.py`](data-analyst-python/joining_data_pandas/merging_tables_different_join_types.py) - Inner, outer, left, and right joins
- [`merging_ordered_Time-Series.py`](data-analyst-python/joining_data_pandas/merging_ordered_Time-Series.py) - Working with time-series data
- [`advanced_merging_concatenating.py`](data-analyst-python/joining_data_pandas/advanced_merging_concatenating.py) - Complex merge patterns

### 4. Exploratory Data Analysis (EDA)
**Path:** `exploratory_data_analysis/`

Techniques for understanding and exploring datasets.

- [`introduction_dataset.py`](data-analyst-python/exploratory_data_analysis/introduction_dataset.py) - Dataset overview and initial exploration
- [`exploratory_analysis.py`](data-analyst-python/exploratory_data_analysis/exploratory_analysis.py) - Statistical summaries and distributions
- [`relationships_data.py`](data-analyst-python/exploratory_data_analysis/relationships_data.py) - Analyzing correlations and relationships
- [`imputation_cleaning_data.py`](data-analyst-python/exploratory_data_analysis/imputation_cleaning_data.py) - Handling missing data
- [`analyzing_crime_los_angeles.py`](data-analyst-python/exploratory_data_analysis/analyzing_crime_los_angeles.py) - Real-world case study

### 5. Data Visualization with Seaborn
**Path:** `seaborn_data_visualization/`

Creating informative and attractive visualizations.

- [`introduction_seaborn.py`](data-analyst-python/seaborn_data_visualization/introduction_seaborn.py) - Seaborn basics
- [`visualizing_two_quantitative_variables.py`](data-analyst-python/seaborn_data_visualization/visualizing_two_quantitative_variables.py) - Scatter plots and regression plots
- [`visualizing_categorical_quantitative_variable.py`](data-analyst-python/seaborn_data_visualization/visualizing_categorical_quantitative_variable.py) - Box plots, violin plots, bar plots
- [`customizing_seaborn_plots.py`](data-analyst-python/seaborn_data_visualization/customizing_seaborn_plots.py) - Styling and customization
- [`analyze_nobel_prize.py`](data-analyst-python/seaborn_data_visualization/analyze_nobel_prize.py) - Project: Nobel Prize analysis

### 6. Sampling in Python
**Path:** `sampling_python/`

Statistical sampling techniques and distributions.

- [`introduction.py`](data-analyst-python/sampling_python/introduction.py) - Sampling fundamentals
- [`methods.py`](data-analyst-python/sampling_python/methods.py) - Random, stratified, and systematic sampling
- [`sampling_distributions.py`](data-analyst-python/sampling_python/sampling_distributions.py) - Understanding sampling distributions
- [`bootstrap_distributions.py`](data-analyst-python/sampling_python/bootstrap_distributions.py) - Bootstrap resampling methods

### 7. Hypothesis Testing
**Path:** `hypothesis_testing/`

Statistical inference and hypothesis testing methods.

- [`fundamentals.py`](data-analyst-python/hypothesis_testing/fundamentals.py) - Hypothesis testing basics
- [`proportion_tests.py`](data-analyst-python/hypothesis_testing/proportion_tests.py) - Testing proportions
- [`Two-Sample_ANOVA-Tests.py`](data-analyst-python/hypothesis_testing/Two-Sample_ANOVA-Tests.py) - Comparing multiple groups
- [`Non-Parametric_Tests.py`](data-analyst-python/hypothesis_testing/Non-Parametric_Tests.py) - Tests for non-normal distributions
- [`man_and_woman_soocer_match.py`](data-analyst-python/hypothesis_testing/man_and_woman_soocer_match.py) - Case study: Soccer match analysis

---

## 🗄️ SQL Track (`data-analyst-sql/`)

### 1. Query Basics
**Path:** `query/`

Fundamental SQL query operations.

- [`count.sql`](data-analyst-sql/query/count.sql) - Counting records
- [`show_columns_films.sql`](data-analyst-sql/query/show_columns_films.sql) - Exploring table structure
- [`unique_key.sql`](data-analyst-sql/query/unique_key.sql) - Working with unique values
- [`view_unique.sql`](data-analyst-sql/query/view_unique.sql) - Creating views

### 2. Sorting and Grouping
**Path:** `sorting-grouping/`

Organizing and aggregating query results.

- [`sorting.sql`](data-analyst-sql/sorting-grouping/sorting.sql) - ORDER BY operations
- [`grouping.sql`](data-analyst-sql/sorting-grouping/grouping.sql) - GROUP BY and aggregations

### 3. Aggregate Functions
**Path:** `aggregate_function/`

Statistical calculations and summaries.

- [`aggregate-functions.sql`](data-analyst-sql/aggregate_function/aggregate-functions.sql) - SUM, AVG, MIN, MAX, COUNT

### 4. Joining Data
**Path:** `joining-data/`

Combining data from multiple tables.

- [`inner-joins.sql`](data-analyst-sql/joining-data/inner-joins.sql) - INNER JOIN operations
- [`outer_cross_self_joins.sql`](data-analyst-sql/joining-data/outer_cross_self_joins.sql) - LEFT, RIGHT, FULL OUTER, CROSS, and SELF joins
- [`set-theory-for-set-joins.sql`](data-analyst-sql/joining-data/set-theory-for-set-joins.sql) - UNION, INTERSECT, EXCEPT
- [`subqueries.sql`](data-analyst-sql/joining-data/subqueries.sql) - Nested queries
- [`analyzing-students-mental-health.sql`](data-analyst-sql/joining-data/analyzing-students-mental-health.sql) - Case study

### 5. Functions and Data Manipulation
**Path:** `functions_manipulating/`

Working with different data types and functions.

- [`common_data_types.sql`](data-analyst-sql/functions_manipulating/common_data_types.sql) - Data type overview
- [`DATE_TIME_functions_operators.sql`](data-analyst-sql/functions_manipulating/DATE_TIME_functions_operators.sql) - Date and time operations
- [`parsing_manipulating.sql`](data-analyst-sql/functions_manipulating/parsing_manipulating.sql) - String manipulation
- [`search_extensions.sql`](data-analyst-sql/functions_manipulating/search_extensions.sql) - Pattern matching and search

### 6. Advanced SQL Manipulation
**Path:** `manipulation_sql/`

Complex query techniques and operations.

- [`case.sql`](data-analyst-sql/manipulation_sql/case.sql) - CASE statements and conditional logic
- [`subqueries.sql`](data-analyst-sql/manipulation_sql/subqueries.sql) - Advanced subquery patterns
- [`correlated-queries-nested-queries-and-common.sql`](data-analyst-sql/manipulation_sql/correlated-queries-nested-queries-and-common.sql) - Correlated subqueries and CTEs
- [`window_functions.sql`](data-analyst-sql/manipulation_sql/window_functions.sql) - Analytical window functions

### 7. Window Functions
**Path:** `sate_and_window_function/`

Advanced analytical queries with window functions.

- [`window_functions.sql`](data-analyst-sql/sate_and_window_function/window_functions.sql) - Window function basics
- [`fetching_ranking_paging.sql`](data-analyst-sql/sate_and_window_function/fetching_ranking_paging.sql) - RANK, DENSE_RANK, ROW_NUMBER
- [`aggregate_frames.sql`](data-analyst-sql/sate_and_window_function/aggregate_frames.sql) - Moving averages and cumulative sums
- [`beyond_window_function.sql`](data-analyst-sql/sate_and_window_function/beyond_window_function.sql) - Advanced patterns

### 8. Database Design
**Path:** `database-design/`

Designing efficient and normalized databases.

- [`processing-storing-and-organizing-data.sql`](data-analyst-sql/database-design/processing-storing-and-organizing-data.sql) - Data organization principles
- [`database-schemas-and-normalization.sql`](data-analyst-sql/database-design/database-schemas-and-normalization.sql) - Normalization forms
- [`database-views.sql`](data-analyst-sql/database-design/database-views.sql) - Creating and managing views
- [`database-management.sql`](data-analyst-sql/database-design/database-management.sql) - Database administration

### 9. Relational Databases
**Path:** `relational-databases/`

Understanding relational database constraints and integrity.

- [`database.sql`](data-analyst-sql/relational-databases/database.sql) - Database fundamentals
- [`key-constraints.sql`](data-analyst-sql/relational-databases/key-constraints.sql) - Primary keys and unique constraints
- [`foreign-keys.sql`](data-analyst-sql/relational-databases/foreign-keys.sql) - Foreign key relationships
- [`consistency-with-attribute-constraints.sql`](data-analyst-sql/relational-databases/consistency-with-attribute-constraints.sql) - CHECK and NOT NULL constraints

### 10. Data Analysis with SQL
**Path:** `data_analysis_sql/`

Practical SQL for real-world data analysis.

- [`database.sql`](data-analyst-sql/data_analysis_sql/database.sql) - Database setup
- [`summarizing_aggregating_numeric.sql`](data-analyst-sql/data_analysis_sql/summarizing_aggregating_numeric.sql) - Numeric data analysis
- [`categorical_data_unstructured_text.sql`](data-analyst-sql/data_analysis_sql/categorical_data_unstructured_text.sql) - Categorical and text analysis
- [`dates_timestamps.sql`](data-analyst-sql/data_analysis_sql/dates_timestamps.sql) - Time-based analysis

### 11. Data-Driven Decision Making
**Path:** `data_driven_decision/`

Business intelligence and analytical SQL queries.

- [`introduction_business_intelligence.sql`](data-analyst-sql/data_driven_decision/introduction_business_intelligence.sql) - BI concepts
- [`sql_ queries.sql`](data-analyst-sql/data_driven_decision/sql_ queries.sql) - Standard query patterns
- [`advanced_sql_queries.sql`](data-analyst-sql/data_driven_decision/advanced_sql_queries.sql) - Complex analytical queries
- [`olap_sql_queries.sql`](data-analyst-sql/data_driven_decision/olap_sql_queries.sql) - OLAP operations

### 12. Database Tables
**Path:** `table/`

Sample database schemas and table definitions.

- [`films_table.sql`](data-analyst-sql/table/films_table.sql) - Movies database
- [`people_table.sql`](data-analyst-sql/table/people_table.sql) - People/actors data
- [`reviews_table.sql`](data-analyst-sql/table/reviews_table.sql) - Review information
- [`countries_table.sql`](data-analyst-sql/table/countries_table.sql) - Country data
- [`populations_table.sql`](data-analyst-sql/table/populations_table.sql) - Population statistics
- [`economies_table.sql`](data-analyst-sql/table/economies_table.sql) - Economic data
- And more...

---

## 🎯 Learning Path Recommendations

### Beginner Path
1. Start with **Introduction to Python**
2. Move to **Query Basics** in SQL
3. Practice **Sorting and Grouping**
4. Learn **Intermediate Python**

### Intermediate Path
1. Master **Joining Data** in both Python and SQL
2. Explore **Exploratory Data Analysis**
3. Learn **Data Visualization with Seaborn**
4. Study **Aggregate Functions** and **Window Functions**

### Advanced Path
1. Deep dive into **Hypothesis Testing**
2. Master **Advanced SQL Manipulation**
3. Study **Database Design** principles
4. Learn **Sampling** techniques
5. Apply knowledge in **Data-Driven Decision Making**

---

## 💡 Getting Started

### Prerequisites
- Python 3.x
- pip (Python package manager)
- SQL database (PostgreSQL, MySQL, or SQLite)

### Python Setup
```bash
# Install required packages
pip install pandas numpy matplotlib seaborn scipy
```

### Running Python Files
```bash
cd data-analyst-python
python <folder>/<filename>.py
```

### Running SQL Files
```bash
# For PostgreSQL
psql -U username -d database_name -f data-analyst-sql/<folder>/<filename>.sql

# For MySQL
mysql -u username -p database_name < data-analyst-sql/<folder>/<filename>.sql
```

---

## 📖 Additional Resources

- [Pandas Documentation](https://pandas.pydata.org/docs/)
- [Seaborn Documentation](https://seaborn.pydata.org/)
- [SQL Tutorial](https://www.postgresql.org/docs/)
- [Python for Data Analysis Book](https://wesmckinney.com/book/)

---

## 📝 Notes

- Each file contains practical examples and exercises
- Code is commented for learning purposes
- Case studies provide real-world application experience
- Files build upon concepts from previous lessons

---

**Last Updated:** December 22, 2025
