# DSA-Search-Engine
Objective:To create a DSA search engine that finds the problem statement for a requested title
• Search engine requires a database which I scrapped from CodeChef,leetcode using BeautifulSoup,
Selenium.
• Scrapped problem statements, URLs, and titles of problems for recognizing during problem searched by the
user.
• Used TF-IDF vectorization which converts scrapped textual data into numerical data and stored in a file
then into. the database that can be used for comparing the text entered by a user
• Comparision did by cosine similarity between numerical data stored in the database to numerical data
converted
• Designed the front-end of the search engine using HTML, CSS, Javascript, and Express.JS, converted
thescrapped data into a vector, stored it in the MongoDB backend server.
