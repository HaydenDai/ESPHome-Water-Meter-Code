Code for water meter pulse counters by using ESP8266

Basically, I wanted to make two water meters for the project Cottage Research by John Scofield, a professor in Oberlin College, Ohio.
You can learn more about his research on his website, https://thepragmaticsteward.com/.

Because Mr. Scofield's add-on device is API friendly, the number of water usage was always greater than he expected. 
Thus, he thought there was something wrong with his add-on device. 
I need to build two water meter pulse counters: one is for the amount of water used everyday; the other one is for the useage of hotwater.
I need to hook up ESP8266 with his water meter DAE AS200U-75P Water Meter with Pulse Output, 3/4" NPT Couplings, Measuring in Gallons that was bought from amazon.
And I should display the water usage on Home Assistant which he used to collect data from.

The basic concept is that, when a gallon of water is used, the switch is closed and there is a high boot (voltage). My ESP8266 aims to detect the number of times of high boots.
