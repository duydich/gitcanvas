# GitCanvas — Project Context & Handoff

> Tài liệu tóm tắt từ cuộc trò chuyện để chuyển cho một ChatGPT/AI agent khác. Đây là **ý tưởng và kế hoạch đề xuất**, không phải bằng chứng sản phẩm đã hoàn thiện hoặc đã có doanh thu.

## 1. Tên và định vị

- **Brand:** GitCanvas
- **Tagline:** *Your Code. Your Canvas.*
- **Category:** Developer Personal Branding Service / GitHub Profile README Customization.
- **Core idea:** Dịch vụ trực tuyến giúp developer biến GitHub profile thành hồ sơ cá nhân chuyên nghiệp bằng README tùy chỉnh, template, banner, badges, project showcases và hỗ trợ biên tập nội dung.
- **Không phải:** Git hosting, nền tảng tuyển dụng, hay dịch vụ bảo đảm tìm được việc.
- **Định vị mong muốn:** Không chỉ bán file Markdown/template; bán sự cá nhân hóa, tiết kiệm thời gian và cách trình bày kỹ năng/dự án phù hợp mục tiêu nghề nghiệp.

## 2. Khách hàng và vấn đề

**Khách hàng chính:** sinh viên IT Việt Nam, fresh graduates, junior developers chuẩn bị thực tập/ứng tuyển; mở rộng đến freelancers và software engineers.

**Giả thuyết vấn đề:** người dùng có dự án GitHub nhưng thiếu thời gian, kỹ năng thiết kế hoặc kỹ năng kể câu chuyện dự án để tạo profile rõ ràng, hấp dẫn. Đây là giả thuyết cần phỏng vấn kiểm chứng, không phải kết luận nghiên cứu.

## 3. Sản phẩm và quy trình khách hàng dự kiến

1. Truy cập GitCanvas, xem ví dụ trước/sau và các gói dịch vụ.
2. Nhập GitHub username hoặc dùng dữ liệu demo.
3. Chọn template/gói dịch vụ, chọn style, tùy chỉnh giới thiệu, skills, projects.
4. Xem preview.
5. Thêm gói vào cart và hoàn thành **test checkout** (trong EBU).
6. Nhận `README.md`, visual assets và hướng dẫn đăng lên GitHub (quy trình giao hàng mục tiêu, chưa khẳng định đã tự động hóa).

**MVP cho môn học:** storefront responsive, landing page, pricing, template gallery, ví dụ/preview, cart, test checkout, chính sách privacy/terms/refund, social page và nội dung marketing. **Chưa cần** tích hợp GitHub API, AI generator, database, auth hay payment production trong giai đoạn scaffold.

## 4. Business model đề xuất

**Freemium + phí một lần (one-time personalization fee).** Không ưu tiên subscription lúc đầu vì người dùng ít có nhu cầu thiết kế lại profile hằng tháng.

| Gói | Giá giả định | Giá trị đề xuất |
|---|---:|---|
| Free | 0 VND | README templates cơ bản, badges, chỉnh sửa thủ công, Markdown export |
| Pro | 79.000 VND/lần | Thiết kế premium, banner/theme, README cá nhân hóa, số lần chỉnh sửa giới hạn |
| Career | 199.000 VND/lần | Tính năng Pro + biên tập nội dung theo mục tiêu nghề nghiệp, project storytelling, hỗ trợ Việt/Anh |

**Lưu ý:** Giá, phạm vi dịch vụ và willingness-to-pay đều **chưa được xác thực**; cần nghiên cứu khách hàng và tính chi phí nhân công. Không thu tiền thật trong bài EBU.

**Tại sao khách hàng trả tiền:** cho kết quả cá nhân hóa, hướng dẫn, biên tập và tiết kiệm thời gian — không phải độc quyền file README.

## 5. Competitors và differentiation

Đối thủ/công cụ cần nghiên cứu: **GitSkins** (đối thủ trực tiếp), **ProfileMe.dev**, **GitHub Profile README Generator**; có thể đối chiếu với freelancers làm GitHub profile. Carrd, Framer và Portfoliobox thuộc nhánh portfolio website rộng hơn, ít trực tiếp hơn với README customization.

**Định hướng khác biệt cần kiểm chứng:** dịch vụ hướng dẫn cá nhân hóa dành cho junior developers Việt Nam, lựa chọn dự án thật, career-focused storytelling, hỗ trợ song ngữ và có thể có human assistance. **Không tuyên bố** GitCanvas là công cụ đầu tiên có templates, AI, GitHub README builder hoặc career features — đối thủ đã có các khả năng tương tự.

## 6. Rủi ro và cách giảm thiểu

| Rủi ro | Hướng giảm thiểu |
|---|---|
| Người mua chia sẻ/copy README, template công khai | Không phụ thuộc vào việc giữ bí mật file; bán công sức cá nhân hóa, hỗ trợ, cập nhật; điều khoản license chỉ giúp về quyền sử dụng, không chặn sao chép kỹ thuật |
| Có nhiều giải pháp miễn phí/giá rẻ | Kiểm chứng khách hàng có trả tiền cho hướng dẫn và chất lượng nội dung hay không |
| Mua một lần, repeat purchase thấp | One-time pricing; có thể bán dịch vụ update sau này |
| Chi phí làm thủ công cao | Giới hạn số dự án, số vòng sửa, tiêu chuẩn hóa và tự động hóa |
| AI viết sai/phóng đại thành tích | Dùng thông tin được người dùng xác nhận; không bịa thành tích hoặc hứa hẹn việc làm |
| Phụ thuộc GitHub | Ưu tiên Markdown chuẩn, giảm tích hợp không cần thiết |
| Privacy/security | Không yêu cầu mật khẩu hoặc token từ testers; chỉ dùng dữ liệu công khai/được đồng ý |

**Vấn đề cốt lõi:** GitHub profile README hiển thị công khai, do đó không thể ngăn hoàn toàn việc sao chép. Sự khác biệt kinh doanh phải đến từ dịch vụ, không chỉ file.

## 7. EBU Final Project — bối cảnh bài học

Dự án GitCanvas được chọn cho **EBU Final Project**. Theo brief đã thảo luận:
- Ý tưởng cần được giảng viên phê duyệt trước khi triển khai/thử nghiệm.
- Phỏng vấn **ít nhất 5 khách hàng tiềm năng**.
- Nghiên cứu **3 competitors** bằng dữ liệu thực, không bịa giá/reviews/doanh số.
- Website có cart và **test checkout**, không nhận thanh toán thật.
- Có social media page và **7 bài đăng**; thử nghiệm biến thể nội dung.
- Test với **8–10 khách hàng thật**, sửa **3–5 vấn đề**, re-test với **ít nhất 3 người**.
- Ghi bằng chứng: screenshots, hành vi, phản hồi, before/after, quyết định cải thiện.
- Không bịa reviews, kết quả testing hoặc giao dịch.

**Kế hoạch 4 tuần:** W1 research/approval → W2 storefront + marketing → W3 usability testing → W4 improvements, re-test, final report/presentation.

## 8. Tech stack & repository

- **Remote origin dự kiến:** `https://github.com/DwaftPainter/gitcanvas.git`
- **Stack đề xuất:** Next.js App Router, React, strict TypeScript, Tailwind CSS, pnpm, ESLint, Prettier, Lucide React.
- **Kiến trúc:** một Next.js app, không monorepo/backend/database/auth cho scaffold ban đầu.
- **Các routes đề xuất:** `/`, `/pricing`, `/templates`, `/preview`, `/cart`, `/checkout`, `/policies/privacy`, `/policies/refund`, `/policies/terms`.
- **Folders đề xuất:** `src/app`, `src/components/ui`, `src/components/layout`, `src/components/features`, `src/lib`, `src/types`, `public`.
- **Quy tắc agent:** kiểm tra repo, git state, origin và file hiện hữu trước khi scaffold; không ghi đè, force push hoặc push khi chưa được phép; chạy install/lint/typecheck/build và báo kết quả.
- **Trạng thái chưa xác minh:** Trong cuộc trò chuyện, GitHub repo từng không truy cập được qua connector (404). Không suy diễn repo trống, đã clone hoặc đã scaffold thành công.

**Development phases:** 0 scaffold → 1 storefront → 2 cart/test checkout → 3 README builder/preview/export → 4 GitHub integration → 5 premium service fulfillment. Ưu tiên phases 0–2 cho EBU.

## 9. Branding

- Brand name: **GitCanvas**, tagline **Your Code. Your Canvas.**
- Định hướng: modern, minimal, technical, creative, developer-focused.
- Có ý định dùng `kaankiziltug/logo-design-skill` với Codex để phát triển logo; chưa chốt logo, màu thương hiệu hoặc final brand kit trong cuộc trò chuyện.
- **Aven ecosystem** (Ping, DevFlow, Harbor, Atlas, Vera) là hệ sản phẩm khác được thảo luận về branding; **GitCanvas hiện là dự án EBU riêng**, không mặc định là sản phẩm Aven.

## 10. Pitch tiếng Anh ngắn

> GitCanvas is a developer personal-branding service that helps IT students and junior developers create professional GitHub profiles through customizable README designs, visual components, and guided career-focused content. We propose a freemium model: basic templates are free, while personalized design and content support are offered for a one-time fee. Since public README files are easy to copy, our value is not template exclusivity but personalization, convenience, and professional guidance. We will validate customer demand, pricing, and usability through interviews and test checkout before any real launch.

## 11. Những việc chưa chốt / cần xác minh

- Giảng viên đã duyệt ý tưởng hay chưa.
- Kết quả phỏng vấn, willingness-to-pay, giá chính thức và unit economics.
- Thiết kế logo/brand identity chính thức.
- Repo có sẵn những file nào, app đã chạy được hay chưa.
- Khả năng thực thi tự động của README builder và dịch vụ fulfillment.
- Dữ liệu competitor mới nhất và dẫn nguồn trước khi đưa vào báo cáo.

## 12. Hướng dẫn cho ChatGPT/agent tiếp theo

Hãy dùng tài liệu này làm **product context**. Giữ nhất quán GitCanvas là dịch vụ tùy chỉnh **GitHub Profile README**, ưu tiên MVP storefront/test checkout cho EBU. Phân biệt rõ **đề xuất**, **giả thuyết**, **yêu cầu assignment**, và **tính năng đã thực sự xây dựng**. Không mặc định có khách hàng, doanh thu, tích hợp GitHub hoặc thanh toán thật. Khi làm việc với repository, kiểm tra trạng thái thực tế trước khi sửa mã.
