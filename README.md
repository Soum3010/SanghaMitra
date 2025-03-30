# 🌟 SanghaMitra - A Friend of the Leet-Coding Community

**SanghaMitra** (संघमित्र), meaning *"a friend of the community"*, is a smart and socially-aware LeetCode extension that helps you learn, compete, and grow with your peers. It intelligently analyzes your coding patterns, compares them with your friends’, and recommends the most meaningful problems for you to solve next.

---

## 📌 Problem Statement

LeetCode users often face the following challenges:

1. ❓ **Uncertainty about what to solve next** after finishing popular problem lists.
2. 🧠 **Lack of insight into personal weak topics** and solving patterns.
3. 👥 **No way to track or compare progress with friends** in a meaningful way.
4. 🔁 **Repetitive or irrelevant problem suggestions** from existing tools.
5. 💤 **Low motivation** due to the solo nature of competitive coding prep.

**SanghaMitra** solves these by providing:
- Personalized recommendations based on topic and semantic gaps.
- Socially-driven insights by comparing your progress with friends.
- A hybrid recommendation engine powered by **Phi-2** (an open-source LLM).
- Friendly challenges and explainable suggestions to keep learning fun and focused.

---

## 🎯 Features & Use Cases

### 1. 🔍 Personalized Problem Recommendations
- Recommends new problems based on your weak areas and past performance.

### 2. 👥 Add & Track Friends
- Add friends by LeetCode username.
- View their progress, solved problems, and strengths.

### 3. ⚖️ Compare Profiles with Friends
- Analyze topic-wise gaps between you and your friends.
- Get recommendations based on what they’ve mastered that you haven’t.

### 4. ⚔️ Mutual Challenges
- Create friendly competitions on problems only one of you has solved.
- Track who solves them faster or with fewer attempts.

### 5. 💬 Explainable AI-Powered Suggestions
- Each recommended problem comes with a reason:
  - Topic you're weak in
  - Your friend already solved it
  - Similar to problems you've done before

### 6. 📈 Weekly Leaderboard & Insights
- Weekly recap of your and your friends' progress.
- Tag-wise comparison and difficulty-based scoring.

---

## 🧰 Tech Stack

- **Frontend**: JavaScript (Chrome Extension)
- **Backend**: Java + Python microservice for LLM + analysis
- **LLM**: [Phi-2 by Microsoft](https://huggingface.co/microsoft/phi-2)
- **Database**: Lightweight DB (SQLite or Supabase) + Vector DB (FAISS/Chroma)
- **Hosting**: Free platforms like Vercel, Render, or Railway

---


## ✨ Contribute

Have ideas or want to improve SanghaMitra? PRs and Issues are welcome!
