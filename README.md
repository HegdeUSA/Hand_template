# Anatomical template of the Healthy Adult Human Hands 
# Files in this repository:

	(1) Hand template (.nii file, zipped): Hand_template_image.zip
	(2) 3-D printable version of the template (.stl file, zipped): 3D_model_of_hand_template.zip
	(3) 3-D printable version of the bones in the template (.stl file, zipped): 3D_model_of_segmented_bones.zip

# Background

During medical image analysis, it is often useful to align, or ‘normalize’, a given image of a given body part to a representative standard, or ‘template’, of that body part. Normalizing images in this fashion ensures that a given voxel of each registered image represents the same anatomical part.

However, no template has been available heretofore for helping register/normalize human hands. This is a significant barrier to progress in the field.

To help overcome this barrier, we have created ana anatomical template for healthy adult human hands. To do this, we obtained T1-weighted MR images of 27 different healthy adult hands from 21 different subjects. The subject sample was fairly representative from a demographic viewpoint (14 and 13 images of left and right hands, respectively; 8 men and 13 women; mean age, 35.9 years±17.9 [standard deviation]; age range, 19.4–66.9 years; African American, 2; Asian 3; Caucasian, 14; Latino, 2).

To create the template we used the aforementioned 27 images as input to a template creation script using the ANTs (Advanced Normalization Tools) software platform. For details, see the ANTsX GitHub.

The 3-D printable 3D models of the files were created using 3D Slicer (slicer.org).

# References

(1) Hegdé J, Tustison NJ, Parker WT, Yanasak N, Stumpo LA. 2022 5th International Conference on Digital Medicine and Image Processing. In: Chen Y, Li Q, editors. Proceedings of the 5th International Conference on Digital Medicine and Image Processing. 2022 5th International Conference on Digital Medicine and Image Processing; 2022 November 10; Kyoto, Japan. Kyoto, Japan: 2022 5th International Conference on Digital Medicine and Image Processing; c2022.

(2) The STL file herein is mirrored at the 3D Print Repository of the US National Institutes of Health (NIH): https://3dprint.nih.gov/discover/3DPX-017237
