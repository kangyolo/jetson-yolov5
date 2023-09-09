# YOLOv5 on Jetson Nano

## Clone the Repository
We are using custom Ubuntu 20.04 and we just need a couple update in Jetson Nano for YOLOv5.
```
git clone https://github.com/ultralytics/yolov5.git
```
the custom ubuntu has a custom library too, so we just need some small tunning to run YOLOv5
copy and paste the [custom req file](https://github.com/kangyolo/jetson-yolov5/new/main) to `requirements.txt` in YOLOv5 default folder.
```
pip3 install -r requirements.txt
```
after the installation completed, the check the `detect.py`

## Testing
go to `/krti/yolov5`

```
python3 detect.py --weights yolov5s.pt --source 0
```
