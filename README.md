# Power_bi_project_worldcup_cricket_T2022

![image](https://user-images.githubusercontent.com/123319398/227054573-45233466-c321-4a49-9071-fa3a86d62a23.png)


## About this project: This project shows the performance of the players in different teams and the best 11 player of the tournament.
Datasource : Webscrapping the ESPN website usign brightdata. The data we got in json file format. So we used jupyter Notebook is used to convert
the json files into the dataframes and then these dataframes into csv files for further data analysis.

![image](https://user-images.githubusercontent.com/123319398/222778774-d10dbcea-2e36-4df4-9732-807ccca804a4.png)

###Data Cleaning: For the data cleaning, I used Power Query Editor. I took followed steps for data transformations
## In dim_players
- renaming the files
* using first row as a header
+ splitting the name into two columns
- removing duplicate records
## In dim_match_summary
- adding a custom column 'stage' to categorize the game into qualifier or Super12
* changing the datatype of stage column to text
## In fact_bowling
- renaming column Bowling Team to team
* creating a ball column from overs column by splitting (like 2.5 over to 2 over and 5 balls)
+ replacing null values to 0
## In batting_summary**
- renaming columns 4s to fours, 6s to sixes, and team innings to team
* renaming column 'out/not_out to out where out=1 and not_out=0
+ changing datatype of 'balls' to whole number
- removing ( text after name from batsman_name


**Power BI: Import data using CSV files, data modelling, transformations using Power Query Editor, created DAX measures, designed dashboard using 
bookmark, tooltip, matrix,scatter chart, area chart, buttons, slicers and many more features.**


![image](https://user-images.githubusercontent.com/123319398/222763389-5d931ad6-f84a-4eaf-9c4e-ed1ae2aa09b1.png)
This image shows the top opening batsman and their batting average, strike rate, boundaries scored and number of balls they faced.
![Screenshot (6)](https://user-images.githubusercontent.com/123319398/222766985-8db1ae42-1e89-439d-b987-4cab742a55f5.png)


![image](https://user-images.githubusercontent.com/123319398/222764003-131dda43-f2fb-42ca-adf2-f77a3ef6a22f.png)
This image shows the best 11 players of the T20 cricket world cup and their performance.

Player analysis using tooltip
![image](https://user-images.githubusercontent.com/123319398/222764485-dc14f453-67e0-4913-b2c7-345912cb7aae.png)


📄 **LICENSE & LEGAL WARNING NOTICE**

© 2025 **Md. Tanvir Ahmed** — *All Rights Reserved.*

This repository and all of its contents are the **exclusive intellectual property** of **Md. Tanvir Ahmed**.
Every line of code, design element, and resource herein is **fully protected under international copyright and digital property law**.

---

### 🚫 ABSOLUTELY PROHIBITED ACTIONS

The following actions are **strictly forbidden** without prior written authorization from the owner:

* ❌ Downloading or cloning this repository
* ❌ Copying, redistributing, or reproducing any content
* ❌ Altering, reverse-engineering, or re-uploading any material
* ❌ Using this work for academic submissions, commercial projects, or derivative works

---

### ⚠️ LEGAL CONSEQUENCES

Any unauthorized access, download, duplication, or redistribution will be treated as **intellectual property theft** and may lead to:

* 📛 **Immediate DMCA takedown requests** against all offending repositories and mirrors
* 🧾 **Formal copyright infringement reports** filed to GitHub and relevant authorities
* ⚖️ **Civil and criminal legal action** under applicable national and international law

GitHub and associated digital forensics teams may be contacted for **account trace verification, IP logging, and evidence preservation**.

---

### 👁️ PERMITTED USE

You are allowed **to view this repository online for personal, non-commercial reference only**.
Any other action constitutes a violation and will trigger immediate enforcement procedures.

---

### 🛡️ FINAL NOTICE

**All activity on this repository is monitored and logged.**
Unauthorized users will be **reported, blacklisted, and subject to legal pursuit.**

Respect intellectual property.
**Violation of these terms will result in immediate and permanent consequences.**

