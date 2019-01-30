

#1 Pinning to the edges

First way to position UI element so that it has the same spacing (manually set of course) to top/botttom/left/right edges of the main UIView across all iOS devices irrelevant of the orientation.

Shortcoming of this method is that the object doesn't scale! So if you need to preserve the size you have to use the second method

![capture d ecran 2019-01-30 a 19 39 18](https://user-images.githubusercontent.com/47090408/51996931-cfcdb400-24c6-11e9-9490-6d79e9dd73a8.png)


#2 Alignment mnethod

Alignment allows for the UI object to have the same size across all screen sizes the app is viewed from.
To do that, you have to position UI element vertically and horizontally within another UIView (hierarchy shoudl be parent>chidlren relationship where UI element acts as childer and UIView acts as the parent).

To illustrate, please refer to the image:

![capture d ecran 2019-01-30 a 19 39 30](https://user-images.githubusercontent.com/47090408/51997935-c9d8d280-24c8-11e9-909f-be6ad08c24f9.png)


