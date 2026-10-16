# DFF Studio — Nhóm 13

Website tiếng Việt để học project Master–Slave DFF. Không cần framework, package hay CDN.

## Tải về máy Windows

1. Trên GitHub, bấm **Code → Download ZIP**.
2. Trong thư mục Downloads, nhấp chuột phải tệp ZIP → **Extract All / Giải nén tất cả**.
3. Mở thư mục đã giải nén (thường là `chatgpt-test-main`).
4. Nhấp chuột phải `index.html` → **Open with → Google Chrome / Microsoft Edge / Cốc Cốc**.

Phải giải nén cả thư mục, giữ `app.js`, `style.css` và `docs` cạnh `index.html`. Không mở file HTML ngay bên trong tệp ZIP.

## Chạy qua HTTP (tùy chọn)

Nếu đã có Python:

```sh
cd chatgpt-test
python3 -m http.server 8000 --bind 0.0.0.0
```

Các chức năng: mô hình logic hai latch tương tác, waveform timing có dấu, đồ thị characterization, tính timing budget, đối chiếu số liệu báo cáo, khảo sát W, quiz có phản hồi, ghi chú/tiến độ cục bộ và 8 slide thuyết trình. Giao diện responsive, hỗ trợ chế độ tối và reduced motion.

## Nội dung và giới hạn

- `docs/GROUP13_VLSI.pdf`: tài liệu nhóm do người dùng cung cấp.
- Giáo trình CMOS VLSI Design: tham chiếu §10.4.2 trang in 405–406. Bản PDF không được đưa lên GitHub.
- Mô phỏng trên trang là mô hình giáo dục, không thay thế Cadence/Spectre hoặc PDK.
- Trang project ghi rõ mâu thuẫn tọa độ setup trong PDF; chưa xác minh waveform hoặc dữ liệu sweep gốc. Không dùng bộ số 55/150 ps từ HTML cũ làm kết quả nhóm.
- Không có backend, thu thập dữ liệu hoặc API AI. Ghi chú/tiến độ nằm trong localStorage.

Có thể triển khai thư mục này lên bất kỳ static hosting nào. Bản này chưa được xuất bản trên Sites vì phiên không cung cấp công cụ Sites.
