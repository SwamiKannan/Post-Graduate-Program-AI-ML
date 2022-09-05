# WIDER face detection
## Data:
WIDER FACE dataset is a face detection benchmark dataset, of which images are selected from the publicly available WIDER dataset. We choose 32,203 images and label 393,703 faces with a high degree of variability in scale, pose and occlusion as depicted in the sample images. WIDER FACE dataset is organized based on 61 event classes. For each event class, we randomly select 40%/10%/50% data as training, validation and testing sets. We adopt the same evaluation metric employed in the PASCAL VOC dataset. Similar to MALF and Caltech datasets, we do not release bounding box ground truth for the test images. 
## Data reference: 
WIDER FACE: A Face Detection Benchmark (shuoyang1213.me) http://shuoyang1213.me/WIDERFACE/
## Citation :
	@inproceedings{yang2016wider,
	Author = {Yang, Shuo and Luo, Ping and Loy, Chen Change and Tang, Xiaoou},
	Booktitle = {IEEE Conference on Computer Vision and Pattern Recognition (CVPR)},
	Title = {WIDER FACE: A Face Detection Benchmark},
	Year = {2016}}
## Note:
This project was done as part of the assignment from GreatLearning’s Post Graduate Program for AI/ Machine Learning [https://www.mygreatlearning.com/artificial-intelligence/courses/pg-program-online-artificial-intelligence-machine-learning]

## Key asks:
•	Use transfer learning on an already trained model to build our detector. 
