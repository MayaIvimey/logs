# Generate Reporting Workflow in Microsoft Power Automate
## Trigger when reponse is added to Excel File
time: 1 hour
- Create new excel sheet in the report test folder
- <img width="547" alt="image" src="https://github.com/MayaIvimey/logs/assets/146374490/e7bd49fe-48a7-4d6f-8f60-88d9844ade25">
- Create a schema of the sheet
- <img width="540" alt="image" src="https://github.com/MayaIvimey/logs/assets/146374490/2937e44d-9121-4003-8df7-8f17bb6519fb">
- Create automate cloud flow
- Trigger when file is modified in folder on OneDrive
- <img width="763" alt="image" src="https://github.com/MayaIvimey/logs/assets/146374490/7e3558d4-c58d-4915-ad06-98c188249e2c">
- Realized a scheduled workflow might be better
- <img width="591" alt="image" src="https://github.com/MayaIvimey/logs/assets/146374490/8c719beb-0f2f-4435-a2c9-0cb40fbeb99b">
- added Get Worksheet action
- <img width="740" alt="image" src="https://github.com/MayaIvimey/logs/assets/146374490/4db214c0-1bae-4949-91e5-e9f3664d0055">
- Added a red report to write to
- <img width="450" alt="image" src="https://github.com/MayaIvimey/logs/assets/146374490/9dd61e1d-8306-4b5e-a417-9d83a805f160">
- Looked at various triggers with OneDrive 
## Add Results to a Report
Time - 15 minutes
- Added another get worksheets action for the red report
- <img width="830" alt="image" src="https://github.com/MayaIvimey/logs/assets/146374490/3590f86e-7411-4d6b-bbfe-519931e9bfef">
- Tested it to see if errors popped up
- <img width="215" alt="image" src="https://github.com/MayaIvimey/logs/assets/146374490/2d219c94-64ee-43ab-99ec-f4f618c42c9d">
- Tried to add a variable for a count
- <img width="439" alt="image" src="https://github.com/MayaIvimey/logs/assets/146374490/5d6d8257-916d-4126-98b2-8ad9f620a2cc">
- Scratched that work, it was not going anywhere
## Created Flow for Word Document
Time - 45 minutes
- Created a word template with dynamic text values to populate with Flow
- <img width="685" alt="image" src="https://github.com/MayaIvimey/logs/assets/146374490/d721b03e-aef7-47e2-b3a9-bc09c5f00160">
- Created a selector that counted the number of requests in the worksheet
- <img width="484" alt="image" src="https://github.com/MayaIvimey/logs/assets/146374490/077f1691-cd0d-4818-8518-43e156be91f4">
- Set up the flow to populate a microsoft word template
- <img width="848" alt="image" src="https://github.com/MayaIvimey/logs/assets/146374490/e39fd643-319d-4fde-bccc-ddf04db556af">
- Wouldnt run because apparently I need a premium license for it

