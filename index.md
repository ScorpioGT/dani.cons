---
layout: default
---
# My work

___

# Corporate work
## My biggest achievements
---
### Ever had to give away a full expensive product when you could have swapped a small cheap component?
At TomTom I have developed an algorithm that saved precious resources and money and avoided a lot of in warranty swaps or giveaways.

**Details:**

We had issues tracking the warranty period of devices, which lead to wrong component LTB (Last Time Buys that occurr when a supplier sends a notice about that particular component becoming obsolete).
Our database was lacking a lot of dates of first shipment, from which we could not calculate the warranty period. This lead to buying components only for the devices we certainly knew they were in warranty.
What I did was calculating the manufacturing week from the serial numbers, adding an estimate of warehouse storage, and shop shelf time before the sale, and we were able to have a complete database, that lead to more accurate last time buys of the known defective components, which saved us a lot of newer devices "giveaway".
---
### Ever got frustrated at unavailable or outdated data?
At Seagen, I have re-worked a finance data model that allowed our analyst to go from "I may be able to see fresh data before lunch" to "It's 8.30 pm, let me see what's new today".

**Details:** 

From 2 hours refreshes with frequent disruptions and errors and super slow and unresponsive dashboards, to 10 minutes efficient refresh and better error handling, to snappy dashboards that would filter and switch pages in a matter of 5 seconds instead of 5 minutes. Coordinating with the database administration team, I have provided the tables structure and the queries to generate and refresh our data warehouse in Snowflake, which was then used as a base for further ingestion and transformation in the PowerBI service, leading to much faster refreshes and way more responsive reporting dasboards.
---
### Ever had to "marry" a company just to have one external tool for a job that could be easily sorted out internally?

**Details:**

Our sales agents were blind on the incentives they were about to get until the very last days of the quarter or even later, and then... Surprise!
At Seagen I have developed a dashboard that could track progress for a sales team and a sales agent, in order to give a clear picture of the current status vs the set goal, and make agents aware of their progress, before the deadline. This was very warmly welcomed by the sales team, and proved to work better than the previously used external paid tool.
---
### Ever had to daily, manually and repetitively ingest data received via email?
At Seagen I have implemented a full automation process that grabs attachments from the inbox the moment they show up, checks for data quality, ingest it automagically and sends you a chat DM with the outcome.

**Details:**

Used PowerAutomate to scan the inbox and read for specific criterias in the received email, then save the attachments in a specific location for automatic ingestion in Snowflake, and triggered a message to the DB team.
Every morning at a set time we had also an Automated Teams message which will prompt us about the data "freshness in terms of days. This way we could immediately spot a potential issue in the data ingestion and fix it.
---
### Ever had manually send onboarding email curated by role and compliance for new hires?
At Seagen we had new hires coming in and asking for access to reports which we then manually granted, after checking their role and discussing level of access with their manager, compliance etc.

**Details:**

I have created a dashboard that had an alert value for new hires. If there are new hires, check who by comparing today's employees table with yesterday's, then grab their role and map it automatically based on a mapping table we previously prepared, and automatically insert their email in the users list that has access to the specific information they needed. Our reports were standard for everyone, but higher management could access deeper level of information based on their mapped role. This was done via PowerApps, PowerAutomate and PowerBI, fetching data from Snowflake.
After this, an automated email was sent with the links to the reports they could see. All of this in their first day in the office, or even before!
---
### Ever started a company and have no reliable data sources and reporting?
At Navads and Transferz I have set up the whole data infrastructure from reporting databases to dashboards. We went from "A: My excel sheet says this. B: Well my analysis says the opposite..." to "Let's check on Dani's reports what the numbers say". In CEO's words "It was like finally wearing glasses."

**Details:**

These 2 companies were a bit more than startups, and lacked a structured and centralized source of truth when it came to data and reporting.
At Navads I have created a reporting Datawarehouse acquiring data from the company's MongoDB database, the CRM and other manually ingested source, and combined everything into a reporting data warehouse using talend jobs, scheduled via Jenkins. This allowed us to refresh PowerBI reports daily or even more frequently, and have a cantralized reporting portal in PowerBI.
At Transferz, we have instead set up a Google Big Query data warehouse, using DBT, and the outome was also clear and up to date reporting.
---
## More details on my CV

**[Download my text only CV HERE](/assets/docs/cv_text.pdf)**

**[Download my visual CV HERE](/assets/docs/cv_visuals.pdf)**

---

# Personal projects work

### **Formula 1 telemetry app**
_An app written in Python fetching telemetry data via the fastf1 API, using Godot as graphics engine, to display beautiful animations of every lap of any session of every GP of the F1 seasons, allowing to compare insightful and rich datapoints for up to 3 drivers at a time. Still under development._

![](assets/img/f1tlm.png)

---

### **Automatic short video generator**
_An 100% local n8n workflow that uses Ollama and ffmpeg to automatically generate a short 30 seconds slideshow with dissolvence, watermark logo, and a summary voiceover with subtitles of any text you paste in an input file_

[Example video](https://www.instagram.com/p/DXetp9ziJ0N/)

![](assets/img/n8nwf.png)

---

### **Complete data infrastructure**
_A complete data infrastructure for data analysis and violations detections for a Prop trading firm. Written in python, it fetches data from API calls and organizes everything in a star schema datawarehouse in PostgreSQL, then fed to PowerBI for visual analysis_

![](assets/img/traddm.png)

---

### **Brain aneurysm detection model**
_A model I have trained for a Kaggle competition, on sample data supplied by the competition website, plus augmented and external data i have produced and fetched. Late for the entry but evaluated the score with the competition official formula, would have placed 42nd on top of 1140 entries_

![](assets/img/rsnaiad1.png) ![](assets/img/rsnaiad.png)

---

### **Garage manager pro**
_A local CRM for small/medium auto repair shops, based on Godot and SQLite. Born from a friends need. Under development and to be for sale soon_

![](assets/img/gmpro.png)

---

### **Electronic devices and products**
_As a sidequest I'm trying to launch a brand about motorsports called SDP (Science Driven Performance) for which i have fully engineered a go kart scale that has a touchscreen and connects to the 4 plates under the wheels. It gives full weight distribution in all corner, real time COG and cross weight. The menu switches between 4 languages and imperial and metric units. The products pipeline also has a reaction training device with 6 pads (currently under development) and a full telemetry system_

![](assets/img/sdpscale.jpg)
