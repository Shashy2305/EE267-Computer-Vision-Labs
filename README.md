# EE267 Autonomous Vehicle Labs - Fall 2025

[![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)](https://www.python.org/downloads/)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![UC Riverside](https://img.shields.io/badge/University-UC%20Riverside-gold.svg)](https://www.ucr.edu/)

Comprehensive repository for all EE267 Computer Vision lab assignments completed during Fall 2025 at UC Riverside.

## 📚 Course Information

- **Course**: EE267 - Autonomous Vehicle
- **Semester**: Fall 2025
- **Institution**: University of California, Riverside
- **Instructor**: [Course Instructor Name]
- **Team**: Team 3

## 📂 Repository Structure

```
EE267-Computer-Vision-Labs/
│
├── Lab1/                          # Lab 1: Object Detection and Tracking
│   ├── Pictures/                  # Image datasets and results
│   ├── agents/                    # Agent implementations
│   ├── utils/                     # Utility functions
│   ├── automatic_control.py       # Automatic control system
│   ├── detector.py                # Object detection algorithms
│   ├── eval.py                    # Evaluation scripts
│   ├── generate_traffic.py        # Traffic generation
│   ├── pointpillar.yaml          # Configuration file
│   ├── pointpillar_7728.pth      # Model weights
│   └── README.md                  # Lab 1 specific documentation
│
├── Lab2/                          # Lab 2: Visual Odometry and SLAM
│   ├── Pictures/                  # Image datasets and results
│   ├── agents/                    # Agent implementations
│   ├── utils/                     # Utility functions
│   ├── automatic_control.py       # Automatic control system
│   ├── generate_traffic.py        # Traffic generation
│   ├── odometry.py                # Visual odometry implementation
│   └── README.md                  # Lab 2 specific documentation
│
├── .gitignore                     # Git ignore rules
├── LICENSE                        # MIT License
└── README.md                      # This file
```

## 🔬 Lab Descriptions

### Lab 1: Object Detection and Tracking
**Topics Covered:**
- Object detection using PointPillar architecture
- Real-time tracking algorithms
- Bounding box visualization
- Traffic scenario generation
- Performance evaluation metrics

**Key Files:**
- `detector.py`: Main object detection implementation
- `eval.py`: Evaluation metrics and benchmarking
- `pointpillar_7728.pth`: Pre-trained model weights

**Technologies:**
- Python 3.8+
- PyTorch
- OpenCV
- NumPy

---

### Lab 2: Visual Odometry and SLAM
**Topics Covered:**
- Visual odometry estimation
- Simultaneous Localization and Mapping (SLAM)
- Trajectory planning
- Sensor fusion
- Motion control

**Key Files:**
- `odometry.py`: Visual odometry algorithms
- `automatic_control.py`: Control system implementation
- `generate_traffic.py`: Traffic simulation

**Technologies:**
- Python 3.8+
- Computer Vision libraries
- CARLA Simulator
- Sensor processing

---

## 🚀 Getting Started

### Prerequisites
```bash
# Required Python packages
pip install numpy
pip install opencv-python
pip install torch torchvision
pip install matplotlib
pip install pandas
pip install pyyaml
```

### Installation
```bash
# Clone the repository
git clone https://github.com/Shashy2305/EE267-Computer-Vision-Labs.git
cd EE267-Computer-Vision-Labs

# Navigate to specific lab
cd Lab1  # or Lab2
```

### Running the Labs

**Lab 1:**
```bash
python detector.py
python eval.py
python generate_traffic.py
```

**Lab 2:**
```bash
python odometry.py
python automatic_control.py
```

## 📊 Results and Performance

### Lab 1 Results
- Object detection accuracy: [To be added]
- Processing speed: [To be added]
- mAP score: [To be added]

### Lab 2 Results
- Odometry error: [To be added]
- SLAM accuracy: [To be added]
- Trajectory precision: [To be added]

## 🛠️ Technologies Used

- **Programming Language**: Python 3.8+
- **Deep Learning**: PyTorch
- **Computer Vision**: OpenCV
- **Numerical Computing**: NumPy, Pandas
- **Visualization**: Matplotlib
- **Configuration**: YAML
- **Version Control**: Git, GitHub

## 👥 Team Members

- **Shashwat Shah** - [GitHub](https://github.com/Shashy2305) | [LinkedIn](https://linkedin.com/in/shashwat-shah-32765a248)
- Team Member 2
- Team Member 3
- Team Member 4

## 📝 Assignment Details

### Grading Criteria
- Code implementation: 40%
- Documentation: 20%
- Results and analysis: 30%
- Presentation: 10%

### Submission Requirements
- Complete source code
- Detailed README for each lab
- Results visualization
- Performance analysis report

## 🔗 Related Repositories

- [Original Lab 1 Repository](https://github.com/Shashy2305/ee267-fall25-lab1-team-3)
- [Original Lab 2 Repository](https://github.com/Shashy2305/ee267-fall25-lab2-team-3)

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 📧 Contact

**Shashwat Shah**
- Email: 0012shashwatshah@gmail.com
- LinkedIn: [shashwat-shah-32765a248](https://linkedin.com/in/shashwat-shah-32765a248)
- Portfolio: [shashportfoliorobotics.web.app](https://shashportfoliorobotics.web.app/)

## 🙏 Acknowledgments

- UC Riverside Department of Electrical and Computer Engineering
- Course instructors and TAs
- Team members for collaboration
- Open-source computer vision community

---

**Note**: This repository consolidates all EE267 lab assignments for better organization and accessibility. Individual lab folders contain specific implementations and documentation.
