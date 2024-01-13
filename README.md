# Title
DE101 Bootcamp- Code Review Week 10

# Project Members
Nikisha Banks, Jarvis Wynn, Alex Wallace

# Technologies Used: 
Git hub, Visual Studio Code, Google Cloud, Google Looker Studio

# Languages and tools used: 
Python, Pandas, Kaggle, SQL

# Kaggle Datasets Used:
 https://www.kaggle.com/datasets/tobycrabtree/nfl-scores-and-betting-data

# Description:
In this project, we have created a data pipeline that brings data from Kaggle, transforms it in Visual Studio using Python and then stores it as datasets in Google Big Query. Once it is stored, several visualizations were created in Google Looker Studio to show various metrics on NFL betting.

# Setup/Installation Requirements:
- To see the code files in this project:
  1. Clone the repo in Git Hub: 
                a. Click the green "code" button
                b. Under the "Local" tab, copy and paste the URL that is under HTTPS
- To see the raw data files that were used in this project, 
  [click here](#kaggle-datasets-used)
- To see the Dashboard for this project:
        https://lookerstudio.google.com/reporting/dc08b504-e8d6-4cac-b48e-af466d8bb2cf

# Known Bugs
No known bugs

# Project Visuals
## ERD model
![Image](https://github.com/nbanks062523/CodeReview_week10/blob/main/images/nfl_sports_betting.drawio.png)
---
## Big Query Datasets
**Games Dimension Table Schema**
![Image](https://github.com/nbanks062523/CodeReview_week10/blob/main/images/Games_Dimension_Tble.png)
---
**Over/Under Fact Table Schema**
![Image](https://github.com/nbanks062523/CodeReview_week10/blob/main/images/Ovr_Undr_FctTble.png)
---
**Points Spread Fact Table Schema**
![Image](https://github.com/nbanks062523/CodeReview_week10/blob/main/images/fct_points_spread.png)
---
**Team Lookup Table Schema**
![Image](https://github.com/nbanks062523/CodeReview_week10/blob/main/images/TeamID_LookupSchema.png)
---
**Table Views Queries and Schemas**
---
Games
![Image](https://github.com/nbanks062523/CodeReview_week10/blob/main/images/Games_ViewTable.png)
![Image](https://github.com/nbanks062523/CodeReview_week10/blob/main/images/Query_GamesViewTable.png)
---
Over/Under
![Image](https://github.com/nbanks062523/CodeReview_week10/blob/main/images/Ovr_Undr_TbleView.png)
![Image](https://github.com/nbanks062523/CodeReview_week10/blob/main/images/Query_OvrUndrTbleView.png)
---
Points Spread
![Image](https://github.com/nbanks062523/CodeReview_week10/blob/main/images/PointSpread_ViewTable.png)
![Image](https://github.com/nbanks062523/CodeReview_week10/blob/main/images/Query_PointSpreadViewTble.png)

# License
*Copyright 2024, Data Stack Academy Fall 2023 Cohort*

*Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the “Software”), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:*

*The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.*

*THE SOFTWARE IS PROVIDED “AS IS”, WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.*
# BootCampCodeReview10
