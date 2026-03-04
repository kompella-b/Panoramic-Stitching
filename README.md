# Homography Estimation and Image Stitching
This project demonstrates how to compute and apply homographies for image warping, image replacement, and panorama creation.  
First, a homography matrix is computed using four manually selected point correspondences to warp a source image onto a planar region in another image (e.g., replacing a picture on a wall). The homography is implemented from scratch to understand the underlying mathematics.Next, additional point correspondences are used to form an overconstrained system, and the homography is recomputed using least-squares.  
The results are compared with the four-point solution to observe differences in alignment and stability.  
Finally, multiple overlapping images are stitched together into a mosaic by computing homographies between images and blending them into a panorama.  
**Tools:** Python, NumPy, OpenCV, Matplotlib
