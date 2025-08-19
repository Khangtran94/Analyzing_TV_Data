# Analyzing TV Data for SuperBowl

## Overview
This project focuses on analyzing television broadcast data, specifically exploring datasets related to the Super Bowl and the tv metrics, halftime musicians. Using Python, the project involves data manipulation, cleaning, and visualization to uncover insights into game outcomes, viewership trends, ad costs, halftime shows, and episode ratings. The analysis aims to provide a deeper understanding of television viewership patterns and their cultural impact.

## Dataset
The project utilizes two primary datasets:
- **Super Bowl Data**: Includes information on game outcomes, viewership, advertising costs, and halftime show details (e.g., performers, number of songs). The data spans multiple years, reflecting the increasing costs of Super Bowl ads and viewership trends.
- **tv**: TV metrics
- **halftime_musicians**: halftime musician data for all 52 Super Bowls through 2018

The datasets are used to generate insights through exploratory data analysis and visualization.

## Features
- **Data Cleaning**: Handling missing values, standardizing formats, and preparing datasets for analysis using `pandas`.
- **Data Manipulation**: Filtering and aggregating data to focus on key metrics like viewership, ad costs, and episode ratings.
- **Data Visualization**: Creating visualizations (e.g., line plots, bar charts, scatter plots) using `matplotlib` and `seaborn` to illustrate trends such as Super Bowl viewership over time or episode rating distributions.
- **Exploratory Data Analysis (EDA)**: Investigating relationships between variables, such as the impact of guest stars on *The Office* episode ratings or the correlation between Super Bowl ad costs and viewership.
- **Insights Generation**: Drawing conclusions about trends, such as the rising cost of Super Bowl ads or the popularity of specific halftime show performances.

## Requirements
To run the notebook, you need the following Python libraries:
- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`

Install the dependencies using:
```bash
pip install pandas numpy matplotlib seaborn
```

## Usage
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/Khangtran94/Analyzing_TV_Data.git
   cd Analyzing_TV_Data
   ```

2. **Download the Datasets**:
   - Obtain the Super Bowl and *The Office* datasets from the repository or relevant sources (e.g., DataCamp or Kaggle).
   - Place them in the project directory.

3. **Run the Notebook**:
   - Open `Analyzing_TV_Data.ipynb` in Jupyter Notebook or a compatible environment.
   - Follow the steps in the notebook to clean, process, and visualize the data.

4. **View Results**:
   - The notebook includes visualizations and insights, such as trends in Super Bowl ad costs, viewership patterns, and factors influencing *The Office* episode ratings.

## Results
The project provides insights into:
- **Super Bowl Trends**: Analysis of viewership growth, escalating ad costs, and the impact of halftime show performers on audience engagement.
- **The Office Insights**: Relationships between episode ratings, guest stars, and viewership, highlighting factors that contributed to the show's popularity.
- **Visualizations**: Examples include line plots showing Super Bowl viewership over time, bar charts of ad costs, and scatter plots comparing *The Office* episode ratings with viewership.

## Contributing
Contributions are welcome! To contribute:
1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Commit your changes (`git commit -m "Add feature"`).
4. Push to the branch (`git push origin feature-branch`).
5. Open a pull request.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgments
- DataCamp for providing the project structure and inspiration.
- The open-source community for tools like `pandas`, `matplotlib`, and `seaborn`.
- Publicly available datasets for Super Bowl and *The Office* data.
