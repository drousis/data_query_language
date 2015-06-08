# google_maps_example

####Summary
This is a first attempt at a thin abstraction layer over web services that provide public domain data over HTTP. 

####Example 1
The example uses [Google Maps elevation API](https://developers.google.com/maps/documentation/elevation/).

```
/> cd examples/
/> python example1.py
```
####Framework Requirements
* Throttling - framework will provide a built-in way to handle request limits rather than rely on the web service itself
* Authentication - framework will provide a way for the developer to login (if necessary) to access each web service
* Pagination - web services that require more than one API call to retrieve the full data set will be behave the same way using the framework's API
* 
