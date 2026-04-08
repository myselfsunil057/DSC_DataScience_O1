# 📊 Dataset Documentation – Instagram Influencer Analysis

---

## 🧠 Dataset Overview
This dataset contains Instagram influencer performance metrics used to evaluate influencer effectiveness for brand marketing campaigns.

It enables analysis of:
- Audience reach
- Engagement behavior
- Content activity
- Geographic distribution
- Influence strength

---

## 📁 Dataset Structure

| Column | Description |
|--------|-------------|
| rank | Influencer ranking |
| channel_info | Instagram username |
| influence_score | Platform-based influence rating |
| posts | Total number of posts |
| followers | Total follower count |
| avg_likes | Average likes per post |
| 60_day_eng_rate | Engagement rate over last 60 days |
| new_post_avg_like | Average likes on new posts |
| total_likes | Total likes received |
| country | Influencer location |

---

## 🧹 Data Processing Steps

- Converted follower values (M/K/B) into numeric format
- Standardized engagement rate into decimal format
- Cleaned missing and inconsistent country values
- Ensured numeric consistency across all metrics

---

## 📊 Key Metrics Derived

- Engagement Efficiency = avg_likes / followers
- Audience Reach = SUM(followers)
- Content Activity = SUM(posts)
- Engagement Performance = avg(60_day_eng_rate)

---

## ⚠️ Data Limitations

- Missing country values (~60 records unknown)
- Engagement varies across platforms and time periods
- Dataset represents snapshot analysis, not real-time data

---

## 🎯 Use Case

This dataset is suitable for:
- Influencer marketing analysis
- Brand collaboration strategy
- Social media performance benchmarking
- Business intelligence dashboards

---

## 🚀 Outcome

Transforms raw Instagram data into actionable marketing intelligence for influencer selection and campaign optimization.
