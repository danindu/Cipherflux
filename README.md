# CipherFlux – Unified Crypto & Vulnerability Suite

**CipherFlux** is a lightweight desktop application built with a PyQt graphical interface that bundles several cryptographic utilities and vulnerability‑assessment tools behind one intuitive dashboard. Security engineers and enthusiasts can run quick analyses and scans without juggling multiple command‑line programs.

---

## Features

- **Modular Tool Picker**  
  Select from five integrated components:  
  1. Linear Trails  
  2. SHA‑1 Collision Finder  
  3. Break‑OTS Analyzer  
  4. RSA‑CTF Helper  
  5. S‑Box Exploration

- **Flexible File Support**  
  Accepts **PDF**, **XML**, and **PUB** inputs as required by each module.

- **Live Visual Feedback**  
  Results stream in real time to an on‑screen log pane and a built‑in terminal view so you can watch progress as it happens.

---

## 🎬 Demo

[![Watch the quick tour](https://img.youtube.com/vi/Q6xYT5xk0I0/0.jpg)](https://www.youtube.com/watch?v=Q6xYT5xk0I0)

---

## Getting Started

### 1 . Clone

```bash
git clone https://github.com/danindu/cipherflux.git
cd cipherflux
```

### 2. Install Prerequisites

```bash
sudo apt update
sudo apt install python3 python3-pip python3-pyqt5 -y
sudo apt-get install cmake graphviz libmpich-dev libxml2-dev mpich
pip3 install pyqt5 rsa rsactftool
```

### 3. Run

```bash
python cipherflux.py
```

## Configuration

**Module options:**  
Each built‑in utility ships with tunable parameters—such as hash thresholds, iteration rounds, or RSA key sizes—that let you balance speed against analytical depth. For quick reconnaissance, lower the thresholds or rounds to finish faster; for exhaustive audits, raise them to ensure every corner case is examined.

**File selection:**  
Make sure the input you feed a module matches the format it expects. For instance, the SHA‑1 Collision Finder is designed to parse `.pdf` files, whereas Break‑OTS works best with plain‑text `.txt` data. Providing the right file type prevents parsing errors and guarantees accurate results.

##  Contributing

We welcome pull requests and feature suggestions!

### Fork the Repository

Click the Fork button on the GitHub repository to create your own copy.

### Create a Feature Branch

Create a new branch for your feature

```bash
git checkout -b feature/ FeatureName
```
### Commit Your Changes

```bash
git commit -m "Add detailed feature"
```

### Push the Branch

```bash
git push origin feature/FeatureName
```

### Create a Pull Request
Once pushed, open a pull request (PR) on GitHub to merge your changes into the main repository.

## Acknowledgements

CipherFlux stands on the shoulders of countless open‑source projects.
Thank you to every contributor whose work makes this suite possible.

## Authors

- Samarth Bhat (Samarth@reinfosec.com)
- Sohan Simhar Prabakar ([@Sohan245](https://github.com/Sohan245/))
- Danindu Gammanpilage ([@Danindu](https://github.com/danindu))
