# Chest-Xray-Pneumonia-Detection-Neural-Network-Model
This project aims to detect pneumonia from chest X-ray images using a Convolutional Neural Network (CNN). The model is trained on a dataset of chest X-ray images and evaluated for its performance. The project is ongoing, and I aim to fine-tune the model in the future. 

**If you are seeing this, it means I am still working on the project.**

![image](https://github.com/CodeByGirum/Chest-Xray-Pneumonia-Detection-Neural-Network-Model/assets/60083179/76fee3be-7559-4c6d-bfd8-7f6d01b4bb85)


## Data

The dataset consisted of chest X-ray images divided into two main categories: NORMAL and PNEUMONIA. The images were sourced from a publicly available medical imaging dataset.

## Methodology

1. **Data Preprocessing**: Images were resized and normalized to a uniform scale. Data augmentation techniques like rotation, width shift, height shift, and horizontal flip were applied to increase the robustness of the model.

2. **Model Development**: A CNN was designed with multiple convolutional, max pooling, and dense layers. Dropout layers were also incorporated to prevent overfitting.

3. **Training**: The model was trained on the training dataset, with a portion set aside for validation to monitor the training process for signs of overfitting.

4. **Evaluation**: After training, the model was evaluated on a separate test set to measure its accuracy and ability to generalize to new data.

## Results

- The CNN achieved an accuracy of approximately 74% on the validation dataset.
- The model tended to predict most test images as having pneumonia, indicating potential issues with class imbalance or model sensitivity.

## Discussion

- The results suggest that while the model can identify pneumonia in many cases, its tendency to over-predict pneumonia points to the need for further tuning. Adjustments to the model's architecture, training process, or data preprocessing steps could improve its specificity and overall accuracy.

## Conclusion

The project demonstrated the feasibility of using CNNs for medical image analysis, specifically for pneumonia detection in chest X-rays. Future work will focus on optimizing the model and expanding the dataset to include more varied examples.

## Acknowledgments

Thanks to the providers of the dataset and computational resources that made this project possible.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

