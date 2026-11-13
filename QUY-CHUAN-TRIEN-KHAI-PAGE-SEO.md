# Quy chuẩn triển khai Page SEO — Dự án Metro Việt Nam

## Quy tắc loại nội dung
- Khi người dùng yêu cầu tạo hoặc viết Page, phải tạo/chỉnh sửa WordPress Page, không tạo Post.
- Page Metro Cần Thơ ID 31896 là trang tổng hợp cấp thành phố, nằm dưới Page Metro Việt Nam ID 27979.
- URL https://realestateproject.vn/metro-viet-nam/metro-can-tho.html là trang tổng hợp Metro Cần Thơ và có thể làm trang cha cho các Page chi tiết từng tuyến nếu người dùng yêu cầu.
- Không tự suy diễn yêu cầu thành Post hoặc tự tách/gộp nội dung. Nếu yêu cầu chưa xác định rõ là một Page tổng hợp hay các Page con theo từng tuyến, cần đọc đúng ngữ cảnh công việc trước khi thao tác.
- Giữ nguyên cấu trúc Flatsome UX Builder và nội dung gốc ngoài phạm vi được yêu cầu.

## Checklist bắt buộc cho mỗi Page
1. URL/slug phù hợp cấu trúc cha-con.
2. Bài viết theo độ dài người dùng yêu cầu.
3. SEO title.
4. Meta description.
5. Từ khóa chính (Focus keyphrase).
6. Từ khóa phụ/liên quan (Related keyphrases).
7. Tags phù hợp và chỉ gán khi taxonomy của Page hỗ trợ.
8. Backlink về đúng Page cha.
9. Backlink chéo đến các Page liên quan đang tồn tại; không tạo URL giả.
10. Kiểm tra trạng thái lưu/xuất bản và đọc lại metadata sau khi cập nhật.

## Nguyên tắc SEO metadata
- Không được bỏ sót mô tả SEO, từ khóa chính hoặc từ khóa phụ.
- Không nhầm Jetpack SEO fields với Yoast SEO fields.
- Không tuyên bố Yoast đã cập nhật nếu chưa đọc lại được trường Yoast thực tế.
- Nếu connector không hỗ trợ ghi Yoast metadata, nói rõ giới hạn, lưu bộ metadata đã chuẩn bị vào GitHub và không ghi vào trường không liên quan.

## Quy tắc biên tập Metro
- Phân biệt rõ quy hoạch/định hướng với dự án đã phê duyệt đầu tư, khởi công hoặc vận hành.
- Không suy diễn chiều dài, số ga, vị trí ga, công nghệ, depot, công suất, vốn và tiến độ khi tài liệu chưa xác nhận.
- Phân biệt đường sắt đô thị với đường sắt quốc gia.
- Không thêm mục “Nguồn tham khảo” riêng ở cuối bài nếu người dùng yêu cầu không ghi nguồn; vẫn giữ căn cứ pháp lý cần thiết trong diễn giải khi thích hợp.
- Ưu tiên liên kết nội bộ giữa Page cha và các Page con cùng cụm chủ đề.

## Cụm Cần Thơ
- Trang tổng hợp Metro Cần Thơ: https://realestateproject.vn/metro-viet-nam/metro-can-tho.html
- WordPress Page ID: 31896
- Parent hiện tại: Metro Việt Nam, Page ID 27979, https://realestateproject.vn/metro-viet-nam.html
- Page hiện có trình bày bốn tuyến: Ninh Kiều – Thốt Nốt; ga Cần Thơ – Ô Môn; Hưng Phú – ga Cần Thơ – Khu công nghiệp Vĩnh Thạnh; ga Cần Thơ – Trần Đề.
- Nếu tạo Page chi tiết theo từng tuyến, đặt Page đó dưới Page ID 31896 và backlink về trang tổng hợp Metro Cần Thơ.
- Metadata đề xuất của Page 31896 được lưu tại 05-CAN-THO/SEO-METADATA-METRO-CAN-THO.md.
