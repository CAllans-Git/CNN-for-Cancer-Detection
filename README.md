Breast Cancer Detection Using CNN
Breast cancer is a significant contributor to cancer-related mortality globally. Accurately diagnosing cancer from eosin-stained images poses challenges, often resulting in discrepancies among medical professionals. Computer-Aided Diagnosis (CAD) systems offer a solution to streamline this complex process, reducing costs and enhancing efficiency. While traditional classification methods rely on problem-specific feature extraction techniques based on domain knowledge, deep learning approaches have emerged as promising alternatives to address the limitations of feature-based techniques.

We present a novel approach for classifying hematoxylin and eosin-stained breast biopsy images using Convolutional Neural Networks (CNNs). Our method categorizes images into four classes: normal tissue, benign lesion, in situ carcinoma, and invasive carcinoma, as well as binary classification of carcinoma and non-carcinoma. The network architecture is meticulously crafted to capture information across different scales, encompassing individual nuclei and overall tissue organization. This design facilitates seamless integration with whole-slide histology images. Our approach achieves a classification accuracy of 77.8% for the four-class classification task and demonstrates a sensitivity of 95.6% for detecting cancer cases.

To utilize this project:

Ensure you have Python 3 installed to run the program.
Download the preprocessed image data from here. Place the downloaded files in the same folder as the .py file.
Install the required Python packages using pip install package-name:
keras
tensorflow (both CPU or GPU version should suffice)
PIL
numpy
Adjust the default hyperparameters by modifying the variables indicated between # in the initial lines of the script.
To execute the program, navigate to the folder in the command line and use the following command:

Copy code
python BreastCancer.py
Additionally, we provide a pretrained model. To test your own image or one of the samples using this model, place the image in the folder with the .py file and rename it as my_image.jpg. During execution, follow the on-screen prompts to choose to test your own image.