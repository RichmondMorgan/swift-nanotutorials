

 № 12 CoreLocation. Asking for user location and choose a proper location accuracy in Swift?

1) First of all, 

import CoreLocation


2) Then, we ensure that our ViewController class complies with  CLLocationManagerDelegate rules.

class WeatherViewController: UIViewController, CLLocationManagerDelegate



3) create a sub-class from CLLocationManager() super class

let locationManager = CLLocationManager()



4) Set our locationManager as the class to report to all data fetched by delegate

locationManager.delegate = self


5) Tap into .desiredAccuracy property and pick the accuracy according the needs of our project:

 locationManager.desiredAccuracy =
 
 ![monosnap 2019-02-11 17-10-57 1](https://user-images.githubusercontent.com/47090408/52568535-1654d400-2e20-11e9-92e2-f5c2e76da358.png)



6) Set location request type

locationManager.requestWhenInUseAuthorization()

<img width="455" alt="monosnap 2019-02-11 17-13-45" src="https://user-images.githubusercontent.com/47090408/52568732-a72baf80-2e20-11e9-99d5-aac64583dc28.png">


