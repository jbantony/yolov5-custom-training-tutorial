# yolov5-custom-training-tutorial


[Directlink](https://colab.research.google.com/github/jbantony/yolov5-custom-training-tutorial/blob/main/yolov5-custom-training.ipynb)


# Yolov5 ONNX Conversion

[Direktlink](https://colab.research.google.com/github/jbantony/yolov5-custom-training-tutorial/blob/main/Convert_YOLOv5_ONNX_for_Inference.ipynb)

### Trouble-Shooting

1. Error in Model Form:
And export the model with opset version 12, not the default 17.

`python export_mod.py --weights test_runs/model/best.pt --opset 12 --include onnx` 

 Refernce Onnx conversion issue: https://github.com/ultralytics/yolov5/issues/10665 



2. Model visualisation: https://netron.app/

