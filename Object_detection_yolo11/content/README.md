# Basketball Players Object Detection Dataset

This repository contains the dataset and instructions to train an object detection model to detect basketball-related objects such as players, referees, balls, and the basket using YOLOv8 (YOLO11).

The dataset was sourced from [Roboflow Basketball Players Dataset](https://universe.roboflow.com/jon-betolaza/basketball-players-c8zbl/dataset/2).

## Dataset Description

The dataset includes annotated images for detecting various objects in basketball scenes:

- **Classes**:
  - `ball`
  - `basket`
  - `bench person`
  - `player`
  - `referee`

The dataset has been pre-annotated using [Roboflow](https://roboflow.com/). The images contain instances of basketball players, referees, and objects such as balls and baskets, perfect for training object detection models.

## Requirements

To train the model using YOLOv8 (YOLO11), you need to set up a virtual environment and install the necessary dependencies.

### 1. Set up a Virtual Environment

#### Create a virtual environment:

```bash
python -m venv venv

### Key Sections in the `README.md`:
1. **Dataset Overview**: The dataset and its contents.
2. **Setup Instructions**: Create a virtual environment, install dependencies, and set up the environment.
3. **Training & Evaluation**: Train the YOLOv8 model and evaluate its performance.
4. **Inference**: Run the trained model on new images.
5. **License & Acknowledgments**: Mentions licensing and credits for the tools used.

This guide should help set up the environment and train a YOLO model for object detection on basketball players.
