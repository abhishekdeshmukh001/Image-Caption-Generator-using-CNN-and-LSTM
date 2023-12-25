## Title: Image Caption Generator using CNN and LSTM

### Overview:
Implemented an Image Caption Generator that combines Convolutional Neural Networks (CNNs) and Long Short-Term Memory networks (LSTMs) to generate descriptive captions for images. The project utilizes the Flickr8k dataset, consisting of images and corresponding textual captions.


### A. Key Features
* **Data Preprocessing:** Extracted textual information and images from the Flickr8k dataset, and performed cleaning to enhance the quality of captions.

* **Model Architecture:** Designed a CNN-LSTM model that integrates a pre-trained Xception model for feature extraction from images and an LSTM network for generating captions.

* **Training and Evaluation:** Trained the model over multiple epochs, saving models at each epoch. Evaluated the model's performance on the training set.

* **Real-time Captioning:** Provided a Python script (**'testing_caption_generator.py'**) for generating real-time image captions. The script loads pre-trained models and tokenizers to create captions for user-specified images.

### B. File Structure

* **Models:** Directory to store the trained models.
* **Descriptions.txt:** Text file containing cleaned descriptions for each image after preprocessing.
* **Features.p:** Pickle object containing image features extracted from the Xception pre-trained CNN model.
* **Tokenizer.p:** Pickle object containing tokens mapped with index values.
* **Model.png:** Visual representation of the dimensions of the project.
* **Testing_caption_generator.py:** Python script for generating captions for user-specified images.
* **Image Caption Generator using CNN and LSTM.ipynb:** Jupyter notebook containing the complete code for training and building the image caption generator.


### C. How to Use

**1] Dataset Setup:**

* Link to Download Dataset: 

    * [Flicker8k_Dataset](https://github.com/jbrownlee/Datasets/releases/download/Flickr8k/Flickr8k_Dataset.zip)

    * [Flicker8k_text](https://github.com/jbrownlee/Datasets/releases/download/Flickr8k/Flickr8k_text.zip)


* Download the Flickr8k dataset and organize the images and text files as described in the notebook.
* Adjust file paths in the code to match your dataset location.

**2] Training:**
* Run the provided Jupyter notebook (Image Caption Generator using CNN and LSTM.ipynb) for model training.
* Trained models will be saved in the "models" directory.

**3] Real-time Captioning:**

* Utilize the testing_caption_generator.py script for generating captions for user-provided images.
* Adjust the image path in the script according to your test image.

**4] Customization:**

* Modify hyperparameters, experiment with different pre-trained models, or fine-tune the architecture to suit specific requirements.

 
###  Screenshots

#### * Model Training

![Model Training](https://github.com/abhishekdeshmukh001/Image-Caption-Generator-using-CNN-and-LSTM/blob/main/Model%20Training.png?raw=true)

#### * Sample Output

![Object Tracking](https://github.com/abhishekdeshmukh001/Image-Caption-Generator-using-CNN-and-LSTM/blob/main/Sample%20Output.png?raw=true)


## 🔗 Link
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/abhishek-sachin-deshmukh/)


## Authors

- [@abhishekdeshmukh001](https://github.com/abhishekdeshmukh001)
