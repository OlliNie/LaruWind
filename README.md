# LaruWind

## OBJECTIVE:
Increase the wind forcast accuracy at the Lauttasaari kite spot (Kasinoranta and Kaislikko).  This will require
- Back-end to analyze wind forcast and to improve it
- Front-end to be able to fetch wind forcast data from the back-end using an API and to present the data

## OBSERVATIONS:
- It seems that the wind forcast at Harmaja is typically stronger than at the kite spot
- Even when it is windy at Harmaja for some reason the wind does not get all the way to the kite spot
- The wind seems to die off at the kite spot before the forcasted time especially in the spring
- Sometimes the windforcast is completely wrong

## NOTES:
Similar implementaion allready exists in Oulu and the website for the improved wind direction can be found at https://hawaji.azurewebsites.net.

In the Oulu example a strong correlation was found that the actual wind is considerable stronger than the forcasted.  It seems that in Laru the opposite is true.

## TODO: FRONT-END
- Fetch wind forast from back-end
- Provide wind direction along with if the wind direction is favorable for kiting
- Provide a wind forcast for the next week
- Additional improvements may include details for example on x wind direction it is likely to find holes in the wind or if the forcasted wind showed up early that the wind may die off earlyer as well

## TODO: BACK-END
- Identify key features that effect wind at the local kite spot
- Implement machine learning to come up with a way of improving wind forcast
- Provide an API capable to providing improved forecast to the front-end
- Work with front end deverlopers when creating API routes
