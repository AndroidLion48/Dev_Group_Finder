# Desinging for Everyone - GDG Finder app

This is the app for Lesson 10 of the [Android App Development in Kotlin course on Udacity](https://classroom.udacity.com/courses/ud9012/).
 
## GDG Finder

GDGs, or Google Developer Groups, are communities of developers that focus on Google technologies - including Android - around the world. They host lots of different events like meetups, conferences, study jams, and more!

GDG Finder helps you locate GDGs around the world or start one of your own. You'll learn the principles of Material Design so you can implement professional looking designs and build Android apps that users love to use!

 
## Screenshots

![Screenshot1](screenshots/gdg-finder-home.png)
![Screenshot2](screenshots/gdg-finder-search.png)
![Screenshot3](screenshots/gdg-finder-apply.png)


## Topics Covered  

Application accessability for everyone.
contentDescription for Accessability Talkback specification.
Styles 
Font imports
Themes
Layout Attributes
RTL support
RTL language support
Material Design library and utilization
Material colors
Floating Action Button
Adding ChipGroup
DarkMode Themeing


# Notes:
Content Grouping (for UI controls that Talk should treat as a group): Related content that is grouped together will be announced together.
Live Regions:  A way to tell TalkBack when things change (informing user of a network failure or incorrect password)

Android Drawables (Backgrounds, ImageViews, NinePatch, Statelss)
	-NinePatch:  When you need an image to grow along any of its edges (DropShadows)

Chips Implimentation:
	- Background Drawable
	- Check mark Drawable
	- Ripple Effect (Drawable enables this)

Stateless Drawable:
	- Useful for making backgrounds that will change state. (In our chips we want the background to change for the currently selected chip)