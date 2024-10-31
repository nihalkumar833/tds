**Key Insights**
* **Data Collection**: Using the GitHub API, I gathered profiles of GitHub users in Paris with over 200 followers, along with data on their repositories.
* **Interesting Finding**: The most popular repositories among Paris developers are in JavaScript and Python, indicating a high demand for these languages.
* **Actionable Tip**: Paris-based developers can increase engagement by focusing on popular languages like JavaScript and Python and enabling features like wikis in their repos.

**Project Files**
* **users (1).csv**: Contains a list of Paris-based GitHub users with over 200 followers, including details like username, company, and bio.
* **repositories.csv**: Holds data on these users’ public repositories (up to 500 per user), including stars, language, and license information.
* **README.md**: This file, providing an overview of the project.

**How I Collected the Data**
* **Getting the Data**: I used the GitHub API to find users in Paris with more than 200 followers.
* **Cleaning It Up**: I standardized company names by removing extra spaces, stripping any leading @, and making names uppercase.
* **Repositories**: I collected each user’s most recent repositories, noting details like stars, watchers, and languages used.
