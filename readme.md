# Description

- **App Name:** Personalized News App
- **Description:** An app to get news based on user preference and interest.
- **Github URL:**  
- **Deployed Website:** 

# Problem Being Solved and Target Market
To create a news outlet to let usres get news articles based on their interest and preferences without having to filter out news manually.

## List of React Router Routes

| Route Name | Endpoint | Method | Description | 
|------------|----------|--------|-------------|
| Landing | / | GET | Renders all news article on a page|
| NewsShow | /news/:id | GET | Renders a news article |
| NewsCategoryShow | /news/:category | GET | Renders multiple news article based on category|
| NewsDateShow | /news/:date | GET | Renders multiple news article based on date|
| NewsCreate | /news/create | DELETE | Creates a news article |
| NewsDelete | /news/delete/:id | DELETE | Deletes a session |
| NewsEdit | /news/update/:id | PUT | Updates a news article|
| NewsFavourites | /news/favourites | GET | Shows all liked news article with option to update articles from the list |
| NewsFavouritesDelete | /news/favorites/delete/:id | DELETE | Deletes articles from the list |



## React Architecture (Expected Tree of React Components)
![React Components Architecture](./images/react_component_architecture.png)


## Mockups
Index page
![Desktop Design Mockup](./images/index_page.png)
Show page
![Desktop Design Mockup](./images/show_page.png)
Update showpage
![Desktop Design Mockup](./images/update_page.png)
Create page
![Desktop Design Mockup](./images/create_page.png)