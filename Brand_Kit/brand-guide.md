# GitCanvas Brand Kit

Version 1.0 · 04/11/2026

## Nguồn chính thức và phạm vi

Chỉ dùng hai tài nguyên nhóm đã xác nhận: Logo Gmail khinh.png và Official ảnh bìa.png. Bản sao nguyên vẹn nằm trong assets/. Đây là kit vận hành được phát triển từ hai ảnh đó, không phải xác nhận sản phẩm đã triển khai. Quy tắc typography, khoảng cách, kích thước và template bên dưới là đề xuất áp dụng thống nhất.

Màu được phân cụm từ pixel sRGB của ảnh PNG. Ảnh có chuyển sắc nên mỗi HEX là một màu đại diện cố định, không phải màu duy nhất có trong ảnh. Primary và secondary là vai trò được đề xuất sau khi trích màu. Không có Pantone hoặc CMYK được duyệt; khi in cần proof theo profile của nhà in.

## Nền tảng thương hiệu

- Tên: GitCanvas. Luôn viết đúng G và C hoa.
- Tagline: Your Code. Your Canvas.
- Dịch vụ: template và cá nhân hóa GitHub Profile README cùng README cho repo dự án.
- Khách hàng: sinh viên IT, fresh graduates, junior developers; mở rộng đến người dùng GitHub thích trang trí, học/tải repo, freelancers và chủ dự án.
- Giá trị: làm rõ nội dung, thể hiện cá tính và tiết kiệm thời gian.
- Tính cách: sáng tạo, gần gũi, tinh nghịch, rõ ràng và có năng lực kỹ thuật.
- Phương thức cung cấp và giá gói thời gian chưa chốt. Không dùng kit này để khẳng định đã có tính năng tự động hoặc doanh thu.

## Màu thương hiệu

| Tên | Vai trò | HEX | RGB | Cách dùng |
| --- | --- | --- | --- | --- |
| Canvas Navy | Primary | #092A49 | (9, 42, 73) | Chữ chính, viền, điều hướng, nút chính |
| Creative Teal | Primary | #1CC2A2 | (28, 194, 162) | Icon, trạng thái chọn, mảng thương hiệu |
| Soft Mint | Secondary | #A9F1DD | (169, 241, 221) | Viền sticker, chip và mảng nền nhẹ |
| Gmail Blush | Secondary | #FEC1C0 | (254, 193, 192) | Minh họa tai và má; điểm nhấn cảm xúc |
| Code Aqua | Accent | #15E1CB | (21, 225, 203) | Phím nhấn, con trỏ và chi tiết tương tác |
| Warm Ivory | Neutral | #FEF6F1 | (254, 246, 241) | Nền ấm, mascot và vùng nội dung |
| Paper White | Neutral | #FEFDFC | (254, 253, 252) | Nền sáng và vùng đọc |
| Gmail Charcoal | Neutral | #495364 | (73, 83, 100) | Chi tiết mascot và chữ phụ có kiểm tra tương phản |

Tỷ lệ gợi ý cho trang mới: nền ivory/white 60%, navy 25%, teal/mint 10%, blush/aqua 5%. Không áp tỷ lệ cứng lên minh họa chính thức.

Navy là màu chữ và hành động chính; teal không dùng với chữ trắng nhỏ. Nút teal dùng chữ navy. Mint và blush là màu bổ trợ, không dùng cho đoạn văn dài. Focus dùng viền navy nổi bật. Không dựa riêng vào màu để biểu thị lỗi hoặc trạng thái. Các tỷ lệ tương phản số nằm trong design-tokens.json; phép tính chỉ áp dụng các cặp phẳng, chưa phải kiểm thử accessibility toàn website.

## Hệ logo

Master là logo vuông chính thức, gồm mascot, chữ và nền minh họa. Giữ nguyên tỷ lệ, biểu cảm, mảng đen, màu và cách vẽ chữ. Không thay chữ bằng font gõ lại, kéo giãn, lật ngang, recolor hoặc tự xóa nền. Không đưa bản concept cũ vào chung hệ chính thức.

Khoảng trống đề xuất bên ngoài asset: ít nhất 8% chiều rộng logo ở mỗi phía. Kích thước hiển thị đề xuất: từ 200 px trên web, từ 35 mm trên bản in; cần xem thử ở kích thước cuối. Nếu chật chỗ, dùng tên GitCanvas bằng chữ thông thường như nhãn điều hướng, không coi đó là logo thay thế.

Logo PNG hiện có nền sáng, chưa phải bản transparent, SVG, monochrome hoặc icon mascot tách riêng. Không coi nhúng PNG vào SVG là vector hóa. Chưa có biểu tượng rút gọn được duyệt cho favicon hoặc avatar rất nhỏ. Kiểm tra crop tròn trước khi dùng avatar vì asset chứa chữ gần mép.

## Typography

Chữ logo là lettering minh họa; chưa xác định font gốc, không cố gán tên font. Typography vận hành đề xuất: Arial Bold cho heading, Arial Regular cho body, Consolas cho code. Không đóng gói file font thương mại; máy đích dùng font đã có giấy phép hoặc fallback hệ thống.

Web desktop: H1 48/56, H2 32/40, H3 24/32, body 16/24, caption 14/20 px. Mobile: H1 32/40, H2 26/34; body giữ 16/24. Body tiếng Việt có dấu, tránh all caps cả đoạn. Social: tiêu đề ngắn, tối đa 2–3 dòng; kiểm tra trên màn hình điện thoại.

## Mascot Gmail

Chó French Bulldog thân trắng kem, mảng đen một bên mặt, tai dựng hồng, ánh mắt liếc cùng một hướng. Tinh nghịch nhưng thân thiện; không dùng để chế giễu khách. Giữ hình dáng tai, mũi, mảng đen và sự nhất quán của mắt. Trong cảnh làm việc, paws và phối cảnh phải hợp lý; đồ vật hướng về nhân vật đang sử dụng.

Minh họa dùng đường viền navy rõ, góc bo, nền mint/ivory mềm, ít chi tiết phụ. Chuyển động có mục đích: kéo canvas, trình bày dự án, chỉnh README. Không thêm hiệu ứng neon hoặc cảnh phức tạp không phục vụ thông điệp.

## Giọng văn

Viết cụ thể, thân thiện và ngắn. Có thể vui nhẹ trong headline, nhưng giá, phạm vi và giới hạn phải rõ.

- Dùng: “Chọn một mẫu README hợp với bạn.” / “Xem trước rồi chọn cách tùy chỉnh.”
- Dùng: “Profile gọn hơn. Dự án rõ hơn.”
- Tránh: “Đảm bảo đậu việc”, “Số 1 thị trường”, “Best-seller” khi chưa có dữ liệu.
- CTA đề xuất: Xem mẫu, Xem hướng dẫn, Khám phá dịch vụ. Chỉ dùng “Xuất README” khi tính năng thật sự hoạt động.
- Khi EBU: Student project – E-Business, Hanoi University. Nêu concept và test checkout, không bán thật.

## Web và UI

Lưới khoảng cách 4/8 px; khối nội dung 24–32 px; radius button 12 px, card 20 px. Viền mint cho trang trí, navy cho điều khiển cần dễ nhận diện. Primary button navy/chữ trắng; secondary teal/chữ navy; vùng đọc trên ivory/white. Icon theo một hệ nét thống nhất, không trộn nhiều kiểu 3D. Các trạng thái disabled, error và success cần nhãn riêng và được kiểm tra khi xây UI.

## Social và ảnh bìa

Giữ cover chính thức nguyên tỷ lệ; không kéo giãn. Bản gốc 2061 × 763 px, logo 1254 × 1254 px. Không tự hứa an toàn crop trên mọi thiết bị. Kiểm tra preview desktop/mobile thực tế; logo, mặt và disclaimer phải còn đọc được. Nếu bị cắt, chuẩn bị biến thể riêng thay vì nén ảnh.

Template gợi ý: bài vuông 1080 × 1080, dọc 1080 × 1350 và story 1080 × 1920; đây là canvas thiết kế, không phải cam kết kích thước nền tảng hiện hành. Giữ biên an toàn 72 px cho bài vuông; chừa rộng hơn cho vùng giao diện story. Một bài = một ý, một CTA; ảnh trước/sau phải ghi rõ minh họa nếu không phải kết quả thật.

Hai template SVG đi kèm dùng logo PNG chính thức được nhúng nguyên bản; các khối chữ và layout chỉnh được. Không phải logo vector. Nội dung template là bản nháp, không phải dữ liệu nghiên cứu hoặc bài social đã được duyệt.

## Tài nguyên và bàn giao

- GitCanvas_Brand_Guidelines.pdf: hướng dẫn trực quan.
- brand-guide.md: hướng dẫn dạng text để cập nhật và làm context.
- design-tokens.json, brand.css: màu, typography và token UI.
- palette.svg: bảng màu dạng vector.
- assets/: hai PNG chính thức sao chép nguyên vẹn.
- templates/: hai mẫu social SVG có thể sửa chữ/layout, nhúng logo raster.

Các biến thể transparent, vector, mascot-only, monochrome và favicon cần được làm và duyệt riêng; không được mô tả là đã có trong kit này. Quyền sử dụng tài nguyên/nhân vật bên thứ ba chưa được thẩm định qua việc lập kit. Giữ bản gốc ngoài thư mục này để đối chiếu.
