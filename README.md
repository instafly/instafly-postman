# instafly-postman
Import the ![Postman Collection](Instafly_postman_collection.json) for instafly visual search API Directly into Postman

1. You will need an API key from ![HERE](https://rapidapi.com/barkal/api/instafly-pro) .
2. There are 2 endpoints, one for passing in a url of an image, the other is to upload an image from a local machine. The image to be uploaded must be encoded into base64. this can be done programatically, but for testing purpose you can get your images encoded with ![this online tool](https://www.base64-image.de)

Visit https://rapidapi.com/barkal/api/instafly-pro for more information and to test the API online.

http://www.instafly.me

# Sample API response 
```
{
    "landmarkName": "Saint Joseph's Oratory",
    "lmLatitude": "45.515248",
    "lmLongitude": "-73.643164",
    "confidence": 47.1192,
    "destinationFlightInfoList": [
        {
            "airport": {
                "airportName": "Montreal / Pierre Elliott Trudeau International Airport",
                "airportCity": "Montreal",
                "airportCountry": "Canada",
                "airportIATAcode": "YUL",
                "airportLatitude": "45.47060013",
                "airportLongitude": "-73.74079895",
                "zone": "America/Toronto"
            },
            "kmDistanceFromLandmark": 9.09,
            "mlDistanceFromLandmark": 5.65,
            "flightBookingLink": "http://bit.ly/2IsE2Up",
            "hotelBookingLink": "http://bit.ly/2IjY57e"
        },
        {
            "airport": {
                "airportName": "St Jean Airport",
                "airportCity": "St. Jean",
                "airportCountry": "Canada",
                "airportIATAcode": "YJN",
                "airportLatitude": "45.29439926",
                "airportLongitude": "-73.28109741",
                "zone": "America/Toronto"
            },
            "kmDistanceFromLandmark": 37.44,
            "mlDistanceFromLandmark": 23.27,
            "flightBookingLink": "http://bit.ly/2IoikAL",
            "hotelBookingLink": "http://bit.ly/2IoOtrJ"
        },
        {
            "airport": {
                "airportName": "Montral / Saint-Hubert Airport",
                "airportCity": "Montreal",
                "airportCountry": "Canada",
                "airportIATAcode": "YHU",
                "airportLatitude": "45.51750183",
                "airportLongitude": "-73.41690063",
                "zone": "America/Toronto"
            },
            "kmDistanceFromLandmark": 17.63,
            "mlDistanceFromLandmark": 10.96,
            "flightBookingLink": "http://bit.ly/2IlNRTT",
            "hotelBookingLink": "http://bit.ly/2IjY57e"
        },
        {
            "airport": {
                "airportName": "Montreal International (Mirabel) Airport",
                "airportCity": "Montreal",
                "airportCountry": "Canada",
                "airportIATAcode": "YMX",
                "airportLatitude": "45.679501",
                "airportLongitude": "-74.038696",
                "zone": "America/Toronto"
            },
            "kmDistanceFromLandmark": 35.79,
            "mlDistanceFromLandmark": 22.24,
            "flightBookingLink": "http://bit.ly/2InTb9t",
            "hotelBookingLink": "http://bit.ly/2IjY57e"
        }
    ]
}
```
