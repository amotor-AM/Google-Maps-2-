# Google-Maps-2-
 This is a Google Maps project I worked on integrating the google maps API

This project shows a network of Bitcoin ATM's in my area and allows users to search for the ATM that is closest to them.

I hid the sidebar in the stores-list container which was a bit tricky. Using a webkit scrollbar styling allows for the scrollbar 
to be hid on some web browsers, but browsers such as Internet Explorer and Firefox still display the ugly scrollbar. Because
of this I had to set the width of the scrollbar to none. Interestingly this fixed the scrollbar for every browser I tried it with but  without the webkit scrollbar Google Chrome still displayed the default scrollbar. 

I also set up functionality to navigate to each individual store when the user taps or clicks on the address. This was done by setting up an event listener that opened up the address with the lat and long location of the marker in google maps. 

I also created a custom marker for use in this file. I could not find a default google marker that matched the color I wanted so i created my own and set it as the default for my code. 

I had fun with this project. It was a bit challenging for me as I am new to web developing and javascript in general but I am glad that I was able to put this together. 
