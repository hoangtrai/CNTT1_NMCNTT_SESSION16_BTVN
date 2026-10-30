


# Vấn đề : 
Dự án bãi đỗ xe thông minh của nhóm đang bị quản lý chưa chặt chẽ trên Messenger , Các thông báo kỹ thuật về cảm biến bị lẫn lộn giữa các tin nhắn tán gẫu và meme hài hước. Thành viên thường xuyên quên deadline. 
# yêu cầu : 
- Thiết kế cấu trúc Channels / Topics cho dự án trên Lark hoặc Slack.
- Áp dụng tính năng Reply in Thread.
# cách làm : 
- Danh sách các Channel cần có và quy định nội dung cho từng kênh.
- 3 quy tắc vàng để tránh No-Hello Trap và spam @all.

# Phần 1. sơ đồ kiến trúc :
|tên|mục đích|quy định|
 |-|-|-| 
 |tài liệu|lưu trữ link tài liệu|cập nhật tiến độ và chia sẻ tài nguyên cố định|
|thông báo chung|chuyền đạt thông tin , lịch trình |chỉ Leader hoặc Quản lý được phép đăng tin|
|kênh giải trí |chia sẻ thông tin vui nhộn , tán gẫu|Kênh xả stress|
# Phần 2. Bản quy ước giao tiếp: 
 - không sử dụng **No-Hello Trap** : Gửi toàn bộ thông tin, ngữ cảnh và câu hỏi vào một tin nhắn duy nhất.
 - thời gian Deep Work & Không ép Rep liền : không bắt buộc phải trả lời ngay lập tức , nếu có việc khẩn cấp có thể gọi điện 
 - rep tin nhắn trong luồng Reply in Thread 
