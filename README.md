# U-Net Deep Learning for Efficient and Robust Removal of Unwanted Anatomical Structures in Digital Mammographies


++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++

Standardization is not only related to the recognition of the device, modality, or image orientation, but also to the elimination of errors that exist within mammographic images.

These issues are not limited to the background or the mammography equipment itself, but also include artifacts that may appear in the image during its acquisition. Such artifacts can affect the performance of models used for breast cancer detection or classification, potentially producing false positives in some cases.

An analysis of the first 1,000 mammographic images in the public dataset VinDr-Mammo shows that these artifacts are present in more than 70% of the images. For this reason, the removal of these artifacts—referred to here as Errors—represents an important task that could lead to significant improvements in CADe and CADx models.

The proposed model aims to detect these Errors through segmentation and to remove them from the mammogram, thereby focusing attention on the main breast region. This not only facilitates the identification of regions of interest (ROIs) but also improves the resizing process commonly used as a preprocessing step in CNN and ViT models.

+++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++
