# Try to find out how to automate reporting
## Created A Survey123
Time - 10 Minutes
- Created and published a test Survey123 to report information
- <img width="918" alt="image" src="https://github.com/MayaIvimey/logs/assets/146374490/2d1f0543-b6ef-4bf1-86cc-827762589756">
- Created a test Web Map to show the information
- <img width="956" alt="image" src="https://github.com/MayaIvimey/logs/assets/146374490/373dc79b-4a8c-4c41-a2bf-ff5ffa04f3a1">
## Add Points to Survey 123
Time - 15 Minutes
- Added test points to report on
- <img width="765" alt="image" src="https://github.com/MayaIvimey/logs/assets/146374490/f509295e-de7e-4268-9248-051e6ab8a861">
## Looked Into Different Ways to Automate Sending Responses
Time - 35 minutes
- Could not find a way to automatically report through ArcGIS Online
- Found an ESRI Blog post that used Microsoft Power Automate
- Signed in using my Fleming email.
- Searched for Survey123 Connecter
- Used a template that sends an email every time a response is submitted
- Filled out the required information for the Survey123 part and email part
- <img width="908" alt="image" src="https://github.com/MayaIvimey/logs/assets/146374490/2958736a-bda6-4ee4-9886-37776a7368c1">
- <img width="950" alt="image" src="https://github.com/MayaIvimey/logs/assets/146374490/68967c74-799b-4899-a491-4f37f35d7d44">
- Collected a point to see if it worked
- An email was sent to my Fleming Email
- <img width="743" alt="image" src="https://github.com/MayaIvimey/logs/assets/146374490/477aa483-8ce7-44e7-9656-a11b3edbe4cf">
- This could be manipulated to send reports daily, weekly, or montly
<img width="517" alt="image" src="https://github.com/MayaIvimey/logs/assets/146374490/fca9c57a-caa6-4e9f-9b1c-20651c067d66">
- Also an option to create a report
<img width="788" alt="image" src="https://github.com/MayaIvimey/logs/assets/146374490/1c250c5f-e651-46b8-9bb8-b4c9b770f243">
- Blog Post: https://community.esri.com/t5/arcgis-survey123-videos/survey123-create-report-action-in-microsoft-power/td-p/1253057

## Create a mock reporting flow
Time- 1 hr
- Create a scheduled flow
- This time the flow was manual not a template
- <img width="843" alt="image" src="https://github.com/MayaIvimey/logs/assets/146374490/f85a52ce-91fa-4eb0-bcf6-e2090880fb6a">
- This adds a recurrence to the flow
-<img width="816" alt="image" src="https://github.com/MayaIvimey/logs/assets/146374490/d8d8abd1-1710-4189-ba41-e342cfab84ac">
- Add an action
- <img width="188" alt="image" src="https://github.com/MayaIvimey/logs/assets/146374490/3de0778d-f19b-4552-98c0-4da0e489f418">
- Searched for Survey 123
- <img width="308" alt="image" src="https://github.com/MayaIvimey/logs/assets/146374490/a58747f7-6356-4190-b8b5-4726086ccaa4">
- Selected Create report
- Had to go into the data section of Survey123 to create a report template
- <img width="434" alt="image" src="https://github.com/MayaIvimey/logs/assets/146374490/4d9e135c-e8cc-46dd-8beb-7ee99f3ecd93">
- Filled in the require information
- <img width="383" alt="image" src="https://github.com/MayaIvimey/logs/assets/146374490/364ca3f2-2280-4b68-8e91-097d9c2ed534">
- inserted another action
- <img width="281" alt="image" src="https://github.com/MayaIvimey/logs/assets/146374490/0a02796f-22ee-41ed-a69b-12e031e327e8">
- Selected Office 365 Outlook
- <img width="304" alt="image" src="https://github.com/MayaIvimey/logs/assets/146374490/dd6db66a-70f3-4f64-bc02-21f73efe558c">
- Selected Send an email
- <img width="293" alt="image" src="https://github.com/MayaIvimey/logs/assets/146374490/d7ca9c4e-fef9-4e5d-8412-05d44fd34512">
- Added the url as an attachement
- <img width="305" alt="image" src="https://github.com/MayaIvimey/logs/assets/146374490/c7511bb3-66e3-4b12-a1ec-8055885f4305">
- Did a test run, ran into an issue
- <img width="779" alt="image" src="https://github.com/MayaIvimey/logs/assets/146374490/d9d408a8-9628-40db-a204-9c26df42ef1a">
- Realized the date for the name didn't work, took it out and tried again
- Ran a bad request
- <img width="949" alt="image" src="https://github.com/MayaIvimey/logs/assets/146374490/1bba7c4f-6b28-4bc8-859a-2872502345e2">
-took out the attachnments of the email and tried again
-worked this time, need a new way to attach the reports
- <img width="934" alt="image" src="https://github.com/MayaIvimey/logs/assets/146374490/ff8aa715-5d6c-4411-bf2f-af6b60791a5e">
- Added upload file from url
- <img width="761" alt="image" src="https://github.com/MayaIvimey/logs/assets/146374490/5a98f9f2-3414-4dba-872a-44c90251e5f4">
-  did not work
-  Tried changing the trigger
-  <img width="761" alt="image" src="https://github.com/MayaIvimey/logs/assets/146374490/917f908d-7ab3-4986-b351-27b562e2108e">
- Still did not work
- <img width="866" alt="image" src="https://github.com/MayaIvimey/logs/assets/146374490/824669f1-1c35-49b1-af7e-fcdfc0dc565f">
- Did some research and realized that I needed to add a feature object id to the create report action
- <img width="560" alt="image" src="https://github.com/MayaIvimey/logs/assets/146374490/99eee41c-ee5b-4e23-be9b-2e2b7499be0d">
- managed to get it to run, sent an email and uploaded to OneDrive
- <img width="955" alt="image" src="https://github.com/MayaIvimey/logs/assets/146374490/dab68eec-eec2-4e1f-b6e3-a2e7d648ed75">

## Next Steps
- Implement a time trigger rather than adding a new feature
- create a report template that has statistics that would be useful
- inlcude the file in the email










