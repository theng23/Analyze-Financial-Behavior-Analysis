# Discover-User-Behavior-From-Traffic-Channels
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


