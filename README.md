# README: K-Means Clustering from Scratch

# Summary:
This Python script implements K-Means clustering from scratch using NumPy and Matplotlib. It initializes random cluster centers, assigns data points to the nearest cluster using Euclidean distance, updates cluster centers iteratively, and visualizes the final clustered data.

# Steps:
1. Generate a synthetic dataset using `make_blobs()`.
2. Initialize `k` cluster centers randomly.
3. Assign each data point to the nearest cluster center based on Euclidean distance.
4. Update cluster centers by computing the mean of assigned points.
5. Repeat steps 3 and 4 until cluster centers stabilize.
6. Predict and visualize the final clusters.

# Example Output:
Initial Dataset Scatter Plot:
(Displays randomly generated data points)

Randomly Initialized Cluster Centers:
(Scatter plot with initial centroids)

Final Clustered Data:
(Scatter plot with points colored by cluster and final centroids marked)

# Dependencies:
- NumPy
- Matplotlib
- Scikit-learn

# Installation:
Run the following command to install dependencies:
pip install numpy matplotlib scikit-learn

# Running the Script:
Execute the script with:
python kmeans.py

# Notes:
- The number of clusters (`k=3`) can be modified in the script.
- Random seed ensures reproducibility.

# Results:
- <img width="373" alt="image" src="https://github.com/user-attachments/assets/1c8e77a9-ec0e-4fb1-a9da-38d89a92faf4" />
- <img width="373" alt="image" src="https://github.com/user-attachments/assets/78820ed2-3d41-42eb-ae46-42be39c3ed46" />
- <img width="375" alt="image" src="https://github.com/user-attachments/assets/a642645a-7b1d-4629-9b49-703aa578f2d7" />
- <img width="375" alt="image" src="https://github.com/user-attachments/assets/2564f29d-d03d-44d5-8c98-9110692b116c" />
- <img width="375" alt="image" src="https://github.com/user-attachments/assets/c9dfa8e5-a66a-4bef-bc6f-efdeff30a5db" />

## Author
Developed by Jeremy Martinez-Quinones.

## License
This project is licensed under the MIT License - see LICENSE file for details.

