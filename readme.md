# FastRCNN cho Bài Toán Phát Hiện Đối Tượng Đa Nhãn Đa Đối Tượng

Đây là dự án triển khai và huấn luyện lại mô hình **FastRCNN** với mạng backbone **ResNet** cho bài toán phát hiện đối tượng (Object Detection). Dự án này hỗ trợ phát hiện nhiều đối tượng và nhiều nhãn trong cùng một hình ảnh.

---

## Dữ Liệu Hỗ Trợ

Dữ liệu được sử dụng trong quá trình huấn luyện bao gồm các đối tượng sau với ID nhãn tương ứng:

* **Apple**: 1
* **Grapes**: 2
* **Pineapple**: 3
* **Orange**: 4
* **Banana**: 5
* **Watermelon**: 6

---

## Kết Quả Huấn Luyện

Sau quá trình huấn luyện, các giá trị mất mát (loss) và độ đo AP (Average Precision) đạt được như sau:

* **RPN Localization Loss**: 0.0140
* **FRCNN Classification Loss**: 0.0860
* **FRCNN Localization Loss**: 0.0150
* **Kết quả AP**: 0.52

---

## Cấu Trúc Dự Án

Dự án bao gồm file `object_detection.py`, chứa toàn bộ mã nguồn để xây dựng FastRCNN từ đầu (from scratch), thực hiện quá trình huấn luyện và suy luận (inference) trên dữ liệu.

---

## Mô Hình Đã Huấn Luyện & Kết Quả Suy Luận

Bạn có thể tìm thấy các mô hình đã huấn luyện (.pth) và các ví dụ về kết quả suy luận tại liên kết Google Drive sau: [results](https://drive.google.com/drive/folders/152lWvw_GWE5t8OPXRmxstlvjOoTQj3nL?usp=sharing)
