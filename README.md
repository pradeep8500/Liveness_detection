## install all requirements

pip install -r requirements.txt

## Face detection using OpenCV and Deep Neural Network

For face detection res10_300x300_ssd_iter_140000.caffemodel model used

## Liveness/anti spoofing 

Implement a CNN capable of performing liveness detector For Liveness detection (liveness.model)

### How to run?

```
To use in webcam:
```console
python liveness_detect_faces.py --model liveness.model --le le.pickle --detector detect

```
