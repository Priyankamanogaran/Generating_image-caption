# Generating_image-caption
# GENERATING IMAGE CAPTION USING CNN AND LSTM

### ABSTRACT
  Automatically describing the content presented in an image is a fundamental problem in Artificial intelligence that connects computer vision and natural language processing. This paper focus on the generation of image description to describe an image for the purpose of understanding the visual content of an image. This task is challenging in meaningful description generation process of high level image semantics which requires not only the detection and recognition of the object and the scene, but the ability of analysing the state, the attributes and the relationship among these objects. For retrieving a caption, the proposed work uses encoder-decoder neural architecture. This model which takes an image as an input generate a semantic representation and is trained for producing a sequence of words where each word belongs to the dictionary that describes the image suitably. With qualitative evaluation, the proposed work has attained considerable performance over traditional state-of-the-art method for text sequence generation and has captured the relevant context with syntactic meaning to be generalised for the normal users.
 
Keywords: Artificial intelligence, Computer vision, Natural language processing, Encoder-Decoder neural architecture.

### Requirements
1.	Python 
2.	Keras.
3.	Stanford NLP Toolkit

### Prerequisites
1.	Image captioning with Python, working on colab or jupyter notebook, with tensor flow as backend 
2.	Required libraries like Keras, Numpy, and Natural Language Processing, Tensor flow, Matplotlib, pandas, pillow, numpy, tqdm, bleu, nltk, meteor etc..,

![image](https://user-images.githubusercontent.com/37410701/117040977-15bdf600-ad28-11eb-8504-856950e7aab1.png)

The proposed system uses image description encoder convolutional neural network which is used for extracting features from the image and text description decoder long short-term memory will use the information from the encoder to help generate a caption for the given image. The convolutional neural network will identify the objects present in the image then LSTM will start preparing captions considering the objects present in the image. The proposed system of Image Caption Generator uses Flicker8k dataset for training purpose it is capable of generating caption test images as well as new images. 

### DATA COLLECTION
   **Flickr 8k dataset**
This dataset contains 8000 images each with 5 captions
Flickr8k_Dataset: Contains 8092 images in JPEG format.
Flickr8k_text: Contains a number of files containing different sources of descriptions for the images.

Download
https://github.com/jbrownlee/Datasets/releases/download/Flickr8k/Flickr8k_Dataset.zip 
https://github.com/jbrownlee/Datasets/releases/download/Flickr8k/Flickr8k_text.zip
OR
https://www.kaggle.com/adityajn105/flickr8k/activity


Run all the cell in **IMAGE_CAPTION.ipynb** to get the caption for an image.

### OUTPUT 
![image](https://user-images.githubusercontent.com/37410701/117040902-0343bc80-ad28-11eb-8e62-ab98229260af.png)


