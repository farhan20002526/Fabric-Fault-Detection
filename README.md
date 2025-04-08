# Fabric Fault Detection for Industrial Quality Check

This project leverages computer vision and deep learning to detect faults in fabric for industrial quality control. The system is built using the YOLOv8 model, which has been custom trained on a dataset of fabric images. The web application is deployed using **Streamlit** for real-time detection and visualization.
## About
This system aims to assist in industrial fabric inspection by detecting fabric defects, ensuring quality control and reducing manual labor. It utilizes the state-of-the-art YOLOv8 object detection model, which has been trained on a custom dataset to recognize various types of fabric faults. The app provides a user-friendly interface via **Streamlit** for real-time fault detection.

## Technologies
- **YOLOv8**: Custom-trained deep learning model for object detection.
- **Streamlit**: Framework for creating interactive web applications.
- **OpenCV**: Used for image processing and manipulation.
- **Python**: Programming language for model training and app development.
- **PyTorch**: Deep learning framework used for training the YOLOv8 model.

## Setup Instructions

To run this project locally, follow these steps:

### 1. Clone the repository
```bash
git clone https://github.com/farhan20002526/Fabric-Fault-Detection.git
cd Fabric-Fault-Detection


2. Create a virtual environment and install dependencies
bash
Copy
Edit
python -m venv venv
source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
pip install -r requirements.txt
3. Download the pre-trained YOLOv8 model
Download the model weights and place them in the models/ directory. You can find the pretrained model weights here.

4. Run the Streamlit app
bash
Copy
Edit
streamlit run app.py
Your app will be accessible at http://localhost:8501.

Usage
Once the application is running, you can upload fabric images or videos through the Streamlit interface. The model will process the media and highlight any detected faults in the fabric. The results will be displayed in real-time.

Input: Upload images or videos of fabric.

Output: Visualizations of the detected faults.