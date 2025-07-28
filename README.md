# CSS182-4_CO2.2
Final Project
**Animal Detection and Classification using RF-DETR**
This repository provides the complete implementation of the Receptive Field DETR (RF-DETR) model tailored for detecting and classifying multiple animal classes from images. The system leverages a receptive field enhancement module, CNN backbone, and Transformer encoder-decoder for end-to-end object detection on a custom COCO JSON dataset sourced from Roboflow.

Dataset link: https://universe.roboflow.com/datasci-f3d5w/animals-ij5d2-nkoj2

Format: COCO JSON

Source: Roboflow

Images: 1000 (700 train, 200 val, 100 test)

Classes: cat, chicken, cow, dog, fox, goat, horse, person, raccoon, skunk

# Model: RF-DETR Medium

RF-DETR Medium is a mid-sized transformer-based model designed for real-time object detection. It balances computational efficiency and detection accuracy and can run smoothly on standard GPUs and some edge devices.

**Setup Instructions**

1. Clone the repository
   ```
   git clone https://github.com/Ashton2143/CSS182-4_CO2.2.git
   cd CSS182-4_CO2.2
   ```
  


2. Set Up Virtual Environment
   Before setting up the virtual environement, ensure that Python 3.10.11 is installed. If Python 3.10.11 is not installed, download and install it from Python Downloads.
   ```bash
   # Create and activate a virtual environment
   virtualenv venv --python=python3.10
   source venv/bin/activate   # On Linux/Mac
   .\venv\Scripts\activate      # On Windows
   ```

3. Install Dependencies

    ```bash
    pip install -r requirements.txt
    ```

4. Run the Project Notebook

    After setting up the environment and configuring the dataset, open the Jupyter Notebook to run the training process or start predicting with your own images.
   
   
