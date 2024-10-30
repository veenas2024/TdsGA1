- This project analyzes GitHub users based in Chicago, focusing on their followers, repositories, and other attributes.
- The data was scraped using the GitHub API, targeting users with over 100 followers and their public repositories.
- The analysis uncovered interesting trends, including the influence of hireability on email sharing among developers.

## Data Scraping Explanation

To gather the data, I utilized the GitHub API's `/search/users` and `/users/{username}/repos` endpoints. The process involved authenticating with a personal access token, searching for users in Chicago with more than 100 followers, and then retrieving their public repositories. The data was cleaned and stored in CSV files for analysis.

## Interesting Fact

One of the most surprising findings was the correlation between the number of followers and the number of public repositories. While intuitively, one might assume that more repositories lead to more followers, the analysis revealed a more complex relationship.

## Recommendation for Developers

Developers should consider enhancing their profiles by sharing their email addresses, especially if they are open to being hired. The analysis indicated that hireable users tend to share their email addresses more frequently, which could facilitate networking and job opportunities.
