Facial landmarks detection using two ways, one with large model which has better accuracy, and another which is lightweight and fit weak devices

### 0.1 Classification vs Localization vs Detection

<font color='orange'>Classification</font> \\
<img src="https://drive.google.com/uc?export=view&id=1gTCp1gnCsOIuC3SlmBvzzpwP-XZJaOT1"
 width="200px" align="right">
Simply <font color='yellow'>**single**</font> input(single object in the image) --> <font color='yellow'>**single**</font> output \\
It should be capable of saying that this image has a cat with probability of xx.yy%, but can't say where.




<br> <br> <br> <br> <br> <br> <br>

 <font color='orange'>Detection</font> \\
 <img src="https://drive.google.com/uc?export=view&id=1L1LYG0b9lni4Fb2KGuKveH2hRhtviwvv"
 width="200px" align="right">

 Single image(Containing <font color='yellow'>**multiple**</font> objects)--> outputs <font color='yellow'>**where**</font> are these objects and <font color='yellow'>**what they are**</font>.


 <font color='orange'>Localizatoin</font> \\
By Localization we mean how put rounding boxes around the object.

 
<br> <br> <br> <br> <br> <br> <br>

### 0.3 Detection technique (Sliding window)
Slide a window over the whole image.

Notice the <font color='yellow'>**scale**</font>  effect. It will not be able to detect face from small window. \\

 <img src="https://miro.medium.com/v2/resize:fit:500/1*xueLn_y8Owl31HoNVigVdQ.gif"
 width="500px" align="right">

 To make less computations you may use <font color='yellow'>**stride**</font>, You don't have go pixel by pixel.\\

 [Image sliding window using python](https://lengyi.medium.com/image-sliding-window-using-python-a0e97d2700b4)





