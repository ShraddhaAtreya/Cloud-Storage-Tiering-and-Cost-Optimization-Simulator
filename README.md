# ☁️ Cloud Storage Tiering and Cost Optimization Simulator

> **Simulate and analyze cloud storage costs by intelligently tiering data based on usage, retention, and lifecycle policies.**

---

## 🔍 Overview

This project provides a simulation tool to demonstrate how cloud storage expenses can be reduced by organizing data into appropriate storage tiers—**Hot**, **Cool**, or **Archive**—based on how frequently the data is accessed and how long it needs to be retained.

It offers a complete pipeline from:
- Data ingestion 📥
- Tier classification ⚙️
- Cost estimation 💰
- Visualization 📊
- PDF reporting 📝

---

## ✅ Features

- 🧠 Intelligent storage tier classification (Hot, Cool, Archive)
- 💸 Accurate cost modeling (including lifecycle and retrieval costs)
- 🔁 Automatic simulation of tier migration over time
- 📊 Pie & bar chart visualizations of storage and cost distribution
- 📄 One-click generation of a detailed PDF report
- 📥 Input CSV support with scalable sample dataset (150 records)

---

## 📁 Project Structure

```bash
cloud-storage-tiering-simulator/
│
├── README.md                            ← [This file]
├── storage_simulator.ipynb              ← [Notebook to run and visualize the project]
├── sample_150_files.csv                 ← [Input: Sample dataset with 150 file records when the input being asked]
│
└── output/
    └── Cloud_Storage_Report.pdf         ← [Final PDF report generated after simulation]

