


# vấn đề : 
Startup của bạn đang lưu trữ danh sách CV ứng viên chứa SĐT và mức lương kỳ vọng. Trưởng phòng nhân sự muốn chia sẻ file này cho các trưởng bộ phận để xem và nhận xét, nhưng một nhân viên đã vô tình gửi link với quyền Editor cho một ứng viên bên ngoài.
# yêu cầu : 
-   Áp dụng Quy tắc Cờ Đỏ Bảo mật để thiết lập lại toàn bộ quyền truy cập cho tệp danh sách ứng viên.
    
-   Sử dụng tính năng Suggesting Mode để các trưởng bộ phận có thể góp ý mà không làm thay đổi dữ liệu gốc khi chưa được duyệt.
# cách làm : 
-   Bản thiết kế phân quyền: Bảng phân loại đối tượng tương ứng với các mức quyền truy cập an toàn nhất.
    
-   Kịch bản xử lý sự cố: Quy trình 3 bước xử lý khi phát hiện dữ liệu bị chia sẻ sai quyền


# Phần 1. Bản thiết kế phân quyền :
|Chức vụ|Quyền |
|-|-|
|Trưởng bộ phận|comment|
|trưởng phòng nhân sự|chủ sở hữu|
HR |Edit|
|nhân viên trong CTY|view|
|ứng viên |không có quyền |




# Phần 2. Kịch bản xử lý sự cố:
- **Bước 1 :** thay đổi quyền truy cập 

- **Bước 2 :** xem lại lịch sử chỉnh sửa , rà soát rủi ro 
- **Bước 3 :**  chỉnh sửa lại quyền 
