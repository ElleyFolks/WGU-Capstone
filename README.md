# Project Goals
1. Showcase the computer science skills and knowledge that I have acquired with this degree.
2. Design a project that solves a business problem, and define parameters/measures of success.
3. Use machine learning to solve the business problem.
4. Create meaningful data visualizations that enrich the presentation of this project.
5. Design a user-friendly interface with interactive queries to use the product.

## Project Constraints
1. The machine learning model(s) must be properly designed, trained, and applied. The program must include a means to measure accuracy.
2. The project must show the ability to support featurizing, parsing, cleaning, and wrangling datasets.
3. Industry standard practices for data security must be followed.

## Project Summary
- I designed an ebook recommendation system for a fictitious company.
- The business problem was to design software that could provide accurate and relevant ebook recommendations to the users of an online ebook marketplace.
- The dataset was collected from Kaggle. It contains anonymized user demographic information, so no further action was required to make the dataset more secure.
- Data ETL was performed. Pandas dataframes were used to load the data in from CSV files.
- I employed various data-cleaning methods. Certain data entries and features were excluded based on the criteria that I set.
    - Entries that excluded key user demographic information were omitted from the cleaned dataset.
    - Features of the dataset that provided no value were omitted. Examples include book ISBN, URL links to pictures of the books, etc.
- I used two machine learning models.
  - Matrix Factorization was used for the collaborative filtering of the cleaned data.
  - K-means clustering was used to cluster similar books into groups based on the latent relationships found with Matrix Factorization. Recommendations for a user were generated from these groups.
- 3 key visualizations were used:
    - A bar graph showing the distribution of book ratings before and after the dataset is sampled.
    - A heat map to show the results of training the matrix factorization model.
    - A cluster graph to show the groups created by the K-means clustering model.
-  The GUI was created with a jupyter notebook widget. A user simply has to select a book, and then related suggestions are generated for other books to read.
