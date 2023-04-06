# Deep-Learning
This repository contains materials related to convolutional neural networks (CNNs) and its components, aimed at helping users learn the basics and implement them in their deep learning projects. It includes an overview, explanations of each component, examples, and resources. Contributions are welcome. License: MIT License

# Overview
1. Physical environment
2. Convolution Neural Network (CNN) theory
3. Convolution Neural Network (CNN) implementation
4. Results analysis
5. Model deployment

## Physical Environment
* Python virtual environment
* Neptune account creation
* Dataset **(sample)** **[official](https://www.kaggle.com/datasets/sriramr/fruits-fresh-and-rotten-for-classification)**
* arial.ttf **(font file)**

## Convolution Neural Network Theory
Convolution neural network fundamentals are covered in this section. These include biological neurons, artificial neurons, the convolution and max pooling operation, stride, and padding. **Below are illustrations of biological neuron, artificial neuron, and convolution neural network.**

### 1. Biological neuron
![biological_neuron](https://user-images.githubusercontent.com/89079815/230206085-2ca8def8-e3ac-476b-944c-c5653269e41d.png)

### 2. Artificial neuron
![artificial_neuron](https://user-images.githubusercontent.com/89079815/230207167-b05486c9-c086-4fc1-b46a-5e0fc6f0f36a.png)

### 3. Convolution Neural Network 
![cropped_neuralnet](https://user-images.githubusercontent.com/89079815/230207691-e08606a2-edf1-4718-a028-f52c9ed1f205.png)

## Convolution Neural Network Implementation
* CNN model training **without** image-preprocessing
* CNN model training **with** image-preprocessing
  1. Using pre-defined parameters of **ImageDataGenerator()** class
  2. Using custom parameters
* CNN model architecture visualization
  1. Using netron.app
  2. Using visualkeras library
  3. Using plot_model function
* Using pre-trained model
  1. Transfer learning theory
  2. Fine tunning explanation
  3. Feature-map visualization

## Results analysis using neptune.ai
Neptune.ai is a cloud-based platform designed for managing and organizing machine learning experiments. It allows data scientists and machine learning engineers to track, monitor, and compare different models and experiments in one central location. The platform provides a range of features including automated tracking of experiment metadata, hyperparameters, and code versions. It also has built-in visualizations and tools for analyzing model performance and generating reports. Neptune.ai integrates with popular machine learning frameworks such as TensorFlow, PyTorch, and scikit-learn, making it easy to integrate into existing workflows. Additionally, it provides collaboration tools for teams, allowing members to share results and collaborate on projects. With Neptune.ai, teams can easily manage and organize their machine learning experiments, enabling them to make faster and more informed decisions about their models and data.

  1. neptune-notebooks
  2. init.run()
  ![Screenshot from 2023-04-06 02-51-46](https://user-images.githubusercontent.com/89079815/230214355-2938edc6-f9ac-468b-b719-9ede8150f1f6.png)
  ![Screenshot from 2023-04-06 02-45-47](https://user-images.githubusercontent.com/89079815/230213300-d8b4206f-8193-41b9-b183-65845382f395.png)
  ![Screenshot from 2023-04-06 02-47-18](https://user-images.githubusercontent.com/89079815/230213503-f18929e5-3c57-4482-a2b2-09c5f3790611.png)
  ![Screenshot from 2023-04-06 02-48-37](https://user-images.githubusercontent.com/89079815/230213774-a1164753-ab96-45e2-b5e3-e51a49c99f3e.png)
  ![Screenshot from 2023-04-06 02-50-12](https://user-images.githubusercontent.com/89079815/230214103-3f7e2bca-f9e9-4101-9cab-2e89339c70ad.png)

  
  
  3. init.model()
  4. init.model_version()
  5. init.project()
  
## CNN model deployment using streamlit framework
Streamlit is a popular open-source framework that enables developers to create interactive web applications for machine learning and data science projects. The framework provides an easy-to-use interface that allows developers to create custom data visualizations, charts, and dashboards with Python code. Streamlit handles the backend and front-end of the application, allowing developers to focus on the logic and content of the application. It also has built-in features like caching, widgets, and sharing options, which make it easier to create and deploy applications quickly. Streamlit's community is constantly growing, and the framework is becoming increasingly popular for data scientists, developers, and researchers who need to create interactive data applications. Since it is open-source, anyone can contribute to the framework and create new tools and features, making it a collaborative and flexible platform for data science projects. See examples below:

* [Cross chain monitoring](https://cross-chain-monitoring.streamlit.app/)
* [Background removal](https://bgremoval.streamlit.app/)
* [Prettymap](https://chrieke-prettymapp-streamlit-prettymappapp-1k0qxh.streamlit.app/)
* [Streamlit component hub](https://components.streamlit.app/)
