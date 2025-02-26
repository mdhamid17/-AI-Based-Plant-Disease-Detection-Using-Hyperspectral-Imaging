# AI-Based Plant Disease Detection Using Hyperspectral Imaging

## Overview
This project focuses on **early detection of plant diseases** using **hyperspectral imaging** and **deep learning**. By analyzing spectral and visual features, the model aims to **identify diseases at an early stage**, improving precision agriculture and crop health monitoring.

## Features
- **Multi-Spectral Image Analysis**: Leverages hyperspectral imaging to detect diseases beyond visible spectrum analysis.
- **Deep Learning Model**: Implements **CNN-based models (ResNet, EfficientNet) or Vision Transformers (ViTs)** for disease classification.
- **Custom Dataset Processing**: Works with **public datasets (PlantVillage, PhenoBench)** or hyperspectral datasets from research sources.
- **Explainability (XAI)**: Uses **Grad-CAM** to visualize AI decision-making for interpretability.
- **Edge AI Deployment**: Optimized for **Jetson Nano, Raspberry Pi**, enabling real-time field analysis.

## Technologies Used
- **Python**
- **TensorFlow / PyTorch**
- **OpenCV**
- **Hyperspectral Imaging Techniques**
- **Grad-CAM for Explainability**
- **Machine Learning Frameworks (Sci-Kit Learn, Pandas, NumPy)**

## Installation
```bash
# Clone the repository
git clone https://github.com/yourusername/Plant-Disease-Detection.git
cd Plant-Disease-Detection

# Install dependencies
pip install -r requirements.txt
```

## Usage
```python
python detect_disease.py --input path_to_plant_image --output results.json
```

## Dataset
- **PlantVillage**: Large-scale dataset with labeled healthy and diseased plant images.
- **PhenoBench**: Hyperspectral imaging dataset for plant phenotyping and disease detection.
- **Custom Data Collection**: Can be extended with real-world hyperspectral plant images.

## Results (Undergoing)
| Healthy Leaf | Diseased Leaf |
|-------------|--------------|
| ![Healthy](images/healthy.jpg) | ![Diseased](images/diseased.jpg) |

## Future Work
- Enhance **multi-modal learning** by combining **RGB, thermal, and hyperspectral data**.
- Improve **generalization across different crop species**.
- Develop **mobile applications for real-time field use**.
- Publish findings in **CVPR, ICCV, or AgriAI conferences**.

## Contributing
Feel free to contribute by submitting **pull requests** or opening **issues**.



## Contact
For inquiries, contact **Md Hamid** at mdhamid1752002@gmail.com.
