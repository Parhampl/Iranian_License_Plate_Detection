
# Iranian License Plate Recognition

This repository contains an end-to-end implementation for Iranian License Plate Recognition using modern AI techniques. The project focuses on detecting and recognizing license plates and extracting digits and text using different OCR methods. This project starts with trying to make a custom OCR and custom Detector. However, since the easy OCR and YOLOv8 combination have been way better than the custom ones, I just uploaded the better code and compared them in the README file.

## Features
- **YOLOv8 Detection**: For license plate detection.
- **OCR Methods**: EasyOCR, Detectron, and custom OCR for digit and text recognition.
- **Dataset**: Includes a custom dataset created with Roboflow.

## Project Structure
```
Iranian-License-Plate-Recognition/
├── data/                         # Visualizations and sample results
├── notebooks/                    # Jupyter Notebooks for implementation
├── models/                       # Trained model weights
├── results/                      # Evaluation results
├── docs/                         # Project report and additional documentation
└── README.md                     # Project overview and instructions
```

## Results
- **mAP**: 98.7% (YOLOv8 with Roboflow dataset)
- **Precision**: 97.7%
- **Recall**: 95.5%

## How to Use
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/Iranian-License-Plate-Recognition.git
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Open and run the notebooks for training and evaluation:
   ```bash
   jupyter notebook notebooks/ANPR_OCR_Original.ipynb
   ```

## Comparisons
| Approach       | mAP    | Precision | Recall |
|----------------|--------|-----------|--------|
| YOLOv8        | 98.7%  | 97.7%     | 95.5%  |
| Custom Dataset | 95.2%  | 65.8%     | 76.2%  |

## Acknowledgments
This project was developed as part of an AI course under the guidance of Dr. Zabihifar.


