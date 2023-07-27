# **Model Card**

The Animal Emotion Classifier is an image classification AI model designed to recognize emotions in animals to better help human understanding of animals.
Potential applications of this model range everywhere from fun mobile apps to use for your pets, to assiting caretakers in better understanding the emotional
states of animals to providing appropriate care and support.

# **Intended use:**
Our model is intended to be used as a fun tool for humans to better understand the emotions of animals, specifically common household pets.

# **Training Data:**
Dataset Source: Pet's Facial Expression Image Dataset (https://www.kaggle.com/datasets/anshtanwar/pets-facial-expression-dataset)
Data Augmentation: Tensorflow RandomFlip, RandomRotation, RandomZoom
Augmented Data Size: 2728 images
Image Shape: [128, 128, 3]

# **Evaluation Results:** 
Model Accuracy
Testing Accuracy: 53.7%

# **Ethical Considerations and Limitations**
This model is not sufficent for professional use, or for wildlife monitoring. The only animals trained on by this model are almost exclusively domestic cats and dogs.
Other animals will not yield good results using this model.
