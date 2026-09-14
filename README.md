# Cricket-Player-Performance-Analysis
## Project Overview

This project performs Exploratory Data Analysis (EDA) on cricket player data collected from Cricbuzz.

The analysis focuses on identifying meaningful patterns in player characteristics and batting performance across different cricket formats, playing roles, countries, and playing styles.

The project covers data cleaning, exploratory analysis, statistical relationships, data visualization, and data-driven insights.

## Business Problem

Cricket performance data contains a wide range of player-level statistics across different playing roles, countries, and formats such as Test, ODI, and T20. However, these raw statistics are often presented as isolated metrics, making it difficult to identify meaningful performance patterns, compare players across different contexts, and understand how performance varies across roles, countries, and formats.

## Business Objective

The objective of this project is to analyze Cricbuzz player data to identify meaningful patterns in player characteristics and batting performance across different cricket formats, playing roles, and countries.

## Dataset

The dataset contains cricket player-level information collected from Cricbuzz.

- **Records:** 532 players
- **Attributes:** 79
- **Formats:** Test, ODI, T20, IPL
- **Data includes:** Player profile, country, playing role, batting style, bowling style, batting performance, and bowling performance statistics.

### Key Data Categories

- Player profile and demographics
- Country and playing role
- Batting and bowling styles
- Format participation
- Batting performance
- Bowling performance

## Tools & Technologies

- **Python**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Seaborn**
- **Jupyter Notebook**

## Exploratory Data Analysis

The exploratory analysis was performed to understand player characteristics, format participation, and performance patterns across different cricket contexts.

### 1. Player Profile & Representation

- Distribution of players across countries
- Distribution of players across playing roles
- Distribution of player ages

### 2. Format Participation

- Comparison of player participation across Test, ODI, T20, and IPL formats
- Analysis of player involvement across different cricket formats

### 3. Batting Performance

- Distribution of runs across different formats
- Relationship between batting average and strike rate
- Relationship between age and strike rate

### 4. Bowling Performance
- Distribution of economy across different formats

### 5. Role-Based Performance

- Comparison of T20 runs across different playing roles
- Comparison of T20 wickets across different playing roles

### 6. Multivariate Analysis

- Relationships among multiple batting and bowling performance metrics
- Performance patterns across batting styles and playing roles
- Correlation analysis of bowling performance metrics

### Key Visualizations

#### Player Distribution by Country

![Player Distribution by Country](visuals/player_distribution_by_country.png)

#### Format-wise Player Participation

![Format-wise Player Participation](visuals/format_player_participation.png)

#### Runs Distribution Across Formats

![Runs Distribution Across Formats](visuals/runs_distribution_by_format.png)

#### Average vs Strike Rate

![Average vs Strike Rate](visuals/average_vs_strike_rate.png)

#### Age vs Strike Rate

![Age vs Strike Rate](visuals/age_vs_strike_rate.png)

#### Role-wise T20 Performance

![Role-wise T20 Runs](visuals/role_vs_t20_runs.png)

#### T20 Performance Correlation

![T20 Performance Correlation](visuals/t20_performance_correlation.png)

#### Bowling Performance Correlation

![Bowling Performance Correlation](visuals/bowling_metrics_correlation.png)
