# python-api-challenge

Part 1 Summary:

There are three observable trends with the generated city weather data:
  
    1. There is a strong correlation between latitude and max temperature as shown by the linear regression of the relationship between Northern Hemisphere Latitiude            values and Max Temperature values. The r-value of that linera regression is ~-0.853 suggesting a relatively strong negative correlation between the two values. This makes sense as the farther north one goes in the globe, the colder temperatures one experiences.
    
    2. There is no strong observable correlation between cloudiness and northern hemisphere latitudes. The r-value of the linear regression between the two values is 0.223 suggesting that there is no correlation between cloudiness and latitudfes for the cities randomly pulled by the API. 
    
    3. Cities closer to the equator have the lowest amount of humidity. As shown by the scatter plot between City Latitude and Humidity, the plot suggests that cities with the highest levels of humidity belong on either the far positive-end of far negative-end of the latitude scale. This indicates that cities closest to the equator experience the least amount of humidity which makes sense since areas around the equator experience the highest levels of dry heat.
