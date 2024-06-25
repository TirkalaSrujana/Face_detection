# Face_detection
# Working
Imports: Loads necessary libraries: OpenCV for computer vision tasks and cv2_imshow for image display (specifically in Google Colab).
Face Detection Model: Loads a pre-trained cascade classifier for face detection.
Image Loading: Reads the image from a specified path.
Grayscale Conversion: Converts the image from color (likely BGR) to grayscale for better face detection.
Face Detection: Uses the loaded model to detect faces in the grayscale image, specifying parameters like scaling and minimum face size.
Bounding Boxes: Stores the detected faces as bounding boxes (coordinates for location and size) in a list.
Visualization: Iterates through detected faces and draws green rectangles around them on the original color image.
Display: Shows the image with rectangles using cv2_imshow.
User Interaction: Waits for a key press to close the image window.
Cleanup: Closes any open OpenCV windows.
Overall, this code effectively detects and visualizes human faces in a given image using OpenCV's pre-trained model and computer vision techniques.
