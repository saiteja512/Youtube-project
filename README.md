# 📈 YouTube Trending Video Analysis

This project analyzes the characteristics of trending YouTube videos in the US and uncovers patterns that influence video performance. The analysis was conducted using a combination of **Excel** for data preprocessing and **Tableau Public** for interactive visualizations.

---

## 🔍 Objective

To identify the key factors that make a video trend on YouTube, such as:
- Video category
- Publish time and day
- Title length and tag count
- Engagement metrics (views, likes, comments)

---

## 🛠️ Tools Used

- **Microsoft Excel** – Data cleaning, transformation, and feature creation  
- **JSON** – Mapping category IDs to readable names  
- **Tableau Public** – Visualization and dashboard building  

---

## 📁 Dataset

- 📌 Source: [Kaggle - YouTube Trending Video Dataset](https://www.kaggle.com/datasets/datasnaek/youtube-new)
- Country: United States  
- Includes: Video metadata, trending dates, engagement stats

---



## ⚙️ Feature Engineering

Additional fields created:
- `title_length` – Number of characters in the video title  
- `tag_count` – Number of tags per video  
- `publish_day` – Day of the week the video was published  
- `publish_hour` – Hour of the day the video was published  
- `category_name` – Mapped from `category_id` using YouTube API metadata

---

## 🎥 Top YouTube Categories by Average Views

| Rank | Category         | Performance |
|------|------------------|-------------|
| 1    | Music            | 🚀 Highest  |
| 2    | Entertainment    | High        |
| 3    | Film & Animation | High        |
| 4    | Comedy           | Moderate    |
| ...  | Travel & Events  | Low         |

> **Note**: Music far outperforms other categories in average view count.

---


## 📊 Dashboard Highlights (Built in Tableau)

- **Top Categories by Views**
- **Best Times to Publish**
- **Title Length vs Views**
- **Tags vs Engagement**
- **Likes vs Comments Correlation**


---

## 📄 Report

A 2-page PDF report with the project summary is available:  
📄 [YouTube_Trending_Analysis_Report.pdf]

---

## ✅ Conclusion

This project reveals the power of data storytelling in understanding content trends on platforms like YouTube. By combining structured analysis with visual insights, we can uncover meaningful strategies for content optimization and audience engagement.

---

## 👤 Author

**Saiteja**  
