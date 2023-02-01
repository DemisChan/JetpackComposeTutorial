# JetpackComposeTutorial
The Learn Together app displays a list of articles about several Jetpack libraries. Users can choose the topic of their choice and learn about its latest developments.
## Compose Article
In this exercise, you build a screen for the app, which displays a tutorial for Jetpack Compose. You use the image and string resources provided in the Resources section for this problem.

### Final Screenshot
After you finish the implementation, your design should match this screenshot:

<img src="./app/src/main/res/drawable-nodpi/screenshot.png" style="width:300px;"/>

**UI specifications**

Follow this UI specification:

<img src="./app/src/main/res/drawable-nodpi/screenshot2.png" style="width:400px;"/>

* Set the image to fill the entire screen's width.
* Set the first **Text** composable to a **24sp** font size and **16dp** padding (start, end, bottom, and top).
* Set the second **Text** composable to a default font size, **16dp** padding(start and end), and Justify text align.
* Set the third **Text** composable to a default font size, **16dp** padding (start, end, bottom, and top), and Justify text align.

**Resources**

* Jetpack Compose tutorial
Jetpack Compose is a modern toolkit for building native Android UI. Compose simplifies and accelerates UI development on Android with less code, 
powerful tools, and intuitive Kotlin APIs.

* In this tutorial, you build a simple UI component with declarative functions. You call Compose functions to say what elements you want and the Compose 
compiler does the rest. Compose is built around Composable functions. These functions let you define your app\'s UI programmatically because they let 
you describe how it should look and provide data dependencies, rather than focus on the process of the UI\'s construction, such as initializing an 
element and then attaching it to a parent. To create a Composable function, you add the @Composable annotation to the function name.
