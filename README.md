Here’s your updated portfolio with the image forgery detection project added:  

---

# Portfolio of AI Projects  

Welcome to my AI portfolio, where I showcase a range of exciting projects that leverage deep learning, natural language processing, and computer vision techniques. Below is an overview of the projects included in this repository:  

## Projects  

1. **[Image Forgery Detection Using Hybrid Deep Learning](#image-forgery-detection-using-hybrid-deep-learning)**  
2. **[Text Summarization with BART](#text-summarization-with-bart)**  
3. **[Dueling DQN and Standard DQN for Pong](#dueling-dqn-and-standard-dqn-for-pong)**  
4. **[Luxy: Hotel Booking Chatbot](#luxy-hotel-booking-chatbot)**  
5. **[Cat vs Dog Image Classifier](#cat-vs-dog-image-classifier)**  

---  

## Image Forgery Detection Using Hybrid Deep Learning  

This project aims to detect manipulated images using a hybrid approach that combines deep learning with traditional image processing methods. The model integrates MobileNetV2, Enhanced Laplacian of Gaussian (ELA), and Local Binary Patterns (LBP) to detect forgery in images, even with limited training data.  

### Features:  
- **Hybrid Model**: Combines deep learning (MobileNetV2) with traditional techniques (ELA & LBP).  
- **Forgery Detection**: Identifies image manipulations by analyzing compression artifacts and texture changes.  
- **Efficient Training**: Uses transfer learning and feature extraction to work effectively with small datasets.  

### Installation:  
```bash
git clone https://github.com/your-repository/image-forgery-detection.git  
cd image-forgery-detection  
pip install tensorflow opencv-python numpy  
```  

### Usage:  
To train the model:  
```bash
python train_model.py  
```  
To test on new images:  
```bash
python test_model.py --image path/to/image.jpg  
```   
## Text Summarization with BART

This project demonstrates the implementation of a text summarization model using the BART (Bidirectional and Auto-Regressive Transformers) architecture from the `transformers` library. The model is trained on the CNN/DailyMail dataset to generate concise and coherent summaries of input articles.

### Features:
- **Text Summarization**: Generates concise summaries of input articles.
- **Beam Search**: Uses beam search decoding to improve the quality of generated summaries.
- **Memory Management**: Implements memory usage monitoring to ensure efficient use of resources.

### Installation:
```bash
git clone https://github.com/prempraneethkota/BriefBot.git
cd BriefBot
pip install transformers datasets torch psutil
```

### Usage:
Run the interactive script to generate summaries for input articles:
```bash
python Run.py
```
## Dueling DQN and standard DQN for pong

This project trains both a Dueling DQN (Deep Q-Network) and a standard DQN to play the game Pong using the OpenAI Gym environment. It includes code for preprocessing frames, managing stacked frames, and optimizing the model using experience replay.

### Features :
- **Standard DQN**: A simple Q-learning model with a deep neural network.
- **Dueling DQN**: A more advanced variant that separates the value and advantage streams to improve training efficiency.
- **Results Visualization**: Includes plotting total rewards per episode during training.

### Installation:
```bash
git clone https://github.com/your-repository/pong-dueling-dqn.git
cd pong-dueling-dqn
pip install -r requirements.txt
```

### Usage:
To train the standard DQN:
```bash
python pong.py
```
To train the Dueling DQN:
```bash
python pong2.py
```

## Luxy: Hotel Booking Chatbot
Luxy is a chatbot built to streamline hotel room bookings at Singapore's Oasis beach resort. It helps users gather basic details, provides information about the resort, and guides them through the booking process.

### Features:
- **Reservation Assistance**: Helps users book rooms with predefined parameters.
- **Information Provider**: Answers queries about amenities, room features, and availability.
- **Payment Integration**: Collects payment preferences and finalizes the reservation.

### Development:
Luxy was developed using Botpress, providing an easy-to-use visual interface for creating conversational flows and integrating with the hotel's knowledge base.

### Link to chatbot:
```bash
https://mediafiles.botpress.cloud/2443abf8-9e24-4cb1-9926-c0b8832d1af0/webchat/bot.html
```

## Cat vs Dog Image Classifier
This project implements a Convolutional Neural Network (CNN) for binary image classification, specifically to classify images of cats and dogs. The model is trained using data augmentation and preprocessing techniques, achieving high accuracy for classification.

### Features:
- **Data Augmentation**: Uses image transformations to improve model generalization.
- **CNN Architecture**: A simple CNN with convolutional, pooling, flatten, and dense layers.
- **Binary Classification**: Classifies images into two categories: cat or dog.

### Installation:
```bash
git clone https://github.com/your-repository/cat-dog-classifier.git
cd cat-dog-classifier
pip install -r requirements.txt
```

### Usage:
Train and evaluate the model using:
```bash
python train_model.py
```
