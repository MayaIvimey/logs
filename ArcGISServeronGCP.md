# Created an ArcGIS Server on Google Cloud Platform
## Learned how to creat a virtual machine in Google Cloud with the provided image
Time: 1.5 hours
- created a new project in Google Cloud Platform => NEW PROJECT => named it "My First Project"
- <img width="375" alt="image" src="https://github.com/MayaIvimey/logs/assets/146374490/63c6de76-50c9-419e-b160-77958afd2a79">
- Installed Computer Engine API
- created instance called arcgisservermivimey
- <img width="414" alt="image" src="https://github.com/MayaIvimey/logs/assets/146374490/b55de7d2-9edd-409a-9ee4-303a5807f4ba">
- changes boot disk to be the custom geom99 images
- allowed both http and https traffic
- <img width="206" alt="image" src="https://github.com/MayaIvimey/logs/assets/146374490/8a7707d5-28a5-4cff-aab6-9dfcce64550e">
- created a new firewall rule
- Named it flemingrdp444
- targeted all instances on the network
- set the Source IPv4 ranges to 0.0.0.0/0
- <img width="428" alt="image" src="https://github.com/MayaIvimey/logs/assets/146374490/46aa711b-df67-4b15-885d-90f5b9827e7c">
- set the TCP port to 444
- <img width="307" alt="image" src="https://github.com/MayaIvimey/logs/assets/146374490/3058ce1e-5016-4de0-aeac-cc5cb80a1311">
- Later realized that I did not set up the firewall rule for 6443 and 6080
- called this arcgisserveradmin
- Set the IP range to my home IP address and the TCP Ports to 6443 and 6080

- <img width="437" alt="image" src="https://github.com/MayaIvimey/logs/assets/146374490/e7c8beb5-ac3f-4968-885f-7446d8d501a2">
- <img width="416" alt="image" src="https://github.com/MayaIvimey/logs/assets/146374490/586eefed-9000-46fe-a40b-d81609f0a5f1">
- Set up the windows password with the username student and kept my password on notepad

## Created ArcGIS Online Layer
Time- 15 minutes
- paster url into new item
- <img width="546" alt="image" src="https://github.com/MayaIvimey/logs/assets/146374490/140abf9c-1390-48c1-aeae-541c36f719c1">
- Called it World Cities V2 because this is the second time doing this workflow
- <img width="551" alt="image" src="https://github.com/MayaIvimey/logs/assets/146374490/c4b7b740-b2ce-4135-8ce0-67bb7473e36d">
- viewed the result in map viewer
- <img width="923" alt="image" src="https://github.com/MayaIvimey/logs/assets/146374490/705c2dca-6ce6-4fdb-b9da-2a8b69fc8304">
used https://enterprise.arcgis.com/en/server/latest/publish-services/windows/services-in-arcgis-enterprise.htm as a resource

## Publishing Canada Map on Server
- opened a project in ArcGIS Pro
- clicked "Add Connection"
- Added a new server with the external IP address making sure to use port 6443
- <img width="939" alt="image" src="https://github.com/MayaIvimey/logs/assets/146374490/f2b02571-4639-4829-a45d-125bc4da2608">
- Published the data, being sure to register the data in the data store
- <img width="504" alt="image" src="https://github.com/MayaIvimey/logs/assets/146374490/431735c8-b4c4-47b6-afa7-624ea296e814">
- Published the Canada Map in ArcGIS Pro, making sure to validate the map in the data store
- <img width="689" alt="image" src="https://github.com/MayaIvimey/logs/assets/146374490/73db427b-44b1-4446-8366-5e06a87d173a">




