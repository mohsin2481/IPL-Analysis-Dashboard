# IPL-Analysis-Dashboard📊
1.⚡🏏 IPL Insights Dashboard: Tableau Analysis of IPL Trends and Performances
An interactive Tableau dashboard built to explore Indian Premier League (IPL) data—highlighting team champions, top performers, scoring trends (sixes/fours), toss decision impacts, and head-to-head win patterns across seasons.
(Includes a small Tableau logo icon next to the title when embedding in HTML/Markdown:
or use 📊 to denote Tableau visuals.)

2. Short Description / Purpose
The IPL Insights Dashboard is a visually engaging and analytical Tableau report designed to help cricket analysts, commentators, team strategists, and enthusiastic fans dive into IPL match data across all seasons. It surfaces key metrics like title winners 🏆, Orange Cap (highest run-scorer) 🎖️, Purple Cap (highest wicket-taker) 🎗️, overall sixes/fours tally 💥, and the influence of toss decisions on match outcomes.

3. Tech Stack
📊 Tableau Desktop / Tableau Public – Main visualization platform used to build and publish the dashboard.

🛠️ Data Preparation Tools – Data cleaning/transformation in Excel and/or Python (Pandas) to shape match- and player-level datasets into Tableau-ready extracts.

🔢 Calculated Fields & Parameters in Tableau – For dynamic KPIs (e.g., season selector, computed totals, win percentages).

📁 Data Source Files – CSV/Excel extracts (e.g., Kaggle IPL dataset containing matches, players, ball-by-ball details).

☁️ Hosting – Published to Tableau Public for sharing; can embed in blogs or GitHub README with Tableau embed code or snapshot images.

(Tip: next to “Tableau” mentions, you can include a small Tableau icon or use an emoji like 📊 or 📈 for visual cues in documentation.)

4. Data Source
Primary Source: IPL historical data (commonly from a public repository such as Kaggle’s IPL datasets).

Data Structure:

Matches Table 📝: season, match ID, teams, venue, toss winner/decision, match winner, margin, etc.

Players/Performance Table 📋: aggregated stats per season (runs scored by player, wickets taken).

Ball-by-Ball Data (optional) 🎯: to compute total sixes/fours per season or per team.

Supplementary Tables 🏷️: team metadata (names, logos), season metadata (year, final match info).

Data Preparation:

Clean inconsistent team naming over seasons (e.g., “Delhi Daredevils” → “Delhi Capitals”).

Aggregate player stats per season for Orange Cap & Purple Cap winners.

Summarize match outcomes by toss decision and by team.

Compute counts of sixes and fours across matches/seasons (💥 & ▉ visuals).

(You can include small icons or inline images of team logos when presenting in HTML or rich Markdown for documentation.)

5. Features / Highlights
• Business Problem 🎯
IPL generates massive match and player data annually, but extracting quick insights is challenging:

Which teams have been most successful overall or in specific seasons? 🏆

Who are the top run-scorers (Orange Cap) and wicket-takers (Purple Cap) by season? 🎖️🎗️

How many sixes and fours have been hit league-wide, and how has hitting power evolved? 💥

Does winning the toss and choosing to bat/field correlate strongly with match wins? 🎲

How do teams fare in wins when batting first vs. chasing? 🚀 vs. 🛡️

• Goal of the Dashboard 🎯
To deliver an interactive visual tool that:

Enables filtering by season (or view all seasons) and instantly see key outcomes. 🔄

Highlights season-by-season champions and standout individual performances. 🌟

Reveals scoring trends (total sixes/fours) across IPL history. 📈

Analyzes toss-decision-based win percentages and team-specific win distributions. ⚖️

Supports data-driven discussions for commentators, analysts, team management, and fans. 🧠

• Walkthrough of Key Visuals 📺
Top KPI Tiles (Top Row) 📌

Title Winner 🏆: Displays the IPL champion team for the selected season (or summary “Most successful team overall” when “All”). Shows team name + logo.

Orange Cap 🎖️: Highest run-scorer of the season with total runs and player image/icon.

Purple Cap 🎗️: Highest wicket-taker of the season with total wickets and player icon.

Tournament 6’s 💥: Total number of sixes hit in that season (or cumulatively).

Tournament 4’s ▉: Total number of fours hit in that season (or cumulatively).

(Visual cue: place small cricket bat/ball icons next to these tiles in Tableau or documentation.)

Season Selector (Parameter / Filter) 🔄

Dropdown or slider allowing users to pick a specific season (2008, 2009, …) or “All”. All visuals update accordingly.

Use a season icon (📅) next to the control in documentation.

Match Win by Team & Toss Decision (Stacked Bar Chart) 📊

Horizontal stacked bars listing teams on vertical axis (e.g., Mumbai Indians, Chennai Super Kings).

Bars split by matches won batting first (“bat” icon 🏏) vs. fielding first (“field” icon 🛡️).

Hover reveals exact counts; clicking filters other visuals.

In documentation, embed a small illustrative thumbnail or icon legend: 🏏 = batting-first wins, 🛡️ = field-first wins.

Toss Decision-Based Winning Percentage (Pie Chart) 🥧

Pie showing percentage of matches won when choosing to bat first vs. field first.

Include legend icons: 🏏 for bat-first wins %, 🛡️ for field-first wins %.

In docs, show a small pie icon or embed the actual pie snapshot.

(Optional) Trend Over Seasons (Line / Bar Charts) 📈

Line chart showing total sixes or fours by season (use a cricket icon marker on points).

Another line for toss-win % trend over years with markers (e.g., ⚖️ icons).

Documentation: include a small line-chart icon or embedded static thumbnail.

(Optional) Top Performers Over Time (Table or Small Bar Chart) 🥇

Table or mini bar chart ranking top 5 run-scorers or wicket-takers overall or per season.

Use trophy 🏆 or medal 🎖️ emojis in column headers for visual flair.

Tooltips & Interactivity 💡

Hover tooltips: show extra context (e.g., season average run rates, team win percentages).

Quick filters: e.g., click on a team icon to filter.

In docs, note “Hover over bars to see detailed stats” with a cursor icon 🖱️.

6. Screenshots / Demos 📷
Below is a static snapshot of the dashboard; for full interactivity, visit the live Tableau Public link.

![Dashboard Screenshot](sandbox:/mnt/data/IPL Analysis Dashboard.png)
(Consider overlaying a small “Tableau” watermark or icon in the corner of screenshots for branding.)

Screenshot on GitHub:

GitHub: IPL Analysis Dashboard Screenshot

Raw image URL for embedding:
https://raw.githubusercontent.com/mohsin2481/IPL-Analysis-Dashboard/main/IPL%20Analysis%20Dashboard.png

You can also embed a small Tableau icon next to this link: 📊.

Interactive Version:
Explore the IPL Insights Dashboard on Tableau Public 🔗

How to Use / Demo Walkthrough 🎬
Open the Dashboard: Click the link above to load it in Tableau Public.

Select Season 📅: Use the season dropdown at the top-right to choose a specific IPL season or “All”.

View KPIs 🏏: Observe who won the title, Orange Cap, Purple Cap, and total sixes/fours for that season.

Analyze Match Wins 📊: Check the horizontal bar chart to see each franchise’s match wins split by batting-first vs. field-first.

Review Toss Impact 🥧: See the pie chart for overall win percentages based on toss decisions.

Drill Down 🔍: If interactive filters are enabled, click on a team or specific KPI to filter other visuals and uncover deeper insights.
