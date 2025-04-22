# 📊 Analysis of Top Trending YouTube Videos (Titles) Across Different Countries

## **Objective:**
The goal of this project is to analyze the titles of the top trending YouTube videos across different countries. We perform various text analyses to understand the dominant themes and topics, including:
- Word frequency analysis
- Country-based comparison of trending video topics

## **Summary of Findings:**

The analysis of trending video titles across South Korea (KR), Canada (CA), the United States (US), Germany (DE), India (IN), Japan (JP), France (FR), Great Britain (GB), Mexico (MX), and Russia (RU) reveals a fascinating snapshot of global online attention:

**Overarching Trends:**

* **Local Culture and Language Matter:** Trending content is heavily influenced by local languages, cultural icons (like "BTS" in France or specific sports teams), and current events within each country.
* **Personalities and Names Drive Views:** Across many regions (KR, US, IN, JP, MX), specific names of individuals, whether celebrities, public figures, or even show hosts, are prominent in trending titles.
* **Event-Driven Peaks:** Specific timeframes (months like February, March, April, November) and events (like "Birthday," "Festival," "Remembrance Day," elections) often correlate with trending video topics.
* **Diverse Content Consumption:** While some themes are universal (like "New" content or entertainment), the specific categories that dominate vary significantly by country, ranging from sports to religion, education, and specific reality TV shows.

**Country-Specific Highlights:**

* **South Korea (KR):** Strong focus on individual personalities ("Hongki," "Human," "Kim"), events, music performances ("Flying," "Performance"), and educational content ("Education," "Lecture").
* **Canada (CA):** Overwhelmingly dominated by local sports teams ("Toronto Raptors," "Maple Leafs"), with some interest in finance ("Bitcoin," "Stocks").
* **United States (US):** Driven by news and current events, particularly investigations and misconduct, along with specific personalities ("John," "Jeffrey") and topics like Amazon and a "Thunderbird" phenomenon.
* **Germany (DE):** Emphasis on positive themes ("New Day," "Inspiration"), national content ("German/Germany," "Bundesliga"), finance ("Bitcoin," "Ethereum"), and product reviews.
* **India (IN):** Strong interest in specific personalities ("Satish," "Kumar"), religious content ("Prayer," "Calvary Temple"), daily updates, and content in various regional languages.
* **Japan (JP):** Focus on serialized content ("Video," "Part," "Episode"), work-related themes, Japanese pop culture (anime, manga), and specific timeframes.
* **France (FR):** Dominated by episodic content and live streams, the popularity of BTS, children's content, and new releases.
* **Great Britain (GB):** Strong interest in wildlife (wolves), cycling, a specific topic/brand ("Cotic"), and sports (rugby).
* **Mexico (MX):** Massively influenced by the reality show "Exatlón," along with interest in Mexican football and romantic content.
* **Russia (RU):** Emphasis on educational/informative content ("New Course"), finance (Ruble/Dollar exchange), Russian news/politics, and various forms of entertainment and sports.

In essence, these word clouds illustrate that while video is a global medium, the content that captures attention is deeply rooted in local interests, current affairs, and cultural preferences. Each country presents a unique profile of trending topics, highlighting the diverse online video consumption habits across the world.

## **Dataset:**
We are using the *"Trending YouTube Video Statistics"* dataset, which includes information about video titles, descriptions, views, likes, and dislikes. The dataset is available in Kagglehub in both **JSON** and **Excel** formats. The available data is for the year of **2017** and **2018**.

## **Required Libraries:**
- `pandas`: For data manipulation
- `nltk`: For text cleaning and stopwords removal
- `wordcloud`: For visualizing the most frequent words in video titles
- `matplotlib`: For generating plots
- `re`: For text cleaning
- `sqlalchemy`: For database operations
- `pyodbc`: For connecting to ODBC databases.

---
