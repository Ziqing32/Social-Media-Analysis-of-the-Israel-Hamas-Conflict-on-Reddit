# Social-Media-Analysis-of-the-Israel-Hamas-Conflict-on-Reddit

## Overview 

This project explores Reddit discussions surrounding the Israel-Palestine conflict between 2023 and 2025. It focuses on analyzing public sentiment trends and thematic shifts across time using Reddit comments and metadata.


---

## Dataset Description

The dataset `reddit_opinion_PSE_ISR.csv` (≈3.7GB) includes 2.5 million+ Reddit comments. Each row represents a single comment enriched with post-level and user-level metadata.



### Key Fields

| Column Name             | Description (English)                                         
|-------------------------|----------------------------------------------------------------|
| `comment_id`            | Unique identifier of the comment                               | 
| `score`                 | Net upvotes (upvotes - downvotes)                              |
| `self_text`             | Full text of the comment                                       | 
| `subreddit`             | Subreddit where the comment was posted                         | 
| `created_time`          | Timestamp of the comment                                       | 
| `post_id`               | Associated post ID                                             | 
| `post_title`            | Title of the post                                              | 
| `post_self_text`        | Body text of the post                                          |
| `post_created_time`     | Time the post was submitted                                    |
| `post_score`            | Post score (aggregated upvotes)                                | 
| `post_upvote_ratio`     | Post upvote ratio                                              |
| `controversiality`      | 1 if the comment is controversial, else 0                      |
| `ups`, `downs`          | Raw upvotes and downvotes                                      |
| `user_total_karma`      | Total karma of the comment author                              |
| `user_comment_karma`    | Karma earned from comments                                     |
| `user_link_karma`       | Karma earned from links/posts                                  |
| `user_awarder_karma`    | Karma earned from giving awards                                |
| `user_awardee_karma`    | Karma earned from receiving awards                             |
| `user_is_verified`      | Whether the user is email-verified                             |
| `user_account_created_time` | User registration timestamp                                | 

---

## Project Goals

### 1. Sentiment Dynamics Tracking 
- Analyze comment sentiment trends using `self_text` and `created_time`
- Use `score` and `controversiality` to gauge sentiment intensity and polarization


### 2. Topic Evolution Analysis
- Apply NLP (e.g. LDA topic modeling) to `self_text` and `created_time`
- Track how topics shift around key dates (e.g. 2023-10-07 Gaza attack)

---

## Methods & Tools 

- **Pandas** 
- **NLTK, Stopwords** 
- **VADER** 
- **Gensim (LDA)**
- **Matplotlib / Seaborn / Plotly** 

---

## Time Scope 

- **Data coverage:** From *2023-01-01* to *2025-03-31*
- **Analysis range:** Filtered to focus on *2023-01 to 2024-07* for event-centered study


---

## Sample Questions

- What are the main topics discussed by Reddit users during the Israel-Hamas war? How do these topics evolve across different time periods?
- What are the emotional trends in Reddit discussions about the conflict, and how do these expressions of sentiment vary across different subreddits?

---

## License & Usage

This dataset is for **educational and research purposes only**, based on publicly available Reddit content. No personally identifiable information is included.


---

## Author

- **Project Lead**: *[ZHAO ZIQING / CHEN ZIQING]*  
- **Institution**: *[Nanyang Technological University WKWSCI]*  
- **Last Updated**: April 21, 2025

---

