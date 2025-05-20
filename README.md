# IPL Analysis Dashboard: Insights from the Indian Premier League
A vibrant, interactive Power BI report designed to explore match-level and player-level data across IPL seasons—focusing on performance metrics, team dynamics, match outcomes, and venue-specific insights.

# Purpose
The IPL Analysis Dashboard is a dynamic visualization tool built to explore key statistics from the Indian Premier League (IPL). It helps users analyze match results, player performances, and team strategies across seasons. The dashboard is ideal for cricket enthusiasts, sports analysts, and strategists who want quick insights into the T20 cricket league.

# Tech Stack
The dashboard was built using the following tools and technologies:

•📊  Power BI Desktop – Main platform for dashboard development and interaction.

•📂Power Query – For data loading, filtering, and transformation.

•🧠DAX (Data Analysis Expressions) – To create dynamic measures like strike rates, averages, and win counts.

•📝Data Modeling – Relationships established between match, player, and venue data for seamless filtering.

•📁File Format – .pbix for development; .png for visuals.

# Data Source
Source : Kaggle IPL Matches Dataset (2008–2024)

The dataset has two csv files: 

•First file is ipl matches data(from 2008-2024) includes over 900 IPL matches with details such as teams, venues, toss outcomes, match results, margins, and individual performances.

•Second file is ipl ball by ball data(from 2008-2024) includes details such as innings,overs, ball_number, batter, bowler, non_striker, extras_type, batsman_run, extras_run, total_run, iswicket_delivery, player_out, dismisal_kind, fielders_involved, batting_team, bowling_team.

# Features
• **Business Problem**

The IPL is one of the most-watched cricket leagues globally. However, its extensive data—ranging from player stats to venue performance—can be overwhelming to interpret without visual assistance.

Key questions like:

• Which teams dominated in particular season?

• How do toss decisions impact win probability?

• Who were the top performers with the bat and ball?

• Which venues favoured chasing vs. defending?

are challenging to answer from raw CSVs.

• **Goal of the Dashboard**

To deliver an interactive IPL report that:

• Highlights key batting and bowling performances by player.

• Explores win trends by toss decision, venue, and result type.

• Provides team-level summaries for a season.

• Helps users understand contextual success factors (e.g., pitch, toss, player).

•**Key Visuals**

• Title Winners, Orange Cap, Purple Cap (Top Row Cards)
  Snapshot of the season’s top team and standout players:
  
  - Winner: Kolkata Knight Raiders
    
  - Most Runs: Virat Kohli (741)
    
  - Most Wickets: Harshal Patel (24)
    
• Batting & Bowling Stats (Middle Left)
  Dropdown filters let users select a player.
  
 For example, selecting KL Rahul reveals:
 
    - Runs: 520
    
    - 6s: 19 | 4s: 45
    
    - Strike Rate: 130.65

   Similarly, selecting Yuzvendra Chahal shows bowling stats:
   
    - Wickets: 19
    
    - Economy: 6.95
    
    - Average: 19.68
    
    - Strike Rate: 17.00

• Wins by Toss Decision (Donut Chart)
  Shows 80% of wins came when teams chose to field first.
  
• Wins by Result Type (Donut Chart)
  Visualizes how teams won:
  - 61.7% by wickets
  - 36.6% by runs
  - Few ties
• Venue-Wise Match Wins (Stacked Bar)
  Insights into venue-specific trends, e.g.,
  - Dubai: More wins by chasing (wickets).
  - Sharjah: Balanced win distribution.

• Team Wins in Season (Bar Chart)
  Displays total wins:
  - Chennai Super Kings led with 11
  - Delhi Capitals: 10
  - RCB & KKR: 9
# Business Impact & Insights
• Fan Engagement: Helps viewers understand player form, toss outcomes, and match dynamics.

• Strategy Planning: Team analysts can optimize decisions based on toss patterns and venue trends.

• Fantasy Leagues: Useful for players selecting top performers by season.

• Broadcast & Media: Generates visuals for quick match highlights and previews.
# Dashboard Screenshot


