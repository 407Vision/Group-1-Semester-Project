# Group-1-Semester-Project




# Image Filtering Techniques
# Group 1

## 1. Implementing and Comparing Basic Image Filters
Objective:
This task focuses on implementing basic image filters for noise reduction and edge enhancement. The primary goals are:

## Apply smoothing filters: Mean and Median filters.
Apply sharpening filters to enhance edges.
Compare the results for images affected by different noise types, such as Gaussian noise and Salt-and-Pepper noise.
Libraries Used
OpenCV: For image processing operations.
NumPy: For numerical computations.

## Adding Noise:

Gaussian Noise: Simulated using random values from a normal distribution.
Salt-and-Pepper Noise: Simulated by randomly setting pixels to maximum (salt) or minimum (pepper) intensity.

## Applying Filters:

Mean Filter: Reduces overall noise by averaging pixel intensities in a neighborhood.
Median Filter: Reduces noise by replacing each pixel with the median value of its neighborhood, effective for Salt-and-Pepper noise.
Sharpening Filter: Enhances edges by emphasizing intensity differences.
Comparing Results:

The filters are applied to noisy images to observe their effectiveness in noise reduction and edge preservation.
Outcome
By completing this task, you'll understand:

The role of smoothing filters in noise reduction.
The trade-offs between noise removal and edge blurring.
How sharpening filters enhance edges but may amplify noise.
