Problem Statement: 

Navigating a large university campus can be a significant hurdle for new members of the community, leading to inefficiency and frustration. The absence of a simple, quick-reference tool for locating facilities and understanding campus layout necessitates the development of an accessible, text-based navigation system.
Scope of the Project
The scope of the Campus Pathfinder project is confined to a command-line interface (CLI) application developed exclusively in Python 3.x.
1.	Data: All campus data (locations, types, and connectivity) is managed using hardcoded Python dictionaries (CAMPUS_MAP).
2.	Functionality: The system provides basic search, filtering, and conceptual route mapping based on this static data.
3.	Exclusions: The project deliberately excludes complex features such as graphical user interfaces (GUI), real-time location tracking (GPS), external database integration, and advanced graph-based pathfinding algorithms (like Dijkstra's).
Target Users
1.	New Students: Requiring fast directions to classrooms and services during orientation.
2.	Campus Visitors: Needing to locate specific administrative or academic buildings.
3.	Campus Personnel: Seeking quick reference information about less-frequent locations.
High-Level Features
•	Display location type and a list of neighbouring locations.
•	Filter and list all locations belonging to a specified type.
•	Suggest a basic, conceptual route between any two known campus locations.
•	Ensure application stability through graceful error handling for invalid user inputs 
