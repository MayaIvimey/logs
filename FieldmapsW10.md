# Looked at Field Maps with Workforce
## Finished looking at how to add the layer to field maps
Time - 30 minutes
- Tried configuring the layer a different way, did not work and would not show up in the mobile app
- Opened up the layer in Field Maps Designer, tried sharing it differently and creating new fields. Also saved it in a different location
- <img width="236" alt="image" src="https://github.com/MayaIvimey/logs/assets/146374490/3d1fd909-19df-4bed-afdd-8355f57c257f">
- Eventually resorted to using the QR Code.
- <img width="446" alt="image" src="https://github.com/MayaIvimey/logs/assets/146374490/ffb7e34d-2ec5-4a5d-a1ae-62f0ab3384f3">
- wanted to see if it was possible to place a layer from Workforce into Field Maps as it is, which could save time.
## Played around in Field Maps
Time- 1hr 
- Scanned the QR code
- Went to the Field Maps Mobile App
- Added a few points
- <img width="198" alt="image" src="https://github.com/MayaIvimey/logs/assets/146374490/6bbf2292-b256-4541-807c-567af78124c7">
- Was able to show my availability as if I was a worker
- However, I found that this could add a lot of redundant points to the map if workers were to be clocking in and out. Need to find a way to delete the old points if worker's availability changes.
- Found that there could be a lot of issues with using Field Maps in this fashion
  1. There fields were set
     This was probably the biggest issue. When converting a already created layer from workforce to field maps there were a lot of fields that did not make sense. For example, there was a required location field that was a string that Field Maps Designer would not let me delete. Also could not change the field type to a drop down or map
     <img width="489" alt="image" src="https://github.com/MayaIvimey/logs/assets/146374490/a303eef3-d0cf-4627-8d5b-980fa7c32489">

  2. There was a lot of room for error
     Because I could not change the field type, the user could type in whatever they want and it would not show up on the dashboard if the information such as the userid was incorrect
     <img width="560" alt="image" src="https://github.com/MayaIvimey/logs/assets/146374490/4573554d-bb61-4c3c-967e-51941548b770">

  - Concluded that Field Maps has some issues when used this way.
  - In the future, need to see if there are better ways to integrate Field Maps that do not creae all of the redundant fields
  - Should have more dropdowns and proper formatting
