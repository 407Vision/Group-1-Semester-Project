# Group-1-Semester-Project


# Image Filtering Techniques
# Group 1
# 1. Implementing and Comparing Basic Image Filters
## Objective
This task focuses on implementing basic image filters for noise reduction and edge enhancement. The primary goals are:

1. Apply smoothing filters: Mean and Median filters.
   
3. Apply sharpening filters to enhance edges.
   
5. Compare the results for images affected by different noise types, such as Gaussian noise and Salt-and-Pepper noise.

## Libraries Used:
OpenCV: For image processing operations.

NumPy: For numerical computations.

#Steps
## Adding Noise:

1. Gaussian Noise: Simulated using random values from a normal distribution.
 
3. Salt-and-Pepper Noise: Simulated by randomly setting pixels to maximum (salt) or minimum (pepper) intensity.

## Applying Filters:

Mean Filter: Reduces overall noise by averaging pixel intensities in a neighborhood.

Median Filter: Reduces noise by replacing each pixel with the median value of its neighborhood, effective for Salt-and-Pepper noise.

Sharpening Filter: Enhances edges by emphasizing intensity differences.

## Comparing Results:

The filters are applied to noisy images to observe their effectiveness in noise reduction and edge preservation.

## Key Insights

### Effectiveness of Filters:

Mean Filter: Smoothens the image but may blur edges.

Median Filter: Highly effective for reducing Salt-and-Pepper noise while preserving edges.

Sharpening Filter: Enhances edges and fine details but may increase noise visibility.

## Noise Handling:

Gaussian noise is better handled by smoothing filters.

Median filters perform well against Salt-and-Pepper noise due to their resilience against outliers.
