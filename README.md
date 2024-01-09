# Automatic Road Traffic Signs Detection using Object-Localization and Classification Model

**Motivation:**

*This project aims to address the challenges of road sign recognition for both visually impaired individuals and autonomous vehicles. Our model addresses safety concerns, contributes to accessibility, and enables automation for vehicles, creating a safer and more inclusive transportation ecosystem.*

**Technology:**

* YOLOv8 object detection system

**Dataset:**

* Chinese Traffic Sign Dataset (CATSDB) with 20,000 images split 70/30 for training and testing

**Methodology:**

* **Iteration 1:** Trained YOLOv6 model on a subset of the dataset with accurate bounding box identification.
* **Iteration 2:** Used full dataset with 4-5 epochs and batch size of 16 to balance overfitting and underfitting.

**Results:**

* Achieved zero dfl_loss, indicating accurate bounding box identification.
* Final learning rate: 0.0001976
* iou_loss: 0.2402
* cls_loss: 0.5126

**Impact:**

* Improved safety for individuals with visual impairments and ADHD.
* Enhanced accessibility for diverse needs.
* Contributed to safer and more efficient autonomous driving.

**Background:**

* Traditional road sign recognition methods lack real-time accuracy, especially for individuals with disabilities. YOLOv8 offers a real-time object detection solution for overcoming these limitations.

**Algorithm:**

* YOLOv8 architecture with input, backbone, neck, and output stages. Utilizes data augmentation, C2F and SPPF layers, FPN and PAN combination in the neck, and decoupled detection and classification in the output.

**Future Work:**

* Further optimize model performance.
* Explore integration with autonomous vehicle systems.
* Develop user interface for accessibility applications.

