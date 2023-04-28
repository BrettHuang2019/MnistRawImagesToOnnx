# MnistRawImagesToOnnx
Generate onnx model with raw mnist images

## Prerequisites
pip install tensorflow
pip install tf2onnx

## Data Preparation
Put data in data/train/ in their corresponding folder with the name of the label. 

data_dir = 'data/train/' // data directory
validation_split=0.2 // split ratio for validation
batch_size=10  // common practice is 32, use 32 when amount is high
output_path = "onnx/test010.onnx"  // define the name of the output onnx

## Notice
The sample images under different labels do not have to be the same number.