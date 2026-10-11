# Từ vựng HSK1 – Tiếng Trung Tiểu Huyền

Website học 500 từ vựng HSK1 (chuẩn HSK 3.0): thẻ từ, 1011 câu ví dụ có pinyin và bản dịch, phát âm, hoạt ảnh thứ tự nét, bảng tự luyện viết và chế độ ôn thẻ.

Toàn bộ trang nằm trong một file `index.html` (đã nhúng sẵn âm thanh, dữ liệu nét và thư viện hoạt ảnh).

## Đưa lên GitHub Pages

1. Tạo repository mới trên GitHub (ví dụ `hsk1-tu-vung`), chọn **Public**.
2. Bấm **Add file → Upload files**, kéo thả toàn bộ nội dung thư mục này (gồm `index.html`, `README.md`, `.nojekyll`, thư mục `data`), rồi bấm **Commit changes**.
3. Vào **Settings → Pages**, mục *Build and deployment* chọn **Deploy from a branch**, nhánh `main`, thư mục `/ (root)`, bấm **Save**.
4. Sau 1–2 phút, trang có địa chỉ dạng `https://<tên-tài-khoản>.github.io/hsk1-tu-vung/`.

Lưu ý: file `.nojekyll` bắt đầu bằng dấu chấm nên có thể bị ẩn trên máy; trang vẫn chạy được nếu thiếu file này.

## Phụ thuộc bên ngoài

- Phông chữ tải từ Google Fonts; khi không có mạng, trang dùng phông hệ thống.
- Nút “giọng máy” dùng giọng đọc tổng hợp có sẵn trên thiết bị (cần giọng tiếng Trung).
- Âm thanh người thật, dữ liệu nét và thư viện Hanzi Writer đã nhúng trong `index.html`.
- Đánh dấu “từ khó” chỉ lưu trên trình duyệt của từng người.

## Nguồn và giấy phép

- **Nội dung từ vựng:** tài liệu “TỪ VỰNG HSK1 – CHUẨN FORMAT HSK3.0”. Câu ví dụ và ghi chú do Tiếng Trung Tiểu Huyền bổ sung.
- **Âm thanh người thật (424 file):** giọng Yue Tan, bộ *cmn-caen-tan* của dự án Shtooka, lấy qua https://github.com/hugolpz/audio-cmn — giấy phép **CC BY-SA**. Khi dùng lại hoặc chỉnh sửa âm thanh phải ghi nguồn và giữ cùng giấy phép. Nguồn và kết quả kiểm tra từng file: `data/audio-manifest.json`.
- **Dữ liệu thứ tự nét:** Make Me a Hanzi, qua gói hanzi-writer-data 2.0.1 — Arphic Public License (`data/LICENSE-stroke-data-ARPHICPL.txt`).
- **Thư viện hoạt ảnh:** Hanzi Writer 3.7.3 — MIT (`data/LICENSE-hanzi-writer.txt`).
