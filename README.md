



## Extracting region of intrest within images

### RIO EXTRACTIOM.py :

First image is converted into gray scale

Then the use on Erosion, Dilation, and GaussianBlur to apply more accurite Canny

Image threshold is applied to find contours and find Bounding rectangle

Image is then cropped based on Bouding Rectangle +- 50pixles to leave some room around the images


^-- posible improvments could consist of running script 2 times first with bounding rectangle +- 100pixles then +- 20pixeles as there were around 5 images that were         bounded in the middle there for lost (bad data)


### UNITE RIO IMG SIZE.py
Simple loop to resize all the images of extracted RIO into similar sizes in respect to thier original Aspect Ratio 



^-- overall scripts can be concatinates into one file, messy repeated codes can be made into function. Possible fun idea is creat a GUI with drag and drop feature to run     all above in a simple fun manner 
