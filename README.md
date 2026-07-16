# PiWeatherStation

small project with an raspberry pi pico 2 WH in rust. 


### Functionality 

The Pico 2 W connects to the setted Wifi and checks the Location where it is on the world.
When the Location is found it handsover to the the modul for the API to get the weather data.
The weather data will be from [OpenWetaherMap](https://openweathermap.org/)


A Waveshare e-Paper will be the Display to show the data from the API
The entire screen will be updated every hour. 
Every 10- 15 min the dsiplay will be updated partial for the Temperatur and humidity information.




 #### References

  - https://crates.io/crates/cyw43
  - https://crates.io/crates/embedded-graphics
  - https://crates.io/crates/epd-waveshare
  - https://crates.io/crates/waveshare-rp2040-zero
