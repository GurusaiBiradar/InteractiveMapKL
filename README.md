Description: Display a map of Kaiserslautern using leaflet.js (Background: OSM-basemap + clickable districts of KL), when one of those shapes is selected, population information on the respective district should be displayed.

Steps to run the file:
1.	The place the file KL.html in the folder along with the dataset.
2.	When tried to run the file on browser directly it was unable to access the local dataset.
  a.	Run the command python -m http.server in the folder of files ( This creates a local server to run html file without any issue).
  b.	Run the http://localhost:8000/KL.html command on your local browser.
3.	All the districts are blue coloured by default.
4.	When a district is selected/clicked on map its details are displayed in the right description box.
5.	I choose to include only features such as District Name, Population (Men, Women, Total and Foreign) as I felt these were important and others were less important because they were relative             features. (Assuming my understanding of features are correct).
6.	The details are displayed in separate box because its more intuitive and clearer to read. When the details are on the map they could hide the view of some other part, also suppose I want to zoom       on other districts with previous district details still visible, its more convenient to use this approach in such cases.
7.	The selected district is highlighted using different colour.


