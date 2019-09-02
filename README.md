# crown-volume
codes for crown-volume calculation with SfM point clouds including convex hull and alpha shape algorithms, using
the Alphashape3D (Lafarge and Pateiro-Lopez 2014) and rLiDAR (chullLiDAR2D, Silva et al. 2017) packages. In convex hull, it constructs an envelope by considering the number of input points belongs to the convex hull to represent the outward curving shape of tree crowns. In the alpha shape approach, a predefined and reduced alpha value serves as size criterion to construct more details, thus shrinking the corresponding convex hull closer down to the 3D point cloud (Pateiro-Lopez and Rodriguez-Casal 2010; Colaço et al. 2017). I calculated the crown volumes for both trees and oil palms with a convex hull algorithm and alpha shape algorithms, the latter using the alpha values 0.75, 0.50 and 0.25. You can find more information and usages of this parameter in this article;

Drone-based photogrammetry derived crown metrics for predicting tree and oil palm water use
https://doi.org/10.1002/eco.2115
Joyson Ahongshangbam*, Watit Khokthong*, Florian Ellsäßer, Hendrayanto, Dirk Hölscher, Alexander Röll
 *authors contributed equalliy to the manuscript

References of codes;
Colaço, A. F., Trevisan, R. G., Molin, J. P., Rosell-Polo, J. R., & Escolà, A. 2017. A method to obtain orange crop geometry information using a mobile terrestrial laser scanner and 3D modeling. Remote Sensing 9(8): 10–13.

Lafarge, T., & Pateiro-Lopez, B. 2014. Alphashape3d: Implementation of the 3D Alpha-Shape for the Reconstruction of 3D Sets from a Point Cloud. R package version.

Silva, C. A., Crookston, N. L., Hudak, A. T., Vierling, L. A., Klauberg, C., & Silva, M. C. A. 2017. Package ‘rLiDAR.’

Pateiro-López, B., & Rodrıguez-Casal, A. 2010. Generalizing the convex hull of a sample: the R package alphahull. Journal of Statistical Software 34(5): 1–28.

