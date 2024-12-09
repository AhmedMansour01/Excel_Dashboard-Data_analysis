# Steam Games Analysis Dashboard

## Overview

This Excel dashboard analyzes a dataset of Steam games, providing key insights into user engagement, game popularity, and review ratings. The data was cleaned and prepared using Power Query which I found to be valuable asset it to me, and the dashboard is powered by interactive Pivot Tables, Pivot Charts, and a slicer for dynamic exploration.

![Steam dashboard](https://github.com/user-attachments/assets/85a31ab4-8b1a-4db1-ad6e-6c10737b9fcd)


---

## Skills Used

This project involved the application of the following skills:  
- **Power Query:** For data cleaning and transformation.
  ![Power_query_steamspy](https://github.com/user-attachments/assets/37ff9da8-70a3-454c-899a-2061d95d5860)
- **Pivot Tables:** To summarize and analyze data.  
- **Pivot Charts:** For visualizing insights and trends.  
- **Data Analysis:** For uncovering meaningful patterns and metrics.  

---

## Contents

1. [Dataset Overview](#dataset-overview)  
2. [Dashboard Features](#dashboard-features)  
3. [Skills Used](#skills-used)  

---

## Dataset Overview

The dataset contains detailed information on Steam games, including:  
- **Game Titles**  
- **Genres**  
- **Concurrent Users**  
- **Percentage of Positive Review of Total Owners**  
- **Number of Owners**  
- **Publishers**  

---

## Dashboard Features

### 1. **Concurrent Users and Owners for every Genre**  
   - **Chart:** Displays the total concurrent users and owners for each genre.  

![Genre CCU chart](https://github.com/user-attachments/assets/fe5de207-8636-4408-b391-950ccf554288)

Indie games had a signficant number of downloads but not many CCU which is expected. free-to-play and strategy games were the opposite, likely skewed by games like Dota 2.

I wanted to see which genre had the most downloads and the most concurrent users, if I wanted to make a game and wanted to look at which genres were the most played I would probably look at the average instead of the total.

### 2. **Top Games by Concurrent Users**  
   - **Chart:** Highlights the games with the highest average concurrent users.

![top played games](https://github.com/user-attachments/assets/e18ecc41-7f95-4f7f-b58e-7e0aba8ed96b)

Dota 2, PUBG, and CS:GO are the highest by a large margin affiriming that the games with that multiplayer, action-based games are the most addictive.

### 3. **Games with the Highest % of Positive Reviews**  
   - **Chart:** Visualizes the games with the most positive user reviews (as a percentage).  
   - **Slicer:** Allows filtering by the number of owners to set minimum or maximum thresholds.

![most + reviews](https://github.com/user-attachments/assets/8abf2ed2-0e48-4181-8f4e-9b444ff35c87)

The above chart offers a look at the games with the highest % of positive reviews to total downloads. the slicer helps as the games with highest % were all games of around 10k Owners.


### 4. **Top Game by Owners and Largest game Publisher**  
   - **Box 1:** Displays the game with the most owners.
   - **Box 2:** Displays the publisher who has released the most games.

![Biggest game   publisher](https://github.com/user-attachments/assets/cb332d49-3553-4ef4-ba35-b97646b01d97)

As expected Dota 2 is the most owned game. Big Fish Games living up to their name.

