# 🚀 Safe Lunar Landings Using Reinforcement Learning and Chandrayaan-2 OHRC Imagery

> A project integrating computer vision and reinforcement learning to autonomously identify safe lunar landing zones using Chandrayaan-2 OHRC data.

![Python](https://img.shields.io/badge/Python-3.9%2B-blue)
![YOLOv8](https://img.shields.io/badge/YOLOv8-ultralytics-yellow)
![RL](https://img.shields.io/badge/Reinforcement%20Learning-PPO-green)

---

## 🧠 Overview

This project focuses on ensuring safe and autonomous lunar landings by combining high-resolution terrain analysis with AI-driven decision making. Using Chandrayaan-2 OHRC imagery, the system:
- Detects terrain hazards via YOLOv8
- Trains a PPO-based reinforcement learning agent
- Identifies the safest landing zones based on terrain flatness, obstacle density, and proximity to hazards

---

## 🎯 Objectives

- Analyze lunar surface using high-res OHRC imagery
- Detect craters, rocks, and ridges using YOLOv8
- Apply Reinforcement Learning (PPO) to select safe landing coordinates
- Replace low-res Apollo-era data with Chandrayaan-2 data for improved accuracy

---

## 🛰️ Technologies Used

- Python 3.9+
- YOLOv8 (Ultralytics)
- OpenCV
- Stable-Baselines3 (PPO)
- Numpy, Pandas, Matplotlib, Seaborn
- Lunar imagery from Chandrayaan-2 OHRC dataset

---

## 🗂️ Project Structure

<pre><code>Safe-Lunar-Landings/ │ ├── data/ # OHRC imagery and labeled datasets ├── detection/ # YOLOv8 training & inference code ├── rl_agent/ # PPO model training and inference ├── utils/ # Helper functions for preprocessing, plotting, etc. ├── models/ # Saved models and weights ├── results/ # Visual outputs and metrics ├── main.py # Main pipeline script ├── requirements.txt # Python dependencies └── README.md # This file </code></pre>


---

## 📊 Results

- High-precision hazard detection using YOLOv8
- PPO agent successfully learns to avoid craters and slopes
- Significant improvement over random or heuristic-based landings

_Visualization samples available in the `results/` folder._

---

## 📌 Future Work

- Integrate real-time simulation environments (e.g., Gazebo, Unity)
- Expand to 3D terrain models from Chandrayaan-3 or LRO
- Include physics-aware dynamics for descent modeling

---

## 📜 Citation / Credits

- ISRO: Chandrayaan-2 OHRC Dataset
- Ultralytics YOLOv8
- Stable-Baselines3 RL Library

---


