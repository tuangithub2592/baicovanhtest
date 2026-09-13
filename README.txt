PANOEE + MC OVERLAY — HƯỚNG DẪN

Mục đích:
- Tour Panoee chạy toàn màn hình.
- MC là lớp canvas cố định trên màn hình, nên khi xoay 360° MC không xoay theo.
- Video mc.mp4 được tách nền xanh bằng JavaScript ngay trong trình duyệt.
- Không cần Export $19 của Panoee.

Cấu trúc:
  index.html
  mc.mp4

Cách dùng:
1. Upload cả index.html và mc.mp4 lên một hosting hỗ trợ HTML tĩnh.
2. Mở URL của index.html.
3. Nếu cần đổi vị trí/kích thước MC, chỉnh phần #mcCanvas trong index.html:
   - right: 2.5vw;
   - bottom: 0;
   - width: min(24vw, 300px);

Lưu ý:
- Không mở nút Fullscreen bên trong Panoee nếu muốn MC vẫn nằm trên cùng.
  Hãy dùng trang wrapper này ở chế độ toàn màn hình của trình duyệt.
- Nếu viền xanh còn nhiều, tăng DISTANCE từ 72 lên khoảng 85–100.
- Nếu áo/quần bị mất màu, giảm DISTANCE xuống khoảng 55–65.
