## Cataloging information regarding Point Cloud Alignment

### Research Papers

Older paper , least square fitting of two 3-D point sets, predates ICP, gives good intuition for the matrix transformations :  
http://post.queensu.ca/~sdb2/PAPERS/PAMI-3DLS-1987.pdf

More modern note for explaining above algorithm :  
https://igl.ethz.ch/projects/ARAP/svd_rot.pdf

Blogpost on aligning 3d points - A gentle introduction to above topic :  
http://nghiaho.com/?page_id=671

Slides on ICP :  
https://cs.gmu.edu/~kosecka/cs685/cs685-icp.pdf

The original paper introducing ICP (not sure when ICP originated) :  
http://www-evasion.inrialpes.fr/people/Franck.Hetroy/Teaching/ProjetsImage/2007/Bib/besl_mckay-pami1992.pdf

Compares variants of the ICP algorithm :  
http://www.pcl-users.org/file/n4037867/Rusinkiewicz_Effcient_Variants_of_ICP.pdf

Alternative to two stage ICP , 1 step Global Registration (implemented in Intel library):  
http://vladlen.info/papers/fast-global-registration.pdf

Older Paper on Global Registration :  
https://graphics.stanford.edu/~smr/ICP/comparison/chen-medioni-align-rob91.pdf

### Software Libraries

From Intel, has Python bindings, ICP , Global Registration, Sampling of Points, kd-tree :  
http://www.open3d.org/docs/release/introduction.html

From ETH-Zuric, Permissive BSD (C++) :   
https://github.com/ethz-asl/libpointmatcher

From pointclouds.org, Lots of corporations backing it, BSD (Free for commerical and academic use) (C++) :  
https://github.com/PointCloudLibrary/pcl/


### Code Examples
How to apply matrix transformations to point clouds from libpointmatcher :  
https://libpointmatcher.readthedocs.io/en/latest/Transformations/

How to use ICP from pointclouds.org :  
http://pointclouds.org/documentation/tutorials/iterative_closest_point.php

Python ICP implementation from random guy on the internet, seems popular, very readable :    
https://github.com/ClayFlannigan/icp
