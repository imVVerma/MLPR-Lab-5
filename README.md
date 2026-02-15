## Aim

- Detect faces from an image
- Extract colour based features from detected faces
- Group faces into clusters using KMeans
- Predict which cluster a new template face belongs to
- Visualize clusters, centroids, and classification results


## Methodology

### Step 1: Face Detection (Plaksha Faculty)

Detected faculty faces using Haar Cascade and enclosed each face within a bounding box.

**Output**


### Step 2: K Means Clustering

The plot shows KMeans clustering of detected faces based on their average Hue and Saturation values in HSV colour space.

**Output**


### Step 3: Clusters with Centroids

This plot visualizes the clustered faces in Hue–Saturation space along with their corresponding centroids representing the center of each group.

**Output**


### Step 4: Template Face Detection

This output shows the detected face in the template image highlighted with a bounding box using the Haar cascade face detector.

**Output**


### Step 5: Dr. Shashi Tharoor’s Cluster Prediction

This plot shows the predicted cluster of the template face by placing it in the Hue–Saturation feature space alongside previously clustered faces.

**Output**


### Step 6: Final Cluster Visualization with Template Class

This visualization displays both clusters with their centroids and highlights the template face to show its final cluster assignment in the Hue–Saturation feature space.

**Output**


## Conclusion

- HSV colour features can be used for simple face grouping
- KMeans effectively clusters faces based on colour characteristics
- A new face can be classified by comparing its feature values with learned cluster centroids
- Visualization helps in clearly understanding clustering behaviour and classification results
