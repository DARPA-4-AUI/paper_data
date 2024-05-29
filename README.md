To help readers better understand DARPA and our paper, we provide necessary data mentioned at our paper in this project .

Our Yolov5 models is trained based on [Yolov5](https://github.com/ultralytics/yolov5)

- `./dark_pattern_UI_data_set`
  
  - All training dataset  is in coco farmat
  - We added a few more data after the paper was published, so its number might be little different from our source paper [DARPA](https://ieeexplore.ieee.org/abstract/document/10202645/)
  - Totally 3 types: `cross, skip and close`. Cross and skip are AGO in paper, and close are UPO.
- `./pytorch_model`
  
  - The Yolov5 model in Pytorch format
  - We use yolov5s as the base model
- `./ncnn _model`
  
  - The Yolov5 model in ncnn format which is inferenced from `./pytorch_model`by [ncnn](https://github.com/Tencent/ncnn)
