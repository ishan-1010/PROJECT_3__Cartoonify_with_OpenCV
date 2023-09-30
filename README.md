# Cartoonify_with_OpenCV
Transform your ordinary images into captivating cartoons using Python and OpenCV.

## How It Works

We'll go through the following steps to achieve this:

1. **Importing the required modules**: We'll import necessary libraries for image processing, file selection, and more.

2. **Building a File Box to Choose a Particular File**: We'll create a graphical interface to select an image file.

3. **Transforming the Image to Grayscale**: The first step in creating a cartoon effect is to convert the image to grayscale.

4. **Smoothening the Grayscale Image**: We'll apply a median blur to smoothen the grayscale image.

5. **Retrieving the Edges of the Image**: We'll use adaptive thresholding to retrieve the edges of the image.

6. **Preparing a Mask Image**: We'll apply a bilateral filter to remove noise and keep the edges sharp.

7. **Giving the Cartoon Effect**: We'll combine the smoothed color image with the edges to create the cartoon effect.

8. **Plotting All the Transitions Together**: We'll display all the transformation steps together for a clear visual understanding.

9. **Saving the Cartoonified Image**: We'll provide an option to save the cartoonified image.

## How to Use

1. Run the Python script.
2. Click the "Cartoonify an Image" button to choose an image from your device.
3. Observe the step-by-step transformation of the image into a cartoon.
4. Once the transformation is complete, click the "Save cartoon image" button to save the cartoonified image.

## Dependencies

- Python 3.x
- OpenCV
- NumPy
- Imageio
- Matplotlib
- tkinter (for the graphical interface)
- PIL (Python Imaging Library)

## Working:
https://github.com/ishan-1010/PROJECT_3__Cartoonify_with_OpenCV/assets/98383932/db4e0e5b-307c-4d71-8bd4-5dd670de9819
