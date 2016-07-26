# Project Name

Feature-discovery-animations

Since May Google has updated his Material Design website. I have seen an interesting and cool design pattern in the new section named "Feature discovery" : https://www.google.com/design/spec/growth-communications/feature-discovery.html#feature-discovery-design-patterns. This is a sample to create the same animation.

#Android support

This sample has been made for Android 4.1+. To make it work for devices below Android 5 I had to disable hardware Acceleration. That's why in the Manifest you will find android:hardwareAccelerated="@bool/isBelowLollipop", with values and values-v21 we are able to set trur to "hardwareAccelerated" depending of Android API.

# Issues and Pull requests

Feel free to report issues and make pull requests. 
