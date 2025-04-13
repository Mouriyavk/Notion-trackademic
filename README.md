# Trackademic: Automated Student Progress Tracker

**Trackademic** is an automated platform that helps students track their progress across multiple academic subjects. Students log their progress directly in **Notion**, and Trackademic uses **OAuth authentication** to sync data, providing real-time updates on student performance. The platform features a dynamic leaderboard and individual progress tracking for each student.

---

## Features

- **Student Progress Logging via Notion**  
  Students log their task completions in Notion across various subjects.

- **Real-Time Sync with Notion**  
  Trackademic automatically syncs progress from Notion through secure OAuth authentication, eliminating the need for manual updates.

- **Dynamic Leaderboard**  
  View a leaderboard that ranks students based on their progress across subjects.

- **Subject-Specific Progress Insights**  
  Students can check their individual progress, including task completion percentages, streaks, and more.

- **Customizable Dashboard**  
  A user-friendly dashboard displays overall student performance in real time.

---

## How It Works

1. **Progress Logging in Notion**  
   Students manually log their completed tasks in Notion for each subject.
   
2. **OAuth Authentication**  
   Trackademic integrates with Notion via OAuth authentication, securely syncing student data without the need for manual input.
   
3. **Real-Time Data Sync**  
   The platform automatically fetches progress data from Notion, ensuring up-to-date progress tracking.

4. **Leaderboard & Progress Dashboard**  
   The frontend displays a leaderboard ranking students based on their progress. Students can also view detailed progress for each subject.

5. **Scalable & Secure**  
   Trackademic is designed to handle large datasets and thousands of students while ensuring privacy and secure data handling.

---

## Tech Stack

- **Backend**: Python (FastAPI) 
- **Frontend**: React (for dynamic dashboards)
- **Database**: PostgreSQL
- **Notion API**: OAuth authentication and data syncing

