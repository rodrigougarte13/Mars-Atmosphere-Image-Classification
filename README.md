Analysis done on the HIRISE Mars Atmosphere image database from JPL. The objective is to use binary image classification to identify frozen atmospheric photos. The methods used are Neural Networks, first a CNN + MLP model, followed by 3 pretrained models using EfficientNetB0, ResNet50 and VGG16. We found that the Transfer Learning models provider better classification metrics (>0.9) than the CNN + MLP architecture.          
<br><br>
To set up the environment, install these libraries using pip:
```python
pip install opencv-python tensorflow scikit-learn
