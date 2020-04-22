# dissertation_extra_data
Contains extra data for dissertation

This repo contains the following data:

- **checkpoint_old:** Contains training checkpoint using the traffic light images with a white background
  - batch1
  - batch12
  - batch24
  - batch48: These are the checkpoints trained with different batch size for comparison
  
- **checkpoint_ssd:** Contains training checkpoint using our final data (white background + other background, whole traffic light selected), training a SSD model. This is the one we used to perform traffic light detection.

- **checkpoint_ssdlite:** Contains training checkpoint using our final data, training a SSDLite model.

These checkpoints can be visualized with Tensorboard, and can also be used to export frozen inference graph which can be loaded by objD.py and processTime.py.

This repo also contains
- **recorded:** The sample recorded data for FR00, recorded by our modified vehicle.py. 
