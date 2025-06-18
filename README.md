# IPL-Analysis-Dashboard📊
1.⚡🏏 IPL Insights Dashboard: Tableau Analysis of IPL Trends and Performances
An interactive Tableau dashboard built to explore Indian Premier League (IPL) data—highlighting team champions, top performers, scoring trends (sixes/fours), toss decision impacts, and head-to-head win patterns across seasons.
(Includes a small Tableau logo icon next to the title when embedding in HTML/Markdown:
or use 📊 to denote Tableau visuals.)

2. Short Description / Purpose
The IPL Insights Dashboard is a visually engaging and analytical Tableau report designed to help cricket analysts, commentators, team strategists, and enthusiastic fans dive into IPL match data across all seasons. It surfaces key metrics like title winners 🏆, Orange Cap (highest run-scorer) 🎖️, Purple Cap (highest wicket-taker) 🎗️, overall sixes/fours tally 💥, and the influence of toss decisions on match outcomes.

3. Tech Stack 📊🛠️
Tableau Desktop / Public 📈

Core platform for building and publishing interactive visuals.

Data Preparation 🧹

Excel or Python (Pandas) for cleaning, normalizing team/player names, aggregating stats.

Tableau Calculations & Parameters 🔢

Dynamic fields (season selector, win% calculations, KPI metrics).

Data Files 📁

CSV/Excel extracts (e.g., matches table, player-season aggregates, ball-by-ball if available).

Hosting & Sharing ☁️

Published on Tableau Public; embedded in README or presentations via snapshot images or embed code.

4. Data Source 📂
Primary IPL Dataset

Matches table: season, match ID, teams, toss winner/decision, match winner, margin, venue, etc.

Player-season aggregates: total runs by player, total wickets by player.

Optional Ball-by-Ball Data 🎯

Used to compute total sixes/fours per season or by team.

Supplementary Metadata 🏷️

Team logos/names (normalize across seasons), season info (year, final match).

Preparation Steps

Clean & Normalize: harmonize team names (e.g., “Delhi Daredevils” → “Delhi Capitals”).

Aggregate Stats: compute Orange Cap (highest run-scorer) and Purple Cap (highest wicket-taker) per season.

Summarize Wins: tally match wins by team, split by batting-first vs. fielding-first.

Compute Totals: total sixes and fours per season (or overall if “All” selected).

5. Features / Highlights ✨
🎯 Business Problem
IPL data is rich but manual analysis is slow:

Which teams dominated in a given season or overall?

Who led in runs/wickets each year?

How have sixes/fours trends evolved?

Does toss decision (bat vs. field) influence win rates?

🎯 Goal
Build an interactive Tableau dashboard for:

Filtering by season (or “All”) to surface key outcomes.

Displaying season champion, Orange Cap, Purple Cap, sixes/fours totals.

Analyzing toss-decision impact on wins, and team-specific batting-first vs. field-first performance.

📺 Key Visuals Walkthrough
KPI Tiles (Top Row)

🏆 Title Winner: Team name + logo for selected season (or summary “Most titles” when All).

🎖️ Orange Cap: Player name + runs + image/icon.

🎗️ Purple Cap: Player name + wickets + image/icon.

💥 Total Sixes: Count for season or overall.

▉ Total Fours: Count for season or overall.

Season Selector 🔄

Dropdown or slider (📅 icon) to pick season or “All”; updates all visuals.

Match Wins by Team & Toss Decision 📊

Horizontal stacked bars: each team on vertical axis.

Color/legend: 🏏 batting-first wins vs. 🛡️ fielding-first wins.

Hover tooltip shows exact counts; clicking filters other charts.

Toss Decision Win % 🥧

Pie chart: % wins choosing to bat-first (🏏) vs. field-first (🛡️) for selected context.

(Optional) Trends Over Seasons 📈

Line chart of sixes/fours by season (with cricket-ball markers 🏏).

Toss-win % trend line to spot strategic shifts.

(Optional) Top Performers Over Time 🥇

Mini bar chart or table listing top 5 run-scorers or wicket-takers across seasons.

Interactivity & Tooltips 💡

Hover for extra context (e.g., average run rates).

Click filters: drill into a single team or player across visuals.

6. Screenshots / Demos 📷
Static Snapshot
![IPL Dashboard Screenshot](sandbox:/mnt/data/IPL Analysis Dashboard.png)
(Use small Tableau icon 📊 in corner of documentation or README.)

GitHub Reference

Screenshot file in repo:
https://raw.githubusercontent.com/mohsin2481/IPL-Analysis-Dashboard/main/IPL%20Analysis%20Dashboard.png

Embed next to “View Dashboard” link.

Interactive Version
Explore on Tableau Public 🔗 https://public.tableau.com/app/profile/mohsin.khan3774/viz/Book1_17159475855320/Dashboard1

##How to Use / Demo Walkthrough 🎬
Open the Dashboard: Click the link above to load it in Tableau Public.

Select Season 📅: Use the season dropdown at the top-right to choose a specific IPL season or “All”.

View KPIs 🏏: Observe who won the title, Orange Cap, Purple Cap, and total sixes/fours for that season.

Analyze Match Wins 📊: Check the horizontal bar chart to see each franchise’s match wins split by batting-first vs. field-first.

Review Toss Impact 🥧: See the pie chart for overall win percentages based on toss decisions.

Drill Down 🔍: If interactive filters are enabled, click on a team or specific KPI to filter other visuals and uncover deeper insights.
