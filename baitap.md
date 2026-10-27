# Bài tập 10: So Sánh Hai Giải Pháp Viết Tài Liệu Kế Hoạch Hội Nghị

## Phần 1. Phân Tích Bài Toán (I/O) & Đánh Giá Chi Tiết Giải Pháp

### 1. Phân tích Yêu cầu Bài toán (Input & Output)

- **Input (Nhu cầu & Bối cảnh của Ban Thư ký):**
  - Nhóm 8 thành viên cùng soạn thảo "Tài liệu Kế hoạch Hội nghị 2026" (dài 40 trang).
  - Yêu cầu kỹ thuật: Tự động hóa mục lục (Auto TOC), phân cấp H1/H2/H3, tích hợp bảng biểu.
  - Yêu cầu thực tế: Xuất file in A4 không lỗi font/vỡ layout để phát cho Ban Giám khảo; có thành viên dùng máy không có Microsoft Word bản quyền; in ấn tại trường thông qua máy tính chỉ cài sẵn Word.

- **Output (Tài liệu mong đợi & Giải pháp tối ưu):**
  - Bản phân tích chi tiết ưu/nhược điểm và bảng so sánh 5 tiêu chí nghiệp vụ giữa 2 công cụ.
  - Đề xuất quy trình làm việc (Workflow) tối ưu tránh xung đột phiên bản và khắc phục 2 bẫy dữ liệu thực tế.
  - Cấu trúc khung tiêu đề (Heading Hierarchy) chuẩn 3 cấp cho tài liệu kế hoạch 40 trang.

---

### 2. Phân tích Ưu & Nhược điểm của 2 Giải pháp

#### Giải pháp A: Microsoft Word (.docx) trên OneDrive
- **Ưu điểm:**
  - Định dạng nâng cao và căn chỉnh trang in (Page Layout, Margin, Break) cực kỳ chuẩn xác, tuyệt đối không bị vỡ khung hay lỗi font khi xuất sang file PDF/in ấn A4.
  - Công cụ Auto TOC và Heading Styles vô cùng mạnh mẽ, dễ dàng tùy biến giao diện chuyên nghiệp.
  - Hỗ trợ tính năng `Track Changes` xem chi tiết từng lịch sử chỉnh sửa văn bản của các thành viên.
- **Nhược điểm:**
  - Yêu cầu bản quyền phần mềm Microsoft Office (Word tính phí).
  - Trải nghiệm cộng tác trực tuyến trên bản Word Online bị hạn chế tính năng so với bản App Desktop; nếu sửa offline dễ gây ra bẫy xung đột file `.docx`.

#### Giải pháp B: Google Docs trên Google Drive
- **Ưu điểm:**
  - Miễn phí 100%, chạy hoàn toàn trên trình duyệt web, không bắt buộc cài đặt phần mềm.
  - Khả năng cộng tác thời gian thực (Real-time Collaboration) cho 8 người cùng sửa mượt mà, tự động lưu và theo dõi lịch sử phiên bản (Version History) rất chi tiết.
  - Dễ dàng chia sẻ link cho các thành viên trong nhóm truy cập mọi lúc mọi nơi.
- **Nhược điểm:**
  - Khả năng dàn trang và in ấn không mạnh bằng Microsoft Word (dễ bị lệch lề, tràn dòng khi tải về dạng `.docx` hoặc in trực tiếp từ trình duyệt).
  - Phụ thuộc 100% vào kết nối Internet (nếu mất mạng sẽ không thể cộng tác trực tuyến).

---

## Phần 2. Bảng So Sánh & Đề Xuất Giải Pháp Lai (Hybrid Workflow)

### 1. Bảng so sánh 5 tiêu chí nghiệp vụ

| Tiêu chí đánh giá | Giải pháp A: MS Word (OneDrive) | Giải pháp B: Google Docs (Drive) | Đánh giá & Ghi chú |
| :--- | :---: | :---: | :--- |
| **1. Cộng tác nhóm (8 người)** | ⚠️ | ✅ | Google Docs tối ưu vượt trội khi 8 người cùng sửa online không bị xung đột file |
| **2. Tính năng văn phòng (TOC/Styles)** | ✅ | ⚠️ | MS Word hỗ trợ tùy biến Heading Styles và Auto TOC chuyên nghiệp hơn |
| **3. In ấn & Xuất PDF chuẩn A4** | ✅ | ❌ | MS Word giữ nguyên định dạng 100%, không lo vỡ khung hay lỗi font khi in |
| **4. Yêu cầu hạ tầng & Chi phí** | ⚠️ | ✅ | Google Docs miễn phí hoàn toàn, không yêu cầu mua bản quyền MS Word |
| **5. Khả năng nộp & In ấn thực tế** | ✅ | ⚠️ | Máy tính phòng in của trường cài sẵn Word, mở file `.docx` xử lý cực nhanh |

---

### 2. Chốt Lựa Chọn & Giải Quyết Bẫy Dữ Liệu (Đề xuất Giải pháp Lai)

**QUYẾT ĐỊNH CHỌN:** Sử dụng **Giải pháp Lai (Hybrid Workflow)** kết hợp điểm mạnh của cả Google Docs và Microsoft Word.

**Lập luận giải quyết 2 bẫy dữ liệu:**
- **Giải quyết Bẫy 1 (Thành viên không có MS Word):** Trong giai đoạn 1 (Soạn thảo & Gom nội dung), cả nhóm 8 người sẽ dùng **Google Docs**. Nhờ đó, thành viên không có MS Word vẫn tham gia viết bài, đóng góp ý kiến và sửa lỗi thời gian thực bình thường trên trình duyệt web mà không tốn chi phí mua phần mềm.
- **Giải quyết Bẫy 2 (In tài liệu ngày hội nghị tại máy tính trường):** Vào giai đoạn 2 (Dàn trang & In ấn), Trưởng ban Thư ký sẽ tải file từ Google Docs về dưới dạng `.docx`, mở bằng **Microsoft Word** để chuẩn hóa lại Heading Styles, tạo Auto TOC, chỉnh lề A4 và xuất ra file **`Ke_Hoach_Hoi_Nghi_2026.pdf`**. 
- khi mang ra máy in tại trường (chỉ có Word), Ban tổ chức chỉ cần mở file PDF đã xuất để bấm in. Phương pháp này đảm bảo 100% tài liệu không bị lỗi font, vỡ layout hay nhảy trang ngoài ý muốn.

---

## Phần 3. Thiết Kế Cấu Trúc Phân Cấp Heading (Tài Liệu 40 Trang)

Dưới đây là thiết kế cấu trúc tiêu đề 3 cấp (H1/H2/H3) chuẩn hóa cho "Tài liệu Kế hoạch Hội nghị 2026":

# 1. TỔNG QUAN HỘI NGHỊ KHOA HỌC 2026 (Heading 1)
## 1.1. Mục đích và ý nghĩa sự kiện (Heading 2)
## 1.2. Thời gian và Địa điểm tổ chức (Heading 2)
### 1.2.1. Lịch trình tổng quan các phiên báo cáo (Heading 3)
### 1.2.2. Sơ đồ phân công phòng hội thảo (Heading 3)

# 2. CƠ CẤU BAN TỔ CHỨC VÀ NHÂN SỰ (Heading 1)
## 2.1. Ban Nội dung và Hội đồng Thẩm định (Heading 2)
### 2.1.1. Danh sách Hội đồng chấm đề tài KHKH (Heading 3)
### 2.1.2. Quy trình kiểm duyệt và duyệt bài báo cáo (Heading 3)
## 2.2. Ban Thư ký và Hậu cần (Heading 2)
### 2.2.1. Phân công nhiệm vụ 8 thành viên thư ký (Heading 3)
### 2.2.2. Dự trù kinh phí và trang thiết bị in ấn (Heading 3)

# 3. KẾ HOẠCH TRIỂN KHAI VÀ TIẾN ĐỘ CHI TIẾT (Heading 1)
## 3.1. Giai đoạn chuẩn bị hồ sơ và tiếp nhận bài (Heading 2)
## 3.2. Giai đoạn tổng duyệt và in ấn tài liệu (Heading 2)
### 3.2.1. Quy chuẩn định dạng file tài liệu A4 (Heading 3)
### 3.2.2. Quy trình nghiệm thu file PDF trước khi phát cho Giám khảo (Heading 3)
