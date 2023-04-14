# How to make map with chimp groups and sniffing points:

**To separate latitude and longitude into separate columns in CSV file if not already done so**
1. Make a new column called "Lat"
2. Type code: =MID(a, b, c)
* a: the cell you're getting the latitude data from (e.g. K9)
* b: the number you're starting at (e.g. if it says 4.590,3.509 you could want 4)
* c: the number of characters (e.g. 5)
3. Then do the same thing but for longitude (this time make a column called "Long")

**To add sniffing data points to map**
1. Download Google Earth Pro (it's free) https://www.google.com/earth/versions/
2. Import data file(s) with sniffing points to Google Earth Pro. Make sure latitude and longitude are separate columns (see steps above if you need help doing that)
3. In the left-hand side of Google Earth Pro, click the checkboxes for the file(s) you want to include the data points from

**To add the circles for the communities to map:**
1. Open Ngogo map on GoogleMyMaps (it's free) https://www.google.com/maps/d/u/0/viewer?mid=1FIgnxcTwj04jZhizFcqchXcRGjoUwejf&ll=0.43334365430693905%2C30.378669500000008&z=10
2. Click the ... in the left-hand side of GoogleMyMaps
3. Click "Download KML/KMZ"
4. Pick "Split" and "Post-Split" or whatever you want
5. Click "Ok"
6. Download as KMZ
7. Upload that to Google Earth Pro
