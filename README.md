**Traffic Sign Detection using German Dataset:**

This repository contains code for traffic sign detection using the German Traffic Sign Recognition Benchmark (GTSRB) dataset from Kaggle. The project involves implementing various data science techniques, including convolutional neural networks (CNN) and transfer learning, to classify and detect traffic signs accurately.

**Dataset:**

The German Traffic Sign Recognition Benchmark (GTSRB) dataset is used for training and evaluation. It consists of thousands of images of traffic signs categorized into various classes.![0_10037_1577671998 6750946](https://github.com/mdoctos/Traffic_sign_prediction/assets/57889962/a354f3fa-cfdc-425b-a6de-73471b45abe7)
![0_10036_1577671998 6740978](https://github.com/mdoctos/Traffic_sign_prediction/assets/57889962/8f2a3811-476a-4885-b9e0-421ca070898f)
![14_29269_1577672016 5996525](https://github.com/mdoctos/Traffic_sign_prediction/assets/57889962/351fc2db-244e-4bf2-8f3b-81c25eaacfb9)
![14_29268_1577672016 5986552](https://github.com/mdoctos/Traffic_sign_prediction/assets/57889962/c3d2e7eb-8707-4d54-a0c4-e0920dcf41dc)
![14_29225_1577672016 559761](https://github.com/mdoctos/Traffic_sign_prediction/assets/57889962/d92ce9a6-ca23-49f1-be85-26d91d30fd1c)


**Project Overview:**

1. **Data Preprocessing:**
   - The dataset is preprocessed to resize images, normalize pixel values, and perform data augmentation techniques such as rotation, scaling, and flipping to enhance model generalization.

2. **Model Building:**
   - Two approaches are explored for traffic sign detection: CNN and transfer learning.
   - CNN: A custom CNN architecture is designed and trained from scratch to classify traffic signs directly.
   - Transfer Learning: Pre-trained models such as VGG16, ResNet50, and MobileNet are fine-tuned on the GTSRB dataset to leverage learned features for improved performance.

3. **Evaluation:**
   - The trained models are evaluated using various performance metrics such as accuracy, precision, recall, and F1-score.
   - Model performance is compared between CNN and transfer learning approaches to determine which method performs better for traffic sign detection.

**Results:**

- The results of the experiment demonstrate that the custom CNN architecture outperforms transfer learning models in terms of accuracy and overall performance.
- The CNN approach achieves superior results due to its ability to learn features directly relevant to traffic sign classification, thereby eliminating potential domain adaptation issues associated with transfer learning.

**Repository Structure:**

- **data:** Contains the GTSRB dataset used for training and evaluation.
- **notebooks:** Jupyter notebooks containing code for data preprocessing, model building, training, and evaluation.
- **models:** Trained model weights and architecture files.
- **src:** Source code files for data preprocessing, model building, and evaluation.
- **results:** Performance metrics and evaluation results.



3. Run the Jupyter notebooks in the `notebooks` directory to preprocess data, build and train models, and evaluate performance.

**Conclusion:**

This project demonstrates the effectiveness of CNN for traffic sign detection using the GTSRB dataset. By comparing performance between CNN and transfer learning approaches, it is concluded that a custom CNN architecture yields superior results for this task. The repository serves as a valuable resource for researchers and practitioners interested in traffic sign recognition and related computer vision applications.
