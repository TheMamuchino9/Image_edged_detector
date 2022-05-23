# Edges visualization service.

In this project I developed an API that take an image and 2 parameters as inputs and visualize the edges of the image.

To do that, I implemented the Canny algorithm, that is available on OpenCV, and designed this user interface in HTML/CSS: 

![image](https://user-images.githubusercontent.com/86535567/169723679-dcf91a7f-4a3f-4f10-b51e-8220cd5e96f8.png)


Where "Min value" and "Max value" are inputs for the canny algorithm thresholds, the function of these thresholds are explained [here](https://docs.opencv.org/4.x/da/d22/tutorial_py_canny.html) 

"These thresholds control if any edges with intensity gradient more than maxVal are sure to be edges and those below minVal are sure to be non-edges, so discarded. Those who lie between these two thresholds are classified edges or non-edges based on their connectivity. If they are connected to "sure-edge" pixels, they are considered to be part of edges. Otherwise, they are also discarded."

For an input image: 

![image](https://user-images.githubusercontent.com/86535567/169723974-6e43f8fa-9782-4c06-8ec7-a59b1a0295fa.png)

The Canny algorithm finds the edges: 

![image](https://user-images.githubusercontent.com/86535567/169724239-3cfa7799-16a9-42c0-b903-249818338086.png)

Combining the images: 

![image](https://user-images.githubusercontent.com/86535567/169724445-9c3d935e-ef72-4091-83d6-b13531669838.png)


The frontend allows the user to see the results like this: 

![image](https://user-images.githubusercontent.com/86535567/169724482-130e3de3-07bf-4e8a-b5a4-bbabf59ee62f.png)



