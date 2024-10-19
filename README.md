# Fire Detection using YOLO

The goal of this project was to build a model for detecting smoke, and thus fire-related objects, in images using a YOLO-based object detection system.

## Approach
I used the [YOLO11](https://github.com/ultralytics/ultralytics) model for object detection, fine-tuning it on a dataset of wildfire images. The model was trained and evaluated on a subset of the dataset to ensure fast iterations. Performance tracking and experimentation were logged via [Weights and Biases](https://wandb.ai/), with the results available [here](https://wandb.ai/tlh45/HIParis).

## Files
- `code_TimLukaHorstmann.ipynb`: The Jupyter notebook containing the code for training and evaluating the YOLO model.
- `approach_TimLukaHorstmann.pdf`: A detailed report explaining the approach, results, and future improvements.

Alternatively, the notebook can be viewed and run on [Google Colab](https://colab.research.google.com/drive/1YHZ3t1HF2IgCF74kVfxOS4Bm1fEzCCi0?usp=sharing).
