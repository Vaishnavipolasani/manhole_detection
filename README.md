# Manhole Detection using Convolutional Neural Networks (CNN)

## Abstract
Urban safety is crucial, with manholes posing risks when left open or improperly maintained. This project employs CNNs for real-time manhole status prediction to assist authorities in addressing hazardous conditions effectively.

---

## Features
- **Real-time detection** of manhole statuses (Open, Closed, Road).
- High accuracy and robustness with a **CNN-based model**.
- Visualizations for **confusion matrix**, **F1-scores**, and **predictions**.

---

## Methodology

![Image Description](Manhole%20detection/dd.jpg)

### Data Collection
- Images of manholes were captured using **drones**.

### Data Preprocessing
- Converted images to **grayscale**.
- Resized images to **72x72 pixels**.

### Model Architecture
- Built a CNN with:
  - **Three convolutional layers**.
  - **Max-pooling layers**.
  - **Fully connected layers**.

### Training and Evaluation
- Achieved:
  - **Accuracy**: 92.003%
  - **Test Loss**: 0.44
  - **F1-Score**: 0.92

### Metrics and Results
- Evaluated **precision**, **recall**, and **F1-score** for each class (Open, Closed, Road).
- Generated visualizations:
  - **Heatmaps**.
  - **Bar plots** for performance insights.

## Results
- **Accuracy**: 92.003%
- **F1-Score**: 0.92
- **Test Loss**: 0.44
- Detailed metrics and **confusion matrix** are included for further insights.

---

## Visualizations
- **Confusion Matrix**
- **F1-Score by Category**
- **Sample Predictions**

---

## Applications
- **Urban safety** and infrastructure management.
- **Real-time hazard detection** and mitigation.
- **Smart city initiatives** integrating drone-based monitoring systems.

---

## Future Work
- Enhance **dataset diversity** for broader generalization.
- Optimize the model for **real-time deployment** on edge devices.
- Integrate **predictive maintenance analytics**.

---

## References
1. Amit Mankotia et al., *IoT-based systems for manhole detection*.
2. Nguyen Truc Ha et al., *Deep learning for urban event detection*.
3. Dangfeng Pang et al., *Optimized YOLO for manhole detection*.
4. Additional references as listed in the research paper.

---

## Acknowledgments
We extend our gratitude to all researchers and institutions whose work has inspired this project. Special thanks to the project contributors and advisors.
