# Sign Language Detector
A CNN project for detecting sign language.
Here, I have implemented CNN (Convolution Neural Network) using Keras.

### Tools Used
1. Python 3
2. OpenCV 3
3. Tensorflow
4. Keras
5. mediapipe


### Running this project
1. Run SignLanguageDetection.ipynb file :- show results with sign images ( Like and Dislike Images )

2. Run SignLangDetection_Upgrade.ipynb file :- show results without images


### project implement and test
1. Install Python 3, Opencv 3, Tensorflow, Keras.

2. First Train the model.
    ```
    python cnn_model.py
    ```
3. Now to test the model you just need to run recognise.py
    ```
    python recognise.py
    ```
    Adjust the hsv values from the track bar to segment your hand color.

3. To create your own data set.
    ```
    python capture.py
    ```