## Articles Headlines App
Create a proof of concept for an App that displays trend articles and allow the user to save news for reading later.

## Requirements
- App to be built with a tab bar main navigation containing 3 tabs: **Headlines, Sources, Saved.**
- **Headlines**: screen to display a list of headlines based on the user-selected sources, each row should display (title, description, author and thumbnail picture)
  - Tapping on a row should open the headline URL to read the full article within the app.
  - When viewing an article the user should be able to save it for reading later.
- **Sources**: screen to display the list of available sources for articles, the user should be able to select multiple sources and the selection should persist user sessions.
- **Saves**: screen to display a list of previously saved headlines, tapping a row should open the article for reading, same way as the Headlines screen.
  - User should be able to delete previously saved articles
  - Integrate the app with [https://newsapi.org/](https://newsapi.org/) API to fetch data (register to get your API Key)  

## Technologies and Methodologies Expectations
- Highly modular
- Use of modern Swift syntax
- URLSession
- Autolayout
- Light weight, smart code
- Good use of MVC, MVVM preferable
- Reuse of components
- RxSwift would be a bonus

## Points of consideration
- Keep code simple and concise (e.g. avoid unnecessary complexity/over engineering)
- It is not expected to have a fancy user interface, well layout structure will be the key element to be evaluated.
- Pagination is not required, API will return only the latest 10 articles per source
- The API doesn’t provide a way to fetch articles from multiple sources in one request, you will have to wrap multiple requests based on the user’s selected sources e.g.:
  - If the user has selected 3 sources you will have to wrap 3 requests and display the 30 results back in the headlines screen
- Documentation for the API [https://newsapi.org/docs](https://newsapi.org/docs)
- Filter sources to be only for English language

## Allocated time
- Please provide submission no more than 3 days after received.
- Submissions will only be accepted via GitHub.