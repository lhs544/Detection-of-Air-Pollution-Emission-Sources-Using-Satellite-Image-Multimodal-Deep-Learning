# Detection-of-Air-Pollution-Emission-Sources-Using-Satellite-Image-Multimodal-Deep-Learning
National Information Society Agency (NIA) Data Creator Camp (Sep-Nov 2025) , Completion Certificate Awarded

AI-hub Air Pollution Emission Source Spatial Distribution Data
- Use AI-hub-provided data only, do not add external images

Mission 1: The first discovery of a source of pollution
Object Detection
■ Kompsat-3/3A satellite image (Training>TS)_
Learned with 8,052 data in KS folder,
Validation>1,006 pieces of data in VS_KS folder
evaluation), TL_KS_BBOX with labeling data,
Use VL_KS_BBOX
■ You can use models like YOLOv8 freely
The location of the chimney in the image in the form of a bounding box
Make a prediction.
■ Evaluated based on mAP@IoU = 0.5 indicator.

Mission 2: Estimating emissions
Height Estimation from Images
■ Kompsat-3/3A satellite image (Train>TS_KS)
Learned with 8,052 pieces of data in the folder,
Validation>With 1,006 pieces of data in VS_KS folder
evaluation), TL_KS_LINE, VL_KS as labeling data_
Use LINE (In height estimation, each labeling data)
My shape_attributes values are available)
■ Feel free to use models such as ResNet to image
Estimate the height of my chimney in meters.
■ Evaluate based on RMSE indicators.

Mission 3: Finding an Industrial Complex
Semantic Segmentation
■ Sentinel-2 Industrial Complex Image (Training>TS)_
Learn from 8,000 pieces of data in SN10_SN10 folder,
Validation > Data in VS_SN10_SN10 folder
1000), TL_SN10 as labelling data,
Using VL_SN10
■ Use U-Net models, etc. freely in an image
Divide the area of the industrial park.
■ Evaluate based on mIoU indicators.
