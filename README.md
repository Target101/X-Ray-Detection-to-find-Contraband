# Analysis of X-ray images to detect contraband

## problem statement?
Providing solutions to automated security through scanning images on the x-ray scanner to detect banned items present within.

There are over 4.5 billion passengers travelling using airports in 2022 and is expected to reach 10 billion by 2040. Security needs to work around the clock to ensure safety of the passengers and stopping the wrong passengers for search slows down the timeline of all persons. By automating some of these security measures, the security can be better equipped to search for illegal items carried by passengers.
<hr>

## Models Used and Accuracy metrics
Mask R-CNN will be the algorithm/technique primarily used on the image

ML Library used
TensorFlow, Keras

Other python libraries used
Numpy, Scipy, Pandas, Seaborn, Matplotlib

Model performance metrics -> RMSE, Adjusted r^2
<br>
Classification metrics -> F1 score, AU-ROC

<hr>

## Models tested:
- Masked RCNN was used initially to train, but poor accuracy
- YOLO v5 was implemented to detect and draw boundary box of prediction. Could be used to find arms in videos as well as pictures with excellent accuracy
- RCNN was implemented again with few tweaks for classification with very accurate results.

<hr>

## Execution Steps:
- Install python and required Libraries
- Download dataset from github
- replace image path in training.ipynb
- run the cells to get output
