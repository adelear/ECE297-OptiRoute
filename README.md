# OptiRoute_ECE297
 OptiRoute is our own custom Geographic Information System (GIS) built entirely in C++. We developed the map implementation from scratch with a focus on usability, responsiveness, and scalability. The system includes robust pathfinding functionality, featuring both the A* algorithm and a greedy algorithm with simulated annealing to explore solutions to the Traveling Salesman Problem. Designed with a user-friendly interface and informed by usability testing, this project showcases how complex algorithms can be applied in a practical GIS environment while laying the groundwork for future extensions and applications.

# **Key Features**

## 1) A Learnable and Memorable User Interface
- Intuitive Map View
	- Full-screen map display with clear street layouts and parks highlighted.
	- Closest intersections and points of interest (POIs) displayed at the bottom for quick reference.
- Easy Navigation Controls
	- Zoom in/out buttons (+ / –) for precise map scaling.
	- Reset or “Clear Path” button to remove previous routes.
	- Toggle UI button for a clutter-free map view.
- Simple Search Functionality
	- Search bars for entering first and second intersections to find pathways.
	- Dedicated “Search on Map” button for direct location search.
- Helpful Guidance & Feedback
	- On-screen instructions under “Pathway Directions” guide users in using the search feature.
- Organized Points of Interest (POI) Categories
	- POI toggle buttons (Essentials, Attractions, Food and Dining, Transportation) allow users to filter map markers.
- Accessible Help & Support
	- “Help” button available for users needing guidance on using the application.
- Clean and Minimal Design
	- Minimal visual clutter, clearly labeled buttons and categories.
	- Color-coded map elements (roads, parks, water) improve readability.
<img width="1512" height="837" alt="image" src="https://github.com/user-attachments/assets/5b4b2a20-805a-4fd1-9cc6-f29e170b3d8d" />

## 2) Live Weather and Temperature  
- Real-time weather API to display current temperature and conditions directly on the map interface.
- Provides users with up-to-date environmental context while navigating or planning routes.
<img width="993" height="519" alt="image" src="https://github.com/user-attachments/assets/9e99e3e2-2b62-40a2-a48d-089402450c5b" />

## 3) Contrast Mode
- Built-in contrast mode enhances visibility by adjusting the map’s color scheme.
- Improves accessibility for users in low-light environments.
- Ensures better readability for those with visual impairments.
<img width="1073" height="550" alt="image" src="https://github.com/user-attachments/assets/067387e2-73cb-4f4c-8af5-3a9c88b81b64" />

## 4) Pathfinding with A* Algorithm
- Allows users to click two points on the map to automatically generate and display the shortest route with step-by-step directions.
- Also allows uers to generate the shortest between between two locations with a search of their intersections
- The A* algorithm calculates the quickest path by combining:
  	- Travel time along each street
	- Turn angles (e.g., sharper turns may take longer)
	- Turn penalties (extra time added for left turns or difficult maneuvers)
- For each possible path, A* combines the time already traveled and an estimate of the time remaining to the destination.  
- The route with the lowest total time is chosen, providing users with the most efficient path and clear step-by-step directions.
<img width="1085" height="556" alt="image" src="https://github.com/user-attachments/assets/cb913820-7e6b-4738-b9ef-08ea64a6de98" />

## User Testing
A significant notion our team followed, as mentioned as our first key feature, was that a usable design is Learnable and Memorable. Thus, we followed Nielsen’s five attributes, and we picked 2 that gave us the most flexibility to add features. Altogether, these attributes help us achieve a universal design.

<img width="640" height="443" alt="image" src="https://github.com/user-attachments/assets/1ee2690a-5f0e-4df6-b777-d3693caa0c57" />

To evaluate usability, we conducted user testing sessions focused on intuitive control, clear directions, loading speed, and accessibility. Participants interacted with the map and provided feedback through surveys, which we analyzed to measure how well our application embodied Nielsen’s usability attributes.

The results showed strong performance in intuitive control (4.39/5) and clear directions (4.35/5), with accessibility also rated positively (4.0/5). The lowest score was loading speed (3.74/5), highlighting a key area for future optimization. Overall, the application received an average score of 4.14/5, indicating that users found the system effective and user-friendly.


<img width="1009" height="453" alt="image" src="https://github.com/user-attachments/assets/153e3e46-b767-4d5f-bd1a-8d1fe8b24d66" />


