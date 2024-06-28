# Project Dicribe:
I. Sử dụng YOLOv10 với pre-trained models yolov10n.pt
   tự động xác định vị trí của các đối tượng trong một tấm ảnh làm Input, 
   Output trả về Tọa độ (bounding box) của các các đối tượng.

## 1. Khởi tạo môi trường trong Anaconda bằng dòng lệnh sau:
'''
- Khởi tạo môi trường trong Anaconda bằng dòng lệnh sau:
$ conda create -n yolo_env python=3.9 -y
- Kích hoạt môi trường ảo đã tạo
$ conda activate yolo_env
- Tải mã nguồn YOLOv10 từ GitHub:
Nếu trong Terminal:
$ git clone https://github.com/THU-MIG/yolov10.git
Di chuyển vào thư mục mã nguồn của YOLOv10: dùng lệnh cd

Trên Google Colab, các bạn khởi tạo một code cell sử dụng lệnh:
!git clone https://github.com/THU-MIG/yolov10.git

(refresh lại phần Files của Google Colab để xem thư mục YOLOv10 đã xuất hiện hay chưa).
'''
