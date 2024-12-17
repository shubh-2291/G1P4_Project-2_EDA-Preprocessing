# GL United FC Player Recommendation

## Project Overview
GL United FC, a newly formed football club, aims to build its first team roster using a data-driven approach. This project involves analyzing player data to recommend 20 potential players, out of which 15 will be selected for the team.

## Dataset Description
The dataset contains information on over 18,000 players from various European football clubs. It includes attributes such as:

- **Player Details**: Name, Age, Nationality, Current Club, and Position.
- **Performance Metrics**: Ratings for Dribbling, Finishing, Sprint Speed, and more (scaled to 100).
- **Market Information**: Current Market Value, Wage, and Release Clause.
- **Physical Attributes**: Height, Weight, and Body Type.

### Key Columns
- `Overall`: Overall skill rating of the player.
- `Potential`: Potential future skill rating.
- `Wage`: Weekly wage of the player.
- `Value`: Market value of the player.
- `Position`: Preferred position on the field.
- `Skill Moves` & `Weak Foot`: Technical abilities.

For a detailed description, refer to the dataset documentation in the notebook.

## Objectives
1. Analyze player data to shortlist 20 candidates based on:
   - Skill ratings.
   - Market value and wage compatibility.
   - Positional requirements.
2. Provide recommendations to the club's management to finalize 15 players.

## Project Workflow
1. **Data Loading and Preprocessing**: Importing libraries and cleaning the dataset.
2. **Exploratory Data Analysis (EDA)**: 
   - Statistical summaries.
   - Visualizations to understand distributions and correlations.
3. **Player Filtering and Ranking**:
   - Filtering players based on positional needs.
   - Ranking players using weighted metrics.
4. **Final Recommendations**: Generate a list of top 20 players.

## Tools and Libraries Used
- **Programming Language**: Python
- **Libraries**: 
  - Data Manipulation: `pandas`, `numpy`
  - Visualization: `matplotlib`, `seaborn`
  - Machine Learning (if applicable): `scikit-learn`

## How to Use
1. Clone the repository.
   ```bash
   git clone <repository-url>
   ```
2. Open the Jupyter Notebook file `Group_Project.ipynb`.
3. Follow the cells to execute the analysis step-by-step.

## Results and Recommendations
The final list of 20 players with relevant metrics will be presented at the end of the notebook. Management can use this list to finalize the team.

## Future Enhancements
- Automate the ranking system using machine learning models.
- Integrate additional datasets for a more comprehensive analysis.
- Develop a web interface for easier interaction with the recommendations.

