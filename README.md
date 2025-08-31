
# EdgeAI-RiscV-VSDSquadron

**A comprehensive 10-day workshop repository covering RISC-V and Edge AI development**

---

## Overview

**EdgeAI-RiscV-VSDSquadron** is a repository documenting a 10-day extensive workshop on applying **RISC-V architecture** in **Edge AI** contexts.  

It contains instructional Jupyter notebooks, datasets, header files, and visual outputs used throughout the sessions—making it a complete reference for learners, researchers, and hobbyists exploring the intersection of **AI and RISC-V**.

---
This repository documents my learning journey through the RISC-V Edge AI with VSDSquadron PRO course, offered by VLSI System Design (VSD). The course focuses on implementing machine learning (ML) and artificial intelligence (AI) models on resource-constrained embedded systems, targeting the VSDSquadron PRO board powered by the SiFive FE310-G002 RISC-V SoC. Due to the absence of physical hardware, this project was developed and simulated using Visual Studio Code (VSCode) for both the camera-based image capture and the training of a quantized neural network for MNIST handwritten digit classification.

The project uses a training.py script to train and quantize an 8-bit neural network model for MNIST digit recognition, with inference simulated in a bare-metal environment compatible with the SiFive FE310-G002. This README outlines the course content, project setup, key learnings, and instructions for running the simulated application.

## 📂 Repository Structure

```
├── Datasets(.csv)/
│   └── ...         # CSV files used for training, evaluation, or demonstration
├── Output_Images/
│   └── ...         # Visual outputs and plots generated during the workshop
├── header files/
│   └── ...         # C headers for interfacing with RISC-V or system code
├── MNIST_prediction(keras).ipynb
├── Neural_Networks.ipynb
├── Regression_Classification.ipynb
├── Regression_Optimization.ipynb
├── README.md       # (You are here)
├── LICENSE         # Repository's open-source license
└── zadig-2.9.exe   # Utility used for USB driver installation (optional)
```

---

## 📖 Content Highlights

### 🔹 Jupyter Notebooks
- **`Neural_Networks.ipynb`**  
  Covers the fundamentals of neural networks, model building, training visualization, and hyperparameter influences.

- **`Regression_Classification.ipynb`**  
  Explores regression and classification tasks with datasets, including performance evaluation.

- **`Regression_Optimization.ipynb`**  
  Introduces optimization techniques such as gradient descent, learning rate tuning, and regularization.

- **`MNIST_prediction(keras).ipynb`**  
  Demonstrates handwritten digit recognition using Keras, with deployment insights for RISC-V edge devices.

### 🔹 Supporting Assets
- **Datasets(.csv)** – Input datasets for training and testing.  
- **Output_Images** – Visualization results (accuracy curves, confusion matrices, plots).  
- **header files** – Useful C headers for RISC-V programming and integration.  
- **zadig-2.9.exe** – Windows tool for USB driver installation (only needed if using hardware setup).

---

## Getting Started

###  Prerequisites
- Python 3.x  
- Jupyter Notebook or JupyterLab  
- Python libraries:  
  ```bash
  pip install numpy pandas matplotlib scikit-learn tensorflow keras
  ```

*(Consider adding a `requirements.txt` for convenience.)*

---

### ⚡ Setup & Usage

1. **Clone the repository**
   ```bash
   git clone https://github.com/manal-a7med/EdgeAi-RiscV-VSDSquadron.git
   cd EdgeAi-RiscV-VSDSquadron
   ```

2. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```
   *(If `requirements.txt` is not yet available, manually install the libraries above.)*

3. **Run notebooks**
   ```bash
   jupyter notebook
   ```
   Open and execute the notebooks in order for a structured learning flow.

4. **(Optional: Hardware Setup)**  
   If interfacing with RISC-V hardware, use `zadig-2.9.exe` to configure USB drivers.

---

## Suggested Workshop Flow

1. **Neural_Networks.ipynb** → Basics of neural networks  
2. **Regression_Classification.ipynb** → Apply ML models on datasets  
3. **Regression_Optimization.ipynb** → Improve models with optimization  
4. **MNIST_prediction(keras).ipynb** → Real-world application on MNIST  

Use `Output_Images/` for visual reference of results.

---

## Contributing

Contributions are welcome! 🚀  
- Improve notebooks  
- Add more datasets or case studies  
- Enhance RISC-V integration examples  
- Refine documentation  

Open an **issue** or submit a **pull request** if you’d like to collaborate.

---

## License

This project is licensed under the **MIT License**.  
See the [LICENSE](LICENSE) file for details.

---

## Contact

Maintained by **[Manal Ahmed](https://github.com/manal-a7med)**.  
For questions or collaboration ideas, reach out via GitHub.

---

✨ Happy exploring and building at the intersection of **RISC-V and Edge AI**!
