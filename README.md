# visualizing_cnns
in this repository, the visualization of VGG16, MobileNet and Inception V3 using Grad-CAM, Occlusion analysis and Integrated Gradients is available.

Here is a breakdown of each notebook:

### Thesis_Model_Pipeline.ipynb

In this file, the dataset, which is a subset of the Plantvillage dataset is preprocessed and fed into the 3 network architectures for either training from scratch, feature extraction or fine-tuning.

The trained model then is saved to be used later in visualizations for model prediction.

### Thesis_Visualization_Codes.ipynb

In this file, the already trained models from the previous step are fed into Occlusion Analysis and Gradcam along with a sample set of images from test_dataset, so that the corresponding heatmaps of Occlusion and Gradcam are generated. 

### Thesis_Integrated_Gradients.ipynb
The same thing as the above visualizations, only with Integrated Gradients happen in this notebook and it is separated from the previous notebook because the data processing was slightly different than the other two visualization methods.

### SSIM_thesis.ipynb
In this file, the pairs of visualizations of the same model and the same image, only in different training modes are compared and the Structural Similarity Index Measure (SSIM) of them are computed and then visualized using matplotlib.



