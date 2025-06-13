# The Anatomy of a Bestseller: Genre, Platform, and Region in Game Sales

## Tools

**SQL:** The core language used to analyze the dataset. It enabled me to extract, filter, and aggregate data efficiently to uncover actionable insights.

**PostgreSQL:** Database management system used to store and manage the dataset.

**Visual Studio Code:** My development environment for writing and executing SQL queries, as well as managing database connections through integrated extensions.



## What features of a game influence its sales success in global and regional markets?

[SQL QUERIES - GENRES](SQL_queries/1_genre_sales)


***Which game genres sell best globally?***

1. Action (1751.18 million units),
2. Sports (1330.93 million),
2. Shooter (1037.37 million).

***Do different regions prefer different genres?***


🔸North America heavily favors Shooter games (56.16% of that genre’s sales), followed by Sports and Action.

🔸Europe shows similar preferences but with a higher share for Racing (32.57%) and Sports.

🔸Japan stands out with a clear preference for:
Role-Playing games (37.99% of RPG sales occur in Japan), other popular genres in Japan include Fighting, Puzzle, and Adventure.

***Which genres dominate global sales?***

Action is the most profitable genre worldwide.
Sports and Shooter follow closely, especially dominant in Western markets.




[SQL QUERIES - PLATFORMS](SQL_queries/2_platform_sales)

***Which platforms are the most profitable?***

1. PS2 – 1255.64 mln

2. X360 – 979.96 mln

3. PS3 – 957.84 mln

4. Wii – 926.71 mln

5. DS – 822.49 mln

***Are certain platforms stronger in specific regions?***

***🔸(NA)🔸***

Dominated by X360 (601.05) and Wii (507.71),
Strong performance from PS2 and DS as well.

***🔸(EU)🔸***

Highest sales on PS3 (343.71) and PS2 (339.29),
Notably strong PC sales here (139.68 million), much more than in other regions.

***🔸(JP)🔸***

Dominated by portable and Japan-made consoles:
DS (175.57), PS (139.82), SNES (116.55),
Also strong performances from 3DS, PSP, PS2, and NES.


[SQL QUERIES - TIME TRENDS](SQL_queries/3_time_trends)

***How has the popularity of genres and platforms changed over time?***

Over the decades, the popularity of game genres has shifted notably:

The 2000s represent the golden era for most genres. Genres like Action, Sports, Racing, Role-Playing, Fighting, Simulation, and Miscellaneous saw their highest total sales during this period.

Action games experienced explosive growth: from 139.29M in the 1990s to 858.91M in the 2000s.

Platform and Puzzle games, highly popular in the 1980s and 1990s (e.g., classic Nintendo titles), declined significantly in the 2010s.

Shooter games are unique in that they peaked in the 2010s, likely driven by franchises like Call of Duty and Battlefield.

Simulation and Strategy games remain niche, but their peak was also during the 2000s.

***When do peak sales occur for specific types of games?***

Almost all genres peaked in the 2000s, with Shooter games being the exception, reaching their highest popularity in the 2010s.

This indicates that the 2000s were a high-growth period for the gaming industry, while the 2010s saw refinements and genre-specific booms, especially in online multiplayer shooters.


[SQL QUERIES - PUBLISHERS](SQL_queries/4_publisher_domination)

***Which publishers dominate the market?***

Nintendo is by far the market leader, responsible for 1 in every 5 games sold globally. EA and Activision follow, commanding significant market shares of over 8–12%. The top 5 publishers together account for more than 50% of the total market.

***Do some publishers specialize in certain regions or genres?***

The answer is YES. Many publishers exhibit clear specialization by genre, and often this reflects their regional focus or brand identity.

🔸 RPG specialists:
Companies like Square Enix, Enix Corporation, SquareSoft, Atlus, and Nippon Ichi Software clearly specialize in Role-Playing games. These publishers are Japan-based, reinforcing the cultural and regional preference for RPGs in Japan.

🔸 Action-focused publishers:
Warner Bros., LucasArts, Take-Two Interactive, and Eidos Interactive derive 50% or more of their sales from Action titles, consistent with Western market trends, especially in North America.

🔸 Racing & Misc specialists:
Codemasters is a UK-based company renowned for racing games like the F1 and Dirt series, while MTV Games focused solely on music/rhythm-based Misc titles (e.g., Rock Band), indicating a niche market strategy.








[SQL QUERIES - COMMON FEATURES](SQL_queries/5_common_features_best_games)

***What are the common characteristics of the highest-selling games globally?***

🔸***Platform***

 Top-selling games most often appear on platforms with large user bases like Wii, DS, Xbox 360, and PS3.

🔸***Publisher***

 Nintendo dominates with over 50 top-selling games, far ahead of competitors like Activision and Take-Two. Trusted publisher brands greatly influence success.

🔸***Genre***

 The most successful genres are Shooter, Platform, and Role-Playing. These genres appeal to both Western and Japanese markets, driving high sales.

🔸***Console Generation***

 Most hits come from the 6th and 7th generations (roughly 2000–2013), when console gaming was booming and global infrastructure was solid.

🔸***Franchise Power*** 

Games from well-established franchises like Mario, Call of Duty, GTA, and Pokémon are consistently top sellers due to loyal fanbases.

🔸***Global Appeal***

Top sellers usually offer broad international appeal, combining accessible gameplay with regionally tailored features.

🔸***Multiplayer or Replayability*** 

Many best-selling games include multiplayer modes or long replay value, which keeps players engaged and encourages continued sales.


[SQL QUERIES - REGIONS](SQL_queries/6_region_sales)

***Which region contributes the most to global sales?***

North America is the largest regional market for video games, consistently contributing the largest share to global sales regardless of a game's performance level.


***What are the sales proportions for bestsellers and mid-tier games?***

🔸***Best-selling games*** perform best in North America, followed by Europe.

🔸***Mid-tier*** (average) games also sell primarily in NA, but have stronger performance in Japan compared to bestsellers.

🔸***Worst-performing games*** have the highest share of sales in Japan (36.60%), indicating that some niche or region-specific titles may perform best locally.


***How significant is the impact of the North American market on a game's global success?***

The North American market has a highly significant impact on a game's global success. For many of the top-selling games, NA accounts for over 50% of global sales. Even among titles with more balanced regional performance, NA still often contributes 30–40% of total sales.



# Summary

The most successful games hit a sweet spot: they leverage top-performing genres, launch on dominant platforms, and are designed primarily with the North American market in mind. Games that miss these strategic alignments struggle to scale, regardless of innovation or creative direction.

# Closing Thoughts
Success is not just about making a good game, it's about making the right game for the right platform, targeting the right audience at the right time. Knowing the anatomy of bestsellers gives developers the blueprint to not just build games, but to build hits.

### DATASET avaiable on: ###
https://www.kaggle.com/datasets/gregorut/videogamesales
