# BarCode-detector
The main library used in this project was Pybzar(‘https://pypi.org/project/pyzbar/’) . Using it we can detect not only barcodes but also QrCodes and other types of code.
For simplitcity and easy detection of these codes from images I converted colorful (RGB) image into Black and White (and it detected 1-2 more codes when I did this). 
Other that this I tried  to shrink the size of the image but it did not improve the results.

One more approach which can be used is that writing our own/pre-trained neural network for barcode detection (Link ‘https://www3.hs-albsig.de/wordpress/point2pointmotion/2021/02/05/barcode-detection-with-a-neural-network/’)
