BaggageAI_CV_Hiring_Assignment
Packages used:
1.OpenCV
2.PIL
3.Imutils
4.Numpy

Explaination:
1.All images from threat_images are been uploaded to image_list.
2.Masking is used to make threat image translucent with transparency of 60% and saved in paste_mask.
3.Saving the size(Height) of image in images_list.
4.By using imutils scaled down the height of threat image and rotate at the angle of 45 degrees and saved to resized folder.
5.Doing same process on masked_images and saved in resized_mask folder.
6.Overlapping threat image on background images while choosing a position that remains inside the boundaries of background image.

Attachments:

a) paste_mask = Transperant images

b) resized = rotated and resized threat images

c) resized_mask = rotated and resized masked images

d) Output = output images