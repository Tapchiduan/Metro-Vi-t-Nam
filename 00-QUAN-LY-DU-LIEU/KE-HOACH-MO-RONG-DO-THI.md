# Kế hoạch mở rộng chuyên đề Metro Việt Nam

- Ngày lập: 13/11/2026
- Repository: https://github.com/Tapchiduan/Metro-Vi-t-Nam
- Website: https://realestateproject.vn/metro-viet-nam.html

## 1. Mục tiêu

Xây dựng cơ sở dữ liệu toàn quốc về đường sắt đô thị và các hệ thống đường sắt có liên quan; từ dữ liệu đã kiểm chứng, phát triển chuyên trang địa phương, hồ sơ từng tuyến và bài phân tích quy hoạch – hạ tầng – TOD.

## 2. Phạm vi triển khai theo giai đoạn

### Giai đoạn A – Hoàn thiện 3 đô thị còn thiếu trong nhóm thành phố trực thuộc Trung ương

1. **Hải Phòng:** lập hồ sơ quy hoạch đường sắt đô thị, rà soát danh mục 9 tuyến theo Quy hoạch thành phố điều chỉnh; theo dõi quy hoạch chuyên ngành giao thông và điều chỉnh quy hoạch chung. Tách riêng đường sắt quốc gia Lào Cai – Hà Nội – Hải Phòng, Hải Phòng – Hạ Long – Móng Cái và các tuyến đường sắt liên vùng.
2. **Huế:** lập hồ sơ các định hướng đường sắt đô thị kế thừa từ Quy hoạch tỉnh Thừa Thiên Huế trước khi sắp xếp hành chính: tuyến kết nối sân bay Phú Bài – trung tâm; tuyến khu vực ga đường sắt tốc độ cao – Hương Trà – Phong Điền; tuyến Hương Trà – trung tâm – Thuận An; và đường sắt du lịch Huế – Đà Nẵng. Phải kiểm tra tính kế thừa và hiệu lực của các định hướng này trong quy hoạch thành phố Huế hiện hành.
3. **Cần Thơ:** lập hồ sơ 3 hành lang đường sắt đô thị theo Quy hoạch thành phố; theo dõi định hướng xe điện mặt đất; nghiên cứu ga Cần Thơ, quỹ đất TOD và tuyến đường sắt quốc gia TP.HCM – Cần Thơ. Không gộp đường sắt quốc gia vào danh mục Metro nội đô.

### Giai đoạn B – Theo dõi các hành lang và đô thị liên quan

- Quảng Ninh: đường sắt Hà Nội – Quảng Ninh và Hải Phòng – Hạ Long – Móng Cái; phân loại đúng là đường sắt liên vùng/quốc gia, không tự gọi là Metro.
- Khánh Hòa: rà soát quy hoạch giao thông công cộng khối lượng lớn, đường sắt và các đề xuất đô thị; chỉ mở hồ sơ Metro khi có căn cứ chính thức.
- Lâm Đồng: theo dõi dự án/định hướng khôi phục đường sắt Tháp Chàm – Đà Lạt; phân loại là đường sắt liên tỉnh/du lịch, không phải Metro đô thị.
- Các địa phương khác: bổ sung khi xuất hiện quyết định quy hoạch, đề án, nghiên cứu tiền khả thi hoặc chủ trương đầu tư có thể kiểm chứng.

### Giai đoạn C – Chuẩn hóa dữ liệu toàn quốc

- Lập danh mục tuyến theo địa phương và loại hình.
- Lập dòng thời gian văn bản, quyết định và tiến độ.
- Theo dõi thay đổi hướng tuyến, ga, depot, vốn, cơ quan chủ quản.
- Xây dựng bản đồ các tuyến theo mức độ chắc chắn của dữ liệu.
- Định kỳ rà soát nguồn và phát hiện thông tin hết hiệu lực.

## 3. Quy trình nghiên cứu mỗi địa phương

1. Thu thập quy hoạch cấp quốc gia, vùng và địa phương.
2. Thu thập quyết định phê duyệt/điều chỉnh và phụ lục danh mục dự án.
3. Tách từng tuyến thành một hồ sơ riêng.
4. Đối chiếu thông tin giữa văn bản chính thức và nguồn báo chí.
5. Gắn nhãn trạng thái pháp lý; ghi rõ phần chưa xác minh.
6. Cập nhật hồ sơ GitHub, sau đó mới biên tập bài website.
7. Liên kết bài tổng quan địa phương với hồ sơ từng tuyến và nguồn tham khảo.

## 4. Bộ trạng thái thống nhất

- **ĐANG VẬN HÀNH:** đã khai thác thương mại hoặc vận hành theo công bố chính thức.
- **ĐANG THI CÔNG:** có bằng chứng triển khai thi công.
- **ĐÃ PHÊ DUYỆT CHỦ TRƯƠNG/ĐẦU TƯ:** có quyết định đúng thẩm quyền.
- **CHUẨN BỊ ĐẦU TƯ:** đang lập báo cáo, thủ tục hoặc lựa chọn nhà đầu tư; chưa đồng nghĩa đã được phê duyệt đầu tư.
- **ĐỊNH HƯỚNG QUY HOẠCH:** xuất hiện trong quy hoạch được phê duyệt; chưa đồng nghĩa dự án đã triển khai.
- **ĐỀ XUẤT/NGHIÊN CỨU:** mới là đề xuất hoặc nghiên cứu, chưa đủ căn cứ coi là quy hoạch/dự án được duyệt.
- **CẦN RÀ SOÁT:** thông tin cũ, khác biệt giữa nguồn hoặc chưa xác định hiệu lực sau sắp xếp hành chính.

## 5. Mẫu dữ liệu bắt buộc cho mỗi tuyến

| Trường | Nội dung |
|---|---|
| Mã tuyến | Mã nội bộ duy nhất |
| Địa phương | Thành phố/tỉnh hiện hành |
| Tên tuyến | Tên trong văn bản gốc |
| Loại hình | Metro, LRT, tramway, đường sắt quốc gia, đường sắt tốc độ cao, đường sắt du lịch |
| Hành lang | Điểm đầu – điểm cuối hoặc mô tả hướng tuyến |
| Quy mô | Chiều dài, ga, depot, khổ đường nếu có |
| Trạng thái | Theo bộ trạng thái ở mục 4 |
| Cơ sở pháp lý | Số hiệu, ngày ban hành, cơ quan ban hành |
| Nguồn | URL gốc và ngày truy cập |
| Ghi chú | Mâu thuẫn, điểm chưa rõ, nội dung cần xác minh |

## 6. Quy tắc biên tập và SEO

- Bài tổng quan thành phố trình bày toàn cảnh và liên kết đến bài từng tuyến.
- Bài tuyến chỉ sử dụng tên gọi, hướng tuyến, quy mô và trạng thái có nguồn.
- Tiêu đề và mô tả không được khẳng định “đã triển khai/đã phê duyệt” khi tài liệu chỉ thể hiện định hướng.
- Nội dung bất động sản/TOD phải tách dữ kiện quy hoạch giao thông khỏi nhận định thị trường.
- Ghi ngày cập nhật ở bài và liên kết nguồn văn bản gốc.

## 7. Nguồn nền tảng đã thu thập

- Hải Phòng: Quyết định 5455/QĐ-UBND ngày 31/12/2025 về điều chỉnh Quy hoạch thành phố; Sở Xây dựng Hải Phòng thông tin quy hoạch thành phố xác định 9 tuyến đường sắt đô thị và đang lập quy hoạch chuyên ngành giao thông.
- Huế: Quy hoạch tỉnh Thừa Thiên Huế thời kỳ 2021–2030, tầm nhìn 2050, trong đó có các định hướng đường sắt đô thị và đường sắt du lịch Huế – Đà Nẵng. Cần đối chiếu văn bản quy hoạch hiện hành sau thay đổi địa giới.
- Cần Thơ: Quyết định 1519/QĐ-TTg ngày 02/12/2023 về Quy hoạch thành phố Cần Thơ; phụ lục có 3 hành lang đường sắt đô thị và định hướng xe điện mặt đất. Cần đối chiếu quyết định điều chỉnh quy hoạch thành phố ban hành cuối năm 2025.
- Mạng lưới quốc gia: Quyết định 2404/QĐ-TTg ngày 29/10/2025 điều chỉnh Quy hoạch mạng lưới đường sắt thời kỳ 2021–2030, tầm nhìn 2050.

## 8. Nguồn tham khảo

- Hải Phòng – Sở Xây dựng: https://soxd.haiphong.gov.vn/tin-tuc/tong-hop-y-kien-tiep-thu-giai-trinh-y-kien-gop-y-phan-bien-xa-hoi-doi-voi-du-thao-quyet-dinh-quy-993374
- Hải Phòng – Quyết định 5455/QĐ-UBND: https://thuvienphapluat.vn/van-ban/Xay-dung-Do-thi/Quyet-dinh-5455-QD-UBND-2025-dieu-chinh-quy-hoach-Hai-Phong-thoi-ky-2021-2030-695185.aspx
- Huế – Quy hoạch tỉnh Thừa Thiên Huế: https://xaydungchinhsach.chinhphu.vn/toan-van-quy-hoach-tinh-thua-thien-hue-thoi-ky-2021-2030-tam-nhin-den-nam-2050-119240107215655699.htm
- Cần Thơ – Quyết định 1519/QĐ-TTg: https://thuvienphapluat.vn/van-ban/Xay-dung-Do-thi/Quyet-dinh-1519-QD-TTg-2023-Quy-hoach-Thanh-pho-Can-Tho-2021-2030-tam-nhin-2050-588979.aspx
- Cần Thơ – Quyết định 3639/QĐ-UBND điều chỉnh quy hoạch: https://thuvienphapluat.vn/van-ban/Xay-dung-Do-thi/Quyet-dinh-3639-QD-UBND-2025-dieu-chinh-quy-hoach-Can-Tho-2021-2030-694345.aspx
- Quy hoạch mạng lưới đường sắt quốc gia: https://moc.gov.vn/vn/Pages/chitiettin.aspx?ChuyenmucID=1196&IDNews=89340&tieude=quyet-dinh-phe-duyet-dieu-chinh-quy-hoach-mang-luoi-duong-sat-thoi-ky-2021--2030-tam-nhin-den-nam-2050.aspx
- Đường sắt TP.HCM – Cần Thơ: https://baochinhphu.vn/dau-tu-tuyen-duong-sat-tphcm-can-tho-truoc-nam-2030-102250311171759742.htm

## 9. Việc cần làm tiếp theo

Ưu tiên xác minh phụ lục quy hoạch Hải Phòng và Cần Thơ bản mới nhất; sau đó hoàn thiện hồ sơ tuyến Huế dựa trên quy hoạch hiện hành. Chỉ sau khi xác minh mới chốt URL bài viết và nội dung SEO trên website.
