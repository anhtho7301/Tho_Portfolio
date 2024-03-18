# Bellabeat Case Study: How Can a Wellness Technology Company Play It Smart?
By Tho Tran

## Introduction
Urška Sršen and Sando Mur founded Bellabeat, a high-tech company that manufactures health-focused smart products. Sršen used her background as an artist to develop beautifully designed technology that informs and inspires women around the world. Since it was founded in 2013, Bellabeat has grown rapidly and quickly positioned itself as a tech-driven wellness company for women. 

Bellabeat is a successful small company, but they have the potential to become a larger player in the global smart device market. Urška Sršen, cofounder and Chief Creative Officer of Bellabeat, believes that analyzing smart device fitness data could help unlock new growth opportunities for the company. I have been asked to focus on one of Bellabeat’s products and analyze smart device data to gain insight into how consumers are using their smart devices. The insights I discover will then help guide marketing strategy for the company. In this case study, I will present my analysis to the Bellabeat executive team along with my high-level recommendations for Bellabeat’s marketing strategy. 

Bellabeat has several products such as leaf, application, time, spring, etc. For this analysis, we will focus on the Bellabeat app. The Bellabeat app provides users with health data related to their activity, sleep, stress, menstrual cycle, and mindfulness habits. This data can help users better understand their current habits and make healthy decisions.

This project was completed using the framework of six steps of the data life cycle: Ask, Prepare, Process, Analyze, Share, Act

### 1.Ask
The stakeholders of Bellabeat would like to gain insight into how consumers use non-Bellabeat smart devices. They want to know the trends in smart device usage, how they can be applied to Bellabeat customers, and how they can influence Bellabeat's marketing strategy.
The stakeholders/audience:
+ Urška Sršen: Bellabeat’s cofounder and Chief Creative Officer 
+ Sando Mur: Mathematician and Bellabeat’s cofounder; a key member of the Bellabeat executive team
+ Bellabeat marketing analytics team: A team of data analysts responsible for collecting, analyzing, and reporting data that helps guide Bellabeat’s marketing strategy. You joined this team six months ago and have been busy learning about Bellabeat’s mission and business goals — as well as how you, as a junior data analyst, can help Bellabeat achieve them.

create table daily_activity
(
Id varchar,
ActivityDate date,
TotalSteps numeric,
TotalDistance	numeric,
TrackerDistance	numeric,
LoggedActivitiesDistance numeric,
VeryActiveDistance numeric,
ModeratelyActiveDistance numeric,
LightActiveDistance numeric,
SedentaryActiveDistance numeric,
VeryActiveMinutes numeric,
FairlyActiveMinutes numeric,
LightlyActiveMinutes numeric,
SedentaryMinutes numeric,
Calories numeric
);

create table daily_calories
(
Id varchar,
ActivityDay date,
Calories numeric
);

create table daily_intensities
(
Id	varchar,
ActivityDay	date,
SedentaryMinutes numeric,
LightlyActiveMinutes numeric,
FairlyActiveMinutes	numeric,
VeryActiveMinutes numeric,
SedentaryActiveDistance	numeric,
LightActiveDistance	numeric,
ModeratelyActiveDistance numeric,
VeryActiveDistance numeric
);
