======================================================================
                     Auto-WCEBleedGen Challenge Test Dataset Readme
======================================================================

This document provides instructions and information regarding the Test Dataset 1 and 2, evaluation metrics for validation dataset, and submission format for the Auto-WCEBleedGen Challenge in collaboration with 8th International Conference on Computer Vision and Image Processing (CVIP 2023). 

1. Information about Test Datasets:

Test Dataset 1: 
- The Test Dataset 1 contains 49 frames. 
- The frames have been randomly collected from seven different patient's data.
- The frames have been annotated by a group of experienced gastroenterologists from the Department of Gastroenterology and HNU, AIIMS Delhi. The annotations are marked in the frames. 

Test Dataset 2: 
- The Test Dataset 2 contains 515 images.
- The frames have been collected from twenty-three different patient's data. The annotations are NOT marked in the frames.
- The frames have been organized into twenty-three patients (P1 to P23) with varying ranges of image IDs for each patient, as follows:
     - P1:  A0050 - A0075
     - P2:  A0076 - A0296
     - P3:  A0297 - A0303
     - P4:  A0304 - A0311
     - P5:  A0312 - A0321
     - P6:  A0322 - A0334
     - P7:  A0335 - A0338
     - P8:  A0339 - A0370
     - P9:  A0371 - A0378
     - P10: A0379 - A0391
     - P11: A0392 - A0411
     - P12: A0412 - A0421
     - P13: A0422 - A0431
     - P14: A0432 - A0441
     - P15: A0442 - A0453
     - P16: A0454 - A0465
     - P17: A0466 - A0476
     - P18: A0477 - A0490
     - P19: A0491 - A0509
     - P20: A0510 - A0529
     - P21: A0530 - A0537
     - P22: A0538 - A0552
     - P23: A0553 - A0564

2. Submission Format:

   Participants should submit their results in the following format in the README:

   - From Test Dataset 1, submit the best 5 predicted frames with bounding boxes and confidence level.

   - From Test Dataset 2, submit the best 5 predicted frames with bounding boxes and confidence level.

3. Excel Sheet Submission:

   Participants are required to submit an excel sheet containing image (frame) names and their corresponding predicted class labels for all frames in Test Dataset 1 and Test Dataset 2. 

   The format of the excel sheet is as follows: 
   - Column 1: Image name.
   - Column 2 : Predicted class label for each image.

*******You may add the predicted coordinates of the bounding box and confidence level of all frames.

A screenshot of the excel sheet has been attached for reference. It should be uploaded in the GITHUB repository.

4. Important Notes:

   - Ensure that all submissions are properly labeled and organized.
   - Follow the guidelines and instructions provided by the organizers for submitting predictions, and inter-pretablity plots.

5. Following formula's can be utilized for calculating the evaluation metrics of validation dataset:

Classification: 

Accuracy - (TP+TN) / (TP+TN+PF+FN)
Recall - TP/ (TP+FN)
F1 score = (2 * Precision * Recall) / (Precision + Recall)  [In F-beta, beta=1]

Detection:

Intersection over Union (IoU) - area (ground truth ∩ prediction) / area (ground truth ∪ prediction) 
                              - area of overlap / area of union
Average Precision (AP) is Area Under the Precision-Recall Curve(AUC-PR) evaluated at α IoU threshold. Threshold can be taken as 0.5 and 0.75.
Mean Average Precision (mAP) is the average of AP values over all classes, here 2 (bleeding and non-bleeding).


True Positive (TP), False Positive (FP), False Negative (FN), and True Negative (TN). 
intersection - ∩ 
union - ∪
=========================================================================================================================
