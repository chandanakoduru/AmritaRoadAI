AmritaRoadAI – Multi-Hazard Road Damage Detection and Unified Risk-Based Maintenance Prioritization Using Deep Learning

Project Description

AmritaRoadAI is an AI-powered road inspection and maintenance support system developed using Deep Learning and Computer Vision to detect multiple types of road damage and support risk-based maintenance prioritization.

The system uses a YOLOv8s object detection model trained on the RDD2022 (Road Damage Dataset 2022) to identify four major road damage categories: Longitudinal Cracks (D00), Transverse Cracks (D10), Alligator Cracks (D20), and Potholes (D40).

The application allows users to upload road images or capture images using a live camera for automated damage detection. It identifies damaged regions using bounding boxes, displays prediction confidence scores, and calculates a unified maintenance screening priority to help identify roads that may require attention.

The platform also supports GPS-based location recording, inspection history, map visualization, evidence preservation, and report generation in PDF, CSV, and JSON formats.

Key Features

Multi-class road damage detection using YOLOv8s.

Automated identification of four road damage categories.

Bounding-box visualization with confidence scores.

Image upload and live-camera inspection.

GPS-based inspection location recording.

Unified risk-based maintenance screening prioritization.

Inspection history and interactive map visualization.

PDF, CSV, and JSON report generation.

Technologies

Python, YOLOv8s, PyTorch, ONNX, ONNX Runtime Web, React, TypeScript, Vite, FastAPI (optional backend), Leaflet, SQLite, and IndexedDB.
