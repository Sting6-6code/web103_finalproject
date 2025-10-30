# CodeTrack

CodePath WEB103 Final Project

Designed and developed by: Suraj, [Partner Name]

🔗 Link to deployed app: [Coming soon]

## About

### Description and Purpose

CodeTrack is a comprehensive interview preparation and progress tracking platform designed specifically for software engineers navigating the technical interview process. The app helps users organize their coding practice, track problem-solving progress, manage job applications, and strategically prepare for interviews at target companies.

At its core, CodeTrack solves the common problem of scattered interview prep - where coding problems are tracked in spreadsheets, applications live in email folders, and study plans exist only in your head. Instead, CodeTrack centralizes everything: you can browse a curated library of coding problems tagged by company and topic, track which ones you've attempted, maintain detailed notes on your solutions, and monitor your overall progress through intuitive dashboards and statistics.

The platform bridges the gap between isolated practice and strategic preparation by connecting problems to real companies, allowing users to focus their efforts on questions frequently asked by their target employers. Whether you're grinding LeetCode daily or preparing for a specific interview next week, CodeTrack keeps you organized, focused, and motivated throughout your job search journey.

### Inspiration

This project was born from personal frustration during the job search process. As graduate students actively interviewing for software engineering positions, we found ourselves juggling multiple tabs, spreadsheets, and notes apps just to keep track of what we'd practiced and where we'd applied. We'd forget which problems we struggled with, lose notes on clever solutions, and have no clear sense of our progress over time.

We realized that while there are plenty of platforms for practicing coding problems (LeetCode, HackerRank, etc.), there wasn't a good tool that combined practice tracking with application management and strategic interview prep. We wanted something that would tell us "You've attempted 45 problems this month, you're strong in arrays but need work on dynamic programming, and here are 10 problems frequently asked by the 3 companies you're interviewing with next week."

CodeTrack is the tool we wish we had from day one of our job search - a single source of truth that makes interview prep less chaotic and more strategic. By building this, we're not only solving our own problem but creating something that can help thousands of other developers navigate the challenging interview process more effectively.

## Tech Stack

- **Frontend:** React, React Router, CSS3
- **Backend:** Node.js, Express.js
- **Database:** PostgreSQL
- **Deployment:** Render

## Features

### ✅ Problem Library with CRUD Operations

Users can view a comprehensive library of coding problems with full CRUD functionality. Each problem includes title, difficulty level (Easy/Medium/Hard), problem description, and tags. Users can add new problems they encounter from various sources, edit existing problem details to keep information current, and remove problems from their library. The library serves as the central hub for all coding practice material.

[gif goes here]

### ✅ Problem Attempt Tracker

Track every attempt at solving a coding problem with detailed information including attempt date, time spent, solution approach, code snippets, notes on what worked or didn't work, and status (Solved, Attempted, Need Review). Users can view their complete attempt history for each problem and see their improvement trajectory over time. This feature helps identify patterns in problem-solving approaches and areas needing more practice.

[gif goes here]

### ✅ Smart Filter and Sort System ⭐ (Custom Feature)

Advanced filtering and sorting capabilities allow users to find problems based on multiple criteria: difficulty level (Easy/Medium/Hard), topic tags (Arrays, Dynamic Programming, Trees, Graphs, etc.), companies that frequently ask them, and completion status. Multiple filters can be combined simultaneously, and results update in real-time without page navigation. Users can also sort by difficulty, recent attempts, or success rate to customize their practice sessions.

[gif goes here]

### ✅ Company-Problem Association

Link coding problems to companies that frequently ask them in interviews through a many-to-many relationship. This strategic feature helps users prepare efficiently by focusing on problems relevant to their target employers. Users can view all problems associated with a specific company (e.g., "Show me all Google problems") and see which companies ask each problem. The system tracks frequency data to highlight the most commonly asked questions.

[gif goes here]

### ✅ Topic-Based Organization

Problems are tagged with relevant topics (Arrays, Hash Tables, Dynamic Programming, Trees, Graphs, System Design, etc.) using a many-to-many relationship. This allows users to identify knowledge gaps and focus their practice on specific algorithm types or data structures. The join table includes additional metadata like difficulty distribution per topic, helping users understand which areas are their strengths and weaknesses.

[gif goes here]

### ✅ Job Application Tracker

Manage the entire job application pipeline in one centralized location. Track companies you've applied to, current interview stage (Applied, Phone Screen, Technical Interview, Onsite, Offer, Rejected), upcoming interview dates, recruiter contacts, and detailed notes about each interaction. View applications in a kanban-style board organized by status, helping you stay on top of your job search and prioritize interview preparation based on upcoming deadlines.

[gif goes here]

### ✅ Auto-Generated Study Plans ⭐ (Custom Feature)

When users specify target companies or roles, the system automatically generates personalized study plans by intelligently selecting relevant problems based on company interview patterns, topic frequency, and the user's weak areas identified from past attempts. New users receive a starter set of 20-30 fundamental problems covering essential data structures and algorithms to begin their journey. Study plans adapt over time based on user performance and upcoming interview schedules.

[gif goes here]

### ✅ Progress Dashboard

Comprehensive visual dashboard displaying key metrics and insights: total problems attempted, success rate broken down by difficulty level, topic distribution showing strengths and gaps, calendar heatmap of recent activity, current streak tracking for motivation, and weekly/monthly progress charts. The dashboard provides an at-a-glance view of preparation progress and helps users stay motivated by visualizing their improvement over time.

[gif goes here]

### ✅ Problem Detail Pages with Dynamic Routing

Each problem has a dedicated detail page accessed via dynamic routes (e.g., `/problems/123`) created with React Router. These pages display comprehensive information including the full problem statement, difficulty and topic tags, list of companies that ask it, timeline of all user attempts with notes, quick actions for recording new attempts, and links to related problems. Navigation between problem list and detail views is seamless with proper URL management.

[gif goes here]

### ✅ Database Reset Functionality

Administrative feature to reset the database to its default state, restoring the original curated problem library with pre-loaded companies and topics while clearing all user-specific data (attempts, applications, custom problems). This feature is essential for testing, demonstrations, and allowing users to start fresh if needed. Includes confirmation dialogs to prevent accidental data loss.

[gif goes here]

## Installation Instructions

[Instructions will be added in Milestone 3]
```bash
# Clone the repository
git clone [repository-url]
cd WEB103_FINALPROJECT

# Install dependencies for client
cd client
npm install

# Install dependencies for server
cd ../server
npm install

# Set up PostgreSQL database
# Configure environment variables
# Run database migrations

# Start the development servers
# Client: npm run dev (in client directory)
# Server: npm start (in server directory)
```

## License

Copyright [2025] [Suraj, Siting]

Licensed under the Apache License, Version 2.0 (the "License"); you may not use this file except in compliance with the License. You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software distributed under the License is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the License for the specific language governing permissions and limitations under the License.