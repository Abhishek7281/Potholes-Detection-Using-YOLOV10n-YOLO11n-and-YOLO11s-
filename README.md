# Potholes-Detection-Using-YOLOV10n-YOLO11n-and-YOLO11s-


# Project Overview

    This project leverages YOLO (You Only Look Once) models for real-time pothole detection to enhance road safety and maintenance. By utilizing deep learning and computer vision, this solution enables efficient, automated, and cost-effective pothole detection through video footage captured by vehicles.

    Dataset Link : https://drive.google.com/file/d/1qEBV9wqBzuLbUBFnV_GBROCJLSoygrUT/view
    Output Video Link after applying YOLOV10n model : https://drive.google.com/file/d/1Qm3A7G3lJha_4IugQAhVfgAz7DwmUZtk/view?usp=sharing

# Key Features

    I. Real-Time Detection: Uses YOLOv10n, YOLO11n, and YOLO11s models for accurate pothole identification.
    
    II. High Efficiency: Achieves up to 85.8% mAP@50 accuracy with a compact model size (5.6MB).
    
    III. Geospatial Mapping: Integrates GPS & GIS for precise pothole localization and reporting.
    
    IV. Cost Estimation Algorithm: Provides estimated repair costs based on detected pothole data.
    
    V. Interactive Dashboard: Visualizes real-time pothole data for road maintenance authorities.


# Methodology

    I. Data Collection: Utilized 13,767 pothole images from multiple sources.
    
    II. Model Training: Trained YOLO models using PyTorch on NVIDIA RTX A4000 GPU.
    
    III. Performance Evaluation: Assessed models based on mAP, precision, recall, and inference time.
    
    IV. Real-Time Processing: Integrated detection system into vehicles with live video feeds.
    
    V. GIS Integration: Tagged detected potholes on an interactive geographic information system.

# Installation & Usage

    I. Clone the repository:
     git clone https://github.com/your-repo/pothole-detection.git
    cd pothole-detection
  
    II. Install dependencies:
     pip install -r requirements.txt
  
    III. Run real-time detection:
     python detect.py --video input_video.mp4
  
     IV. Generate pothole reports:
      python report_generator.py


# Applications

    I. Automated Road Inspections
    
    II. Smart City Infrastructure Monitoring
    
    III. Autonomous Vehicle Navigation
    
    IV. Government Road Maintenance & Planning

# Future Enhancements

    I. Improve detection under varying weather conditions.
    
    II. Optimize for deployment on mobile & IoT devices.
    
    III. Expand dataset for broader generalization.

<!-- Contributors

Abhishek Kumar Pathak (IIT Indore)

Ankit Kumar Singh (Motihari College of Engineering)

Pankaj Kumar (Vaishali Engineering College)

Vimal Bhatia (IIT Indore, Skoda Auto University)

Ondrej Krejcar (MJIIT, Universiti Teknologi Malaysia)-->

# Acknowledgments

    This research is supported by SERB, DST, Government of India (CRG/2021/001215) and iHub DivyaSampark, IIT Roorkee.

# License

    This project is licensed under the MIT License.
