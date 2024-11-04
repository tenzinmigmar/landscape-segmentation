# Lunar Landscape Segmentation with U-Net

A machine learning project that trains a semantic segmentation model for synthetic lunar landscape image data using the U-Net architecture.

![](https://github.com/tenzinmigmar/landscape-segmentation/blob/main/banner.png)

## Overview
This project uses computer vision to segment various realistic lunar landscapes into one of three different classes (small rocks, large rocks, and the sky), using a segmentation model built on the U-Net architecture that was trained on nearly ~10k realistic renders of lunar landscapes and their masks.

## Features
- About the dataset
- Data Visualization
- Data Preprocessing
- U-Net Architecture
- Compiling the model
- Predictions + Model Performance
- Notes on Model Performance
- Final thoughts

## Project Structure
```
.
├── lunar-rocky-landscape-segmentation-with-u-net.ipynb
└── README.md
```

## Installation
```bash
# clone repository
git clone https://github.com/yourusername/landscape-segmentation.git

# install required packages
pip install -r requirements.txt
```

## Dependencies
- Python 3.7+
- tensorflow/keras
- cv2
- os
- sklearn
- numpy
- matplotlib

## Contributing
Feel free to open issues and pull requests for any improvements.

## License
MIT License

## Acknowledgments
- Dataset sourced from Kaggle: [Lunar Rocky Landscape Dataset](https://www.kaggle.com/datasets/romainpessia/artificial-lunar-rocky-landscape-dataset)
