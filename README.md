# Drone-Route-Planning

### Problem Statement
---
 Planning a route (for **Shortest Time to cover Area**) and schedule of Drones for **Mapping** a given area.

 The **input** provided will be:
1) Map of area to be covered. (**Shapefile**) 
2) **Number** of drones. 
3) **Source** and **Sink** Locations 
4) Depreciation **Rate** (% per unit)
5) Location of automatic **Charging station**.

**Output** will be:
1) **Minimum** number of Drones required to map the area.
2) **All Unique Routes** taken by each drone.
3) Remaining **Battery** of each Drone after completing its journey.
4) A **Google Map** plotted with all **Nodes** and **Charging stations** and **edges** connecting them.
5) **All Unique Routes plotted on another Google Map as the final output with a different colour for each traversed route.**

## Technology
* Python 
   * **NumPy**
   * **gmplot**
   * **webbrowser**
   * **Tkinter** for GUI
   * **pyshp**
   * **pandas**
   * **math**
* Shapefile (SHP)
* Keyhole Markup Language (KML)

## Implementation

Algorithms used, Cases covered and Example can be found **[here](https://github.com/farhankapadia/Drone-Route-Planning/blob/master/Implementation.md)**.

## Screenshots 
![alt text](https://github.com/farhankapadia/Drone-Route-Planning/blob/master/pics/1.png)
|||
|--|--|
|![alt text](https://github.com/farhankapadia/Drone-Route-Planning/blob/master/pics/2.png)|![alt text](https://github.com/farhankapadia/Drone-Route-Planning/blob/master/pics/3.png)|
|![alt text](https://github.com/farhankapadia/Drone-Route-Planning/blob/master/pics/4.png)|![alt text](https://github.com/farhankapadia/Drone-Route-Planning/blob/master/pics/5.png)|

## Setup
1. Clone this repository or download zip.  
2. Navigate to project folder in terminal and type (if mentioned above **python modules** not installed)  

   ```
   pip install numpy
   ``` 
      ```
      pip install gmplot
      ```
      ```
      pip install pyshp
      ```
      ```
      pip install pandas
   ```
3. To run the project,
   ```
    python djik.py
   ```
4. All set.
