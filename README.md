# 🏏 Cricket Analysis Dashboard

A dynamic and fully interactive Power BI project designed to analyze cricket tournament data, providing deep insights into team performances, player statistics, and match dynamics across multiple dimensions.

## 📊 Project Overview

This dashboard transforms raw cricket tournament data into actionable visual insights across two fully interactive pages. It helps users easily dissect and understand team strengths, player contributions, and historical trends.

### 🔑 Key Metrics Tracked

  * **Total Runs Scored**
  * **Total Wickets Taken**
  * **Count of PlayerID**
  * **Count of MatchID**
  * **Count of Teams**

## 🖼️ Dashboard Screenshots

### Tournament Overview

![Tounament Overview](https://github.com/sbhSajid/Cricket-Dashboard-Analysis/blob/main/Tournament_Overview.png)

### Performance Analysis

![Performance Analysis](https://github.com/sbhSajid/Cricket-Dashboard-Analysis/blob/main/Performane%20Analysis.png)

## 📁 Dashboard Structure & Interactivity

The dashboard is split into two specialized pages. Slicers applied on one page carry over or can be used independently to drill down into the specifics of the tournament.

### 1\. Tournament Overview

This page gives a macro-level view of the tournament's biggest contributors and overall team distributions.

  * **Runs Scored by Team:** A bar chart showcasing the total runs dominated by specific teams.
  * **Top Ten Run Scorers:** Highlights the most impactful individual batsmen of the tournament.
  * **Average Age by Team:** A breakdown of team youth vs. experience.
  * **Balls Faced by Team:** Analyzes which teams spent the most time at the crease.
  * **Wickets Taken by Team:** Shows overall bowling dominance across the tournament.

### 2\. Performance Analysis

This page takes a closer look at team efficiencies and trend lines.

  * **Wicket Trends by Team:** An interactive area and line chart combo analyzing how consistently teams picked up wickets.
  * **Team Comparison Averages:** Dynamically explore more in-depth team stats.



## 🎛️ Navigation & Slicers

To allow users to drill down into specific data, both pages of the dashboard include a collapsible side navigation panel with multi-select slicers:

  * **Stage:** Filter by specific phases of the tournament.
  * **Venue Name:** See how teams perform at specific stadiums.
  * **Country:** Filter data by the country where the matches took place.
  * **City:** Narrow down the metrics to specific city dimensions.



## 🛠️ Tools Used

  * **Power BI Desktop** - For data modeling, DAX measures, and visualization.
  * **DAX (Data Analysis Expressions)** - Used for calculating complex aggregates and KPIs.



