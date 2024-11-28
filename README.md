# Ethernamed 



<!-- END doctoc generated TOC please keep comment here to allow auto update -->
<br>



<p>Introducing EthernaMed, a pinnacle of healthcare innovation, where cutting-edge AI meets compassionate care. Our platform is a symphony of precision and efficacy, harnessing the boundless potential of artificial intelligence to revolutionize wellness. Mediquity empowers users with personalized insights and proactive guidance, fostering healthy lifestyles and preventing illness. With unparalleled efficiency, we streamline healthcare delivery, optimizing outcomes and resource utilization. Join us on this transformative journey towards a future where health and well-being know no bounds. Welcome to Mediquity, where every interaction is a step towards a brighter, healthier tomorrow.</p>


## FEATURES

## 1. DISEASE ANALYSIS

   - This feature allows users to receive assistance via text and image analysis for disease identification and prediction.
   - The service provides insights based on symptoms and medical history, aiding in early diagnosis and proactive healthcare management.
   - 

## 2. CHATBOT

   - Engage in interactive conversations with the bot to obtain information, support, and guidance on various health-related topics.
   - The bot's conversational interface facilitates easy communication, making health inquiries accessible and user-friendly.

## 3. DISEASE DETECTION MODELS

   - Variety of detection/prediction models like Brain tumor detection,Pneumonia detection,Diabetes detection,tubercolosis detection and more.
   - This feature aids in early detection and referral for further medical evaluation and treatment, potentially improving patient outcomes.

## 4. PHYSIO-ASSISTANCE

   - Receive personalized assistance and guidance from the bot for physiotherapy-related queries and exercises.
   - The service offers support in rehabilitation and injury prevention, enhancing the user's physical well-being and recovery process.

## 5. PERSONAL THERAPIST

   - Access a virtual therapist through the bot for emotional support, counseling, and mental health management.
   - Users can engage in confidential conversations and receive guidance on coping strategies and self-care techniques


## 6. BOOK APPOINTMENTS
   - Book appointments with nearby doctors based on your specific medical concerns.
   - This feature will provide users with the ability to conveniently schedule appointments with doctors in their vicinity, tailored to address their specific medical concerns.


How It Works
Data Preprocessing: Normalization: The pixel values of images are normalized to a range of 0 to 1. 
Data Augmentation: The training data is augmented using Keras' ImageDataGenerator, applying transformations such as rotation, flipping, zooming, and shifting. SMOTE Resampling: The class imbalance is handled using SMOTE, ensuring the minority class is not underrepresented.

Model:

Architecture: The CNN consists of multiple convolutional layers with ReLU activation followed by max-pooling layers. The final layers include a fully connected network with a softmax output for binary classification (Autism/No Autism). Regularization: Dropout is applied to prevent overfitting during training. Optimizer: Adam optimizer is used with a learning rate of 0.001 for efficient training.

Training:

The model is trained using the ImageDataGenerator on the resampled and augmented dataset. Early stopping ensures that training halts when validation accuracy stops improving, while a model checkpoint saves the best version of the model during training.


Key Features:
1. Hybrid Model: Combines classical deep learning with quantum layers to potentially improve the model's performance in image classification tasks.

2. Custom Dataset: Uses an autism dataset with pre-labeled images for binary classification.

3. Performance Comparison: Provides a side-by-side comparison of model accuracy and loss between quantum and non-quantum models.

4. Visualization: Includes detailed plots to visualize model performance across training epochs.

## Libraries

## Frontend Libraries:
React.js: For building the user interface.
Redux: For state management.
TailwindCSS: For styling.
Figma: Used for UI/UX design (external tool).
## Backend Libraries and Frameworks:
Node.js: As the runtime environment for server-side JavaScript.
Express.js: To create APIs and handle server-side routing.
MongoDB: A NoSQL database for storing application data.
Flask: A Python microframework for additional backend services.
Cloudinary: For handling and storing media assets like images.

How It Works:
The project initializes a simple CNN using Keras. Two versions of the model are trained: one with a quantum layer and one without.
The dataset is preprocessed, and the images are converted into a format suitable for training.
The models are trained for 30 epochs, with the results saved and visualized.
Results:
After training, the notebook outputs a comparison of accuracy and loss for both the quantum-enhanced and classical models, helping assess the impact of quantum layers on performance.

Installation:

Prerequisites: To run this project, you'll need to install the following dependencies:

Python 3.11+
TensorFlow 2.17
Keras
Scikit-learn
Imbalanced-learn
Pillow
You can install the required packages using the provided requirements.txt file: pip install -r requirements.txt

Contributing
Contributions to the project are welcome! To contribute:

Fork the repository.
Create a new feature branch (git checkout -b feature/AmazingFeature).
Commit your changes (git commit -m 'Add some amazing feature').
Push to the branch (git push origin feature/AmazingFeature).
Open a Pull Request.

