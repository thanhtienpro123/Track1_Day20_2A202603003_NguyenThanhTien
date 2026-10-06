# Stocklens — Product Metrics Retention & Engagement

- **Họ tên:** Nguyễn Thành Tiến
- **Mã học viên:** 2A202603003
- **Bài tập:** Day 20 · AI thực chiến
- **Dự án:** BYP — dashboard sàng lọc và phân tích cổ phiếu cho nhà đầu tư cá nhân ít thời gian, chưa thành thạo đọc báo cáo.

## Tệp Metrics Pack

**[Mở Metrics Pack](./metrics-pack.html)** — tệp HTML độc lập, có mục lục 00–06, bảng metric, retention, loop hai chu kỳ và tám tracking events. Tải tệp và mở bằng Chrome hoặc Edge; không cần cài đặt, không cần mạng. Trên giao diện GitHub, HTML có thể chỉ hiện mã nguồn; chọn tải tệp rồi mở trong trình duyệt.

Màn hình chính minh họa đưa các mã đáng tìm hiểu lên ngay, kèm lý do, rủi ro và nguồn. DEMO A/B/C là nhãn minh họa, không phải khuyến nghị cổ phiếu thật. Bài tập tập trung vào product metrics; đây không phải dashboard chứng khoán đã nối dữ liệu.

## Chuỗi quyết định của bản đề xuất

1. **Core action:** đánh giá một mã và lưu Theo dõi hoặc Bỏ qua có lý do sau khi xem lý do và rủi ro.
2. **Cadence:** rà soát hàng tuần ở cấp user, cần xác nhận với persona thực tế.
3. **North Star:** số user có ít nhất một bản đánh giá đạt chuẩn trong tuần .
4. **Retention:** cohort theo lần hoàn tất đánh giá đạt chuẩn đầu tiên; quay lại hoàn tất đánh giá mới trong đúng tuần 1, tuần 2 hoặc tuần 4 sau tuần bắt đầu.
5. **Loop:** quyết định đã lưu → thông tin mới → xem thay đổi → đánh giá tiếp.
6. **Tracking:** tám event, identity, quality rule và sáu tiêu chí nghiệm thu.

## Điều mang về áp dụng cho dự án thật

Đề xuất áp dụng là chuyển trọng tâm từ số lượt mở dashboard sang số người hoàn tất sàng lọc có căn cứ. Stocklens cần lưu quyết định cùng phiên bản dữ liệu, giúp người dùng xem điều gì đã thay đổi và kiểm tra chất lượng bằng phản hồi hữu ích/hiểu nhầm. Nội dung này do AI đề xuất để học viên rà soát, không phải reflection tự viết đã được xác nhận.

## Cấu trúc

```text
Track1_Day20_2A202603003_NguyenThanhTien/
├── README.md
├── metrics-pack.html
└── ai-support-log.md
```

## Nguồn và tình trạng nộp bài

- Yêu cầu được đối chiếu với tài liệu `Ngày 4 · Day 20_ Product Metrics - Retention & Engagement.docx` do người dùng cung cấp.
- Số liệu minh họa, ngưỡng và giả thuyết được gắn nhãn; chưa có dữ liệu người dùng thực tế hoặc benchmark bên ngoài.
- Bộ tệp được lưu trong repository này. Chưa bật GitHub Pages hoặc kiểm chứng quyền xem công khai. Link tương đối ở trên có thể dùng khi người xem có quyền truy cập repository.
- Đề bài yêu cầu học viên tự chọn core action, cadence, metric hypothesis, rationale và reflection. Bản này được AI hỗ trợ soạn toàn bộ theo yêu cầu người dùng; cần học viên rà soát và tự xác nhận các quyết định trước khi nộp. Xem [AI Support Log](./ai-support-log.md).


