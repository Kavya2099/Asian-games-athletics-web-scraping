# Websraping project on Asian games
Asian games athletics web scraping using python

<p align="center">
<img src="https://cdn.dribbble.com/users/406059/screenshots/2885391/hurdles_run.gif"  width="300" height="300" />
</p>

This dataset contains two files.

**Atheletics_record** - Contains the list of winning countries in athletics in the Asian Games between 1951-2018

**Country_code** - Contains the country code of the countries( old and new codes)

**Source**

- https://en.wikipedia.org/wiki/List_of_Asian_Games_medalists_in_athletics
- https://en.wikipedia.org/wiki/List_of_IOC_country_codes

## Steps
- Getting the list of countries who bagged medals in atletics from the year 1951-2022
- We'll be scarping out year, country, category, gender and medals--> gold, silver, bronze deatils from wikipedia
- We'll be using Beautiful Soup to parse and extract information
- Getting the columns category and athletics sports type using find_all() html tags
- Getting the wikipedia table records for year gold, silver and bronze columns
- Making few transformations in year and gold, silver and bronze columns to extract only the year and country code
- Creating another dataset for country code along with full countries names
- The reason for adding this dataset is beacause, we could see some countries have use different country codes for the specific time period.
- This dataset will help us to identify the old and new country codes in that cases.

# Columns in each dataset
## Atheletics_record 

- Year- the year when the Asian games held
- Gold- Countries that won the gold medal
- Silver- Countries that won the silver medal
- Bronze- Countries that won the bronze medal
- Category- Gender category (male/female/mixed)
- Sports- Types of athletics

## Country_code

- Code - 3 letter country code
- National Olympic Committee - Full name of country
- Other codes used - Other country code that has been used earlier


Dataset is published in Kaggle: https://www.kaggle.com/datasets/kavya2099/asian-games-athletics-winning-countries19512018

Medium Blog: https://medium.com/@Kavya2099/web-scraping-on-asian-games-data-using-beautiful-soup-7a6f776a3edc
