# Traffic-monitoring-system-using-Computer-Vision

 # 1. Video Data Preprocessing
Annotation: Labeled road users in the video data for supervised learning.
Fragmentation into frames: Converted video sequences into individual frames to facilitate frame-by-frame analysis.
# 2. Feature Extraction
Scale-Invariant Feature Transform (SIFT): Extracted key features from the images that remain stable under scale, rotation, and translation.
Pixel Values: Utilized raw pixel values as an additional set of features for more detailed analysis.
# 3. Image Representation
K-Means Clustering: Grouped similar image features into clusters, creating "visual words" to form a vocabulary for image representation (Bag of Visual Words).
# 4. Machine Learning Models
K-Nearest Neighbors (KNN): Applied KNN for classification, where it showed strong performance.
AdaBoost Ensemble Model:
Combined three classifiers: Random Forest, Support Vector Machine (SVM), and KNN to enhance overall model performance.
# 5. Evaluation and Metrics
Accuracy: Assessed the correctness of predictions across the dataset.
Area Under the Curve (AUC): Measured the classifier’s ability to distinguish between classes, providing insight into the model’s performance.
# 6. Contribution to Traffic Monitoring
Improved the understanding and application of traditional machine learning methods in the context of road user detection and traffic monitoring.
