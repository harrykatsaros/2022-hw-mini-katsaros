Harry Katsaros and Eunhye Kwon
EC463
September 16, 2022
Mini-Project Write Up
	For our first mini project, we worked with the Raspberry Pi Pico. This included downloading the appropriate software and running the pulse width modulation file on our Raspberry Pis and getting familiarized with Github. 
	We first ran the original code given to us and noticed that the LED on the Raspberry Pi oscillated between different blinking cycles and frequencies. At first the light blinks slower, followed by a quicker and quicker blink as time goes on. Eventually to the human eye, it was even hard to notice the blink. 
After running the original code, we proceeded to modify the clock divider and fade length in pwm_led_fade.c. We reduced the counter clock value of the Raspberry Pi Pico by modifying the divider value of 4 to 100. The larger divider value triggered the LED cycle on the Raspberry Pi to operate at a faster frequency. In other words, the system clock modification made the LED blink at a faster rate which can be seen in the attached video measurements. 
	Another change we made pertained to the fade length. The fade counter was originally incrementing by 1 until it reached the MAX_LED_BRIGHTNESS of 255 and decreasing by 1 until it reached the MIN_LED_BRIGHTNESS of 0. A modification was made so that the fade counter would increase and decrease at a faster clip, in increments of 5 instead of 1. As a result, the cycle further quickened, thus complementing the effect of the clock divider modification.  
