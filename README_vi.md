[English](README_en.md) | [中文](README.md) | **Tiếng Việt**

# BBDown_GUI

Phiên bản giao diện đồ họa của BBDown - Tải video, âm thanh và phụ đề từ Bilibili.

## Ảnh chụp màn hình

### Chế độ Đơn giản

<img src="https://user-images.githubusercontent.com/29673994/169644975-066c4ac5-7fb1-4361-8c62-bb1e5aba4381.png" height="50%" width="50%" >

### Chế độ Nâng cao

<img src="https://user-images.githubusercontent.com/29673994/200099369-51250aa4-bd7f-4547-864c-f552143adcc1.png">

## Tính năng

- [x] Ghi nhớ các tham số tải xuống
- [x] Tùy chọn tải theo tập (tập hiện tại, tất cả các tập, tập mới nhất)
- [x] Ưu tiên hiển thị các tùy chọn phổ biến, đồng thời giữ lại toàn bộ tính năng
- [x] Quản lý tiến trình tải xuống

## Cách sử dụng

Đặt tệp thực thi BBDown vào cùng thư mục với chương trình UI này và chạy trực tiếp. Bằng cách này, nếu chương trình BBDown chính được cập nhật trong tương lai, bạn chỉ cần thay thế trực tiếp và sử dụng.

## Tải xuống

### Tải từ [Releases](https://github.com/1299172402/BBDown_GUI/releases) [![img](https://img.shields.io/github/v/release/1299172402/BBDown_GUI?label=Phi%C3%AAn%20b%E1%BA%A3n)](https://github.com/1299172402/BBDown_GUI/releases) 

Các tệp nhị phân đã được đóng gói sẵn, bao gồm:
- BBDown - GUI
- BBDown
- FFmpeg
- Aria2c

### Cài đặt từ [PyPI](https://pypi.org/project/BBDown-GUI/) [![](https://img.shields.io/pypi/v/BBDown_GUI)](https://pypi.org/project/BBDown-GUI/) 

Cài đặt:

```
pip install BBDown-GUI
```

Chạy (không phân biệt chữ hoa chữ thường, dấu gạch dưới có thể bỏ qua):
```
BBDown_GUI
```

### Chạy từ mã nguồn
```
pip install -r requirements.txt
python -m BBDown_GUI
```

### Tải từ [Continuous Integration (CI)](https://github.com/1299172402/BBDown_GUI/actions/workflows/build.yml) (phiên bản beta) [![Pack Python application](https://github.com/1299172402/BBDown_GUI/actions/workflows/build.yml/badge.svg?branch=main)](https://github.com/1299172402/BBDown_GUI/actions/workflows/build.yml)
Vào phần Actions, chọn Pack Python application, và mở quy trình làm việc (workflow) bạn muốn tải:
![image](https://github.com/1299172402/BBDown_GUI/assets/29673994/d7944b79-ae96-4c6a-9892-f8e7d3238a61)
Đi xuống phần Artifacts để tải xuống BBDown_GUI:
![image](https://github.com/1299172402/BBDown_GUI/assets/29673994/45c92ba5-80cc-47db-b5cc-8abe23de2078)

## Chú thích & License (Bản quyền)

 - https://github.com/nilaoda/BBDown (Giấy phép MIT)
