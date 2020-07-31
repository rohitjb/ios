## Articles Headlines App
Create a proof of concept for an App that displays trend articles and allow the user to save news for reading later.

## Requirements
- App to be built with a tab bar main navigation containing 3 tabs: **Headlines, Sources, Saved.**
- **Headlines**: screen to display a list of headlines based on the user-selected sources, each row should display (title, description, author and thumbnail picture)
  - Tapping on a row should open the headline URL to read the full article within the app.
  - When viewing an article the user should be able to save it for reading later.
- **Sources**: screen to display the list of available sources for articles, the user should be able to select multiple sources and the selection should persist between application launches.
- **Saves**: screen to display a list of previously saved headlines, tapping a row should open the article for reading, same way as the Headlines screen.
  - User should be able to delete previously saved articles
  - Integrate the app with [https://newsapi.org/](https://newsapi.org/) API to fetch data (register to get your API Key)  

- Documentation for the API [https://newsapi.org/docs](https://newsapi.org/docs)

## Expected to be used
- URLSession
- Autolayout
- UIKit
- RxSwift would be a bonus

## Key points under evaluation
- Highly modular
- Use of modern Swift syntax
- Good use of MVC, MVVM preferable
- Reuse of components
- Simple and concise code
- Simple and concise project structure
- Clarity over brevity
- It is expected from the App to offer a good UX
- Pagination is not required, you can return a fixed number of records for the headlines
- Filter sources to be only for English language

## Allocated time
- Please provide submission no more than 3 days after received.
- Submissions will only be accepted via GitHub.