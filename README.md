# Medical News of 2022: identifying article sentiment and unique news topics through topic modeling, k-means clustering, and classification

### Summary
I worked in a team utilizing Jupyter Notebooks to web scrape 8,500 articles from Medscape, a medical news site for medical students, physicians, and other healthcare workers and indentified key topics and events from the period March 2022 - March 2023. I executed API requests and BeautifulSoup to collect article information (body of text, title, author, company) from each scraped HTML file. My group manually classified sentence sentiment and applied several classification techniques to predict article sentiment. 

Finally, I implimented LDA topic modeling using gensim libraries and identified 22 clearly defined topics of medical news, ranging from COVID-19, cardiovascular health, mental health, abortion policies and access, healthcare costs and finances, the monkeypox outbreak, and more. These topics were also supported in a k-means clustering analysis. 

<img width="1105" alt="Screenshot 2023-05-04 at 10 34 12 AM" src="https://user-images.githubusercontent.com/116750192/236256859-80f07d18-ea0d-44e7-bc88-929272ddcac9.png">

### Results
The following screenshot details the results from my LDA topic modeling. I used gensim libraries and visualized 26 topics since this accounted for the highest coherence value achieved. To see this in more detail, you can refer to '4_GensimLDA.html'.

<img width="673" alt="Screenshot 2023-08-11 at 1 50 00 PM" src="https://github.com/gtrane/Medical-News-of-2022-Topic-Modeling-Clustering-and-Classification/assets/116750192/b3334159-06f7-4683-b1cb-cae88f9abbee">
<img width="1210" alt="Screenshot 2023-08-11 at 1 48 34 PM" src="https://github.com/gtrane/Medical-News-of-2022-Topic-Modeling-Clustering-and-Classification/assets/116750192/f0021fd7-61a3-4dfd-a4f2-ffd731722da1">
<img width="934" alt="Screenshot 2023-08-11 at 1 50 48 PM" src="https://github.com/gtrane/Medical-News-of-2022-Topic-Modeling-Clustering-and-Classification/assets/116750192/70585816-97b2-465e-910f-c2983816811c">
