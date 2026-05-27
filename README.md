# Nhận Diện 5 Món Ăn Việt Nam Bằng CNN

## Giới thiệu

Đây là bài tập ứng dụng mô hình CNN trong nhận dạng hình ảnh món ăn Việt Nam.  
Hệ thống được xây dựng trên Google Colab, sử dụng TensorFlow/Keras để huấn luyện mô hình phân loại ảnh món ăn.

Dự án nhận diện 5 món ăn Việt Nam gồm:

- Phở
- Bánh mì
- Cơm tấm
- Bún bò Huế
- Gỏi cuốn

## Mục tiêu đề tài

- Xây dựng mô hình CNN để phân loại ảnh món ăn Việt Nam.
- Tiền xử lý và tổ chức dữ liệu hình ảnh theo từng lớp.
- Huấn luyện mô hình trên tập dữ liệu gồm 5 món ăn.
- Đánh giá kết quả bằng độ chính xác Accuracy.
- Thử nghiệm mô hình bằng ảnh món ăn tải lên.

## Công nghệ sử dụng

- Python
- Google Colab
- TensorFlow / Keras
- NumPy
- Pillow
- Matplotlib

## Dataset

Dữ liệu ảnh được thu thập từ Roboflow/Kaggle và được chia thành 5 lớp món ăn.

Cấu trúc dữ liệu sử dụng trong bài:

```text
dataset/
│
├── pho/
├── banh_mi/
├── com_tam/
├── bun_bo_hue/
└── goi_cuon/
