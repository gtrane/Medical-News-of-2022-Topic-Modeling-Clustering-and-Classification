# News-in-Medicine-Topic-Clustering

Utilized Jupyter Notebooks to scrape over 8,000 articles from Medscape, a medical news site for medical students, physicians, and other healthcare workers. These articles were scraped from March 2022 - March 2023. 

Used requests and BeautifulSoup to collect article information (body text, titles, author, company) from each saved HTML file. Following, manually classified sentence sentiment to then apply classification machine learning techniques. Finally, LDA topic modeling indentified 22 clearly defined topics on the past year's medical news, including COVID-19 information (vaccine and booster related topic, China's zero-tolerance policy related topic), mental health, abortion news, policies, and access, healthcare costs and finances, the monkeypox outbreak, and more. These topics were corroborated in our K-means clustering analysis. 
