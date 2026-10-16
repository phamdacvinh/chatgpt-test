# Kế hoạch và kết quả triển khai

1. Đọc nguồn: PDF báo cáo làm nguồn chính, giáo trình §10.4.2 đối chiếu phương pháp, hai HTML cũ chỉ tham khảo nhu cầu tương tác.
2. Thiết kế giao diện: sidebar xanh đậm, nền sáng, chữ Việt rõ ràng, module theo hành trình học; hỗ trợ điện thoại và dark mode.
3. Xây module cơ chế: TG, hồi tiếp, hai pha master/slave; thao tác D/CLK, lịch sử, phân biệt mô hình logic và mạch analog.
4. Xây timing lab: cửa sổ có dấu, hold âm/dương, tCQ, uncertainty khi vi phạm; tính timing budget đường đồng bộ.
5. Xây characterization: đồ thị giải tích minh họa, cực tiểu tDQ, độ dốc −1; phân biệt x với ymin và đơn vị FO4 với ps.
6. Giải mã project: bảng kết quả có nguồn, hold −11/−9.5 ps, bảng khảo sát W, Calculator workflow, ảnh gốc setup.
7. Luyện bảo vệ: 8 câu trắc nghiệm kèm giải thích, 6 câu hỏi mở, ghi chú tự luyện, 8 slide có điều khiển bàn phím, checklist lưu cục bộ.
8. Kiểm tra: cú pháp JavaScript, HTTP/PDF và tương tác bằng Chromium, kiểm tra overflow cả 7 màn hình ở viewport 390 px; xem ảnh desktop thực tế.

## Nội dung còn cần dữ liệu gốc từ nhóm

- Setup bắt 1: văn bản kết luận 32.9991 ps, ảnh Hình 4.12 hiển thị X khoảng 32.8446 ps, Y khoảng 73.62 ps; câu diễn giải đảo x/y.
- Setup bắt 0: ảnh Hình 4.34 hiển thị X 31.1774 ps, Y khoảng 67.35 ps; tổng từ số setup/tpcq kết luận lại là 67.4343 ps.
- Website gắn cờ rõ các mâu thuẫn; không sửa dữ liệu gốc và không tuyên bố đã tái chạy Cadence.

## Phạm vi hoàn thành

Mã nguồn và tài liệu đã đóng gói, chạy độc lập không CDN/API. Chưa xuất bản lên Sites: phiên làm việc không cung cấp công cụ connector Sites. Không tạo URL công khai hoặc đẩy lên GitHub.
