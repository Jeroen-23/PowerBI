Free Power BI Usage Metrics dashboard:
This dashboard utilizes the Power BI REST API to retrieve user metrics data. To get the latest data, you need to retrieve a bearer token from the Microsoft website. Note: You need Power BI Admin rights to retrieve data from the Power BI REST API.

Link to Microsoft website: Admin - Get Activity Events - REST API (Power BI Power BI REST APIs) | Microsoft Learn

Look for: Request Preview --> Authorization --> Bearer Token.
Fill in this bearer token into the BearerToken function in the query editor.
The BearerToken expires every 30 minutes, so you'll need to obtain a new one from the Microsoft website each time.
