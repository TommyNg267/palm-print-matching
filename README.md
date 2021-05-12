# palm print matching
 - ROIextration
    - ROI (region of interest)
    - work for left hand only
    - extrat by gray scale therefore suggest to use image with black background
    - don't use image with hand rotated too much

- comparer
    -   calculate the wavenet energy features of the ROI
    -   find match by the cityblock distance of features
# dependencies
- numpy
- pyplot
- pywt
- scipy.spatial 
- cv2
