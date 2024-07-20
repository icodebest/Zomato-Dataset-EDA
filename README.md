# Zomato Dataset Exploratory Data Analysis (EDA)

## Project Description

This project involves performing Exploratory Data Analysis (EDA) on the Zomato restaurant dataset. The goal is to uncover insights and trends in the data to better understand restaurant characteristics, customer preferences, and regional differences.

## Dataset

The Zomato dataset includes the following columns:
- `Restaurant ID`: Unique identifier for each restaurant
- `Restaurant Name`: Name of the restaurant
- `Country Code`: Country where the restaurant is located
- `City`: City where the restaurant is located
- `Address`: Full address of the restaurant
- `Locality`: Local area or neighborhood of the restaurant
- `Locality Verbose`: Detailed locality information
- `Longitude`: Longitude coordinate of the restaurant
- `Latitude`: Latitude coordinate of the restaurant
- `Cuisines`: List of cuisines offered by the restaurant
- `Average Cost for two`: Average cost for a meal for two people
- `Currency`: Currency used in the restaurant’s pricing
- `Has Table booking`: Whether the restaurant accepts table bookings (Yes/No)
- `Has Online delivery`: Whether the restaurant offers online delivery (Yes/No)
- `Is delivering now`: Whether the restaurant is currently delivering (Yes/No)
- `Switch to order menu`: Whether there is a menu for ordering (Yes/No)
- `Price range`: Price range of the restaurant (1-4)
- `Aggregate rating`: Overall rating of the restaurant
- `Rating color`: Color code representing the rating
- `Rating text`: Textual description of the rating
- `Votes`: Number of votes the restaurant has received
- `Country`: Country where the restaurant is located

## EDA Workflow

1. **Data Cleaning**
   - Handle missing values in critical columns.
   - Convert categorical variables into a usable format.
   - Remove duplicate records.

2. **Data Exploration**
   - Analyze the distribution of ratings and cost.
   - Explore the relationship between average cost and rating.
   - Examine regional differences in restaurant ratings and cuisine preferences.

3. **Visualization**
   - Plot the distribution of restaurant ratings and price ranges.
   - Visualize the average cost for two across different cities and countries.
   - Create heatmaps to show the concentration of restaurants in various regions.
   - Generate bar charts to compare the popularity of different cuisines.

4. **Insights and Findings**
   - Identify trends and patterns in restaurant ratings and costs.
   - Understand regional preferences and popular cuisines.
   - Highlight key factors influencing restaurant ratings.

## Tools and Libraries

This project uses the following tools and libraries:
- **Python**: Programming language
- **Pandas**: Data manipulation and analysis
- **NumPy**: Numerical computing
- **Matplotlib**: Data visualization
- **Seaborn**: Statistical data visualization

## How to Run

1. Clone the repository:
    ```sh
    git clone https://github.com/icodebest/zomato-dataset-eda.git
    ```
2. Navigate to the project directory:
    ```sh
    cd zomato-eda
    ```
3. Install the required libraries:
    ```sh
    pip install -r requirements.txt
    ```
4. Open the Jupyter Notebook or Python scripts to review the EDA process and visualizations.

## Conclusion

The EDA on the Zomato dataset provides valuable insights into restaurant characteristics and customer preferences. It highlights trends, regional differences, and factors influencing restaurant ratings, which can be useful for business analysis and decision-making.

Feel free to explore the notebook and scripts to see the detailed analysis and visualizations.
