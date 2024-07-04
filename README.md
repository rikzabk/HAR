# HAR
Final College Project: Video-Based Human Activity Recognition with Keyframe Extraction and Convolutional Neural Networks

## Major Challenge
The **large number of frames** in videos significantly **increases** the **computational load** during model training, resulting in **slower training times**

## Objectives
1. To analyze the impact of the keyframe extractor, Katna, on the model training process
2. To identify the optimal combination of feature extraction and CNN architectures

## Research Methodology
<img width="1630" alt="image" src="https://github.com/rikzabk/HAR/assets/81854367/57121ac5-7d12-495b-81a1-5372addcc72f">
<img width="751" alt="image" src="https://github.com/rikzabk/HAR/assets/81854367/08e57106-0154-474f-bd93-1e961ce19af6">



## Findings
1. The VGG19 model exhibited **overfitting** as a consequence of its suboptimal development.
   <img width="733" alt="image" src="https://github.com/rikzabk/HAR/assets/81854367/6d330214-8105-4da7-949b-321aed216b78">
2. The combination of frame extraction and MobileNetV2 achieved the highest performance, with an **overall evaluation score of 94%**.
   <img width="512" alt="image" src="https://github.com/rikzabk/HAR/assets/81854367/9da3a7fc-28b6-4d85-b193-704b73bdc963">
3. The keyframe extractor, Katna, significantly **accelerated training time** by **up to 11.12 times or 111.96% faster**.
   <img width="626" alt="image" src="https://github.com/rikzabk/HAR/assets/81854367/e815d24d-9196-4b94-b5a5-04353f622d19">



## Suggestions
1. The VGG19 model requires the application of **batch normalization** and **dropout** to **minimize overfitting**.
2. To effectively handle the spatiotemporal nature of the data and learn motion patterns, the implementation of architecutres like **3D-CNN or LSTM** is **strongly advised**.
