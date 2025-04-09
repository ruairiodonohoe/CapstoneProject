This is the code and files used for my thesis titled: "Comparison of Classification Methodologies using Convolutional Neural Networks in a Dataset of Plant Leaf Diseases”.
This project is inspired by "FieldPlant: A Dataset of Field Plant Images for Plant Disease Detection and Classification With Deep Learning" (Moupojou et al., 2023). (https://ieeexplore.ieee.org/document/10086516)
It focuses on disease detection using a multilable dataset of images of plant leaves, using transfer learning and fine-tuning of several pre-trained CNN models.

The FieldPlant research is replicated using their original settings as much as is possible.
These original settings appear consistent with a multilabel classification task:
activation function: "softmax"
loss function: "categorical crossentropy"
metrics: "categorical accuracy"

Afterwhich the models are then retrained using different parameters suited to this multilabel dataset.
activation function: "sigmoid"
loss function: "binary crossentropy"
metrics: "binary accuracy"

The thesis for this project is published at:
O’Donohoe, R. (2024) Comparison of Classification Methodologies using Convolutional Neural Networks in a Dataset of Plant Leaf Diseases. CCT College Dublin. DOI: https://doi.org/10.63227/966.235.32
