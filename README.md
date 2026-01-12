# 🖼️ Computer Vision Detection — Classical Techniques from Scratch

![Python](https://img.shields.io/badge/Python-3.9+-blue.svg)
![NumPy](https://img.shields.io/badge/NumPy-Array%20Computing-orange.svg)
![Computer Vision](https://img.shields.io/badge/Computer%20Vision-Classical%20Methods-green.svg)
![Status](https://img.shields.io/badge/Status-Complete-success.svg)
![License](https://img.shields.io/badge/License-MIT-lightgrey.svg)

---

## 📌 Overview
This project implements **classical computer vision detection techniques from scratch**, focusing on **algorithmic fundamentals rather than high-level abstractions**.

The work demonstrates how core vision concepts—such as geometric structure detection—can be built using **low-level numerical operations**, ensuring solutions remain **robust, efficient, and generalisable** across unseen images.

---

## 🎯 Objectives
- Build detection algorithms without relying on black-box APIs
- Operate directly on image arrays using numerical computation
- Ensure correctness, termination safety, and performance
- Design solutions that generalise beyond fixed or known inputs

---

## 🧠 Technical Approach
- Detection logic implemented manually using NumPy
- Image primitives (lines, circles) constructed using low-level routines
- Algorithms tested against varying image inputs to ensure robustness
- Strict control over execution flow to prevent infinite loops or unsafe termination

This approach mirrors real-world scenarios where **dependency constraints**, **performance limits**, or **explainability requirements** prohibit heavy frameworks.

---

## 🛠️ Tech Stack
The project intentionally uses a minimal and transparent stack:

- **Python**
- **NumPy**
- **Matplotlib**
- **scikit-image (drawing primitives only)**

```python
import numpy as np
from matplotlib import pyplot as plt
from skimage.draw import line, line_aa
from skimage.draw import circle_perimeter, circle_perimeter_aa


🚫 No OpenCV
🚫 No deep learning frameworks
🚫 No helper or utility functions

📂 Project Structure
├── cvca.ipynb        # Main implementation and experimentation notebook
├── main.py           # Core detection logic and functions

⚙️ Design Constraints

These constraints are intentional and central to the project’s value:

No helper or abstraction layers

Fixed execution structure for reproducibility

Safe termination under all inputs

Algorithms must work on previously unseen images

Such constraints reflect production environments with strict validation, security, or deployment rules.

✅ What This Project Demonstrates

Strong foundation in computer vision fundamentals

Ability to translate mathematical concepts into working code

Writing safe, deterministic, and efficient algorithms

Problem-solving under tight technical constraints

Clear, readable, and maintainable implementation style

🚀 Possible Enhancements

Performance optimisation for high-resolution images

Improved robustness to noise and distortions

Benchmarking against OpenCV implementations

Extension to more advanced detection pipelines

📄 License

This project is licensed under the MIT License — feel free to use, modify, and build upon it.
