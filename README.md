# Xbox Game Pass Data Analysis

This repository contains a data analysis project examining the Xbox Game Pass dataset to uncover factors influencing game popularity, completion rates, and ratings. The analysis provides actionable insights for game developers to optimize user experiences and gameplay strategies.

## Project Description

The project analyzes the 'Enhanced_Gamepass_Games_v2' dataset from Kaggle, which includes data on 455 games such as genres, gamer counts, completion percentages, playtimes, and ratings. Key objectives include identifying popular genres, exploring relationships between difficulty, playtime, and engagement, and classifying games using unsupervised machine learning.

The analysis is conducted in a Jupyter Notebook and covers:
- Data preparation: Cleaning, handling missing values, and format conversions.
- Genre analysis: Identifying top genres like Sandbox, Compilation, and MMO, with visualizations showing gamer preferences.
- Difficulty and playtime analysis: Using K-means clustering to classify games into four types (Casual, Epic, Challenge, Mainstream).
- Insights and recommendations: Highlighting success models (high-engagement vs. mass-appeal) and strategies for developers.

Skills demonstrated: Data cleaning, statistical analysis, visualization, unsupervised machine learning (K-means), and deriving business insights.

For **detailed executive summary and code**, refer to the [Jupyter Notebook](Xbox_Game_Project.ipynb).

## Data

- **Source**: 'Enhanced_Gamepass_Games_v2' dataset from Kaggle (published by Rohan). Original dataset is included in the repo; or you can download from [Rohan - Kaggle]([https://www.kaggle.com/datasets/rohanchopdekar/enhanced-gamepass-games-v2](https://www.kaggle.com/datasets/vines666/enhanced-xbox-game-pass-genres)).
- **Structure**: Columns include GAME, RATIO (difficulty), GAMERS, COMP % (completion rate), TIME (playtime), RATING, GENRES, and more.
- **Note**: Processed data is handled in the notebook; no raw data is uploaded here.

## Tools and Libraries

- Python 3.11
- Libraries:
  - pandas
  - numpy
  - seaborn
  - matplotlib
  - scikit-learn (for K-means clustering)
- Environment: Jupyter Notebook

## Installation

Clone the repository and install required libraries using the requirements.txt file. Then, launch Jupyter Notebook to run the analysis.

## Usage

1. Download the dataset from Kaggle and place it in the `data/` directory as `Enhanced_Gamepass_Games_v2.csv`.
2. Open `Xbox_Game_Project.ipynb` in Jupyter Notebook.
3. Run cells sequentially to perform data loading, cleaning, analysis, and visualizations.
4. Outputs include charts (e.g., bar plots for genre rankings, bubble charts for relationships, scatter plots with clusters) saved in the notebook or `outputs/` folder.

## Key Results

- **Popular Genres**: Sandbox (247,504 avg. gamers), Compilation (181,648), MMO (133,438) are top performers. Success driven by high-engagement (long playtimes, community focus) or mass-appeal (short, creative experiences).
- **Game Classifications**: K-means clustering identifies:
  - Casual (easy-short): Dominant with diverse genres like Action/Adventure.
  - Epic (hard-very long): High gamer averages but limited variety; untapped potential.
  - Challenge (very hard-short): Niche appeal.
  - Mainstream (hard-long): Balanced but focused on Action/Compilation.
- **Insights**: Popularity correlates with engagement depth or accessibility, not completion rates. Recommendations: Prioritize multiplayer/narrative for loyalty (MMO/RPG) and creativity/freedom for broad appeal (Sandbox).


## Contributing

Contributions are welcome! To contribute:
1. Fork the repository.
2. Create a new branch.
3. Commit changes.
4. Push and open a Pull Request.

## Contact

- Email: duyanhbin19@gmail.com
- GitHub: [AnhNgo2803](https://github.com/AnhNgo2803)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
