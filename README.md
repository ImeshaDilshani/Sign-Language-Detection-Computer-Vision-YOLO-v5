# Sign Language Detection Computer Vision YOLO-v5

The project focuses on leveraging computer vision techniques to detect sign language gestures using the YOLO v5 model. By training the model on a dataset of annotated images, we enable it to recognize and interpret various hand activities associated with sign language.

![val_batch0_labels](https://github.com/ImeshaDilshani/Sign-Language-Detection-Computer-Vision-YOLO-v5/assets/93858302/bf8d3356-5b0e-44ae-95bd-d6329ded1cfc)

## Implementation Steps

**1. Data Collection:** collected images of sign language gestures for six specific gestures: "Hello," "Yes," "No," "Thanks," "I love you," and "Please." Images were captured using OpenCV and a webcam, ensuring a diverse set of hand poses and lighting conditions.
   
**2. Annotation and Training:** The collected images were annotated using the LabelImg tool, and the dataset was prepared for model training by organizing images and annotations into training and testing sets.
   
**3. Model Training:** The YOLO v5 model was trained using the annotated dataset, with configurations tailored to the task of sign language detection. The YOLO v5 model was fine-tuned for sign language detection. We configured the model parameters, including image size, batch size, and the number of epochs. During training, the model learned to recognize patterns and classify sign language gestures accurately. Training progress and performance were monitored using TensorBoard.

![train_batch2](https://github.com/ImeshaDilshani/Sign-Language-Detection-Computer-Vision-YOLO-v5/assets/93858302/4fd84a3d-c1bf-4899-bcd4-186ac0c1e3e9)

![train_batch1](https://github.com/ImeshaDilshani/Sign-Language-Detection-Computer-Vision-YOLO-v5/assets/93858302/a0f7417a-f2bf-43dd-8cb5-c5c82f009ecd)
