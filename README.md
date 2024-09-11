# data-feature

# MealMovie Matcher

This project is a Python-based application that suggests a movie based on a meal input. 

## Description

The MealMovie Matcher works as follows:
1. The user inputs a meal name.
2. The application retrieves information about the meal, including its country of origin.
3. Based on the country of origin, the application suggests a movie from the same country.

This project utilizes two external APIs, TheMealDB API for fetching meal information and the TVDB API for movie data, providing an entertaining way to explore different cultures through food and film.

## How to Run the Project

1. Ensure you have Python (Python 3.12 used for development) installed on your system.

2. Clone this repository to your local machine.

   ```
   git clone https://github.com/ZYTao12/data-feature.git
   cd data-feature
   ```

3. Install the required dependencies. You may need to install additional libraries. Use pip to install any missing dependencies:

   ```
   pip install -r requirements.txt
   ```

4. Set up the environment variables (you will need to create an account to get the TVDB API key).

   ```
   touch .env
   echo TVDB_API_KEY=your_tvdb_api_key >> .env
   ```

5. Run the main script:

   ```
   python meal_with_movie.py
   ```

6. When prompted, enter a meal name.

7. The application will display information about the meal's origin and suggest a movie from the same country.

## Example

Please refer to Assignment_01_Data_Features.ipynb.