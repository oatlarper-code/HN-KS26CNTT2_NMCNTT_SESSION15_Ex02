# 5.Yêu cầu đầu ra

|Đối tượng|Phân Quyền|Phạm vi
|-|-|-|
Manager|Owner|Toàn quyền chia sẻ, chỉnh sửa, xóa, phê duyệt và phân quyền
Designer|Editor|Chỉ những người thiết kế mới được truy cập
Business|Viewer|Chỉ xem được sản phẩm và sử dụng sản phẩm để thuyết trình hay đưa form cho đối tác 
Partnership|Commenter|Cho đối tác xem được sản phẩm và đánh giá

- Kịch bản xử lý sự cố: 
  - Bước 1: Xóa tài khoản của thành viên trước khi họ chỉnh sửa
  - Bước 2: Kiểm tra hoạt động trên trình duyệt để rà soát dữ liệu
  - Bước 3: Tuyệt đối không kết hợp Editor + Anyone access link để tránh rủi ro bị sửa hay mất dữ liệu định danh cá nhân và luôn để chế độ hạn chế chỉ cấp quyền nội bộ
  - Bước 4: Sử dụng tính năng Suggesting Mode cho phép bạn đóng góp ý kiến hoặc sửa đổi nội dung mà không làm thay đổi trực tiếp văn bản gốc ngay lập tức
