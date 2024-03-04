# Data mining GooglePlacesAPI
The project aims to retrieve place details (lat &amp; long) from Google API for Hotels &amp; Restaurants.
These latitude and longitude values will be joined with anonymized cellphone data to generate weekly, monthly, and annual visitor counts for hotels & restaurants

Problems: Google Places API returns paginated results up to a maximum of 60 per query
Solution: to pull all the restaurants in the radius a tiled grid was used in the search radius to query unique results only

**Module 1** calculates the total cost of the request to Google Places API by counting the unique number of results in the search radius
![image](https://github.com/Alex-Zeo/GooglePlacesAPI/assets/6181715/cc934fd5-e4f0-41be-8997-012e7dbd3611)


**Module 2** creates an Excel extract with the needed place details for creating geofenced POIs
![image](https://github.com/Alex-Zeo/GooglePlacesAPI/assets/6181715/69fee885-08a4-433e-bc5b-88aa4f7274e2)

**Excel Extract:**
![image](https://github.com/Alex-Zeo/GooglePlacesAPI/assets/6181715/3e117c01-e1f0-4e74-afd4-ad7bc2ee6de8)

