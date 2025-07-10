\# World University Opportunity Analysis Dashboard


Ever been confused comparing university rankings from QS, THE, and other sources? So have I. That's why I created this dashboard to simplify the campus search, especially for finding 'hidden gems' from the list of universities targeted by the Indonesia Endowment Fund for Education (LPDP).


\[View the Interactive Dashboard on Looker Studio](https://lookerstudio.google.com/reporting/a26778f6-5e58-450f-a386-b41315e022f4)


!\[Dashboard Screenshot] (https://github.com/Darelrk/Dashboard-Analisis-Universitas-LPDP/blob/fd1ef80bb7b077cc2028753d5f6c130a753fa405/images/dashboard.png)


About This Project

Often, a university with a modest overall ranking turns out to have an outstanding Computer Science department. That's what I call 'Hidden Gems'. This project was born from a desire to find such campuses: those that are proven leaders in their field, even if they aren't always in the spotlight.

Most importantly, all universities in this dashboard are from the official LPDP scholarship destination list, making this analysis highly relevant for those preparing to apply.

Key Features

With this dashboard, you can:

\* View the distribution of top world universities (based on the LPDP list) on an interactive map.

\* Directly compare overall rankings from QS, THE, and CWUR.

\* Discover 'Hidden Gems' through a special score that highlights excellence in Computer Science.

\* Filter all data by country for a more specific search.


Technology Stack

\* Data Visualization: `Looker Studio`

\* Data Storage: `CSV Upload`

\* Data Collection: `Python` (Selenium)

\* Data Analysis: `Python` (Pandas, Jupyter Notebook)



Behind the Scenes

1\.  Data Collection

&nbsp;   Overall and Computer Science-specific ranking data was automatically collected from various sites (QS, THE, CWUR) using the official LPDP directory as the university list.

2\.  Cleaning \& Merging

&nbsp;   All raw data from multiple sources was then cleaned, standardized, and merged into a single master CSV file using Pandas.

3\.  Visualization

&nbsp;   The cleaned CSV file was then uploaded to Looker Studio to create the interactive dashboard you can see and use.

