# MilkGuard — AI-Powered Milk Quality & Adulteration Detection

> **Published research · Featured in Gujarat Samachar (newspaper) · Food safety impact**

![Python](https://img.shields.io/badge/Python-3.8%2B-blue?style=flat-square&logo=python)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-ML-orange?style=flat-square)
![Published](https://img.shields.io/badge/Published-EBSCO-green?style=flat-square)
![Press](https://img.shields.io/badge/Press-Gujarat%20Samachar-red?style=flat-square)

---

## Overview

According to FSSAI, **68% of milk in India is adulterated**. Lab-based quality testing is slow, expensive, and inaccessible at the rural dairy level.

MilkGuard is an ML-based classification system that detects milk quality and adulteration — analyzing fat content, color, odor, and other physicochemical properties — in real time, without laboratory equipment. Built under the guidance of **Prof. Debabrata Swain, Pandit Deendayal Energy University**.

This project was **published (EBSCO)** and covered by **Gujarat Samachar**, one of India's largest Gujarati-language newspapers, for its potential impact on food safety.

---

## Press Coverage

> *"AI model developed by students can detect milk quality and adulteration — Computer Science Department students Drashti Bhavsar and Yash Jobanputra have built an AI device that rapidly checks milk quality, adulteration, fat, color, and odor properties."*
> — **Gujarat Samachar** (Ahmedabad edition)

<img width="747" height="500" alt="1adc904d-15fe-465e-80bb-b11d89e904a0" src="https://github.com/user-attachments/assets/4c46688a-a834-414c-b94a-d1ecf02d7b85" />


---

## Results

| Model | Accuracy |
|---|---|
| Random Forest | Best performer |
| Support Vector Machine (SVM) | Competitive |
| Decision Tree | Baseline |

> Full accuracy metrics and confusion matrices available in the notebook: `Milk Quality Prediction.ipynb`

---

## Problem & Impact

| Challenge | Current Reality | MilkGuard Solution |
|---|---|---|
| Testing speed | Hours in a lab | Real-time inference |
| Cost | Lab equipment required | Software only |
| Accessibility | Urban labs only | Deployable at rural dairy level |
| Scale | Manual sampling | Automated pipeline |

**Future integration potential:** IoT sensors + mobile app at village dairy cooperatives — reducing both testing time and cost significantly (as noted in the press coverage).

---

## Features Analyzed

- **Fat content** — primary adulteration indicator
- **Color** — visual quality signal
- **Odor** — spoilage detection
- **Other physicochemical properties** — density, pH, turbidity

---

## Quick Start

```bash
git clone https://github.com/Drashti0913/Milk-Quality-Prediction-using-SVM-Decision-Tree-and-Random-Forest.git
cd Milk-Quality-Prediction-using-SVM-Decision-Tree-and-Random-Forest

pip install -r requirements.txt

# Run the notebook
jupyter notebook "Milk Quality Prediction.ipynb"
```

---

## Project Structure

```
├── Milk Quality Prediction.ipynb   # Full EDA, training, evaluation
├── README.md
└── requirements.txt
```

---

## Publication

**"Milk Quality Prediction Using Machine Learning"**
Published in EBSCO · Indexed research journal
Authors: Drashti Bhavsar, Yash Jobanputra
Guided by: Prof. Debabrata Swain, PDEU

---

## Research Context

This project was developed during undergrad at **Pandit Deendayal Energy University (PDEU)**, Gandhinagar, India. The motivation came directly from the FSSAI report highlighting widespread milk adulteration across India — a public health problem that disproportionately affects rural consumers who lack access to lab testing infrastructure.

---

## License

MIT
