This Code has been modified for recognizing Indian Number Plates.
The Indian Number plate has certain constraints which can utilised different models which can be separately used to recognize the characters from the plate.
Also, it is necessary to perform pre-processing on the image in order to boost the accuracy.
Hough transform is used for skew correction.
The images are trained for 128x128 for digits dataset, first letter dataset and second letter dataset, and 96x96 for characters dataset.

This part is further merged with [ANPR for Residential Societies](https://github.com/online5/FinalYearBEProject) to create a complete django based application.
## Credit
[quangnhat185](https://github.com/quangnhat185/Plate_detect_and_recognize)
