# YOLO, A look into Object Detection models:
##### Yassin Bahid

## Itroduction:
While prrevious object detection models reused classifers to perform detections. Im his paper, Redmond reframes the problem as a regression problem aiming to spacially seperate bounding boxes associated with certain classes. In order to achive this result, Redmond proposes a new loss function that optimizes classification and object boxing. YOLO is suprisingly fast and can process 45 frames per second. We shall create a YOLO Neural Net, train it, and test it's Accuracy.
