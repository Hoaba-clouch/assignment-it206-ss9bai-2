# [Vận dụng cơ bản - 2] PHÂN LOẠI VÀ SỬA BIÊN BẢN SPRINT RETROSPECTIVE

## Phần 1 - Phân loại ý kiến

Dưới đây là bảng phân loại và cách xử lý các ý kiến ghi trong biên bản Sprint Retrospective Sprint 11:

| Mã | Cột hiện tại | Ý kiến ghi trong biên bản | Phân loại | Cách xử lý |
|---|---|---|---|---|
| R-01 | Start | Thêm nút cho khách tự hủy đơn trên mạng xã hội. | Phản hồi sản phẩm | Chuyển Product Owner xem xét trong Product Backlog để ưu tiên phát triển tính năng. |
| R-02 | Start | Giao tiếp tốt hơn. | Cần làm rõ | Ý kiến mơ hồ, cần hỏi lại để làm rõ về vấn đề giao tiếp cụ thể nào. Có thể đã được đề cập cụ thể hơn ở R-04. |
| R-03 | Stop | Không để Nam tự đổi quy tắc vì Nam làm mọi người phải sửa theo. | Cách làm việc (đổ lỗi cá nhân) | Viết lại: "Stop: Việc thay đổi quy tắc chuyển người không được thông báo và cập nhật tài liệu chung, gây khó khăn cho các thành viên khác." |
| R-04 | Stop | Đổi quy tắc qua tin nhắn riêng mà không cập nhật tài liệu chung. | Cách làm việc | Giữ ở cột Stop. Đây là một hành vi cụ thể cần dừng lại. |
| R-05 | Continue | Pairing (hai người cùng làm) giữa người kiểm thử và người làm luồng hội thoại khi tái hiện lỗi. | Cách làm việc | Giữ ở cột Continue. Đây là một thực hành tốt cần duy trì. |
| R-06 | Start | Tăng tỷ lệ AI tự trả lời lên 90%. | Phản hồi sản phẩm / Chỉ số sản phẩm | Chuyển Product Owner xem xét. Đây là mục tiêu về sản phẩm, không phải cải tiến quy trình làm việc của nhóm. |
| R-07 | Stop | Bỏ yêu cầu "không còn lỗi mức nghiêm trọng cao" khỏi Definition of Done cho kịp Sprint. | Cách làm việc (hạ chuẩn DoD) | Không chấp nhận hạ chuẩn Definition of Done. Thay vào đó, cần có hành động cải thiện quy trình để phát hiện lỗi sớm hơn và đảm bảo chất lượng. |

## Phần 2 - Sửa Improvement

### 2.1. Chọn và loại bỏ Improvement

Dựa trên Quy tắc nghiệp vụ QT1, QT2 và QT3, Scrum Team nên chọn tối đa hai Improvement.

*   **IM-11-01: Giao tiếp tốt hơn**
    *   **Loại bỏ:** Nội dung quá mơ hồ, không cụ thể để thực hiện và kiểm tra. Việc giao hết cho Scrum Master cũng không phù hợp với nguyên tắc cả nhóm cùng theo dõi.
*   **IM-11-02: Kiểm thử kỹ hơn**
    *   **Chọn:** Mặc dù còn mơ hồ, nhưng có thể cụ thể hóa hành động để giải quyết các vấn đề về lỗi và kiểm thử đã nêu (R-07, IM-10-02).
*   **IM-11-03: Tăng tỷ lệ AI tự trả lời lên 90%**
    *   **Loại bỏ:** Đây là chỉ số liên quan đến sản phẩm, không phải Improvement về quy trình làm việc của Scrum Team. Cần chuyển về Product Backlog cho Product Owner ưu tiên.
*   **IM-11-04: Khi đổi quy tắc chuyển người, cập nhật tài liệu chung trước khi triển khai**
    *   **Chọn:** Hành động này cụ thể, giải quyết trực tiếp vấn đề đã được nêu ở R-03 và R-04, cũng như sự kiện Ngày 2.

### 2.2. Viết lại Improvement đã chọn

Dưới đây là hai Improvement đã chọn và được viết lại theo mẫu gợi ý, đảm bảo đủ 4 cột:

1.  **Improvement: IM-11-02 (Kiểm thử hiệu quả hơn)**
    *   **Hành động:** Khi một Product Backlog Item (PBI) đã sẵn sàng để kiểm thử tích hợp (Integration Test), Developers sẽ đảm bảo người kiểm thử (Khánh Vy) được cấp đủ quyền truy cập môi trường thử nghiệm từ Ngày 1 của Sprint và thực hiện Integration Test ngay lập tức.
    *   **Người/nhóm theo dõi:** Developers
    *   **Khi kiểm tra:** Retrospective Sprint 12
    *   **Bằng chứng:** Biên bản ghi nhận ngày cấp đủ quyền truy cập môi trường thử nghiệm cho người kiểm thử và báo cáo về ngày chạy Integration Test đầu tiên trong Sprint.

2.  **Improvement: IM-11-04 (Quy trình thay đổi quy tắc)**
    *   **Hành động:** Khi có bất kỳ thay đổi nào về quy tắc chuyển người (hoặc các quy tắc làm việc khác của nhóm), nhóm sẽ cập nhật tài liệu chung và thông báo cho tất cả thành viên trong nhóm trước khi triển khai quy tắc mới.
    *   **Người/nhóm theo dõi:** Developers (hoặc Scrum Team)
    *   **Khi kiểm tra:** Retrospective Sprint 12
    *   **Bằng chứng:** Biên bản ghi nhận việc cập nhật tài liệu chung có phiên bản và ngày thông báo cho nhóm khi có thay đổi quy tắc.

### 2.3. Xử lý Improvement cũ (IM-10-02)

Improvement cũ IM-10-02 (chạy Integration Test không muộn hơn Ngày 4) chưa hoàn thành ở Sprint 11 do nguyên nhân rõ ràng là Khánh Vy mới được cấp đủ quyền truy cập môi trường thử nghiệm vào Ngày 4. Việc này khiến việc kiểm thử sớm là bất khả thi.
Thay vì bỏ qua hay chỉ gia hạn y nguyên, nhóm sẽ điều chỉnh hành động cải tiến dựa trên nguyên nhân gốc rễ: gộp việc đảm bảo quyền truy cập sớm cho người kiểm thử vào Improvement IM-11-02 đã sửa. Nhóm sẽ theo dõi việc thực hiện IM-11-02 và kiểm tra lại hiệu quả tại Retrospective Sprint 12.

## Phần 3 - Nhận xét cách điều phối

Dưới đây là hai điểm chưa phù hợp trong cách Scrum Master và Product Owner điều phối buổi họp, cùng với tác động của chúng:

1.  **Scrum Master mở đầu bằng câu hỏi đổ lỗi cá nhân:**
    *   **Điểm chưa phù hợp:** Scrum Master mở đầu buổi Retrospective bằng câu hỏi: "Ai đã làm sáu khiếu nại bị phân loại sai?". Đây là một câu hỏi mang tính đổ lỗi cá nhân, vi phạm Quy tắc nghiệp vụ QT2 ("Trao đổi tập trung vào hành vi và hệ thống, không công kích cá nhân") và tinh thần của Sprint Retrospective là xem xét cách Scrum Team làm việc, không đổ lỗi.
    *   **Tác động:** Cách mở đầu này tạo ra một môi trường không an toàn, khiến các thành viên cảm thấy bị công kích và e ngại chia sẻ ý kiến thật lòng. Việc "hai người còn lại ngừng phát biểu" là minh chứng rõ ràng cho việc giao tiếp bị đóng lại, cản trở sự minh bạch và khả năng cùng nhau tìm ra giải pháp cải tiến hiệu quả của Scrum Team.

2.  **Product Owner độc quyền chọn giải pháp:**
    *   **Điểm chưa phù hợp:** Product Owner trả lời từng ý và tự chọn giải pháp. Điều này đi ngược lại Quy tắc nghiệp vụ QT2 ("Scrum Team cùng chọn Improvement; Scrum Master không chọn thay") và tinh thần tự quản lý của Scrum Team.
    *   **Tác động:** Hành động này tước đi quyền cùng quyết định các hành động cải tiến của Developers và Scrum Master, biến Retrospective thành một buổi báo cáo và nhận chỉ thị thay vì một buổi động não và cam kết chung. Điều này làm giảm sự tham gia, quyền làm chủ và trách nhiệm của các thành viên đối với các Improvement đã chọn, ảnh hưởng đến khả năng thực hiện thành công các cải tiến trong Sprint sau.
