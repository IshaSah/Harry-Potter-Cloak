# Harry-Potter-Cloak
Hello Everyone,<br />
Here I have created an Invisible Cloak using an image processing technique called **Color detection and segmentation** with OpenCV. <br />
We first have to take a single color cloth that must not contain any other color. I used a green color cloth for my project. <br />
We then install openCV and implement the following steps: <br />
1.Initialize the camera.<br />
2.Capture and Store a single frame(background) before starting.<br />
3.Detect the color of the cloth and create a mask.<br />
4.Apply the mask on frames.<br />
5.Combine the masked frames together.<br />
6.Remove the unnecessary noise from masks.<br />
