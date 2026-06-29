# ML-AI Project: Minecraft object detection.

## Github repository:
[https://github.com/Magistrate-dot/ML-AI-project-_Minecraft_Object_Detection/tree/main]

## Project overview:
This project compare's two object detection models: YOLO11n and YOLO11s, to investigates the trade-off between Computational efficiency and detection performance in object detection. These models are trained and evaluated using the Minecraft Mob's dataset from Huggingface. These models are compared against one and other using the following metrics: precision, recall and mAP, as well as a 'Live' test using an image containing one of the trained mob's and one that isn't trained.

## Required packages and libraries:
ultralytics, huggingface_hub, os, json, shtill, collections, scikit-learn, matplotlib, pandas, !Python.display 

## Dataset
The data set is dowloaded from Huggingface using:
from huggingface_hub import snapshot_download
DATASET_PATH = "/content/minecraft_dataset"

repo_dir = snapshot_download(
    repo_id="twoturtles/minecraft-mobs",
    repo_type="dataset"
)
## Additional files
The notebook downloads additional files from the GitHub repository:

Test_mob.jpg
Model_convergence_line_graph.jpg
Box_chart_comparison.jpg

## How to run the project
1. open in google colab
2. install the required packages
3. run all code cells from top to bottom

## Notes
The notebook has been designed so that the dataset, packages, libraries and images needed are downloaded as the user runs through the program.
