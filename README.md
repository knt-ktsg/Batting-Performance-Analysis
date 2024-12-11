# :baseball: Batting Performance Analysis

## :books: Project Description
**Shohei Ohtani** is regarded one of the best players of all time, as he is able to perform at the highest level in both pitching and hitting. He set a new record, achieving 50 home runs and 50 stolen bases in the same season.
Given his extraordinary abilities, this analysis aims to explore strategies and insights for opposing teams looking to neutralize his impact on the game. By examining his strengths, weaknesses, and patterns, the project will propose actionable strategies to shut down one of the most talented players in baseball history.

## :memo: Table of Contents
- [Dataset](#dataset)
- [Tools and Libraries](#tools-and-libraries)
- [Usage](#usage)
- [Key Findings](#key-findings)
- [Future Work](#future-work)
- [License](#license)

## Dataset
- **Source**: [Baseball Savant](https://baseballsavant.mlb.com/statcast_search?hfPT=&hfAB=&hfGT=R%7C&hfPR=&hfZ=&hfStadium=&hfBBL=&hfNewZones=&hfPull=&hfC=&hfSea=2024%7C&hfSit=&player_type=batter&hfOuts=&hfOpponent=&pitcher_throws=&batter_stands=&hfSA=&game_date_gt=&game_date_lt=&hfMo=&hfTeam=&home_road=&hfRO=&position=&hfInfield=&hfOutfield=&hfInn=&hfBBT=&batters_lookup%5B%5D=660271&hfFlag=&metric_1=&group_by=name&min_pitches=0&min_results=0&min_pas=0&sort_col=pitches&player_event_sort=api_p_release_speed&sort_order=desc#results)
- **Format**: CSV
- **Size**: 2,838 rows, 94 columns

## Tools and Libraries

- **Jupyter notebook**
- **Python**
  - pandas
  - matplotlib
  - seaborn

## Installation
1. Clone the repository:
   ```bash
   git clone git@github.com:knt-ktsg/Coffee-Sales-Analysis.git

2. Install dependencies:
   ```bash
   pip pip install -r requirements.txt

## Usage
1. Open the Jupyter Notebook:
   ```bash
   jupyter notebook Batting_Performance_Analysis.jpynb

## Key Findings
* Batting average tends to be higher in early counts.
* Batting performance in summer wasn't as good as in other months.
* Handling pitches on the inside corner is outstanding.

## Future Work
* Apply machine learning to predict the next season's statistics.
* Investigate how pitching in the upcoming season will affect batting performance, and identify the key factors that contribute to this impact.

## License
This project is licensed under the MIT License. See the [LICENSE](https://github.com/knt-ktsg/Batting-Performance-Analysis/blob/main/LICENSE) file for details.

