## Review Instructions:

- In order for anyone (TMs in this case) to run/test your projects on their devices. Follow the following steps:
1. Close the main.xaml.
2. Open the ReadRequest.xaml and click fix dependencies issues, you should be able to see and evaluate the activities in this workflow.
3. Open the SaaSAutomation.xaml and click fix dependencies issues, you should be able to see and evaluate the activities in this workflow.
4. Now Open Main.xaml and click fix dependencies issues, you should be able to see and evaluate the activities in this workflow.


## Requirements:
- UiPath Studio and Robot Agent connected to your machine and a Chrome UiPath Extention Enabled
- Microsoft Excel (Office)
- Windows 7 or higher
- Any SaaS based ticketing system - I'm using Zoho for this one - already logged in on chrome (or whatever browser so long as you have the necessary plugins specific to that browser installed as well).
- Run the Main file in UiPath studio.
# Job Card Creation Bot

## How it works
- A UiPath based Robot Agent will trigger the automated bot with Hotkey keyboard trigger/shortcuts (ALT +S).
- The bot will then open and read the Request.xlsx excel sheets from the 'Requests' folder,The excel file has the customer details and request.
- The details obtaine from the excel doc will be used to automatially create a job card (a ticket) in Zoho desk website application.
- Once the ticket is created, the request file file will be moved to the 'Processed' folder.
- The Robot agent can place another 'request.xlsx' file in the Request folder and use 'ALT +S' to create another jobcard
- The customare care assistant has to use the 'STOP' option in the UiPath Studio to stop the automation.

