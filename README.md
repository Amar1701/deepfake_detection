# deepfake_detection
We've created a DeepFake Detection system which intends to detect DeepFake videos using Deep Learning techniques like ResNext and LSTM.In this code, we've integrated Intel OneAPI ONEDAL for PCA preprocessing by using its PCA implementation. Additionally, we've imported tbb for potential parallel processing tasks.
In this code, we've integrated Intel OneAPI ONEDAL for PCA preprocessing by using its PCA implementation. Additionally, we've imported tbb for potential parallel processing tasks. 

# Datasets
We've trained our model on a benchmark dataset called Celeb-DF dataset, which includes 590 original videos collected from YouTube with subjects of different ages, ethic groups and genders, and 5639 corresponding DeepFake videos.

# Dataset Structure
Celeb-DF
|--- Celeb-real # 590 Celebrity videos downloaded from YouTube
|--- YouTube-real # 300 Additional videos downloaded from YouTube
|--- Celeb-synthesis # 5639 Synthesized videos from Celeb-real
|--- List_of_testing_videos.txt # 518 videos

# AcceleratedDeep FakeDetection
Utilizing Intel® oneAPI:oneDAL, our Deep Learning Model is trained efficiently, ensuringaccurate detection of deepfakes with high confidence.
