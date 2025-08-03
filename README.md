# PowerBI_marketing_dashboard_edventuredesign
LinkedIn Metrics Dashboard for Edventure Design. Built in Power BI to track impressions, engagement, and visitor insights. Features hashtag analysis, trend visualization, and strategic growth recommendations for content optimization.
Edventure Design LinkedIn Metrics Dashboard — README

## 1️, Background & Overview
Objective:
 Build foundational LinkedIn analytics for Edventure Design, a new instructional design studio with minimal existing social media presence. The dashboard analyzes early performance data to establish content benchmarks, uncover growth levers, and recommend strategies to expand reach, engagement, and audience alignment.
Context:
As a newly established firm, Edventure Design lacked a strong digital presence and had minimal engagement on LinkedIn. The page had no historical benchmarks or baseline metrics, making it difficult to assess performance or plan growth. This project starts from scratch to build, analyze, and grow the studio’s visibility. It aims to define performance standards, validate what content resonates with the target audience, and guide future marketing decisions.

## 2️, Data Structure Overview
Key Tables in the Dashboard

| Table Name      | Description                              | Sample Fields                                      |
|-----------------|------------------------------------------|----------------------------------------------------|
| All Posts       | Content-level metrics by post            | Post Title, Post Date, Impressions, Engagement Rate|
| Metrics         | Daily platform metrics summary           | Impressions (Organic/Sponsored), Clicks, Reactions |
| Followers       | New and total followers by date/location | Date, Sponsored Followers, Total Followers         |
| VisitorMetrics  | Desktop/mobile views and visitors        | Date, Unique Visitors, Page Views                  |
| HashtagMetrics  | Hashtag breakdowns per post              | Hashtag, Post Title                                |
| Date            | Calendar table for filters/trends        | Date, Month, Weekday, Quarter                      |

📌 Relationships are managed using one-to-many or one-to-one joins, centered around the unique Date and Post Title fields. 

## 3, Executive Summaries
Content Engagement: 9 posts generated 1,782 total impressions and maintained an engagement rate >2.0%, exceeding B2B industry benchmarks by +38%.

Follower Growth: Achieved a +59% increase in followers (from 20 to 49), solely through organic reach—indicating strong message-market fit.

Audience Profile:
Top job functions: Education, Media, Communication
Industry alignment: Higher Education, EdTech
Seniority mix: Senior-level (37%), Entry-level (25%)

Page Visitor Behavior: 64 unique visitors, nearly half (45.31%) from mobile devices. Peak traffic directed to the Jobs and Overview pages—a strong signal of interest in Edventure’s brand and opportunities.

Posting Rhythm: Highest impressions occurred on Monday–Wednesday, while Friday posts earned higher engagement per impression.

## 4,Insights Deep Dive
1. Content Format & Performance
Article posts contributed 59.6% of total impressions, leading in search relevance and LinkedIn scoring
Carousel posts generated 33% of impressions, outperforming other formats in engagement duration and storytelling depth
Image-only posts underperformed (just 5.5% of impressions), signaling low visibility and CTR
Platform Algorithms: LinkedIn prioritizes dwell-time formats (articles/carousels), improving reach and credibility—especially in B2B audiences.

2. Post Timing Analysis
| Day     | Impressions ↑    | Engagement Rate ↑          |
|---------|------------------|----------------------------|
| Tuesday | Highest reach    | Competitive rate           |
| Friday  | Lower reach      | Highest engagement (4.5%)  |

Actionable Insight: Weekday posting cadence drives visibility; Friday is ideal for community-driven posts or thought pieces.

3. Visitor Behavior & Device Trends
Desktop visitors: 54.69%, Mobile visitors: 45.31%
Mobile-first optimization needed: carousel visuals currently in 16:6 ratio (desktop) → recommended shift to 12:6 ratio for improved readability and scroll behavior.

4. Follower Composition Strategy

| Attribute | Leading Segments              |
|-----------|-------------------------------|
| Function  | Education, Communication      |
| Industry  | Higher Education, EdTech      |
| Seniority | Senior, Entry-Level           |

=> Interpretation: The brand engages both decision-makers and early-career professionals—an ideal bridge for dual-purpose content: strategic insights + career support.

5. Geographic Reach
Highest activity in North America, light but promising impressions across Europe and Asia
Suggests foundational traction with global relevance potential

## 5, Strategic Marketing Recommendations
Content Distribution Focus
Anchor Posts on Peak Days
 → Publish on Monday–Wednesday to maximize impressions
 → Use Friday for behind-the-scenes, community posts to nurture engagement


Prioritize Format for Visibility and Engagement
 → Lead with carousel and article posts for performance advantage
 → Redesign visuals to 12:6 mobile-friendly dimensions to align with platform behavior


Strengthen Employer Brand for Entry-Level Segment
 → High traffic to Jobs page suggests interest from early-career professionals
 → Add carousel features like “Day in the Life,” team spotlights, onboarding journeys


Amplify with Trend-Focused Topics & Hashtags
 → Highest-performing hashtags include #AIinEducation, #TeachingWithAI, #ThoughtLeadership
 → Align messaging with edtech innovations to tap into LinkedIn’s discovery and search

Create Serialized Campaign Themes
 → Build branded series (e.g. “AI Teaching Tips Week”) to retain traffic and improve post-to-post navigation
 → Encourage repeat engagement with thematic cohesion

## 6, Tools & Techniques
| Tool     | Purpose                                      |
|----------|----------------------------------------------|
| Power BI | Data visualization and dashboard design      |
| Excel    | Data cleaning and preprocessing              |

## 7, Dashboard Features
Interactive visuals: Trend lines, KPIs, and filters
Custom visuals: Hashtag performance and visitor insights
Narrative callouts: Actionable insights embedded in visual reports

## 📸 Dashboard Previews

![Executive Summary](./assets/Screenshot-2025-08-03-182506.png)
![Content Performance](./assets/Screenshot-2025-08-03-182537.png)
![Followers](./assets/Screenshot-2025-08-03-182552.png)
![Visitors](./assets/Screenshot-2025-08-03-182610.png)

## 8, Contact & Credits
Created by Harmony Pham
Inspired by internship work at Edventure Design
LinkedIn: https://www.linkedin.com/in/harmony-pham-362193235/ | Portfolio:https://harmonypham.wixsite.com/hapham