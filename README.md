# 🧩 Sudoku AI Solver

[![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)](https://python.org)
[![PyTorch](https://img.shields.io/badge/PyTorch-2.0+-red.svg)](https://pytorch.org)
[![Computer Vision](https://img.shields.io/badge/CV-Digit%20Recognition-green.svg)](/)
[![Deep Learning](https://img.shields.io/badge/DL-CNN%20%2B%20LSTM-orange.svg)](/)
[![License](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

> **Advanced AI system combining Computer Vision and Deep Learning to solve Sudoku puzzles**  
> *University research project achieving 80%+ accuracy on complex multi-modal AI tasks*

## 🎯 Project Overview

This project implements a sophisticated two-stage AI system that can **read and solve Sudoku puzzles from images** using state-of-the-art deep learning techniques. Developed as part of the **Artificial Neural Networks and Cognitive Models** course at Technical University of Applied Sciences Würzburg-Schweinfurt (THWS).

### 🧠 Key Innovation
- **Multi-modal AI approach**: Combines computer vision for digit recognition with logical reasoning for puzzle solving
- **End-to-end pipeline**: From raw images to complete puzzle solutions
- **Academic rigor**: Individual implementation using only PyTorch APIs (no pre-built libraries)

## 🏗️ System Architecture

### Stage 1: Computer Vision Pipeline 🔍
- **Input**: 252×252 pixel Sudoku images with partially filled grids (41 digits, 40 empty cells)
- **Process**: Convolutional Neural Network (CNN) for digit recognition and spatial mapping
- **Output**: Recognized digits with precise grid coordinates (9×9 position mapping)

### Stage 2: AI Puzzle Solver 🤖  
- **Input**: Partially filled Sudoku grids from Stage 1
- **Process**: LSTM-based neural network enforcing Sudoku constraints
- **Output**: Complete puzzle solution following all Sudoku rules

## 📊 Performance Metrics

| Task | Model | Accuracy | Dataset Size |
|------|-------|----------|--------------|
| **Digit Recognition** | CNN | **85%+** | 50,000 training images |
| **Puzzle Solving** | LSTM | **80%+** | 50,000 puzzle pairs |
| **End-to-End** | Combined | **80%+** | 10,000 test cases |


## 🔬 Technical Implementation

### Computer Vision Module (Task 1)
- **Preprocessing**: Image normalization, noise reduction, grid detection
- **Architecture**: Multi-layer CNN with spatial attention mechanisms
- **Training**: 50,000 images with coordinate-based supervision
- **Challenges Solved**: 
  - Handwritten digit variations
  - Grid alignment and cell extraction
  - Spatial coordinate mapping

### AI Solver Module (Task 2)
- **Constraint Modeling**: Sudoku rules encoded as neural network constraints
- **Architecture**: LSTM with attention mechanism for sequential decision making
- **Training**: Reinforcement learning approach with constraint satisfaction
- **Challenges Solved**:
  - Logical reasoning in neural networks
  - Constraint satisfaction optimization
  - Multi-step decision making

## 📈 Results & Analysis

### Model Performance
- **Digit Recognition Accuracy**: 85%+ on unseen test images
- **Puzzle Solving Success Rate**: 80%+ complete solutions
- **Processing Speed**: <2 seconds per puzzle on CPU

### Key Achievements
✅ **Academic Excellence**: Top performance in university competition  
✅ **Individual Implementation**: No external AI libraries used  
✅ **Scalable Architecture**: Handles 10,000+ test cases efficiently  
✅ **Robust Performance**: Works with various handwriting styles  

## 🛠️ Technologies Used

| Category | Technologies |
|----------|-------------|
| **Deep Learning** | PyTorch, Neural Networks, CNN, LSTM |
| **Computer Vision** | Image Processing, Digit Recognition, OCR |
| **AI/ML** | Constraint Satisfaction, Reinforcement Learning |
| **Data Science** | NumPy, Data Preprocessing, Model Evaluation |
| **Development** | Python, Jupyter Notebooks, Git |

## 🎓 Academic Context

**Course**: Artificial Neural Networks and Cognitive Models  
**Institution**: Technical University of Applied Sciences Würzburg-Schweinfurt (THWS)  
**Program**: Master of Science in Artificial Intelligence  
**Year**: 2023-2024  
**Achievement**: Individual research project with competitive evaluation  


## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👨‍💻 Author

**Gurudeep Haleangadi Nagesh**  
*AI/ML Engineer | Master's Student in Artificial Intelligence*

- 🎓 Technical University Würzburg-Schweinfurt, Germany
- 💼 Working Student at ZMI GmbH  
- 🔗 [LinkedIn](https://linkedin.com/in/gurudeephn)
- 📧 [Email](mailto:gurudeep409@gmail.com)
- 🌐 [Portfolio](https://gurudeep-hn.github.io)

---

⭐ **If this project helped you or inspired your work, please consider giving it a star!** ⭐

*Built with ❤️ for advancing AI research and practical applications*
