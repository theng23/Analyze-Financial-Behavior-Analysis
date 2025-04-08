# Discover-User-Behavior-From-Traffic-Channels - Financial and Stock company| Python, GoogleColab
## I. Introduction
- This topic aims to analyze and evaluate user behavioral indicators from many different sources on the website of Pinetree, a company in the finance and securities industry.
- Below is a summary of this topic. The full topic can be viewed here: [AnalyzeBehaviorofUser](https://colab.research.google.com/drive/1hoBLNEbMmeCC7Bn7T6aY1MfhFxybfR7z?usp=sharing)
## II. Dataset
This is a file database in this topic: **[Database](https://drive.google.com/drive/u/0/folders/10AzT_ChQJtBifj3tyD_RJ32yAMabFv7G)**

- Data week: <br>
    | Field Name | Data Type |
    |-------|-------|
    |Nth week|STRING|
    |Activer users|INTEGER|
    |Sessions|INTEGER|
    |Engaged sessions|INTEGER|
    |Event count|INTEGER|
    |Key events|INTEGER|
    |Engaged sessions per user|FLOAT|
    |Average engagement time per session|FLOAT|
- Event:
    | Field Name | Data Type |
    |-------|-------|
    |Event name|STRING|
    | Event count | INTEGER |
    |Sessions|INTEGER|
- Event Source:
    | Field Name | Data Type |
    |-------|-------|
    | Event name |STRING |
    |Session source / medium|STRING|
    | Event count | INTEGER|
    |Sessions|INTEGER|
- Source:
    | Field Name | Data Type |
    |-------|-------|
    |Session source / medium|STRING|
    |Active users|INTEGER|
    |Sessions|INTEGER|
    |Engaged sessions|INTEGER|
    |Average engagement time per session (s)|INTEGER|
    |Engaged sessions per user|FLOAT|
    |Event count|INTEGER| 
## III. Bussiness Question:

1. Evaluate traffic quality, sources and events: Use specific evaluation criteria to compare and provide detailed data tables about traffic sources, events and conversion rates from these sources.
2. Propose traffic growth strategy: Based on analysis of conversion rates and effectiveness of current traffic sources, we will recommend appropriate investment sources to both increase traffic volume and ensure conversion good rate.
3. Analyze user behavior fluctuations over time: Evaluate fluctuations in user behavior indicators and events week by week to identify the most important behaviors, from which to draw conclusions and lessons important.
4. Proposal to improve landing page: Compare Pinetree's landing page with main competitors in the industry (Shinhan Securities, VPS, SSI, XTB), propose necessary changes to improve user experience and good support more for Pinetree's marketing goals.

## IV. Data Visualization with Python
- Column chart for conversion rate (Conversion Rate) from different sources
![V1](https://github.com/user-attachments/assets/54aad7e3-2fca-4aa5-9d2e-fc94fc3dc2bf)

- Sources/Mediums with traffic greater than 1000
![v2](https://github.com/user-attachments/assets/1000449d-5def-480d-8b9c-01cd7d194a04)

- Sources/Medium with traffic less than 1000
![v3](https://github.com/user-attachments/assets/8de602c3-ed56-49ac-955c-0d2000c8978c)

![v4](https://github.com/user-attachments/assets/ffdbb7a6-ac7b-45d6-bd77-7c957d1bec07)

- Line chart comparion between Engaged Sessions and Key Events
![v5](https://github.com/user-attachments/assets/4aedc902-18c3-4b3d-a262-8c2282176430)

- Evaluate over week by engaged sessions per user, rate and average engagement time per sessions
![v6](https://github.com/user-attachments/assets/27dceaae-aff4-4f06-bf32-daac6363deb8)
- Horizontal bar chart for Event count over a week
![v7](https://github.com/user-attachments/assets/63061f0f-6fcf-4a88-9e70-f65a3b58a644)


- Corelation Matrix
![v8](https://github.com/user-attachments/assets/ab7c8d2d-56eb-453f-b241-57663c3390b1)

- Line and Bar chart of starting a page view

![v10](https://github.com/user-attachments/assets/5bf31290-bddf-4f9a-b03c-7ac68128435c)

- Bar chart of Exploratory Behavior of Event


![v11](https://github.com/user-attachments/assets/9adb27ba-86d6-47c9-bf82-57356ccc5bbb)


- Chart of Conversion Behavior of Event

![v12](https://github.com/user-attachments/assets/4b75fa2b-9c50-46f7-84eb-8c364d0cfc46)

## V. Insight
- Question 1:
    - Google / Organic is the overall most effective source with a large number of traffic, high number of sessions, active users, and high number of events. This source is a top choice for investing in high-quality traffic.
    - finance.vietstock.vn / referral has the highest conversion rate, indicating that this source is very effective in converting users. However, it has a lower traffic volume than Google / Organic.
    - baidu / organic and pino.pinex.vn / referral do not perform well in terms of sessions, active users, and conversion rates. Consider reducing investment in these sources if the goal is to optimize conversion efficiency.
- Question 2:
    - Traffic Growth (Sessions) and Conversion Rate (Conversion Rate):
        - Google / Organic has the highest total number of sessions (82,627) and conversion rate (44.0%). This is a good combination of high traffic and high conversion rate, which is suitable for investment if we want both traffic and conversion growth.
        - bing / organic and coccoc.com / referral have high conversion rate (46.0%) but lower traffic than Google / Organic. They can be good choices if we prioritize higher conversion rate and are willing to accept lower traffic.
        - chat.zalo.me / referral and oa.zalo.me / referral have very high conversion rate (51.0% and 74.0%) but quite low traffic. This can be a potential source if the main goal is to optimize conversion rate and we do not need a lot of traffic.
      - Comparison based on conversion rate and number of active users:
          - Google / Organic not only has the largest traffic volume, but also the highest number of active users (46,634) and high conversion rate (44.0%). This shows that it is a worthy source for both traffic growth and conversion rate.
          - lm.facebook.com / referral and copilot.microsoft.com / referral have very high conversion rates (67.0% and 67.0%) but very low traffic. They can be options if conversion rate is a top priority, although we need to evaluate further the scalability and traffic potential of these sources.
- Question 3:
    - Effectiveness of Traffic Sources
        - Google / Organic is the most effective traffic source, with high traffic volume, high conversion rate and high number of events. Investing in this source is the top choice for traffic growth while maintaining a high conversion rate.
        - Google / Organic is the most effective traffic source, with high traffic volume, high conversion rate and high number of events. Investing in this source is the top choice for traffic growth while maintaining a high conversion rate.
        - baidu / organic and pino.pinex.vn / referral have extremely low traffic volume and are not effective in terms of interaction and conversion. It is necessary to consider reducing investment costs in this source as well as redefining the strategy of operating on the above source.
    - OnSite Behavior Index Fluctuations
        -  The number of users and sessions from Week 1 to Week 9 shows a sharp decrease in user interest or activity. This could also be due to a marketing campaign or activity across sources.
        -  The sharp drop in Week 9 for most metrics (active users, sessions, engaged sessions, event count) could reflect the end of a major campaign or a change in how the platform operates.
    - Correlation Analysis
        -  The correlation between active users and sessions. The number of key events shows that an increase in users leads to an increase in sessions and events.
        -  The strong correlation between key events and interactive sessions shows that interactive events tend to lead to more interactive sessions.
- Question 4:
    -  Source/Media Dominance
        -  Google/Organic is the main source/medium with very high event counts across multiple event types, including Loaded, page_view, and session_start. This suggests that traffic from Google organic search has a major impact on site events.
        -  page_view and session_start are the most common events, indicating that users frequently visit the site and initiate sessions.
        -  Loaded also appears frequently, which may indicate that users are interacting with loaded elements on the site
        -  Differences by Source/Medium*
        -  Sources such as coccoc.com / referral and bing / organic have lower event counts but still play an important role in attracting users.
    -  Other Events Group
        -  Less common events such as video_progress, form_start, form_submit, and events that are not clearly categorized (such as Others) may require further analysis to better understand their role and why they are less common
## VI. Recommendations
- Google / Organic is the overall most effective source with a large number of traffic, high number of sessions, active users, and high number of events. This source is a top choice for investing in high-quality traffic.
- finance.vietstock.vn / referral has the highest conversion rate, indicating that this source is very effective in converting users. However, it has a lower traffic volume than Google / Organic.
- baidu / organic and pino.pinex.vn / referral do not perform well in terms of sessions, active users, and conversion rates. Consider reducing investment in these sources if the goal is to optimize conversion efficiency.
- Google / Organic is the best choice because it combines both high traffic and good conversion rates. Investing in this source can help us achieve our goal of increasing traffic while maintaining high conversion rates.
- If we are looking for additional sources to optimize conversion rates without too much traffic, sources such as chat.zalo.me / referral, oa.zalo.me / referral, and finance.vietstock.vn / referral can be potential options.
- Increase engagement: Look at low-return events and find ways to improve them. For example, optimizing buttons or forms can help increase form_start and form_sumbit rates
- Examine specific factors that influence high-return and low-return events to better understand user behavior
- SEO and SEM Optimization: Improve SEO strategies for Google Organic and optimize SEM campaigns to improve results from Google CPC.
- Create Compelling Content and CTAs: Enhance content and CTA elements to encourage more actions from users.
- Referral Strategy Testing: Evaluate and optimize other referral sources to increase effectiveness from less popular sources.
- Continuous Monitoring and Evaluation: Continuously monitor the effectiveness of campaigns and events to adjust strategies in time.
