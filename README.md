IRIS Recognization System

Image Acquisition: It is the first step of the image processing and can be defined as recovering an image from some source. High-quality image acquisition techniques are used for iris recognition to make accurate models of different surfaces.
Image Preprocessing: It aimed to enhance ability to interpret quantitatively image components. It removes low-frequency noise, normalizes the intensity of individual images, and removes reflections. 
Segmentation: The accomplishment relies on upon the imaging nature of images of eye. Because of the exertion of close infrared light for enlightenment, images in the CASIA iris database do not contain specular reflections.
Normalization: The next stage after iris region segmentation is to change the iris region, so it has fixed measurements to allow comparisons. There are dimensional irregularities between eye images due to extending of iris created by pupil expansion from shifting levels of brightening. The normalization methodology will create iris regions, which have the same measurements, so two photos of the identical iris under exclusive conditions will have characteristic features at the same spatial area.
Feature Encoding and Matching: The template that is created in the feature encoding procedure will require a relating matching metric, which allow comparison between two iris templates.
Algorithm used:
Hough transform
The Hough transform is a feature extraction technique used in image analysis, computer vision, and digital image processing. The purpose of the technique is to find imperfect instances of objects within a certain class of shapes by a voting procedure.The idea of the Hough transform is, that every edge point in the edge map is transformed to all possible lines that could pass through that point. Each edge point is transformed to a line in the Hough space, and the areas where most Hough space lines intersect is interpreted as true lines in the edge map.
Daughman’s algorithm
Daugman’s algorithm is the best for recognizing iris. The algorithm has four steps such as applying Gaussian filter, initialize center and radius, Construct circle with given center and radius, Calculate the circle gradient. The important step in this algorithm is to find out the maximum gradient. Once the maximum gradient is found, the boundary becomes iris boundary.
Gabor Wavelet Transform
Gabor wavelets are used for encoding and feature extraction. The method of encoding iris patterns that is used in all current public deployments of iris recognition technology is based on a set of mathematical functions called Gabor wavelets that analyze and extract the unique texture of an iris. They encode it in terms of its phase structure at multiple scales of analysis.
![image](https://user-images.githubusercontent.com/38567191/194850742-9ec19444-7d6f-4e6e-ac81-c5fc8c051af2.png)


