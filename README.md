# Bảng tính lương nhân viên (PWA – dùng web, điện thoại, online + offline)

## Đưa lên mạng (miễn phí, 5 phút)
**Cách dễ nhất – Netlify Drop:** vào https://app.netlify.com/drop → kéo thả cả thư mục này vào → nhận link HTTPS.
**Hoặc GitHub Pages:** tạo repo → upload toàn bộ file → Settings → Pages → Branch `main` / root.

## Cài lên điện thoại
- **Android (Chrome):** mở link → bấm nút **Cài ứng dụng** (hoặc menu ⋮ → Cài đặt ứng dụng).
- **iPhone (Safari):** mở link → nút Chia sẻ → **Thêm vào Màn hình chính**.
- Mở 1 lần khi có mạng; từ đó dùng được hoàn toàn offline.

## Dữ liệu
Lưu ngay trên thiết bị (localStorage). Mỗi thiết bị có dữ liệu riêng: dùng **Sao lưu** / **Nhập bản sao lưu** để chuyển máy. **Xuất CSV** để mở bằng Excel; **In / PDF** để in phiếu lương.

## Cập nhật phiên bản
Sửa file rồi tăng số trong `sw.js` (`payroll-pwa-v3` → `v4`) để máy cũ nhận bản mới.

## Lưu ý
Công thức (hệ số tăng ca, trừ nghỉ/đi muộn theo 8 giờ/ngày…) lấy từ bản Excel tham khảo, cần đối chiếu quy chế công ty/HR/kế toán.
