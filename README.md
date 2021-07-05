# Image-Processing-02

#Occlusion detection

Given are two aerial images (IMG1.png, IMG2.png) of an airport parking bay. These images were cap-
tured using two cameras placed at dierent locations and at dierent instants of time but overlooking
the same area. It is known that the images are related by an in-plane rotation and translation.
The following point correspondences are given:

Correspondence     IMG1 (x; y)     IMG2 (x; y)
     1              (29; 124)       (93; 248)
     2              (157; 372)      (328; 399)
     
Determine the changes in IMG2 with respect to IMG1.
NOTE: Use bilinear interpolation during target-to-source mapping.
NOTE: Co-ordinate convention followed to represent the above points (same as the standard Python
convention),
1. Origin (0,0) at top left corner of the image
2. x-axis = along the rows of the image
3. y-axis = along the columns of the image
