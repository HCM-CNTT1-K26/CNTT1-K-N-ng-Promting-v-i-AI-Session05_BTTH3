# CNTT1-K-N-ng-Promting-v-i-AI-Session05_BTTH3

### 1. Prompt hoàn chỉnh (Chuẩn Chain-of-Thought)


#### VAI TRÒ
Bạn là Chuyên gia Xử lý Khiếu nại CSKH ngành bán lẻ công nghệ.

#### DỮ LIỆU KHIẾU NẠI
"Tôi mua laptop cách đây 10 ngày. Máy thường xuyên bị nóng, quạt kêu to và pin chỉ sử dụng được khoảng 2 tiếng. Tôi đã mang đến cửa hàng kiểm tra nhưng nhân viên chỉ vệ sinh máy và trả lại. Sau 2 ngày, tình trạng vẫn tiếp diễn. Tôi muốn đổi máy hoặc hoàn tiền."

### NGUYÊN TẮC BẮT BUỘC
1. Không tự giả định chính sách đổi trả/hoàn tiền của cửa hàng.
2. Phân biệt rõ: Dữ kiện thực tế, Giả thuyết nguyên nhân, Thông tin chưa xác định.
3. Không đưa ra kết luận kỹ thuật hoặc cam kết vượt thẩm quyền khi thiếu căn cứ.

#### YÊU CẦU SUY LUẬN TỪNG BƯỚC (CHAIN-OF-THOUGHT)
Trình bày ngắn gọn, súc tích theo đúng 5 bước sau:
- **Bước 1: Phân loại thông tin** (Dữ kiện / Giả thuyết / Chưa xác định).
- **Bước 2: Xác định vấn đề & Mức độ nghiêm trọng** (Đánh giá Thấp/Trung bình/Cao kèm lý do).
- **Bước 3: Danh sách thông tin cần xác minh** (Với Kỹ thuật, Hệ thống chính sách, Khách hàng).
- **Bước 4: Đề xuất 2 phương án xử lý** (Kèm Ưu điểm & Hạn chế của từng phương án).
- **Bước 5: Soạn phản hồi gửi khách hàng** (Chuyên nghiệp, đồng cảm, đúng quy trình).



### 2. Báo cáo phân tích theo từng bước (Chain-of-Thought)

**Bước 1: Phân loại thông tin**

* **Dữ kiện:** Mua máy 10 ngày; máy nóng, quạt kêu to, pin ~2 tiếng; đã ra cửa hàng 2 ngày trước và chỉ được vệ sinh; lỗi tái diễn; khách yêu cầu đổi máy hoặc hoàn tiền.
* **Giả thuyết:** Lỗi phần cứng (tản nhiệt, pin lỗi cell, ăn dòng) HOẶC lỗi phần mềm/sử dụng (chạy ngầm, tác vụ quá nặng); nhân viên kỹ thuật lần 1 kiểm tra sơ sài.
* **Chưa xác định:** Cấu hình/model máy; tác vụ khách sử dụng; biên bản kiểm tra lần 1; chính sách đổi trả/hoàn tiền tại mốc 10 ngày của cửa hàng.

**Bước 2: Xác định vấn đề & Mức độ nghiêm trọng**

1. **Quy trình xử lý lần 1 yếu kém** (máy mới 8 ngày nhưng chỉ vệ sinh rồi trả lại): **Mức độ Cao** – Trực tiếp làm mất niềm tin của khách, dẫn đến yêu cầu hoàn tiền.
2. **Máy quá nhiệt, quạt kêu to:** **Mức độ Cao** – Ảnh hưởng trực tiếp trải nghiệm và có nguy cơ hư hại phần cứng nếu do lỗi tản nhiệt.
3. **Pin chỉ dùng được ~2 tiếng:** **Mức độ Trung bình - Cao** – Bất thường nếu chỉ dùng tác vụ văn phòng cơ bản, cần đối chiếu với thông số thực tế của dòng máy.

---

### 3. Danh sách thông tin cần xác minh

* **Hệ thống / Chính sách:** Quy định đổi trả/hoàn tiền tại mốc 10 ngày sau mua (điều kiện áp dụng, có cần thẩm định từ hãng không); tình trạng máy lúc bán (mới 100% hay trưng bày).
* **Bộ phận Kỹ thuật:** Phiếu tiếp nhận cách đây 2 ngày (ai xử lý, đã đo nhiệt độ và độ chai pin chưa hay chỉ vệ sinh).
* **Khách hàng:** Tác vụ/phần mềm thường dùng khi máy nóng; hiện tượng sụt pin đột ngột hay tắt nguồn bất thường.

---

### 4. Hai phương án xử lý đề xuất

| Tiêu chí | Phương án 1: Thu hồi kiểm tra chuyên sâu cấp tốc (24h) | Phương án 2: Test nhanh đối chiếu trực tiếp tại quầy (Fast-track) |
| --- | --- | --- |
| **Cách làm** | Xin lỗi khách, mời mang máy đến (hoặc nhận tận nơi) để Quản lý Kỹ thuật đo kiểm toàn diện trong 24h; cấp máy mượn nếu khách cần làm việc. Sau đó xử lý đổi/hoàn tiền theo đúng chính sách. | Đối chiếu chính sách trước; nếu mốc 10 ngày được đổi tại chỗ khi có lỗi NSX, hẹn khách đến để Kỹ thuật trưởng test trực tiếp trước mặt khách (30–60 phút) và quyết định ngay. |
| **Ưu điểm** | Có căn cứ kỹ thuật chính xác, khách quan; tuân thủ chặt quy trình, không rủi ro sai chính sách. | Giải quyết nhanh, minh bạch vì khách trực tiếp chứng kiến; xoa dịu bức xúc tốt nhất. |
| **Hạn chế** | Khách có thể khó chịu vì phải chờ đợi kiểm tra thêm một lần nữa. | Phụ thuộc chính sách có cho đổi tại chỗ không; một số lỗi chập chờn khó tái hiện trong 30–60 phút. |

---

### 5. Phản hồi chuyên nghiệp gửi khách hàng

**Tiêu đề:** Hỗ trợ kiểm tra ưu tiên tình trạng laptop – [Tên Cửa Hàng]
 Kính chào anh/chị **[Tên Khách Hàng]**,
 **[Tên Cửa Hàng]** chân thành xin lỗi anh/chị vì sự bất tiện với chiếc laptop vừa mua, đặc biệt là việc hỗ trợ ở lần kiểm tra cách đây 2 ngày chưa xử lý dứt điểm tình trạng nóng máy, quạt kêu to và pin sụt nhanh.
 Chúng tôi đã báo cáo sự việc lên Quản lý Kỹ thuật để ưu tiên xử lý. Nhằm có căn cứ kỹ thuật chính xác nhất để áp dụng đúng quyền lợi đổi trả/bảo hành cho anh/chị, cửa hàng xin đề xuất:
 1. Mời anh/chị mang máy đến cửa hàng (hoặc cung cấp địa chỉ để nhân viên đến nhận tận nơi) để **Quản lý Kỹ thuật** trực tiếp đo kiểm chuyên sâu nhiệt độ, hiệu năng và pin.
 2. Cửa hàng chuẩn bị sẵn **laptop mượn tương đương** để không làm gián đoạn công việc của anh/chị trong thời gian kiểm tra.
 
 
 Anh/chị vui lòng phản hồi khung giờ thuận tiện và các phần mềm thường sử dụng để bộ phận kỹ thuật kiểm tra sát thực tế nhất. Rất mong nhận được hồi âm để chúng tôi hỗ trợ anh/chị chu đáo.
 Trân trọng,
 **[Tên Nhân Viên]** – Bộ phận CSKH **[Tên Cửa Hàng]** | Hotline: **[SĐT]**
