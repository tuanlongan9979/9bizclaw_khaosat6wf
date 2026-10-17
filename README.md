# 9Bizclaw — bản gọn cho Vercel

Website tĩnh, không cần cài thư viện hay build.

## Đưa lên Vercel
1. Đưa các tệp trong thư mục này lên một repository GitHub. index.html nằm ngay ở gốc repository.
2. Trong Vercel chọn Add New → Project rồi import repository.
3. Framework Preset: Other. Root Directory: gốc repository.
4. Không đặt Build Command / Install Command; Output Directory để mặc định (gốc dự án).
5. Deploy.

Hoặc dùng Vercel CLI đã cài: chạy vercel --prod ngay trong thư mục này.

## Phạm vi
- Thiết kế trang mở đầu và đánh giá khoảng 2 màn hình ở điện thoại phổ biến; màn hình nhỏ hoặc phóng to chữ có thể cuộn thêm.
- 12 câu hỏi, tính điểm, 6 năng lực, 3 gợi ý, tải báo cáo.
- Kết quả chi tiết mở theo nhu cầu.
- Không phụ thuộc Sites, không cần API key, không có font bên ngoài.
- Chưa lưu lead lên CRM và chưa gửi/đặt lịch demo. Nút demo tải tệp yêu cầu, không gửi cho doanh nghiệp.
- dataLayer chỉ chứa sự kiện trong trang, chưa kết nối GA/GTM. Không phát demo_booking_complete khi chưa đặt lịch.
- Thông tin cá nhân chỉ tồn tại trong bộ nhớ phiên trang.
