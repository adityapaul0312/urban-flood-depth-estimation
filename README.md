# Urban Flood & Vehicle Wading Depth Estimator 🌊🚘

An end-to-end Computer Vision and Deep Learning pipeline designed to estimate urban waterlogging depth by analyzing vehicle tire submersions. The system combines multi-stage deep learning models with robust geometric fallback algorithms and dual-RANSAC shape fitting.

---

## 📌 Project Overview

Urban flooding poses severe risks to transportation and infrastructure. Measuring flood depth in real time using street cameras can be difficult due to a lack of calibrated physical markers. 

This project solves that challenge by using **vehicles as dynamic reference objects**. By segmenting water bodies, detecting vehicles, and mathematically modeling the visible arc of submerged wheels, the system estimates localized flood depth accurately—even in high-noise, real-world outdoor conditions.

---

## 🏗️ System Architecture & Pipeline

The processing pipeline operates in four major phases:
