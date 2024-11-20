#    White Blood Cell Classification with Deep Learning using Multihead Attention Mechanism

White blood cells protect your body against infection. As your white blood cells travel through your bloodstream and tissues, they locate the site of an infection and act as an army general to notify other white blood cells of their location to help defend your body from an attack of an unknown organism. Once your white blood cell army arrives, they fight the invader by producing antibody proteins to attach to the organism and destroy it.

What are the types of white blood cells?
There are five types of white blood cells:
•	Neutrophils: Help protect your body from infections by killing bacteria, fungi and foreign debris.
•	Lymphocytes: Consist of T cells, natural killer cells and B cells to protect against viral infections and produce proteins to help you fight infection (antibodies).
•	Eosinophils: Identify and destroy parasites, cancer cells and assists basophils with your allergic response.
•	Basophils: Produce an allergic response like coughing, sneezing or a runny nose.
•	Monocytes: Defend against infection by cleaning up damaged cells.

#                                                            PROJECT OVERVIEW
My latest project where I applied Deep Learning techniques to classify White Blood Cell Dataset. In this project, I built two advanced models Xception with Attention and MobileNet with Attention to classify images of White Blood Cells into 08 (Eight) categories.

Dataset Overview: -
This dataset contains segmented images of white blood cells derived from the Peripheral Blood Cell Dataset available on Kaggle. The original dataset consists of 17,092 images of individual normal cells, acquired using the analyzer CellaVision DM96 in the Core Laboratory at the Hospital Clinic of Barcelona. These images were organized into eight groups: neutrophils, eosinophils, basophils, lymphocytes, monocytes, immature granulocytes, erythroblasts, and platelets.
In this dataset, we provide 195 images per class, each with a corresponding binary mask created using OpenCV techniques, including GrabCut and morphological operations. This dataset is suitable for training segmentation models like U-Net, Mask R-CNN, and other advanced image segmentation techniques.
File Structure:
original_images/
Description: Original images of white blood cells from the Peripheral Blood Cell Dataset, categorized into eight classes.
File Count: 1,560 images (195 per class)
File Format: JPG
Naming Convention: class_name_id.jpg
binary_masks/
Description: Binary masks for the white blood cell images, created using GrabCut and morphological techniques.
File Count: 1,560 masks (195 per class)
File Format: JPG
Naming Convention: class_name_id.jpg

### Model Architecture:-
Xception with Attention and MobileNet with Attention.
Both models were trained with high Accuracy and I compared their performance using key metrics.

## Results: -
## •	Xception: Accuracy = 82%; Macro Avg F1-Score =0.82; Weighted Avg F1-Score = 0.82
## •	MobileNet: Accuracy = 98%; Macro Avg F1-Score =0.98; Weighted Avg F1-Score = 0.98
MobileNet with Attention showed a significant improvement, achieving almost perfect classification Accuracy across all classes, while Xception with Attention also demonstrated strong performance with a precision-recall balance.

Key Takeaways: -
•	Advanced models like Xception and MobileNet with Attention mechanisms can achieve impressive results in image classification tasks.
•	MobileNet proved to be more efficient in terms of Accuracy and F1-Scores.
•	The project helped enhance my understanding of image classification, attention mechanisms and Deep Learning model fine-tuning.
