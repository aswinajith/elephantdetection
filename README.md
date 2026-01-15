# Elephant Detection

A real-time elephant detection system built with **YOLO (You Only Look Once)** deep learning and a bot interface for inference. This project uses a trained object detection model to identify elephants in images and live video feeds, enabling applications like wildlife monitoring, human-elephant conflict mitigation, and automated alerting.

## Project Overview

Wild elephant detection is an important task for conservation and safety in regions sharing space with elephants. This repository provides tools to:

- Detect elephants using a custom-trained YOLO model (`best.pt`)
- Run inference on images and video streams
- Integrate detection results with an interactive bot for alerts and automated responses

The core detection leverages state-of-the-art deep learning object detection models similar to YOLOv8, which offer fast inference and high accuracy for real-time applications. :contentReference[oaicite:1]{index=1}

## Features

-  **Elephant Detection Model** – A YOLO-based model (`best.pt`) trained to recognize elephants in various environments.
-  **Bot Integration** – A bot script (`bot.py`) to serve detection results, trigger actions, or send alerts.
-  **Image & Video Support** – Works with static images and live video frames from webcams or CCTV feeds.
-  **Expandable** – Easily extendable to other wildlife species or custom alert pipelines.

## Usage

 **Clone the repository** 
git clone https://github.com/aswinajith/elephantdetection.git
cd elephantdetection

**Create a Python virtual environment**
python3 -m venv venv

