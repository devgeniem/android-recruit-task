# Geniem android developer recruit task  


## requirements
Implement a simple image grid app that displays the image information in a detailed page, using this
project. Use [fragments](https://developer.android.com/guide/components/fragments), [okhttp](https://github.com/square/okhttp)
and [livedata](https://developer.android.com/topic/libraries/architecture/livedata)

The app should pull it's data from [jsonplaceholder](https://jsonplaceholder.typicode.com/) using the
photo - endpoint. The grid should render only thumbnails provided in the json response and details - page
should render the full image as well as the title.  

The app is composed of two fragments:
- image grid fragment
- single image fragment   

Both fragments are whole pages and should be managed by [fragment manager](https://developer.android.com/reference/android/support/v4/app/FragmentManager)

## the boilerplate
This project is the fragment + viewmodel setup provided by android studio. Feel free to refactor
everything as you see fit, as long the requirements are met. You can use kotlin or java, but kotlin
is preferred.

## bonus considerations

1) Do something with the large amount of data on grid, either actual paging or endless scrolling  
2) use [moshi](https://github.com/square/moshi) for json parsing
3) implement pull-to-refresh for the grid 

## delivery  

Either fork this repo on github or provide the whole project compressed     


