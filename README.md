In this project, i have taken 2019 airbnb data for analysis. It includes exploring, filtering and cleaning of the data, by deleting any duplicates and filled the missing and na values. For this i have used pandas dataframe.

Next step i have framed 13 questions for this project which are:
Problem Statement
1. What is the price distribution across the neighbourhood group?
2. What are the most popular room type in different neighbourhood group? 
3. What are the average price in different neighbourhood?
4. What are the most listing in Airbnb from a neighbourhood perspective?
5. What are the minimum nights listed in Airbnd from a neighbourhood perspective?
6. How many total reviews had been given to different neighbourhood?
7. What are the availability in each neighbourhood in the next year?
8. What are the top ten lowest and highest price in cities of all neighbourhood?
9. What are the top ten most popular room types of all neighbourhood?
10. What are the top ten highest min nights in all neighbourhood?
11. Which are the top ten cities which got highest total reviews in airbnb 2019?
12. What are the top ten most host listed cities?
13. What are the top ten most available cities in the next year?

Conclusion:
1. Manhattan has the highest price. Brooklyn has the second highest price after Manhattan. Bronx has the least price. Queens and Staten Island has the same price range of least and highest.
2. The most popular room is Entire home/apt in manhattan. Second highest is private room in Brooklyn. Least popular room is shared room in staten island. Also private room and entire home/apt in brooklyn has good bookings. While all rooms in bronx and shared room in all areas are not having good bookings.
3. Manhattan is the highest avg price city and Bronx is the lowest avg price city. Also Brooklyn is the Second highest avg price city. while Queens and Staten Island is neither Highest nor lowest while it meets in the middle.
4. Both Manhattan and Brooklyn has the highest number of listings. Bronx and Staten Island has the least number of listings. Queens has only 6000 listings as difference from 19000 each of brooklyn and manhattan  listings.
5. Brooklyn has 5000 listing for 2 minimum nights, 4000 for 1 minimum nights and 3000 for 3 minimum nights. Also it has 994 listing for 30 minimum nights. Manhattan has 5000 listing for 1 minimum nights, 4000 for 2 minimum nights and 3000 for 3 minimum nights. Queens has 2000 listing for 1 minimum nights, 1300 for 2 minimum nights and 696 for 3 minimum nights. Staten Island has 121 listing for 2 minimum nights, 110 for 1 minimum nights and 46 for 3 minimum nights. Bronx has 350 listing for 1 minimum nights, 340 for 2 minimum nights and 178 for 3 minimum nights.
6. Brooklyn has the highest number of reviews followed by Manhattan. Staten Island has the least number of reviews preceded by Bronx. Queens only has 14.2% reviews.
7. Staten Island has the highest availability for next year with 200 days average followed by Bronx and Queens with 175 and 140 each. Manhattan and Brooklyn has the least availability with 100 and9 90 days.
8. Bulls head in staten island is the lowest avg price followed by hunts point, tremont and sound view in Bronx. In between 47 and 59, we got 5 staten island, 4 Bronx and 1 queens neighbourhood in the lowest average price. Willowbrook in Staten island is the highest avg price followed by Neponsit and Breezy point in Queens. In between 250 and 179, we got 1 staten island, 2 Queens and 7 Manhattan neighbourhood in the highest average price.
9. In private rooms, most were listed in Bedford-Stuyvesant with 2026 and williamsburg with 1977. In Entire home/apt rooms, most were listed in williamburg with 1723 and Bedford-Stuyvesant with 1528. In shared rooms, most were listed in Hell's kitchen with 95 and Bedford-Stuyvesant with 84. but in this session williamsburg have only 32 listing placing at 9 position in top 10.
10. Spuyten Duyvil has the highest avg min nights with 60+ days. Second is North riverdale with 40+ avg min nights. But from third to 10 positions, they lie in between 25 to 10 days.
11. Bedford-Stuyvesant has got high total reviews with 4800 reviews. Williamsburg is second with 3300 reviews. while Harlem is third with 2900 reviews.
12. Financial District hosted the most with 69000 host listing. Murray Hill hosted the second with 25000 host listing. Hells kitchen is in the third with 21910 host listing.
13. On average Co-op city has 364 days availability. Willow brook has 351 days availability. Spuyten Duyvil, Eastchester, Richmondtown has 300+ days availability Tottenville has 267 days availability.
14. price and number of reviews has a correlation of 0.028. which tend to see that reviews affect the pricing.
15. Also minimum nights and price has a correlation of 0.031 which also affects the price.
16. reviews per month and availability has a correlation of 0.23 which affects the availabilty.

I have calculated and visualized them for better understanding for which i  have used seaborn and matplotlib for visualization.
