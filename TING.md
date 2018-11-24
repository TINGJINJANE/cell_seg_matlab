I have some questions about this paper. 

In the following, I would summarize my points towards the pipeline and practical algorithm implementation.

##### 1. Shpae representation

a) 27000 shape priors to cover the complex shape variation observed in most histopathology images. Shape priors are annotated manually and alligned by the **generated Procrustes algorithm**. 

b) These shapes are clusted with spectral clustering algorithm into *M* clusters and then calculated the average shape of each cluster is couputed. 

c) Aligned each cell contour using scale, rotation, translation. 

d) After mapping all the cell to the shape prior set.  Assuming that cell with associated distance map function can be approximately represented  as a linear compositoin of aligned spare shape priors in the prior shape set. 




 
