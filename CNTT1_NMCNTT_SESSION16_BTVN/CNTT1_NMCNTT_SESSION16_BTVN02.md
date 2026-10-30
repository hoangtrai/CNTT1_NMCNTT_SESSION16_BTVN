


# vấn đề :
```Nhóm của bạn đang thực hiện dự án Số hóa Bảo tàng PTIT. Bạn A chịu trách nhiệm thiết kế 3D các hiện vật. Do thói quen cũ, bạn A chỉ lưu file trên ổ cứng Local và thỉnh thoảng nén gửi qua Zalo. Tối qua, ổ cứng máy bạn A bị lỗi "Bad Sector" khiến file thiết kế quan trọng bị hỏng, trong khi bản gửi trên Zalo đã hết hạn tải về```
# yêu cầu :
-   Thiết kế một quy trình làm việc lai (Hybrid Workflow) đảm bảo file luôn có bản sao lưu tức thời trên Cloud ngay khi nhấn Ctrl + S.
    
-   Xây dựng phương án dự phòng sử dụng Version History để cả nhóm có thể quay ngược thời gian lấy lại bản vẽ ổn định nhất nếu bản hiện tại bị lỗi.
# cách làm : 
-   Báo cáo phân tích: Sơ đồ luồng dữ liệu từ Local SSD lên Cloud và cách hệ thống xử lý khi có xung đột phiên bản 
    
-   Quy trình thực thi: Danh sách 3 bước thiết lập phần mềm đồng bộ chuẩn cho một Designer.
	
	# phần 1. báo cáo phân tích : 
	**1. Sơ đồ luồng dữ liệu từ Local SSD lên Cloud :** 
nhấn tổ hợp phím `ctrl + s` -> ghi vào SSD ->
Auto Sync -> Cloud Storage -> Version History



   **2. cách hệ thống xử lý khi có xung đột phiên bản :** 
   - Không ghi đè đứt đoạn ( tắt máy , hủy bỏ khi tải chưa xong ) 
   - mở tính năng **Version History** trên Cloud Dashboard 
    

# phần 2. Quy trình thực thi:

1. cài đặt gg drive 
2. tạo thư mục thiết kế 3D 
3. đưa thư mục đồng bộ vào gg drive 
