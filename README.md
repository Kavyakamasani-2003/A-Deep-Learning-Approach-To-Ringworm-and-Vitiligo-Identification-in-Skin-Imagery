# A Deep Learning Approach To Ringworm and Vitiligo Identification in Skin Imagery

## Abstract
Diagnosing skin illnesses such as vitiligo and ringworm can be challenging due to their resemblance to other dermatological conditions and varying appearances. This project proposes a novel approach that combines **Local Binary Patterns (LBP)** and **Grey Level Co-occurrence Matrix (GLCM)**, two powerful feature extraction techniques. 

- **Local Binary Patterns (LBP)**: Captures local texture patterns within an image.
- **Grey Level Co-occurrence Matrix (GLCM)**: Analyzes spatial relationships between pixels to extract textural information.

Using dermatological images, these extracted features successfully distinguish vitiligo and ringworm lesions with **99% accuracy**. Various deep learning models were tested for classification, including:
- Google Net
- Mobile Net
- ResNet50
- ResNet101
- Xception
- CNN
- VGG19

Among these, **VGG19** provided the best results, achieving **99.19% accuracy**. By utilizing **transfer learning**, the pre-trained VGG19 model is fine-tuned to enhance its classification capabilities. The integration of **GLCM** and **LBP** features improves the model’s ability to differentiate between skin conditions with limited training data. 

Additionally, a **Graphical User Interface (GUI)** has been developed to facilitate automated diagnosis, aiding medical professionals in early detection and treatment, ultimately enhancing patient care.

## Index Terms
- Deep Learning Algorithms
- Ringworm
- Vitiligo
- Grey-Level Co-occurrence Matrix (GLCM)
- Local Binary Patterns (LBP)
- Weber Local Descriptor
- Histogram of Oriented Gradients (HOG)
- Visual Geometry Group 19 (VGG19)
- Graphical User Interface (GUI)

## Dataset
The dataset consists of dermatological images containing ringworm and vitiligo lesions. Images are preprocessed to enhance feature extraction and classification performance.

## Approach
1. **Data Preprocessing**: Image normalization and augmentation.
2. **Feature Extraction**: Applying LBP and GLCM techniques.
3. **Model Selection & Training**: Implementing deep learning models with transfer learning.
4. **Evaluation**: Performance analysis using accuracy and other metrics.
5. **User Interface**: Development of a GUI for practical implementation.

## Installation & Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/Kavyakamasani-2003/A-Deep-Learning-Approach-To-Ringworm-and-Vitiligo-Identification-in-Skin-Imagery.git
   ```
2. Install dependencies:
   ```bash
   pip install numpy pandas tensorflow keras opencv-python
   ```
3. Run the model:
   ```bash
   python classify_skin_lesions.py
   ```

## Results
The proposed model effectively classifies vitiligo and ringworm lesions with **99.19% accuracy**, leveraging deep learning and advanced texture feature extraction techniques.

## Future Enhancements
- Exploring additional deep learning architectures.
- Expanding the dataset with more diverse dermatological images.
- Optimizing the GUI for real-world clinical applications.

## Contributors
- **Kavyakamasani-2003**

## License
This project is open-source and available under the [MIT License](LICENSE).


