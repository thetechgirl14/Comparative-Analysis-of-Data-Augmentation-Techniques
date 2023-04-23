# Comparative-Analysis-of-Data-Augmentation-Techniques
This Project was done as a part of graduate course MATH7302 Numerical Analysis by Abhilasha Jain

Introduction: In computer vision, data augmentation techniques are widely used to increase the size of the training dataset by generating new examples through transformations of the original images. These techniques are essential to improve the generalization of the models and to avoid overfitting. One of the most common ways to perform data augmentation is by using interpolation methods, which are used to fill the gaps when images are resized.  

Objective: The objective of this project is to perform a comparative analysis of data augmentation techniques using different interpolation methods and computing Mean Squared Error (MSE), Peak Signal-to-Noise Ratio (PSNR), and Structural Similarity Index (SSIM) for them. After computing these metrics, statistical analysis will be performed to determine which technique and interpolation method is the best in terms of performance.

Methodology:

The project will be divided into the following steps:

1. Dataset Preparation: The first step will be to prepare the dataset by selecting a suitable image dataset and dividing it into training and testing sets.
2. Data Augmentation: The second step will be to apply different data augmentation techniques, including rotation, flipping, zooming, and translation, using different interpolation methods such as nearest-neighbor, bilinear, bicubic, and Lanczos. This will generate a new set of images for the training dataset.
3. Metric Calculation: The third step will be to calculate the metrics of interest (MSE, PSNR, and SSIM) for each technique and interpolation method using the augmented training dataset.
4. Statistical Analysis: The final step will be to perform statistical analysis to determine which technique and interpolation method is the best in terms of performance. This will involve comparing the means of the metrics for each technique and interpolation method using analysis of variance (ANOVA) and Tukey's Honest Significant Differences (HSD) test.

Conclusion:
1. Based on the t-test results, it can be concluded that there are significant differences between the different interpolation methods.
2. For PSNR, it is seen that all method pairs have very small p-values, indicating that the differences in PSNR values between the methods are statistically significant. The t-values are also quite high for most pairs, indicating a large difference in PSNR values.
3. For SSIM, it shows the same pattern as PSNR, with all pairs having small p-values and high t-values, indicating significant differences.
4. For MSE, a similar pattern can be seen, with all pairs having small p-values and some pairs having high t-values.
5. Based on these results, it can be concluded that different interpolation methods do have a significant effect on the quality of the image, as measured by PSNR, SSIM, and MSE. Therefore, the choice of interpolation method should be carefully considered based on the specific needs of the task.
