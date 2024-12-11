# CaloCare-MachineLearning
# About the model :
  •	Convolutional Neural Network (CNN) for Image Recognition:

CaloCare employs a Convolutional Neural Network (CNN) for image classification, harnessing its capability to extract intricate hierarchical features from images. CNNs excel in identifying complex patterns, such as textures and visual details, making them ideal for recognizing various Padang food dishes. Within CaloCare, the CNN model is meticulously trained to detect unique characteristics of Padang cuisine, allowing users to capture and identify dishes with precision. By leveraging CNN technology, CaloCare ensures a reliable and efficient recognition process, providing users with an intuitive and enjoyable way to explore the rich variety of Padang food.
  
  •	Nutritional Evaluation Model: 

CaloCare integrates a Nutritional Evaluation Model powered by regression analysis to provide a healthiness score for each dish. This model assigns a score on a 1 to 5 scale, where 1 indicates less healthy and 5 represents highly healthy options. The evaluation considers key nutritional factors such as sugar content, fat levels, calorie count, and other relevant metrics. The model is trained using hyperparameter optimization to ensure accurate and reliable predictions. By analyzing these details, CaloCare empowers users to make informed dietary choices, combining the richness of Padang cuisine with health-conscious insights for a balanced and enjoyable dining experience.

# ML team responsibilities : 

1. **Data Collection and Preparation**:  
   - Curate a comprehensive dataset of Padang food images alongside detailed nutritional information (e.g., sugar content, fat levels, calories).  
   - Ensure high-quality data preprocessing, including image augmentation and standardization, and accurate labeling of nutritional details.  

2. **Image Classification Model Development**:  
   - Design and train a Convolutional Neural Network (CNN) model to accurately classify Padang food dishes.  
   - Optimize the CNN architecture to improve accuracy, efficiency, and robustness in handling diverse food images.  

3. **Nutritional Health Evaluation Model Development**:  
   - Develop a regression-based model to classify the healthiness of food on a 1 to 5 scale using nutritional details.  
   - Employ advanced hyperparameter tuning techniques to ensure precise and reliable health evaluations.  

# ML members :
M117B4KY3900 | Rizal Ahmad Saepulloh | Institut Teknologi Nasional Bandung

M299B4KY3061 | Muhammad Rizki Putra Pratama | Universitas Pendidikan Indonesia

M322B4KY3077 | Muhammad Rusqi Ash Shiddieqy | Universitas Syiah Kuala

# Installation: Image Recognition  

1. **Upload Model to Google Drive**:  
   - Save the trained TensorFlow Lite (TF Lite) model to Google Drive for easy access and deployment.  

2. **Upload Food Image**:  
   - Upload an image of the Padang food dish to the application or designated platform.  

3. **Obtain Predicted Class**:  
   - Use the TF Lite model to analyze the uploaded image and predict the class of the Padang food dish with high accuracy.  

4. **Retrieve Food Details**:  
   - Fetch and display relevant details about the identified dish, such as its name, nutritional information, and associated healthiness score.
