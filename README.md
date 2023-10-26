# Community Survey for Church Events

## Intro

This project was based on one of the annual projects I executed as an administrative assistant at a church near my local university. Every year, we ask new and current community members what kinds of events and groups they would like to see at our church. Here are the five main categories:

- Liturgy (Sunday and daily services, prayer services, choir practice, etc.)
- Education and Faith Development (weekly Bible studies, guest speakers, etc.)
- Community Life (weekly dinners, socials, study halls, etc.)
- Outreach (social media, publicity, campus activities, interfaith events)
- Social Justice (fundraisers, mission trips, etc.)

In this survey, we also asked people what methods of contact they prefer for news and announcements (email, social media, phone).

## Data Sources

Dataset for survey results were randomly generated using [Mockaroo](https://mockaroo.com/).

Here is the table schema: (insert pic)

## Tech Stack

Microsoft Excel (PowerQuery, PivotTables, PivotCharts)

## Data Cleaning

### Power Query

- Used "Pivot Column" function to replace nulls in preferred_method_contact column with "no answer"
- Selected event category columns ('liturgy', 'education_faith_devlp', 'social_justice', 'community_life', 'outreach') and used "Unpivot Only Selected Columns"
- Renamed new columns to "category" and "votes" 

## Key Insights and Recommendations
