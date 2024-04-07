# Finished the Microsoft Power Automate 
Time: 1.25 hours
## Add in email
Time 45 minutes
- Added an action
- ![image](https://github.com/MayaIvimey/logs/assets/146374490/25a59b1d-c803-4c2f-8d5f-52988ae9cffb)
- Selected send an email
- ![image](https://github.com/MayaIvimey/logs/assets/146374490/b23bbd7f-f4b1-4ec4-8b9d-60809803296f)
- Filled out the boxes, sent it to my email
- ![image](https://github.com/MayaIvimey/logs/assets/146374490/bc52d015-5639-47ed-9876-645fcb0c6968)
- added the name and folder path as the attachement
- ![image](https://github.com/MayaIvimey/logs/assets/146374490/3cd2ce54-5db5-4c79-b229-58d994484575)
- Tested the flow
- sent an email, but did not attach the report
- ![image](https://github.com/MayaIvimey/logs/assets/146374490/77a7d7c8-5e10-4586-a375-e5c273d34c4b)
- Tried with a file locator
- tested the flow
- also did not attach the PDF
- ![image](https://github.com/MayaIvimey/logs/assets/146374490/ebdb4ac0-c2da-4bf7-a610-c8a0dc327b0f)
- tried one with the file content
- Sent a blank pdf
- Added another convert file using path action
- ![image](https://github.com/MayaIvimey/logs/assets/146374490/6328f6b7-8d41-406f-baef-0dd99626d407)
- Added the file content of that
- ![image](https://github.com/MayaIvimey/logs/assets/146374490/3de77786-63d9-44e6-a234-57e1b09104e7)
- The test run failed
- ![image](https://github.com/MayaIvimey/logs/assets/146374490/49c6e0a1-9df9-44dd-8156-7930b87569dc)
- Tried pasting in the dynamic content that was used in the create file
- body('Convert_file_using_path')
- Still was blank
- copied the link from one drive right into the body of the email
- That sent the email with the link, but is not ideal
- Next steps
  - Try to see if adding some dynamic content would work
 
## Adding dynamic content
Time: 30 minutes
- Wanted to see if I could add dynamic content that would add the date to the name of the file instead of just overwriting the previous file
- Tried putting the date into the name of the first file
- created the HTML but not pdf
- forgot to add in the time stamp to the convert file name
- ![image](https://github.com/MayaIvimey/logs/assets/146374490/f154ce74-e95e-43b0-85e1-c34132001708)
- Also tried adding dynamic content to the link
- ![image](https://github.com/MayaIvimey/logs/assets/146374490/fd6caf9c-ffb3-4d12-a80f-0aa70cf8911f)
- did not like that
- ![image](https://github.com/MayaIvimey/logs/assets/146374490/265879cd-a93d-4a26-b097-3582c038904b)
- Tried putting in the path
- ![image](https://github.com/MayaIvimey/logs/assets/146374490/a1c36af6-72ca-44f9-9802-d6eb98d9bcd1)
- ran but the pdf link did not work
- put the file name into the link
- ![image](https://github.com/MayaIvimey/logs/assets/146374490/980384e6-e1d5-4836-a9f3-8292bc4e6b1a)
- The link worked
- ![image](https://github.com/MayaIvimey/logs/assets/146374490/9e13af08-c42a-4f9f-b5d4-1b4bd7c0be6a)

## Next Steps
- This is enough for a model, but would have to find a way to only include the entries in the current month

