# TDS-Project-1

## Explanation of Data Scraping Process
The data was scraped using the GitHub API through the Octokit library in Node.js, with authentication handled by dotenv.
fetch_users.js gathered user data by searching for developers in Bangalore with more than 100 followers.
fetch_repo.js fetched repositories for each user, storing data like stars, watchers, language, and license in CSV files.

## Most interesting and surprising fact
Python, though highly popular globally and after being such a easy language, wasn't the top language for users in Bangalore even who joined after 2020—JavaScript took the lead. This could indicate a regional preference for web development skills among newer developers.

## Recommendation for developers
Focus on building JavaScript skills if you’re a developer in Bangalore, especially if you're newer to the field. With its high popularity, especially among recent GitHub users, proficiency in JavaScript could increase job opportunities and collaboration potential in the local tech community.


### Few additional recommendations:
#### Focus on Star Quality:
Since repositories with high stars are more visible, developers could work on polishing their top projects. Adding thorough documentation, useful features, and eye-catching READMEs can increase star count.

#### Leverage Popular Languages: 
If you observe certain languages (like JavaScript or Python) getting more stars per repository, consider creating high-quality projects in these languages to attract more attention and followers.

#### Enable Wiki and Projects: 
Repositories with active wikis and project boards may attract more collaborators. Make these features accessible to showcase project planning and documentation.

#### Choose the Right License: 
If you identified the most popular licenses, using one of them might encourage contributions and make your code more shareable.
