# iiith-image-super-scaler-resolution
Monsoon 2017: PGSSP Team 11

Steps for Executing SRCNN.py

Download SRCNN.py, train.zip, test.zip, and val.zip in local folder.
Extract train.zip, test.zip and val.zip in train, test and val folders respectively.
Use python 2.7.14
Install all dependent packages Keras, scipy, numpy, os, timeit, cv2.
Open terminal/command prompt and navigate to above download folder.
Execute command "python SRCNN.py"
Execution will take maximum 30 mins.
test folder will contain inuput low resolution images, bicubic images and predicted images.
Best PSNR achieved will be reported at the end of execution.
Steps for Executing SRKNN.py

Download SRKNN.py, train.zip and test.zip, in local folder.
Extract train.zip and test.zip in train, test folders respectively.
Use python 3.6.1
Install all dependent packages sklearn, scipy, numpy, os, matplotlib.
Open terminal/command prompt and navigate to above download folder.
Execute command "python SRKNN.py "
Execution will take less than 5 mins.
Input high resolution, reconstructed image and blurred input images are saved in the output folder path given in the command line prompt.
PSNR will be reported on the console after every image reconstruction is completed in the test folder given in the command line prompt.
