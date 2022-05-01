To run the matlab code, click the SkinDetection.mlx. Once there, choose between which network and data you want (you must uncomment the one you want and comment the rest) and then access the readAndPreprocessImage.m file and change line 14.
If you choose: 
-alexnet, change the sizing to [227 227] and change MaxEpochs in the Training Options to 10.
-vgg16 or vgg-19, change the sizing to [224 224] and change MaxEpochs in the Training Options to 5.
Afterwards, the code should run, taking anywhere between 2-80 minutes per run depending on the model chosen and the make of your computer.
*It is important to note that before you can run either network, you must download the necessary support add-on for it. An error will appear allowing you to open up the app downloader to download.*

