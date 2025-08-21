
# Dashboard: ODI – India vs Australia: Visualizing the Game Key Moments & Player Metrics
    


## 📊 Download Power BI .pbix file

[Click here to download the Power BI report](India_vs_Australia.pbix)

## LinkedIn
https://tinyurl.com/IndiaVsAustraliaDashboard

## Problem Statement

In the world of cricket, analyzing player performance is often challenging due to the availability of raw statistics in scattered formats. While platforms like ESPN Cricinfo provide comprehensive data, the absence of interactive and visually engaging insights makes it difficult for fans, analysts, and coaches to quickly evaluate batting and bowling performance.

The challenge lies in:

Transforming large volumes of raw cricket statistics into meaningful insights.

Enabling player-wise analysis for comparing performance across different matches.

Showcasing key performance indicators (KPIs) like runs, strike rate, wickets, economy rate, etc., in an intuitive and interactive manner.

Enhancing storytelling with visuals and navigation to make cricket analytics more engaging and accessible.


This project addresses these challenges by building an interactive Power BI Dashboard that analyzes batting and bowling statistics of players in India vs Australia ODI matches. The dashboard leverages Cricinfo’s Statsguru data (imported directly from the web) and provides slicers, buttons, and KPI visuals to make performance tracking interactive, insightful, and user-friendly.


### Steps followed 

- Step 1 : Load data into Power BI Desktop, dataset is a web.
- Step 2 : Open power query editor & in view tab under Data preview section, check "column distribution", "column quality" & "column profile" options.
- Step 3 : It was observed that in few of the columns errors & empty values were present.
- Step 4 : Empty values and null values were replaced.
- Step 5 : In the report view, under the view tab, theme was selected.
- Step 6 : In the report view, under the insert tab,two text box was added in two report page to the canvas, for highlighting Batting and bowling data 
- Step 7 : Visual filters (Slicers) were added for  field named "Players Name".
- Step 8 : 14 card visuals were added to the Batting Data Analysis canva, representing Runs, Strike rate, Not outs, matches, Innings, Highest score, Number of 6s, Number of 4s, Half Centuries, Centuries, Ball Faced, Zeros, Span. 
- Step 9 : 12 card visuals were added to the bowling Data Analysis canva, representing Runs, Strike rate, Wickets, Over, Maiden Over, Matches, 5 wickets, 4 Wickets, Average, Economy, Winnings, Span.
- Step 10 : A card visual was also added to the both report design area representing the name of the players.
- Step 11 : Python Pandas was used to scrap image URLs from Wikidata to render images dynamically in visual.
  
Above step enabled displaying player profile pictures inside Power BI dashboards, making the analysis more engaging.

- Step 12 : In the report view, under the insert tab, using shapes option from elements group a rectangle and parallelogram was inserted & similarly using image option Indian tricolour flag was added to the report design area.

 # Cover Image Snapshot (Power BI DESKTOP)

![Cover Image Snapshot](https://raw.githubusercontent.com/sujithts31618-ui/Power_Bi_Dashboard-/main/Cover_2025-08-21_005241.png)


# Report Snapshot (Power BI DESKTOP) Batting
1.
![Cover Image Snapshot](https://raw.githubusercontent.com/sujithts31618-ui/Power_Bi_Dashboard-/main/Sachin_2025-08-21-004752.png)



2.

![Cover Image Snapshot](https://raw.githubusercontent.com/sujithts31618-ui/Power_Bi_Dashboard-/main/Virat_2025-08-21_004819.png)


3.

![Cover Image Snapshot](https://raw.githubusercontent.com/sujithts31618-ui/Power_Bi_Dashboard-/main/Dhoni_2025-08-21_004945.png)


4.

![Cover Image Snapshot](https://raw.githubusercontent.com/sujithts31618-ui/Power_Bi_Dashboard-/main/Kedar_2025-08-21_004921.png)

5.

![Cover Image Snapshot](https://raw.githubusercontent.com/sujithts31618-ui/Power_Bi_Dashboard-/main/Gaikwad_2025-08-1_213347.png)

6.

![Cover Image Snapshot](https://raw.githubusercontent.com/sujithts31618-ui/Power_Bi_Dashboard-/main/har_2025-08-21_004857.png)

# Report Snapshot (Power BI DESKTOP) Bowling

1.

![Cover Image Snapshot](https://raw.githubusercontent.com/sujithts31618-ui/Power_Bi_Dashboard-/main/jas_2025-08-21_005037.png)

2.

![Cover Image Snapshot](https://raw.githubusercontent.com/sujithts31618-ui/Power_Bi_Dashboard-/main/anil_2025-08-21_005117.png)

3.

![Cover Image Snapshot](https://raw.githubusercontent.com/sujithts31618-ui/Power_Bi_Dashboard-/main/jadeja_2025-08-21-005133.png)

4.

![Cover Image Snapshot](https://raw.githubusercontent.com/sujithts31618-ui/Power_Bi_Dashboard-/main/ask_2025-08-21_005101.png)


## 👨‍💻 Author
*Dashboard Created By:* Sujith TS 

*Date:* 20th August 2025

## 📂 Download .pbix 
[Click here to download the Power BI report](India_vs_Australia.pbix)

🎥 [Watch the interactive video demo on LinkedIn] 
## Link : https://tinyurl.com/IndiaVsAustraliaDashboard

## 📌 Data Source WEB
All cricket statistics used in this dashboard have been sourced from  
[ESPN Cricinfo – Statsguru](https://stats.espncricinfo.com/)


