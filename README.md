# Road-Map-Data-Structure
<br />
The project involves designing and implementing a data structure to represent road networks, specifically tailored for electric cars. This road map is modeled as an undirected graph where vertices denote places and edges represent roads connecting these places, each with a specified length. Each vertex stores the availability of charging stations, addressing the limited range of electric cars. The primary functionalities include loading a map from a file, checking connectivity between two places with charging stations, and determining the minimum number of assistance cars required for the map
<br />
 - Load a map and print information:
      java RoadMap -i <MapFile>
<br />
 - Load a map and determine if two places are connnected by a path with charging stations:
      java RoadMap -c <MapFile> <StartVertexIndex> <EndVertexIndex>
<br />
 - Load a map and determine the mininmum number of assistance cars required:
      java RoadMap -a <MapFile>
