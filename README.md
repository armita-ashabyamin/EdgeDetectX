# EdgeDetectX
This project explores and compares various edge detection algorithms using OpenCV and Python. It includes implementations of Sobel, Enhanced Sobel, Canny, Marr-Hildreth (Laplacian), and Hough Circle Transform techniques on multiple input images. The results are visualized using Matplotlib to highlight the effectiveness of each method.


# Edge Detection Algorithms in OpenCV

This project demonstrates the application of several edge detection techniques using Python and OpenCV. It includes preprocessing steps, grayscale conversion, blurring, and visualization of results for multiple input images.

## 📂 Features

- Grayscale conversion using `cv2.cvtColor`
- Image blurring with Gaussian kernel
- Sobel edge detection (X, Y, and combined)
- Enhanced Sobel using `convertScaleAbs` and weighted addition
- Canny edge detection with multiple threshold combinations
- Marr-Hildreth edge detection via Laplacian operator
- Hough Circle Transform for detecting circular shapes

## 🛠 Requirements

- Python 3.x
- OpenCV (`cv2`)
- NumPy
- Matplotlib
- Google Colab (optional for cloud execution)

## 📸 Input

Images are read from Google Drive using:
```python
img1 = cv.imread('/content/drive/My Drive/IMG1.jpg', cv.IMREAD_COLOR)
📊 Output
Each algorithm's result is visualized using Matplotlib:

python
plt.imshow(img1_canny, cmap='gray')
plt.title('Canny Edge Detection')
plt.show()
🚀 How to Run
Clone the repository or open the notebook in Google Colab.

Mount your Google Drive and ensure image paths are correct.

Run each cell to process and visualize edge detection results.

👩‍💻 Author
Armita Ashabyamin Under the supervision of Professor Khosravi

Code

Would you like me to help you turn this into a GitHub project structure or add example images and outputs?
