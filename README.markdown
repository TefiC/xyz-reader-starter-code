## XYZ Reader - Udacity ADND Project 5 

##### Udacity Android Developer Nanodegree

## Features

- For this project I took a functional app that didn't follow Material Design Guidelines and redesigned it following Material Design Guidelines.

##### Article List

- Included an AppBarLayout with a CollapsingToolbarLayout to display the app's logo.
- Placed the articles on a single surface since the content was homogeneous and therefore should be presented on the same surface for a better UX on scroll.
- The landscape layout optimizes the blank space on the screen by increasing the size of the images.
- On larger devices, the list is displayed in two columns.
- Added a divider for the RecyclerView items.

##### Article Details

- Resized article image to full width and a fixed height.
- Added two scrims on top of the main article image: 
     - One at the top to guarantee that the white up button will always be visible.
     - One at the bottom to create a transition between the view below and the image.
- Centered the article's title, author and date for a better presentation
- Set a default font family for better consistency and UX.
- The article's body has a max width that will not be exceeded on larger devices.
- Added a landscape layout that utilizes the blank space on the screen by repositioning the image to the left and the title, author, date and body to the right.
- Replaced an ImageButton for a FloatingActionButton provided by the Design Support Library with the correct elevation and dimensions that scale according to the device width ("mini" FloatingActionButton for devices with width less than 460dp and "normal" for devices wider that 460dp).
       - The button's size will change on rotation according to the criteria listed above, following Material Design Guidelines
- Added an icon from [materialdesignicons.com](https://materialdesignicons.com/) to the Floating Action Button.

##### Transitions

- Added a "fade" transition when the user launches the article details activity.

##### Widgets

- When there is no internet connection, a **SnackBar** will warn the user and the articles list will be hidden.

## Attributions

These resources were very helpful during my project:

- [Toolbar Implementation](http://www.codexpedia.com/android/android-actionbar-vs-toolbar/)
- [RecyclerView dividers 1](https://proandroiddev.com/itemdecoration-in-android-e18a0692d848)
- [RecyclerView dividers 2](https://medium.com/@szholdiyarov/how-to-add-divider-to-list-and-recycler-views-858344450401)
- [Coordinator Layout](https://guides.codepath.com/android/handling-scrolls-with-coordinatorlayout)
- [SnackBar](https://www.androidhive.info/2015/09/android-material-design-snackbar-example/)
- [Transition Animations 1](http://lgvalle.xyz/2015/06/07/material-animations/)
- [Transition Animations 2](https://github.com/lgvalle/Material-Animations)
- [Code to check if there is internet connection available](https://stackoverflow.com/questions/4238921/detect-whether-there-is-an-internet-connection-available-on-android)
- [Change SnackBar color 1](https://stackoverflow.com/questions/34020891/how-to-change-background-color-of-the-snackbar)
- [Change SnackBar color 2](https://stackoverflow.com/questions/31590714/getcolorint-id-deprecated-on-android-6-0-marshmallow-api-23)
- [Reusing Layout with the "include" tag](http://hackjutsu.com/2015/10/19/Android%20reusing%20include%20tag/)

<br>

