🗺️ K-Nearest Neighbors (KNN) Prediction on Italy Map
📘 Project Overview

This project implements the K-Nearest Neighbors (KNN) algorithm to predict missing regions on the Italy map using two different distance metrics — Euclidean and Manhattan.
The model was evaluated on partially occluded maps with varying visibility percentages of 10%, 20%, 30%, 40%, and 50% to measure the algorithm’s performance and reconstruction quality.

🧠 Key Features

Applied KNN for spatial prediction on incomplete maps.

Tested with multiple k-values: 1, 3, 5, 7, and 9.

Used Euclidean and Manhattan distance metrics for comparison.

Generated 50 output images:

25 for Euclidean Distance

25 for Manhattan Distance

Visualized predicted maps for performance comparison.

📂 Dataset

The dataset consists of partially occluded versions of the Italy map, generated with:

10% visible data

20% visible data

30% visible data

40% visible data

50% visible data

Each version was processed using different k-values.

⚙️ Methodology

Preprocessing

Loaded and normalized Italy map images.

Masked portions to simulate missing data.

KNN Implementation

Implemented KNN for image-based prediction.

Used both Euclidean and Manhattan distances.

Evaluation

Compared predicted map outputs visually.

Saved generated results for each combination of distance metric and k-value.

📊 Results

The results include a total of 50 generated images:

 like 10-euclidean-k_1.png, 

Each image represents a reconstructed map based on the corresponding k-value and percentage of visible data.

🧩 Technologies Used

Python

NumPy

scikit-learn

Matplotlib

OpenCV
