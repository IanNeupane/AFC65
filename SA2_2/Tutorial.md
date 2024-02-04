# Process and Display Image

In this activity, you will learn to process an image, by converting it into an oil painting and then display it on the screen.

<img src= "https://s3.amazonaws.com/media-p.slid.es/uploads/1525749/images/10475811/oilpaint.png" width = "480" height = "320">

Follow the given steps to complete this activity:

1. Apply the oil painting effect

- Open the file main.py.
- Declare a variable `oilImg`.
- Use the function `cv2.xphoto.oilPainting()` and pass `originalImage`, `size=7`, `dynRatio=1` as parameter to the function.
- Set this function as the value to the `oilImg` varaible.

  `oilImg = cv2.xphoto.oilPainting(originalImage, size=7, dynRatio=1)`

- Use the `cv2.imshow()` function and pass the window title `Oil Paint Image` and the variable `oilImg` to display the oil painting.

  `cv2.imshow('Oil Paint Image', oilImg)`

- Use the `cv2.waitKey(0)` function to set the`esc` key to close the image window.

  `cv2.waitKey(0)`

- Save and run the code to check the output.
