# Tomatina

Classify images with tomatoes from different dishes
- organize.py : Organizes data into tomato and non tomato categories from the given data file.
- generate_tfrecord: Generate tfrecords of the images for tensorflow operations
- Used tensorflow object detection api to train the model for tomato detection.
- Image classification is done by fine tuning Vgg16
- data.zip: Some of sample training images
- train_database.txt: Bounding boxes
