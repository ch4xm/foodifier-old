# Foodifier
Discord bot to notify of UCSC dining hall menu items

# Todo:

- Show nutritional facts + nutritional calculator
    - Add a database for nutrition facts (Whenever new item's calorie count is requested it will take the value and add it to database, shouldn't change)
- Auto select meal based on current time and schedule
    - Specified meal does not exist if first "recipe description" is cereal (itll still show the menu, even for crown on weekends)
- Add notify command
    - Args
        - food_item: string of food item to notify of 
- /blacklist command
    - location: dining hall location to not get notified from 