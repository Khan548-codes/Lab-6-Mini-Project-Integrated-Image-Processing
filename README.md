# Lab-6-Mini-Project-Integrated-Image-Processing
Quick Summary of Image Processing Steps
This experiment involved a multi-step process to clean up, enhance, and extract features from a fabric image.

The Pipeline
Image Prep (Section 1): I started by loading the fabric image and converting it to grayscale. This simplified the data—going from three color channels down to one—which makes the rest of the processing faster and easier.

Noise Clean-up (Section 2): I used a median filter to remove any unwanted noise or speckles. The median filter is great because it smooths the image without blurring the important edges.

Contrast Boost (Section 3): I then used the imadjust function to enhance the contrast. This action makes the dark parts darker and the bright parts brighter, making the details in the fabric stand out more.

Feature Extraction (Section 4): To find important details, I ran the Canny edge detector. This highlighted the boundaries and structural elements of the fabric pattern.

Frequency Filtering (Section 5): As an alternative method, I also applied a low-pass filter in the frequency domain. This is a way of smoothing the image by letting the "slow" changes (low frequencies) pass through while removing the "fast" changes (high frequencies/detail).

Review (Section 6): Finally, I lined up all the versions of the image side-by-side to visually track the changes and see how each processing step affected the result.

Overall Report
The complete process successfully incorporated steps for noise reduction, contrast enhancement, and feature (edge) extraction. Every step relies on Digital Signal Processing (DSP) concepts, like using filters and transformations.

The final image looks cleaner and more detailed, which was the goal. However, to get the absolute best result, I probably need to spend more time carefully adjusting the parameters for each filter and detector.

![images](https://github.com/Khan548-codes/Lab-6-Mini-Project-Integrated-Image-Processing/blob/main/images/sss1.png)
