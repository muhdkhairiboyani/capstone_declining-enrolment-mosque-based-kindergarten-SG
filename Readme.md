##### Capstone: POWERBI INTERACTIVE DASHBOARD
---
---
# DECLINING ENROLMENT - MOSQUE-BASED KINDERGARTEN SINGAPORE

---
---
#### Dashboard
Go to [Presentation](https://github.com/muhdkhairiboyani/capstone_nyp_intake_planned-vs-actual/blob/main/NYP_for%20presentation.pdf) \
Go to [Dashboard](https://github.com/muhdkhairiboyani/capstone_nyp_intake_planned-vs-actual/blob/main/NYP_intake_dashboard.xlsx)
![Dashboard](NYP_intake_dashboard.png)

#### Dataset source:
**Source 01** \
Title: Listing of Centres Incidental Charges \
This data set contains the incidental charges set by the pre-school centres. \
Coverage: March 29, 2019 to April 23, 2023 \
Last updated: April 24, 2023 \
Licence: Singapore Open Data Licence \
Format: CSV \
Link: [Listing of Centres Incidental Charges](https://data.gov.sg/dataset/listing-of-centres-incidental-charges)

**Source 02** \
Title: Listing of Centres Licence History \
This data set contains the licence history set by the pre-school centres. \
Coverage: March 9, 2020 to April 23, 2023 \
Last updated: April 24, 2023, 12:00 (SGT) \
Licence: Singapore Open Data Licence \
Format: CSV \
Link: [Listing of Centres Licence History](https://data.gov.sg/dataset/listing-of-centres-licence-history)

**Source 03** \
Title: Listing of Centres Licence History \
This data set contains the licence history set by the pre-school centres. \
Coverage: March 9, 2020 to April 23, 2023 \
Last updated: April 24, 2023, 12:00 (SGT) \
Licence: Singapore Open Data Licence \
Format: CSV \
Link: [Listing of Centres Licence History](https://data.gov.sg/dataset/listing-of-centres-licence-history)

**Source 04** \
Title: Listing of Centres Licence History \
This data set contains the licence history set by the pre-school centres. \
Coverage: March 9, 2020 to April 23, 2023 \
Last updated: April 24, 2023, 12:00 (SGT) \
Licence: Singapore Open Data Licence \
Format: CSV \
Link: [Listing of Centres Licence History](https://data.gov.sg/dataset/listing-of-centres-licence-history)

#### Description of Capstone
According to the MINISTRY OF SOCIAL AND FAMILY DEVELOPMENT, the definition of Intake is that Intake refers to the new students entering the polytechnics in a particular year.

**planned_intake.csv**: CSV dataset shows data of NYP's intend for students intake across its six schools regardless of gender. Data is from 2013 - 2022

**intake.csv**: CSV dataset shows data of students intake into NYP across its six schools according to gender. Data is from 2016 - 2022.

I identified the following possible questions for this capstone:
- Q_1 : Has the yearly intake match the yearly planned intake?
- Q_2 : What are the top 5 courses among NEW FEMALE students?
- Q_3 : What are the top 5 courses among NEW MALE students?
- Q_4 : Since education evolves with the industry that it is linked to. Were there changes to its courses that helps to increase new student intake?

#### Phase 01: Entity Relationship Diagram - ERD
An entity relationship diagram gives a snapshot of how these entities relate to each other. You could call it the blueprint that underpins your business architecture, offering a visual representation of the relationships between different sets of data (entities).

The ERD screencapture below shows intended changes to be made.

![ERD](ERD.jpg)

#### Phase 02: PostgreSQL
Both CSV files were dumped as SQL files using SQLite3.

Process of normalisation and alteration are done using sql.

![ERD_dataset](IMG_SQL_01.jpg)
![ERD_dataset](IMG_SQL_02.jpg)
![ERD_dataset](IMG_SQL_03.jpg)

#### Phase 03: Dashboard
The layout of the dashboard shows how the five possible questions are answered.
![Explanation_of_dashboard](IMG_dashboard_present.jpg)

---

#### Contact me
- LinkedIn: [Muhammad Khairi](www.linkedin.com/in/muhammd-khairi-boyani-10694061)
- Instagram: [mikistudio21](https://www.instagram.com/mikistudio21/)

---
#### Platforms:
- Dashboards: Microsoft Excel
- SQL: PostgreSQL
- Markdown: [dillinger](https://dillinger.io)

---
#### Illustration:
- www.openpeeps.com

---
