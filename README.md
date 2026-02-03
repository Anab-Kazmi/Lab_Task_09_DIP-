# **Task 09: Comprehensive Color Image Processing**

**Roll Number:** 2023-SE-06

### **Prompt**

*"Write a Python program using OpenCV, NumPy, and Matplotlib to perform comprehensive color image processing. The program should:

1. Allow the user to upload any image (Colab-safe).
2. Load the image, convert it to RGB, and display both the original and grayscale versions side by side.
3. Extract and display the Red, Green, and Blue channels individually.
4. Convert the RGB image to HSV, YCbCr, and Lab color spaces and display each color space.
5. Apply white balance correction using the Gray World assumption and display the corrected image alongside the original.
6. Perform color masking to isolate a specific color (e.g., green) using the HSV color space, and display the original, the mask, and the masked image.
7. Perform simple segmentation on the Lab 'a' channel using thresholding, and display the original image, the HSV masked image, and the Lab 'a' channel segmented image side by side.
8. Ensure all plots are properly labeled, with axes turned off, and figures sized appropriately for clear visualization."*

---

## **Objective**

The objective of this task is to perform **comprehensive color image analysis** including: channel extraction, color space conversion, white balance correction, color masking, and simple segmentation using the Lab color space. This demonstrates a range of common color image processing techniques.

---

## **Methodology / Approach**

1. Upload a color image in Google Colab and display it along with its grayscale version.
2. Extract **Red, Green, and Blue channels** and display them separately for analysis of intensity in each channel.
3. Convert the RGB image into **HSV, YCbCr, and Lab** color spaces to observe color representations in different models.
4. Apply **white balance correction** using the Gray World assumption to adjust color balance and display corrected image.
5. Perform **color masking** to isolate a specific color (green) in HSV space, and display the mask and masked image.
6. Perform **simple segmentation** on the Lab 'a' channel using thresholding to identify specific color components.
7. Display all results with proper titles, layout, and axes turned off for clear visualization.

---

## **Results / Observations**

* **Original vs Grayscale:** Grayscale highlights intensity variations, while RGB shows full color information.
* **RGB Channels:** Individual channels reveal the intensity distribution for Red, Green, and Blue separately.
* **Color Spaces:**

  * HSV separates hue, saturation, and value for better color analysis.
  * YCbCr separates luminance and chrominance components, useful in compression and enhancement.
  * Lab separates perceptual lightness and color-opponent channels (a, b) for segmentation.
* **White Balance Correction:** Gray World assumption balances the color intensities for a natural look.
* **Color Masking:** Successfully isolates green regions in the image.
* **Lab 'a' Channel Segmentation:** Thresholding effectively highlights regions corresponding to specific color ranges.
* Overall, these techniques demonstrate multiple approaches for **color analysis, correction, and segmentation** in images.

---

## **Tools and Libraries Used**

* **Python 3.x**
* **OpenCV (cv2):** Image reading, color conversion, channel extraction, thresholding
* **NumPy (np):** Array operations and calculations for white balance
* **Matplotlib (plt):** Visualization of images and color channels
* **Google Colab:** Image upload and execution environment

---
