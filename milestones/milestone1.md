# Milestone 1

This document should be completed and submitted during **Unit 5** of this course. You **must** check off all completed tasks in this document in order to receive credit for your work.

## Checklist

This unit, be sure to complete all tasks listed below. To complete a task, place an `x` between the brackets.

- [x] Read and understand all required features
  - [x] Understand you **must** implement **all** baseline features and **two** custom features
- [x] In `readme.md`: update app name
- [x] In `readme.md`: add all group members' names
- [x] In `readme.md`: complete **Description and Purpose** section
- [x] In `readme.md`: complete **Inspiration** section
- [x] In `readme.md`: list all features you intend to include in your app (at least 6 required, but you can add more if you'd like)
- [x] In `planning/user_stories.md`: add all user stories
- [x] In `planning/user_stories.md`: add user story titles
- [x] In `planning/user_stories.md`: add user role(s)
- [x] In this document, complete the **Reflection** section below

## Reflection

### 1. What went well during this unit?

The ideation and planning phase went really well for our team. We quickly aligned on CodeTrack because it solves a genuine problem we're both experiencing during our job search - the chaos of scattered interview prep materials and lack of visibility into our progress. The user story writing process was particularly valuable because it forced us to think from the perspective of someone actually using the app, rather than jumping straight into technical implementation details.

We also appreciated how the natural database relationships emerged organically from the user stories. The many-to-many relationships between problems-topics and problems-companies made immediate sense, and we didn't have to force any relationships just to meet requirements. Breaking down features into the smallest meaningful units helped us realize the scope was manageable within the project timeline.

### 2. What were some challenges your group faced in this unit?

Our main challenge was scoping appropriately and resisting feature creep. Initially, we wanted to add features like peer-to-peer problem sharing, discussion forums for each problem, video solution uploads, mock interview scheduling, and resume building tools. We had to have honest conversations about what was achievable in the given timeframe and what would truly deliver the core value proposition.

Another challenge was deciding whether to include the job application tracker or keep CodeTrack purely focused on coding practice. We debated this extensively because it felt like adding a second app within the app. Ultimately, we decided that connecting interview prep to actual applications makes the tool significantly more valuable and strategic, rather than just being another problem tracker. The integration is what makes it unique.

We also found it tricky to write user stories at the right level of granularity - some were too broad ("I want to prepare for interviews") and others too narrow and technical ("I want a JOIN query between problems and topics"). Finding that sweet spot took several iterations.

### 3. What additional support will you need in upcoming units as you continue to work on your final project?

We'll need guidance on efficiently implementing the filtering system since it involves querying across multiple related tables (problems, topics, companies, attempts) simultaneously. We're concerned about query performance and want to make sure we're using PostgreSQL best practices for these kinds of complex queries with multiple JOINs.

We're also curious about the best approach for the auto-generated study plans feature. Should this be algorithm-based on the backend (analyzing user weak spots and company patterns), or more of a curated template approach where we pre-define plans? We'd appreciate seeing examples or discussing the trade-offs.

Finally, we'd benefit from examples of effective data visualization for the progress dashboard. Neither of us has extensive experience with charting libraries in React (like Recharts or Chart.js), so guidance on which library to choose and how to integrate it smoothly would be helpful. We want the dashboard to be visually compelling without spending too much time on custom visualizations.