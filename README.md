# iOS Assignment
## Objective
The Rijksmuseum in Amsterdam showcases one of the most famous paintings in the world: De Nachtwacht - or: The Night Watch in English - painted by Rembrandt van Rijn. To make their collection more accessible, the Rijksmuseum exposed their collection through an open API. 

For this assignment we ask you to create an iOS application that lets the user search and retrieve data from the Rijksmuseum API.

## Project
The app should consist of the following parts:
- Search Screen
    - consisting of a search bar and a list of results. The user should be able to make a query and get the art objects for that query.
- Art object detail page 
    - consisting of the title, image, and 2 or more interesting fields of the art object.
    - A way to mark the object as favourite
- Favourites pages
    - A list of the users favourited art objects.

**Tips**
- Not sure what to search for? Check out this [list of painters](https://en.wikipedia.org/wiki/List_of_painters_in_the_collection_of_the_Rijksmuseum) in the collection of the Rijksmuseum

**API Reference**
- [Documentation for the API](https://data.rijksmuseum.nl/object-metadata/api/). Everything you need to access the API should be on this page
- [How to get an API key](https://data.rijksmuseum.nl/object-metadata/api/#access-to-apis)

## Requirements
**Caching**
* The app must perform some sort of caching of fetched API data, if a screen is reloaded we should expect to see the cached data before the refetched data

**Responsiveness**
* The UI must be updated in real-time, according to the refresh rule explained above.

**Resilience**
* The user should be informed if an error occurred while fetching data.
* If no network is available when a request is due, the app should park the call and perform it as soon as network is back.

**UI**
* You can decide on your own how will the app look, if you need a guide, feel free to look at the TicketSwap app as an example.

## Submission
Please provide a zip of the source code with which we can easily build locally and test out ourselves.

## General notes
- Write the solution in Swift.
- Pay attention to the quality of the code, and the overall design of your software.
- Some demonstration of testing would be nice.
- We recommend you to test your solution on real hardware.
- Document your API and classes where you think it is necessary.

You can make the assessment in your own time. We usually give around 1 week for it.
