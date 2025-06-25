# 📊 Netflix Movies & TV Shows SQL Analysis

This project presents an exploratory data analysis of Netflix content using SQL. It involves running queries on a dataset containing metadata about Netflix movies and TV shows. The objective is to derive insights about content trends, ratings, genres, actors, directors, and more.

## 📁 Project Structure

- `netflix_titles.csv` – Original dataset containing metadata of Netflix content.
- `netflix_sql_project.sql` – SQL script containing:
  - Table creation and data loading logic
  - 15 analytical SQL queries to explore and analyze the dataset

## 🛠️ Technologies Used

- **PostgreSQL**: Relational database used for running SQL queries.
- **SQL**: For data manipulation and analysis.
- **CSV**: Source file format used for dataset.

## 🧠 Key SQL Queries and Their Purpose

1. **Count Movies vs TV Shows**  
   Understand the distribution of content types on Netflix.

2. **Most Common Rating**  
   Find the most frequently assigned ratings for both Movies and TV Shows.

3. **Movies Released in a Given Year**  
   Filter movies released in a specific year (e.g., 2020).

4. **Top 5 Countries by Content Count**  
   Identify which countries have the most content available.

5. **Longest Movie**  
   Discover the movie with the maximum duration.

6. **Recently Added Content**  
   Find content added to Netflix in the last 5 years.

7. **Director-specific Content**  
   List all movies and shows directed by 'Rajiv Chilaka'.

8. **TV Shows with More Than 5 Seasons**  
   Analyze the longest-running series.

9. **Genre Popularity**  
   Count how many titles belong to each genre category.

10. **Content Release Trend in India**  
    Track yearly release trends in Indian content.

11. **Documentary Movies**  
    List all Netflix content categorized under Documentaries.

12. **Content Without Director Information**  
    Identify entries missing director data.

13. **Salman Khan Appearances (Last 10 Years)**  
    Track his recent appearances in Netflix content.

14. **Top Indian Actors on Netflix**  
    Actors who appeared most frequently in Indian content.

15. **Categorize by Keywords ('Kill' or 'Violence')**  
    Group content based on presence of potentially violent descriptions.

## 📊 How to Use

1. Import the `netflix_titles.csv` into your PostgreSQL database using a suitable tool (e.g., pgAdmin or SQL scripts).
2. Run the SQL queries from `netflix_sql_project.sql` to explore and analyze the dataset.
3. Modify queries as per your interest or add new ones for deeper insights.

## 🔍 Sample Insights

- TV Shows slightly outnumber Movies on the platform.
- The "TV-MA" rating is the most common for TV shows.
- United States and India are among the top producers of Netflix content.
- Actor "Salman Khan" has featured in multiple Netflix items in the last decade.

## 📌 Note

- The CSV may include multiple countries, directors, and actors per row. Queries account for these using PostgreSQL string functions like `UNNEST` and `STRING_TO_ARRAY`.
- Make sure to cast and parse dates and durations appropriately depending on your SQL dialect.

## 📬 Contact

For questions or suggestions, feel free to reach out via GitHub issues.

---

⭐ If you found this project helpful, please give it a star!
