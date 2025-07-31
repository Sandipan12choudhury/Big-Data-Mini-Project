**Project Description**
This project showcases two essential data processing tasks executed within a single Google Colab notebook — combining the power of Big Data and Computer Vision using Python.

***Task 1***: Word Frequency Analysis using PySpark
In this task, a user-uploaded text file is analyzed to compute the frequency of every word it contains. By leveraging Apache Spark's parallel data processing capabilities (PySpark), the program efficiently reads the file, tokenizes the text into words, and aggregates word counts. This simulates a scalable solution suitable for processing large text datasets.

Key Steps:

Upload a .txt file from the local system.

Load it into Spark as an RDD.

Use transformations (flatMap, map, reduceByKey) to count words.

Display the word-frequency result.

This approach demonstrates the power of distributed computing, even within a local or Colab environment, and mimics real-world big data word count applications like log analysis, search indexing, or NLP preprocessing.

***Task 2***: Motion Detection in Video using OpenCV
In the second task, the project focuses on analyzing a user-uploaded video to detect motion. The program extracts frames from the video using OpenCV, applies grayscale conversion, blurring, and thresholding, and then identifies regions with motion using contour detection. Bounding boxes are drawn around moving objects to highlight them.

Key Steps:

Upload a .mp4 video file.

Extract all frames using cv2.VideoCapture.

Convert each frame to grayscale, apply Gaussian blur, and detect movement.

Draw rectangles around detected moving regions.

Save processed frames and compress them into a downloadable .zip archive.

This demonstrates a practical use of basic computer vision techniques for motion analysis, which could be extended into security systems, gesture recognition, or video analytics.

***Summary*** :
Together, these two tasks offer a cross-domain learning experience:

Big Data (Task 1): Processing and analyzing large-scale unstructured text.

Computer Vision (Task 2): Real-time video frame analysis and motion detection.

Both tasks are implemented in separate sections of a single Colab notebook, with interactive file uploads, automated processing, and downloadable outputs — making it an ideal educational or prototype-level project.

