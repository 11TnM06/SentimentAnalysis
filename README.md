# Sentiment Analysis - VNU

## Giới thiệu

### Thành viên

20020080 - Hoàng Đức Mạnh

20020295 - Nguyễn Đăng Huỳnh 

20020014 - Phạm Nguyễn Tuấn Hoàng

## Kết quả

| MODEL | Bert | Resnet | Vgg |
|--------------|-------|------|-------|
| AUC - ROC | 0.94 | 0.89 | 0.903 |
## Chuyển đến thư mục làm việc hiện tại
Thay đường dẫn đến thư mục của bạn ở cell đầu tiên. Ví dụ:
```Python
import os
import glob
os.chdir('<project_dir>')
```
## Tải các thư viện quan trọng

Các thư viện được ghi trong file requirements.txt trong cùng thư mục với file README.md


## Dataset

- Sử dụng tập dữ liệu trong cuộc thi bao gồm các file
  - Train.json
  - Train.csv
  - Test.csv
- Thư mục làm việc của dataset
  - Đối với ```foody-resnet.ipynb```  và ```foody-vgg.ipynb```: ```"/kaggle/input/foodyvnu/Data"```
  - Đối với ```foody-bert.ipynb```: ```"/kaggle/input/trainfoodjson/"``` và ```/kaggle/input/dataset/```

## Model

## Train

Đối với code VGG và Resnet, cần lựa chọn model trước khi huấn luyện.

Nếu dùng VGG11: ```img_model='vgg'```

Nếu dùng ResNet18: ```img_model='resnet'```