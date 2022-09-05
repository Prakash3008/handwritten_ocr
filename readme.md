# Train and test the model using the following commands:

python train.py --dataset train.csv --model models/svm.cpickle

python classify.py --model models/svm.cpickle --image images/test2.jpeg

# Execute the easyocr method using the following command

First, change the image_file_name argument in the pretrained.py file then,

python pretrained.py