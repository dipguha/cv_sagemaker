# cv_sagemaker

# Lecture 2: Tech stack
1. MongoDB
2. Express
3. React next js
4. Node.js
5. Digital Ocean
6. Kaggle
7. SageMaker
8. API Gateway, Lambda, CloudWatch
9. Production -> scalability, security, robustness
10. ML Ops - Deploy model to production

# Lecture 5: Setting up SageMaker
1. Amazon SageMaker Build, train, and deploy machine learning models at scale
2. Amazon SageMaker Studio provides a single, web-based visual interface where you can perform all ML development steps
3. 

# Lecture x:

# Lecture 7: Cost optimization
1. Save all Jupyter notebook
2. Shut down the instances
3. Training with GPU might not be available but needs requests, support cases with service limit increase

# Lecture 8: Get data from Kaggle
1. Download data from Kaggle into SageMaket JNotebook
```
pip install -q kaggle
mkdir ~/.kaggle
touch ~/.kaggle/kaggle.json
api_token = {"username":"", "key":""}

```

# Lecture 9: Get data from Kaggle part 2
1. Move download data into /data folder
2. 

# Lecture 11: Visualizing images
1. matplotlib.pyplot to visualize
2. imread, imshow
3. Validation, test and train (normal, pneumonia) are 3 directories where images are stored
   
# Lecture 13: Resizing images
1. image with "person" has pneumonia, normal starts with IM
2. Rename and resize the images
3. ResNet - Built-in image classifier
   
# Lecture 14: Computer vision part 1 part 2
1. Save images as Grey scale using matplotlib
2. SM changes to the images to 3 dimensions
3. RGBA needs to be modified

# Lecture x:

# Lecture 25: Upload images to S3
1. Upload train and test images
2. Bucket, region and role

# Lecture 27: Setting up our Estimator object for training
1. Image classifier docker image from ECR - algorithm image
2. image_classifier_model = sagemaker.estimator.Estimator(algorithm image, instance_type, output path of the trained model)

# Lecture 29: Setting up Hyperparameter tuning
1. hyperparameter setting
  2. epochs = 50 (ideal)
  3. 
4. 

# Lecture 30: Setting up Hyperparameter ranges
1. From sagemaker.tuner - import CategoricalParameter, ContinuousParameter, HyperparameterTuner
2. learning_rate
3. Gradient decent - mini_batch_size

# Lecture 32: Setting up the training job
1. Maximize accuracy
2. Train the model 5 times with 5 different hyperparameter values
3. Bayesian search
4. Amazon SageMaker developer guide

# Lecture 33: Starting our training job 
1. tuner.fit - run the tuner job
2. Check CloudWatch

# Lecture 34: Evaluating our training job
1. 

# Lecture 35: Deploying our model locally

# Lecture x:

# Lecture x:

# Lecture x:

# Lecture x:

# Lecture x:

# Lecture x:

# Lecture x:

# Lecture x:

# Lecture x:

# Lecture x:

# Lecture x:

# Lecture x:

# Lecture x:

# Lecture x:

# Lecture x:

# Lecture x:
