---
layout: default
---
# My work

___

# Corporate work

> I build data solutions that solve real operational pain. Below are situations where a company struggled with something – and I fixed it (in order of impact).

---

### TomTom | Data Analyst (2012–2016)
**Ever had to give away a full expensive product when you could have swapped a small cheap component?**

*What happened:*  
Missing warranty start dates → wrong last-time component buys → unnecessary full-device replacements.

*What I did:*  
Calculated manufacturing week from serial numbers, then added estimated warehouse storage + shop shelf time before sale. Completed the entire warranty database.

*Result:*  
Accurate last-time buys for known defective components. Saved thousands in device giveaways and a substantial amount of money.

`[VBA, ERP data, warranty logic, supply chain, reverse logistics]`

---

### Seagen/Pfizer | BI Developer (2022–2024)
**Ever got frustrated at unavailable or outdated data?**

*Before:*  
2-hour dashboard refreshes, frequent errors, slow unresponsive filters (5+ minutes).

*After:*  
10-minute efficient refreshes, snappy dashboards that filter in 5 seconds instead of 5 minutes.

*How:*  
Coordinated with DB team to restructure Snowflake tables + queries. Rebuilt ingestion and transformation in PowerBI service.

`[Snowflake, PowerBI, SQL, data warehousing, ETL]`

---

**Ever had to “marry” a company just for one external tool that could be easily sorted out internally?**

*Problem:*  
Sales agents only saw their incentives in the last days of the quarter – or later. No visibility = no proactive behavior.

*Solution:*  
Built a dashboard tracking progress per sales team and per agent – against goal, in real time.

*Result:*  
Sales team loved it. Outperformed the previously used paid external tool.

`[PowerBI, Snowflake, stakeholder management]`

---

**Ever had to daily, manually and repetitively ingest data received via email?**

*Before:*  
Someone had to open emails, download attachments, check quality, ingest.

*After:*  
Full automation: email arrives → PowerAutomate scans criteria → saves attachments → triggers Snowflake ingestion → sends Teams DM with outcome.

*Bonus:*  
Automated Teams message every morning reporting data freshness in days. If stale, we fixed it immediately.

`[PowerAutomate, Snowflake, Teams API, data quality]`

---

**Ever had to manually send role and compliance based onboarding emails for new hires?**

*Problem:*  
New hires asked for access to reports. We manually checked role, discussed with manager + compliance, then granted.

*Solution:*  
Dashboard with new-hire alert. Compare today's vs yesterday’s employee table to scan for new hires. Auto-map role to access level. Insert email into correct permission list. All before their first coffee.

*Result:*  
New hires received report links on day one – or even before.

`[PowerApps, PowerAutomate, PowerBI, Snowflake, RBAC]`

---

### Navads - Data and reporting engineer (2017) & Transferz - Business Intelligence Analyst (2021)
**Ever started a company and have no reliable data sources or reporting?**

*Problem:*  
“My Excel says this.” – “Well, my analysis says the opposite.” No source of truth.

*Solution:*  
- **Navads:** Built reporting PostgreSQL data warehouse from MongoDB + CRM + manual sources. Talend jobs + Jenkins scheduled refreshes. Central PowerBI portal.  
- **Transferz:** Google BigQuery + DBT. Clean, up-to-date reporting from day one.

*CEO’s words:*  
> “It was like finally wearing glasses.”

`[MongoDB, Talend, Jenkins, PowerBI, BigQuery, DBT, Python, ETL]`

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
