# image-reader

README

exifread is a python script that accepts command line inputs, including a directory as an input. For each .tif in the directory, the script will determine the color scheme (bitonal, color, or grayscale) of the image using exif data. Any file that is not a .tif will be passed over. A .csv file will be created, listing the directories and exifdata of images with an unexpected output (error files, aka images that do not fit the color, bitonal, or grayscale criteria) and a final count of how many files fit each category (error, bitonal, color, and grayscale). The .csv will be saved wherever the directory is located. Image errors are based upon the color scheme the 'Image BitsPerSample' fits. In a case where the ImageBitsPerSample does not match any tests being run, a grayscale and color BitsPerSample always default to the other test, and a bitonal BitsPerSample defaults to the grayscale test. 

The four cmd inputs accepted are: 

The file directory (as a string, so please enter in quotes)

If you would like to test for bitonal images (Y or N. Not case sensitive.)

If you would like to test for color images (Y or N. Not case sensitive.)

If you would like to test for grayscale images (Y or N. Not case sensitive.)

An example input in the cmd would look like: exifreader.py "C:\Users\Sarah\Documents\failure test set" Y y N

This input would run only the bitonal and grayscale tests on the selected directory. 

CONTACT

If you have any problems, questions, or suggestions, please email saking3@uw.edu. 

WEBSITE

Please visit the linked github repository for updates and downloads. 
https://github.com/saking3/image-reader
