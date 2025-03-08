# K-Means Clustering for Image Color Quantization

## Overview
This project implements the K-Means clustering algorithm from scratch and applies it to reduce the number of colors in an image. The algorithm clusters the colors in the image into `K` groups and replaces each pixel with the mean color of its assigned cluster. Additionally, the elbow method is used to determine the optimal number of clusters.

## Features
- **K-Means Clustering**: Implementation of the K-Means algorithm from scratch.
- **Image Color Reduction**: Reduction of image colors by clustering similar colors together.
- **Multiple K Values**: Experiments with K values of 2, 3, 5, 10, 15, and 20.
- **Elbow Method**: Evaluation of the optimal number of clusters by plotting the cost function for K values ranging from 1 to 25.
- **Data Visualization**: Generation of plots to visualize the elbow method and final clustered images.

## Files
- `Code.ipynb` - Jupyter Notebook containing the implementation of K-Means clustering and visualization.
- `Nature_.jpg` - Sample image used for color quantization.

## Dependencies
Ensure the following Python libraries are installed before running the code:
```bash
pip install numpy pandas matplotlib opencv-python
```

## Usage
1. Open the Jupyter Notebook `Code.ipynb`.
2. Run the cells to:
   - Load the `Nature_.jpg` image.
   - Apply K-Means clustering for different K values.
   - Visualize the color-reduced images.
   - Generate an elbow plot to find the optimal K value.

## Results
- The reduced-color images for different values of K will be displayed.
- The elbow method plot will help determine the optimal K value based on the cost function.


If you encounter any issues or have questions, please feel free to reach out for assistance. Happy coding!




