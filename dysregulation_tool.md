# Pathway Dysregulation Analysis Tool

When choosing the "Pathway Dysregulation" tool from the Visual Analytics page in EcoToxXplorer, an algorithm is executed to infer pathway deregulation scores for each toxic sample on the basis of expression data. The score is at the sample level and the higher the score, the more distant are the treatment samples from the control cases. 

For the working example of Minnow (ethinylestradiol), the following figure is generated with "Lysine degradation" as the top ranked dysregulated pathway. The "Lysine degradation" pathway is fully visualized in the center panel where the user can zoom in and out to explore genes and compounds interactions in the pathway. 

![Image](pathways_dysregulation.png)

The [PCA](background_pca.md) plot at the right side is a visualization of all samples when a specific pathway is highlighted. 
