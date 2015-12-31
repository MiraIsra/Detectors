# Detectors
This is a sample to try to explain how the detectors works in opencv, this sample let us to change the detectors parameters 
and see how de detected points will be changed.

The main goal is to show you how some detectors works implanted in opencv.

For this goal I have created a software in C++ and using opencv which let see the effects to change the detector parameters.

The program has to be executed by console, you might have to build before if you don't download the mounted program, you can download already built as well. To run the code you have to open the terminal and go to the download carpet (Detectores). Once there you will be able to execute the program (./Detectors image).
The program can be executed using a parameter with the name of the image we want to detect points. You also can execute the program with your camera without adding any argument (./Detectors). In both cases the program is going to be detecting points and you will see two windows, one with the image and the other one with detectors buttons. If you choose a detector like Harris, ORB, Freak, SIFT or SURF the detection run without parameters but they also works different each other. If you choose Brisk, Star, Dense, MSer, or Simple Blob you will see one more window with the parameters of the detectors. You can modify this parameters using the track Bars and this values will be appearing in the terminal screen. Now you will be able to check the parameters of the different detectors, and see which of they have the best parameters to detect the points you want. 

To quit the program press key ‘q’ during 2 seconds (It doesn't work sometimes, so I usually press ALT+CMD+ESC to quit it).
