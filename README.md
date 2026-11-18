# SupeRR-Selector-Season-2
Interactive dashboard that picks the 10 most reliable batters and 10 most reliable bowlers under pressure in T20 cricket. Built for the Rajasthan Royals SupeRR Selector Season 2, Round 1


# Under Pressure: Player Dashboard

An interactive dashboard for the Rajasthan Royals SupeRR Selector Season 2, Round 1 challenge: Identify the Most Reliable Players Under Pressure.

It ranks 181 batters and 198 bowlers using only the supplied ball-by-ball data (about 192,900 deliveries, January 2022 to November 2026). It then shows the top 10 in each role and how the model got there.

How the model works, in short

Mark the pressure moments: tight chases, balls that can swing the win chance a lot, or both.
Give every ball a weight based on what is at stake and how recent it is.
Compare each ball with what a typical player does in the same situation.
Pull thin records toward average, so a short hot streak cannot beat a long record.
Combine four scores into one: core performance (30%), pressure performance (40%), dot control (15%) and consistency (15%).

What is inside

Top 10: the final batter and bowler lists, with how firm each place is.
How it works: the model in plain English, with a glossary and FAQ.
Pressure definition, Performance scoring, Fair comparison: the method, with interactive tools. These include a ball tester, a Weight lab and a worked example.
Reliability and limits: how steady the ranks are, what-if checks and the model’s limits.
All players, Player cards, Compare: every eligible player, with a full card for each.

How to use it
Download index.html and open it in any modern browser. It is a single self-contained file. It works offline, but the fonts only load with an internet connection. If you use GitHub Pages, set the repo to serve that file and the dashboard opens at your Pages link.

Independent analysis for the SupeRR Selector challenge. Not an official Rajasthan Royals product. Built only from the supplied data pack. No player photos or club logos are used.
