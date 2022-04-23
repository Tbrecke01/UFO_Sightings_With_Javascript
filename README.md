# UFO_Sightings_With_Javascript

## Overview

### Purpose
The purpose of this project is to create a dynamic website using Javascript to track UFO sightings. The request was to use a dynamic table to allow a user to serach for UFO sightings by Date, Cuty, State, Country, and Observed Shape. Given these conditions, the table would then automatically update to show all results that match the given criteria.

### Website Overview
![Website Search](https://github.com/Tbrecke01/UFO_Sightings_With_Javascript/blob/main/website_search.png)
This is the filter bar used for the table on the website. Users can input whatever filters they wish (there are some examples within the search, as shown above), press 'Enter' and the table to the right will update as needed, like so:
![Website Filters](https://github.com/Tbrecke01/UFO_Sightings_With_Javascript/blob/main/website_filters.png)
Users must be careful to use lowercase with no additional spaces and exact dates/text is also needed.
  
## Summary and Limitations
As mentioned previously, one major drawback is that the filter currently needs exact matches to work. This means that using uppercase or additional spaces will cause the filter to incorrectly display no matches. To address this, updating the filter to use close matches rather than exact is recommended. 
    
Another area of improvement would be to add date ranges to the filter bar and to add suggested auto-completes to the filter searches (ie for the city of 'Fresno' typing in 'Fr' will cause 'Fresno' to autopupulate). This would massively increase the filters ease of use.
