# Patch-OD-dataset-for-fine-grained-segmentation-

The Patch dataset is created cropping patches of size 25 Χ 25 from the Fundus Images in DRISHTI- GS dataset. The patches are created around the borders of the Optical Disc (OD) and Optical Cup (OC) where there  "expected ambiguity" is maximum. The ambiguous points (in class belongingness as OD or OC)  are extracted by EX-OR ing OD and OC labels. The folder named "Expected ambiguities" shows the images with the ambiguous pixels in white.
In the Excel file called "Expected ambiguities" we have taken 70,199 ambiguous points (pixels) randomly from all images. 
The patches of size 25 × 25 is extracted from the original image and OD ground truth for fine grained learning.  
Since “Git Hub” is not accommodating the file size, I share the g-drive with the 70,199 patches of size 25 × 25 created in the images and at the same spatial co-ordinates in the OD labels.
https://drive.google.com/drive/folders/1OeJr0S-iuwugpeUVDMFjNHAjmteQguge?usp=sharing

