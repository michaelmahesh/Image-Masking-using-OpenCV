# Image Masking Exercise Using OpenCV (Bitwise Operations)

## Aim

To write a Python program using OpenCV to create an image mask from a green circle image and combine it with a yellow square image using bitwise operations.

The program performs the following operations:

- Read the yellow square image and green circle image
- Convert the green circle image to grayscale
- Create a binary mask using thresholding
- Generate an inverse mask using bitwise NOT operation
- Apply bitwise AND operation to combine the images
- Display grayscale image, mask, inverse mask, and final combined image

---

## Software Used

- Anaconda – Python 3.7 or above
- Jupyter Notebook / VS Code
- OpenCV (cv2)
- NumPy
- Matplotlib

---

## Algorithm

### Step 1

Import the required libraries OpenCV, NumPy, and Matplotlib.

### Step 2

Read the yellow square image and green circle image.

### Step 3

Convert the green circle image into grayscale using `cv2.cvtColor()`.

### Step 4

Apply thresholding using `cv2.threshold()` to isolate the light gray ring and create a binary mask.

### Step 5

Generate the inverse mask using `cv2.bitwise_not()`.

### Step 6

Apply the inverse mask on the yellow square image using `cv2.bitwise_and()`.

### Step 7

Display the grayscale image, binary mask, inverse mask, and final combined image.

### Step 8

Verify that the final output contains a black ring on a yellow square background.

---

## Developed By

**Name:** ____________________________

**Register No:** _____________________

---

# Output

## Gray Scale Conversion

- Green circle image is converted into grayscale.
- The circular ring appears brighter than the background.

## Binary Mask Creation

- Thresholding isolates the ring.
- The ring appears white and the background appears black.

## Inverse Mask Creation

- The mask is inverted.
- The ring becomes black and the remaining area becomes white.

## Final Combined Image

- Bitwise AND operation is applied.
- A black circular ring is obtained on the yellow square background.


## Result

Thus, the green circle image is successfully converted into a binary mask using thresholding, and the mask is combined with the yellow square image using OpenCV bitwise operations. The desired output containing a black ring on a yellow square background is obtained successfully.
