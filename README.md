# Gợi ý chào hàng kênh sỉ

## Cập nhật số liệu (không cần cài gì)
1. Mở file Excel, chờ tính xong (lần đầu mở bản mới có thể mất vài chục giây), bấm Lưu rồi đóng.
2. Bấm đúp tao-du-lieu.html (mở bằng Chrome hoặc Edge), chọn file Excel, nhập mật khẩu, bấm "Tạo data.enc.json".
3. Vào repo GitHub, Add file, Upload files, kéo data.enc.json vào (đè file cũ), Commit changes.
4. Chờ 1 đến 3 phút, trang web có số liệu mới.

Lần đầu: tải thêm index.html lên repo và bật Settings, Pages (Deploy from a branch, main, root).
Khi có bản index.html mới: tải đè lên repo như trên. Không tải file Excel lên GitHub.

## Gồm
- index.html        trang web gợi ý chào hàng (đưa lên GitHub)
- tao-du-lieu.html  công cụ tạo data.enc.json, chạy trên máy bạn (không cần đưa lên GitHub)
- data.enc.json     dữ liệu đã mã hóa, do công cụ tạo ra
