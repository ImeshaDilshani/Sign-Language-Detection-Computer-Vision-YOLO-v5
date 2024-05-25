# Sign Language Detection Computer Vision YOLO-v5

The project focuses on leveraging computer vision techniques to detect sign language gestures using the YOLO v5 model. By training the model on a dataset of annotated images, we enable it to recognize and interpret various hand activities associated with sign language.

## Implementation Steps
1. Data Collection: collected images of sign language gestures for six specific gestures: "Hello," "Yes," "No," "Thanks," "I love you," and "Please." Images were captured using OpenCV and a webcam, ensuring a diverse set of hand poses and lighting conditions.
2. Annotation and Training: The collected images were annotated using the LabelImg tool, and the dataset was prepared for model training by organizing images and annotations into training and testing sets.
3. Model Training: The YOLO v5 model was trained using the annotated dataset, with configurations tailored to the task of sign language detection. The YOLO v5 model was fine-tuned for sign language detection. We configured the model parameters, including image size, batch size, and the number of epochs. During training, the model learned to recognize patterns and classify sign language gestures accurately. Training progress and performance were monitored using TensorBoard.
