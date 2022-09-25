Harry Katsaros and Eunhye Kwon
EC463
September 16, 2022
Mini-Project Write Up

For our first mini project, we worked with the Raspberry Pi Pico. This included downloading the appropriate software and running the pulse width modulation file on our Raspberry Pis and getting familiarized with Github. We first ran the original code given to us and noticed that the LED on the Raspberry Pi was fading in and out at a consistent rate.
After running the original code, we proceeded to modify the clock divider. We reduced the counter clock value of the Raspberry Pi Pico by modifying the divider value of 4 to 15. The larger divider value triggered the LED cycle on the Raspberry Pi to operate at a lower frequency. In other words, the system clock modification made the LED blink at a slower rate which can be seen in the attached video measurements. 





https://user-images.githubusercontent.com/75341058/192159583-c3067b36-320d-4590-9f03-602220473d34.mov



https://user-images.githubusercontent.com/75341058/192159592-77cf948c-8ec0-4e12-a21b-b9cd1fa9d4c5.mov

