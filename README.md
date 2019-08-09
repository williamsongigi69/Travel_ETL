# Travel_ETL

Our team sought to create an app which would search the Amadeus global reservation system for flights which have specific attributes required by the end user.  For the purposes of this project, we narrowed the scope to create a list of international flights originating from SFO and traveling internationally, i.e. outside of the United States for their destination/itinerary.

Our initial goal was to create a list of the top 50 international flights originating SFO for Valentine's Day 2019 (not sure the year is correct?) which were most popular and lowest in price.

The data we utilized is from the Amadeus API.  There are two options for API access with Amadeus.  The API option we used is the free option which allows for making free API calls.  The second option (Enterprise) is a fee-based access.  The free option furnishes 'test' data via the API which is not authentic, curent data from the actual global reservations system, but rather 'test' data which has similiarities with the actual, current reservation data but again, is not current, updated, or real data.  For our purposes, i.e. creating an app which allows the user to customize their search for flights which conform to certain defined search parameters, the 'test' data, free option from Amadeus suffices.

Amadeus represents one of three key GDS systems worlwide.  The three main GDS/Global Distributions Systems are: 1)SABRE=most common GDS used in North America, 2)Amadeus has the largest market share worldwide but is very weak in the United States, 3)Travelport, which owns Galileo and Wordlspan. Galileo is rapidly losing market share but used to have large market share in Europe, the Middle East, Asia and Africa.

The following link provides a comprehensive overview of the current GDS worldwide booking systems: https://www.youtube.com/watch?v=erzxKPGCBdc
