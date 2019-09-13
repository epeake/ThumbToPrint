# thumb_to_print

As part of a larger image processing project where we developed an app to takes images of thumbs from an iphone and convert them into fingerprint images.  The algorithm takes advantage of fingerprints' high spatial frequencies to create a mask around the thumb region, then uses local threshilding to extract the ridges and valleys of the thumb.

See example below!

Original Photo                                                                        |  Extracted Print
:------------------------------------------------------------------------------------:|:-------------------------:
![Before](https://github.com/epeake/image_to_prints/blob/master/examples/finger.png)  |  ![After](https://github.com/epeake/image_to_prints/blob/master/examples/print.png)

