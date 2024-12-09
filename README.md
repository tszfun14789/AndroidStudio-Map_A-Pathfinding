Pathfinding Android App
This is an Android application implementing an A* Pathfinding Algorithm to calculate and visualize the shortest path on a grid-based map. The app allows users to upload a map image, select a start and end point, and view the calculated path. The pathfinding logic avoids proximity to walls, encouraging navigation through the center of walkable paths.

Features
Upload Map: Users can upload a map image for pathfinding.
Interactive Point Selection: Start and end points can be selected by touching the map.
Path Visualization: The calculated path is displayed on the map.
Proximity-Aware Pathfinding: Paths are calculated with a cost function that avoids walls and narrow spaces.
Custom Grid Conversion: The app processes the uploaded map to create a grid representation for navigation.
Technologies
Android Studio: Development environment.
Java: Primary programming language for the logic.
A* Algorithm: Used for pathfinding.
Canvas API: For drawing the map and path.
Bitmap Processing: Converts the map image to a grid.
Installation
Clone the repository:
bash
Copy code
git clone https://github.com/yourusername/PathfindingAndroidApp.git
Open the project in Android Studio.
Build the project to download dependencies.
Run the app on an emulator or a physical device.
Usage
Upload Map:
Click the "Upload" button to select a map image from your device.
Select Start and End Points:
Tap on the map to select a starting point.
Tap again to select the ending point.
Calculate Path:
Click the "Calculate Path" button.
The shortest path will be drawn on the map.
Reset:
Use the "Reset" button to clear selections and start over.
