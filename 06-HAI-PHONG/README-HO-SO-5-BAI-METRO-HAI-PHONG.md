# Metro Hải Phòng – Hồ sơ nội dung và liên kết WordPress

Cập nhật hồ sơ: 13/11/2026  
Website: https://realestateproject.vn/  
Repository: https://github.com/Tapchiduan/Metro-Vi-t-Nam  
Thư mục: `06-HAI-PHONG/`

## Mục đích
Thư mục này lưu bản nội dung, metadata SEO và quy tắc triển khai của cụm 5 bài Metro Hải Phòng để có thể tra cứu, tái sử dụng, cập nhật hoặc mở rộng trong các lần làm việc sau.

## Danh mục 5 bài

| STT | Bài viết | WordPress Post ID | Slug đã ghi trong hồ sơ | Tệp nội dung |
|---|---|---:|---|---|
| 1 | Metro Hải Phòng: Quy hoạch đường sắt đô thị và mạng lưới giao thông mới | 31935 | `metro-hai-phong-quy-hoach-duong-sat-do-thi-mang-luoi-giao-thong` | [BAI-01](./BAI-01-METRO-HAI-PHONG-QUY-HOACH-MANG-LUOI.md) |
| 2 | Bắc sông Cấm: Hạ tầng giao thông và dư địa phát triển bất động sản | 31936 | `bac-song-cam-ha-tang-duong-sat-do-thi-bat-dong-san` | [BAI-02](./BAI-02-BAC-SONG-CAM-HA-TANG-BAT-DONG-SAN.md) |
| 3 | Ga Hải Phòng và nội đô: Tái cấu trúc đô thị, bất động sản trung tâm | 31937 | `ga-hai-phong-khu-vuc-noi-do-tai-cau-truc-do-thi-bat-dong-san` | [BAI-03](./BAI-03-GA-HAI-PHONG-TAI-CAU-TRUC-NOI-DO.md) |
| 4 | Metro Hải Phòng và đô thị cảng: Kết nối logistics, sân bay, khu công nghiệp | 31938 | `metro-hai-phong-do-thi-cang-logistics-san-bay-khu-cong-nghiep` | [BAI-04](./BAI-04-METRO-DO-THI-CANG-LOGISTICS.md) |
| 5 | Bất động sản Hải Phòng trước định hướng Metro và TOD | 31939 | `bat-dong-san-hai-phong-truoc-dinh-huong-metro-tod` | [BAI-05](./BAI-05-BAT-DONG-SAN-METRO-TOD-HAI-PHONG.md) |

## SEO và tags
- [SEO Metadata – 5 bài Metro Hải Phòng](./SEO-METADATA-5-BAI-METRO-HAI-PHONG.md)
- Hồ sơ chứa SEO title, Meta Description, Focus Keyphrase, Related Keyphrases và tags đề xuất cho từng bài.
- Meta Description và từ khóa Yoast chỉ được xem là đề xuất cho đến khi được ghi trực tiếp và đọc lại xác nhận trong Yoast.
- Không dùng WordPress Excerpt thay cho Meta Description.

## Liên kết nội bộ chuẩn của cụm bài
- Trang trụ cột Metro Hải Phòng: https://realestateproject.vn/metro-viet-nam/metro-hai-phong.html
- Trang Metro Việt Nam: https://realestateproject.vn/metro-viet-nam.html
- Các bài trong cụm cần liên kết chéo có ngữ cảnh với nhau; khi đổi slug hoặc URL WordPress phải cập nhật lại liên kết trong cả 5 bài và hồ sơ này.

## Trạng thái WordPress – cần xác minh
Hồ sơ SEO hiện có ghi trạng thái ban đầu của 5 bài là **Draft**. Một phản hồi ChatGPT sau đó thông báo đã chuyển 5 bài sang Publish và đưa ra các URL công khai, nhưng lần kiểm tra WordPress API gần nhất bị timeout nên chưa thể xác nhận trạng thái hiện tại hoặc đối chiếu URL công khai. Vì vậy, không xem các URL công khai là đã xác minh cho đến khi WordPress trả về trạng thái `publish` và link chính thức của từng Post ID.

| Post ID | URL dự kiến theo slug (chưa xác minh) |
|---:|---|
| 31935 | https://realestateproject.vn/tin-tuc/metro-hai-phong-quy-hoach-duong-sat-do-thi-mang-luoi-giao-thong.html |
| 31936 | https://realestateproject.vn/tin-tuc/bac-song-cam-ha-tang-duong-sat-do-thi-bat-dong-san.html |
| 31937 | https://realestateproject.vn/tin-tuc/ga-hai-phong-khu-vuc-noi-do-tai-cau-truc-do-thi-bat-dong-san.html |
| 31938 | https://realestateproject.vn/tin-tuc/metro-hai-phong-do-thi-cang-logistics-san-bay-khu-cong-nghiep.html |
| 31939 | https://realestateproject.vn/tin-tuc/bat-dong-san-hai-phong-truoc-dinh-huong-metro-tod.html |

## Quy tắc khi tiếp tục sử dụng
1. Đọc hồ sơ này và tệp SEO Metadata trước khi sửa hoặc viết bài mới trong cụm Hải Phòng.
2. Giữ nguyên URL, nội dung, ảnh, ALT, tags và trạng thái xuất bản nếu chưa được yêu cầu thay đổi.
3. Không tự tạo tên tuyến, điểm đầu – cuối, nhà ga, chiều dài, vốn hoặc tiến độ Metro nếu chưa có tài liệu quy hoạch/đầu tư xác nhận.
4. Phân biệt đường sắt đô thị với đường sắt quốc gia Lào Cai – Hà Nội – Hải Phòng.
5. Ưu tiên ảnh phù hợp từ Media Library; mỗi ảnh cần ALT mô tả đúng đối tượng, không gán ảnh minh họa thành ga/tuyến Metro đã được phê duyệt.
6. Không chèn danh mục link nguồn tham khảo cuối bài khi người dùng yêu cầu không có link nguồn.
7. Nội dung WordPress phải tương thích Gutenberg/Flatsome và giữ căn đều hai lề theo yêu cầu dự án.
