# image-reader

README

exifread is a command line tool that accepts a directory as an input, and for each .tif in the directory, will determine the color scheme (bitonal, color, or grayscale) of the image using exif data. A csv file will be written with a list of files with an unexpected output (aka, files that are not .tifs, or are not color, bitonal, or grayscale) and a final count of how many files fit each category. The .csv will be saved wherever the directory is located. 

The four cmd inputs accepted are: 
The file directory (as a string, so please enter in quotes)
If you would like to test for bitonal images (Boolean)
If you would like to test for color images (Boolean)
If you would like to test for grayscale images (Boolean)

An example input in the cmd would look like: exifreader.py "C:\Users\Sarah\Documents\failure test set" True False True

CONTACT

If you have any problems, questions, or suggestions, please email saking3@uw.edu. 

WEBSITE

Please visit the linked github repository for updates and downloads. 
https://github.com/saking3/image-reader
