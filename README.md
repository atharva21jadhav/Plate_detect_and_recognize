##Notes:
This Code has been modified for recognizing [Indian Number Plates](https://en.wikipedia.org/wiki/Vehicle_registration_plates_of_India).
The Indian Number plate has certain constraints which can utilised different models which can be separately used to recognize the characters from the plate.
Also, it is necessary to perform pre-processing on the image in order to boost the accuracy.
Hough transform is used for skew correction.
The images are trained for 128x128 for digits dataset, first letter dataset and second letter dataset, and 80x80 for characters dataset.

This part is further merged with [ANPR for Residential Societies](https://github.com/online5/FinalYearBEProject) to create a complete django based application.

## Credit
I would like to thank [quangnhat185](https://github.com/quangnhat185/Plate_detect_and_recognize) for the blogs [Part2](https://medium.com/@quangnhatnguyenle/detect-and-recognize-vehicles-license-plate-with-machine-learning-and-python-part-2-plate-de644de9849f) , [Part3](https://medium.com/@quangnhatnguyenle/detect-and-recognize-vehicles-license-plate-with-machine-learning-and-python-part-3-recognize-be2eca1a9f12).
