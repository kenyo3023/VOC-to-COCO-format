# VOC-to-COCO-format

### Step
- download the pascal voc dataset 2012 [pascal voc 2012](http://host.robots.ox.ac.uk/pascal/VOC/voc2012/index.html) or other version [pascal voc](http://host.robots.ox.ac.uk/pascal/VOC/).
- unzip and rename the download dataset to VOC2012_trainval, put in the path ./
- run the .ipynb in ./notebook/
  - **01_voc2coco.ipynb** is to convert the voc format (.xml) to coco format (.json). -> ../VOC2012_coco/annotations.json
  - **02_split_traintestval.ipynb** is to split the annotations.json into training, testing and validation set. -> ../VOC2012_coco/{train_voc or test_voc or val_voc}.json
  -  **03_move_images.ipynb** is to move the images under vol format folder (VOC2012_trainval) to coco format folder (VO/C2012_coco).
  -  **04_display_image.ipynb** is use to display and validate the correctness of conversion.
