# Data mining GooglePlacesAPI
This python script retrieves restaurants and place details (lat &amp; long) from Google Places API.
These details are used to create comp sets to model the Fifa World Cup 2026 US markets. 

Problems: Google Places API returns 60 maximum results per query
Solution: Break up a big search into many smaller searches using a tiled grid

V1 Gaps of expected restaurants were identified in the resulting data. To investigate these gaps a visualization was generated and visual gaps were identified.
![image](https://github.com/Alex-Zeo/GooglePlacesAPI/assets/6181715/c0cf9cb6-8808-461a-81b6-41be672dc0de)

V2 Tiled Grid Formula adjusted to add an overlap between the tiles. This ensures all unique restaurants in the search radius are included.
![image](https://github.com/Alex-Zeo/GooglePlacesAPI/assets/6181715/6627ff21-72b3-4184-b95f-3d6621915e5c)


**Module 1** calculates the cost by counting the number of results & generates a tiled grid map to confirm the search parameters.
![image](https://github.com/Alex-Zeo/GooglePlacesAPI/assets/6181715/cc934fd5-e4f0-41be-8997-012e7dbd3611)


**Module 2** creates an Excel extract with the needed place details for creating geofenced POIs
![image](https://github.com/Alex-Zeo/GooglePlacesAPI/assets/6181715/69fee885-08a4-433e-bc5b-88aa4f7274e2)

**Excel Extract:**
![image](https://github.com/Alex-Zeo/GooglePlacesAPI/assets/6181715/3e117c01-e1f0-4e74-afd4-ad7bc2ee6de8)

