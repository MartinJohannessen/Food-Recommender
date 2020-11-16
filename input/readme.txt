--------------------------------------------------------------------------
Semester assignment dataset file for the INFO345 course at UiB in Fall 2020
--------------------------------------------------------------------------
IMPORTANT: This dataset must only be used in the INFO345 for teaching purposes. 
Any further usage is prohibited and sharing of the dataset is only allowed 
among the students signed up for the INFO345 course at UiB in Fall 2020.

The dataset consists of the following 4 files:
user-item-rating.csv
item-profiles1.csv
item-profiles2.csv
item-profiles1.csv
BMJ-data-all--b-new.csv
--------------------------------------------------------------------------
FILE: user-item-rating.csv
This contains 3 columns which are tab seperated.
The format is "user_id\titem_id\trating".

Example: 
455	50	3.0
455	457	4.0
455	28	5.0
455	458	3.0

--------------------------------------------------------------------------
FILE: item-profiles1.csv
This file contains 3 columns ; seperated.
The format is "recipe_id;category;directions".

Example:
1939;Home  >  Recipes  >  Main Dish  >  Roasts;In a medium bowl, stir together the cranberry sauce, salad dressing, and onion. Place pork in a slow cooker, and cover with the sauce mixture.<br>Cover, and cook on High for 4 hours, or on Low for 8 hours. Pork is done when the internal temperature has reached 145 degrees F (63 degrees C).<br>

--------------------------------------------------------------------------
FILE: item-profile2.csv
This file contains the following columns ; seperated: "recipe_id;Name;Fiber (g);Sodium (g);Carbohydrates (g);Fat (g);Protein (g);Sugar (g);Saturated Fat (g);Size (g);Servings;Calories (kCal);Average Rating;Average Sentiment;Number of Ratings;Number of Bookmarks;Year of Publishing"

Example:
2622;Slow Cooker Tender and Yummy Round Steak;4.50;0.83;33.10;13.60;33.80;5.00;4.60;2599.35;6.0;393.00;4.32;1.79;81;2271;2000

--------------------------------------------------------------------------
FILE: item-profile3.csv
This file contains the following columns ; seperated: "recipe_id;Ingredient ID;Amount (g);Quantity;Ingredient"

Example:
1939;5045;448;1 (16 ounce) can;cranberry sauce

--------------------------------------------------------------------------
FILE: BMJ-data-all--b-new.csv
This file is the most complete of all. It's tab-separated and contains the following headers:
"URL	Name	Fiber (g)	Sodium (g)	Carbohydrates (g)	Fat (g)	Protein (g)	Sugar (g)	Saturated Fat (g)	Size (g)	Servings	Calories (kCal)	Average Rating	Average Sentiment	Number of Ratings	Number of Bookmarks	Year of Publishing"

Example line of data:
"http://allrecipes.com/recipe/erics-baked-chicken/detail.aspx	Eric's Baked Chicken	1.30	1.26	14.50	58.30	29.90	5.20	12.30	2324.84	8.0	720.00	4.00	1.20	5	89	2004"





