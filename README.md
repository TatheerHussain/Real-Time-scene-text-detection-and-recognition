# Real-Time-scene-text-detection-and-recognition
This project presents real-time both EAST text detection and OCR text recognition with OpenCV, Python, and Tesseract. Experimental results show the analysis of EAST text detection with OCR text recognition. We adopted EAST with rotated rectangle geometry combine with tesseract and OpenCV on our real-time scene text detector. The method can detect words or words correctly and gives acceptable results for recognition while running at an average speed 3fps


# USAGE
Real time video text detection and recognition
python text_detection_recognition_video.py --east frozen_east_text_detection.pb

Text detection and recognition
python text_detection_recognition.py --image [image_path] --east frozen_east_text_detection.pb

Press Q to stop running
