# pytorch_data

## Datasets & Dataloaders class
code để xử lý dữ liệu có thể bị messy và hard to maintain - bảo trì; lý tưởng nhất là tập data tách khỏi mã đào tào để dễ đọc hơn và dễ mô đun hóa. putorch cung cấp 2 data gốc - torcch.utils.data.Dataloader và torch.utils.data.Dataset cho phép sd bỗ data pre-loaded và của bạn.
- dataset lưu trữ các mẫu và nhãn tương ứng
- Dataloader bọc 1 vòng lặp xung quanh dataset để dễ dàng truy cập vào các mẫu
một số data sẵn như FashionMnist, 


## Loading a dataset

ví dụ load the FashionMNIST Dataset với các tham số **root** đường dẫn lưu trữ train/test data, **train** chỉ định tập dữ liệu training or testing, **download=True** tải data từ internet nếu không có root; **transform** và **target_transform** chỉ định biến đổi tính năng và nhãn


