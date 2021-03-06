# Digit Recognition
Handwritten Digit Recognition using OpenCV, sklearn and Python |
# Dependencies
1. `cv2`
2. `sklearn`
3. `skimage`
4. `numpy`
5. `collections`

# Contents
This repository contains the following files-

1. `generateClassifier.py` - Python Script to create the classifier file `digits_cls.pkl`.
2. `performRecognition.py` - Python Script to test the classifier.
3. `digits_cls.pkl` - Classifier file for digit recognition.
4. `photo_1.jpg` - Test image number 1 to test the classifier
5. `photo_2.jpg` - Test image numbre 2 to test the classifier

## Usage

```python
python performRecognition.py -c digits_cls.pkl -i photo_1.jpg
```
## Results

### Sample Image 1
![Result Number 1](http://hanzratech.in/figures/digit-reco-1-out.png)
### Sample Image 2
![Result Number 2](http://hanzratech.in/figures/digit-reco-2.png)

## TODO

* Add a CNN Based approach
* Reject bounding boxes lesser than some area
* Look into user errors
