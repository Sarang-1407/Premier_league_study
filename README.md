# Cognizance of the Premier League

## Table of Contents
- [Project Overview](#project-overview)
- [Project Goals](#project-goals)
- [Methodology](#methodology)
  - [Match Data Analysis](#match-data-analysis)
  - [Transfer Market Analysis](#transfer-market-analysis)
  - [Referee Performance Analysis](#referee-performance-analysis)
  - [Player Position Prediction](#player-position-prediction)
- [Results](#results)
- [Getting Started](#getting-started)
- [Technologies Used](#technologies-used)
- [License](#license)

## Project Overview

This project provides a comprehensive study of the Premier League, covering areas including match data, the transfer market, comparative analysis of referee performances, and player position prediction. By exploring data from several seasons and using various data sources, this study provides better insights into the dynamics of English football. The analysis spans from the league's inception in the 1992/93 season to the most recent 2022/23 season.

Key insights include an examination of the league’s home advantage, historically dominant and weak-performing teams, and the impact of investments and long-term team planning. Additionally, an analysis of the Premier League transfer market helps understand the trends and behavior of different clubs, along with an exploration of referee performance in the 2021/22 season.

Finally, the project predicts players' positions based on physical, skill, and physiological indicators. This research utilizes a public dataset from Football Manager 2017, extracting 48 player-related attributes processed using advanced techniques like Neural Networks, XGBoost, Random Forest, and Multi-Task ElasticNet for regression tasks. The performance of these models is evaluated using metrics such as Median Absolute Difference (MAD) and R-squared (R²) scores.

## Project Goals

- To analyze historical match data from the Premier League to identify trends and patterns.
- To examine the dynamics of the transfer market and club behaviors over the seasons.
- To conduct a comparative analysis of referee performances and their impact on matches.
- To predict player positions based on their attributes, thereby improving scouting and decision-making in football.

## Methodology

### Match Data Analysis

- Analyze match data from the Premier League from its inception in 1992/93 to the 2022/23 season.
- Identify key performance indicators such as goals scored, clean sheets, and disciplinary records to derive insights into team performance and historical context.

### Transfer Market Analysis

- Examine transfer data, prices, and player transfers within the Premier League.
- Analyze factors such as transfer fees, player nationality, position, age, and club involvement to understand club finances and recruitment strategies.

### Referee Performance Analysis

- Conduct a comparative study of referee performances in the 2021/22 season.
- Analyze referee statistics, including appearances, fouls awarded, bookings, and red cards to assess performance trends and refereeing styles.

### Player Position Prediction

- Utilize the Football Manager 2017 dataset to predict the most suitable on-field positions for players based on their attributes.
- Implement advanced machine learning techniques, including Neural Network, XGBoost, Random Forest, and Multi-Task ElasticNet, to enhance prediction accuracy.

## Results

- The analysis provides valuable insights into the Premier League's dynamics, revealing patterns in match outcomes and transfer market behavior.
- Referee performance analysis sheds light on the effectiveness and consistency of officiating, while player position predictions offer clubs enhanced talent acquisition strategies.

## Getting Started

### Prerequisites

Ensure you have the following installed:
- Python 3.x
- Required libraries (see `requirements.txt`)

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Sarang-1407/Premier_league_study.git
   cd Premier_league_study
   ```

2. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the script:
   ```bash
   papermill pl_insights.pynb output_notebook.ipynb
   ```

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-Learn
- TensorFlow
- Matplotlib/Seaborn for visualization
- Git for version control

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
