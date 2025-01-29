# Video-compression algorithm for CCTV videographs
The Main.ipynb file contains the compression code along with its PSNR and SSIM calculation. The code is also commented for the best understanding.
The Evaluation.ipynb file contains source code for encoding the data set videos using XVID and H.264 codecs and then its PSNR and SSIM value calculation.
Data Set: This folder contains the video used for testing algorithm
H.264: This folder contains the dat set videos encoded through H.264 codec
XVID: This folder contains the dat set videos encoded through H.264 codec
Dependencies:
To calculate the PSNR and SSIM value scikit-image library is required. To install it use the following command.
->	pip install scikit-image
For other operation the required dependencies are below;
-> pip install numpy
-> pip install opencv-python

A research article based on this compression approach is submitted to a research journal. The details of the article is mentioned below
“Optimizing H.264 Codec for Efficient CCTV Video Compression via Inter-frame Redundancy Reduction”. The visual computer journal.


