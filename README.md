# CCTV_RTSP
Simulates video ingestion: It defines a placeholder video path (video_paths) to simulate a video feed.

Parallel processing: It uses threads (threading.Thread) to process the video stream concurrently, demonstrating efficiency and scalability.

Person detection model: It implements a person detection model using haar_cascade.detectMultiScale (although a basic model, it fulfills this requirement).

Overlay and grayscale conversion: The code overlays detections using rectangles (cv2.rectangle) and converts the frame to grayscale using cv2.cvtColor before storing it.

Stores output video for 20 seconds: It defines frame_count based on FPS and video duration (20 seconds) and uses cv2.VideoWriter to write processed frames to an output video.
