# ThucHanhPostman

1. Kiểm thử API cơ bản:
- Tạo một yêu cầu GET mới trong Postman.
![alt text](image.png)

- Nhập URL của API muốn kiểm thử.
![alt text](image-1.png)

- Gửi yêu cầu và kiểm tra mã trạng thái HTTP và nội dung phản hồi.
![alt text](image-2.png)

- Thử nghiệm với các yêu cầu HTTP khác (POST, PUT, DELETE).
POST
![alt text](image-3.png)
![alt text](image-4.png)

PUT
![alt text](image-5.png)
![alt text](image-6.png)

DELETE
![alt text](image-7.png)
![alt text](image-8.png)

- Sử dụng các biến để lưu trữ và truy cập dữ liệu trong Postman.
![alt text](image-12.png)

- Tạo bộ sưu tập dữ liệu để quản lý nhiều yêu cầu và biến.
![alt text](image-13.png)

- Xác minh tính hợp lệ của JSON bằng công cụ JSON validator trong Postman.
![alt text](image-14.png)

2. Kiểm thử API nâng cao:

- Tìm hiểu về các phương thức xác thực và ủy quyền khác nhau được sử dụng trong API.
![alt text](image-9.png)

- Viết các yêu cầu HTTP bao gồm thông tin xác thực và ủy quyền.
![alt text](image-11.png)

- Sử dụng Postman để kiểm tra hiệu suất API bằng cách đo thời gian phản hồi.
![alt text](image-15.png)

API: https://random-data-api.com/api/v2/beers

Tạo một sản phẩm mới
Trường hợp kiểm thử thành công:
Tên: Tạo sản phẩm mới thành công
Đầu vào:
{
    "brand": "Delirium",
    "name": "Founders Kentucky Breakfast",
    "style": "India Pale Ale",
    "hop": "Galena",
    "yeast": "3638 - Bavarian Wheat",
    "malts": "Victory",
    "ibu": "16 IBU",
    "alcohol": "7.1%",
    "blg": "7.1°Blg"
}
Kỳ vọng: Trả về mã trạng thái 400 và thông báo lỗi chi tiết.

