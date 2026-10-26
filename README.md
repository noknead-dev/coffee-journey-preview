# Coffee Journey Preview 1.5.2 Real Scan

Project Preview độc lập. Không upload vào repository production v0.9.5.

## Deploy
1. Tạo repository/project Vercel riêng.
2. Upload toàn bộ nội dung ZIP, giữ nguyên thư mục `api`.
3. Thêm Environment Variable `OCR_SPACE_API_KEY`.
4. Deploy và mở URL HTTPS bằng Safari iPhone.

## Luồng
Camera/thư viện -> preview -> nén dưới khoảng 850 KB -> `/api/ocr` -> kiểm tra form -> Digital Cover -> thư viện -> backup JSON.

Ảnh chỉ tồn tại trong bộ nhớ trang khi test, không được lưu vào backup.
