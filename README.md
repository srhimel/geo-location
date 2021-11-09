# geo-location
 this is a simple example of getting user's geo location 


``` javaScript
function getLocation() {
    if (navigator.geolocation) {
        navigator.geolocation.watchPosition(showPosition);
    } else {
       console.log("Geolocation is not supported by this browser.");
    }
}
function showPosition(position) {
    console.log(position);
}
```