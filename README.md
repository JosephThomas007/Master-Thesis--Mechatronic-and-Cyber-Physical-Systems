# Master-Thesis--Mechatronic-and-Cyber-Physical-Systems

Welcome to the repository for my thesis project! This repository contains all the code and materials related to my thesis.

## Installation

To install and run this project, you'll need to follow these steps:
## Prerequisites

Before you begin, ensure you have the following installed:
- Git
- Python 3.8 or newer
- Node.js and npm (for Potree)

## YOLOv5 Installation

YOLOv5 is a family of object detection architectures and models pretrained on the COCO dataset. Here's how to get started with YOLOv5:

1. **Clone the repository**

   ```bash
   git clone https://github.com/JosephThomas007/yolov5.git
   cd yolov5

2. **Set up Python Environment**
   ```bash
   python -m venv env
   source env/bin/activate

3. **Install dependencies**
   ```bash
   pip install -r requirements.txt

4. **Run YOLOv5**

   detect.py runs inference on a variety of sources, downloading models automatically from the latest YOLOv5 release and saving results to runs/detect.
   ```bash
   python detect.py --source data/images --weights yolov5s.pt --conf 0.25

## Potree Installtion
Potree is a web-based viewer for large point cloud data sets. Here is how to set up Potree:

1. **Clone the repository**
   ```bash
   git clone https://github.com/[YourGitHubUsername]/potree.git
   cd potree

2. **Install Node.js dependencies**
   ```bash
   npm install

# PotreeConverter Guide

This guide provides instructions on how to use PotreeConverter to convert point cloud data for visualization with the Potree viewer.

## Prerequisites

- Download the latest version of PotreeConverter from the [PotreeConverter GitHub repository](https://github.com/potree/PotreeConverter).
- Ensure your point cloud data is in a supported format such as `.las`, `.laz`, `.xyz`, `.ptx`, `.ply`, etc.

## Installation

PotreeConverter can be used directly if you download a pre-compiled binary. No installation is necessary, just extract the files to a known directory.

If building from source, follow the build instructions provided in the repository's README.

## Usage

### Convert Your Data

Open a command prompt or terminal. Navigate to the directory containing `PotreeConverter` or include the path to the executable in your command. Use the following syntax to convert your data:

```bash
./PotreeConverter /path/to/your/pointcloud.file -o /output/directory --generate-page pageName




