# Geniem android developer recruit task  


## requirements
Implement a simple image grid app that displays the image information in a detailed page, using this
project. 

The user should see the grid initially as soon as the data is ready from the http client. Clicking 
image thumbnail on the grid should navigate to the details page, using the json data already available 
from the initial api call. 

Use [fragments](https://developer.android.com/guide/components/fragments), [okhttp](https://github.com/square/okhttp)
and [livedata](https://developer.android.com/topic/libraries/architecture/livedata)

The app should pull it's data from [jsonplaceholder](https://jsonplaceholder.typicode.com/) using the
photo - endpoint. The grid should render only thumbnails provided in the json response and details - page
should render the full image as well as the title.  

The app is composed of two fragments:
- image grid fragment
- single image fragment   

## the boilerplate
This project is the fragment + viewmodel setup provided by android studio. Feel free to refactor
everything as you see fit, as long the requirements are met. You can use kotlin or java, but kotlin
is preferred.


## delivery  

Either fork this repo on github or provide the whole project compressed     


