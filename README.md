# TDS-Project-1

## Explanation of Data Scraping Process
The data was scraped using the GitHub API through the Octokit library in Node.js, with authentication handled by dotenv.
fetch_users.js gathered user data by searching for developers in Bangalore with more than 100 followers.
fetch_repo.js fetched repositories for each user, storing data like stars, watchers, language, and license in CSV files.
