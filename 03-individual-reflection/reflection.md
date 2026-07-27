# 03 — Individual Reflection

> **Báo cáo phản tư cá nhân (Individual Reflection)** — Day 02 Lab: Tìm Đúng Bài Toán Cho AI  
> **Học viên:** Nguyễn Gia Thiều — **Mã học viên:** 2A202601759  
> **Nhóm:** Nhóm 12 thành viên (Nhóm trưởng: Nguyễn Hoàng Minh)  
> **Bài toán cá nhân Pitch:** Viết báo cáo thực tập hàng tuần từ GitHub, Jira, Discord (Candidate #2)  
> **Bài toán nhóm chọn chốt:** Tổng hợp báo cáo tiến độ dự án từ nhiều nguồn (Candidate #1)

---

## 1. Nhật ký hoạt động nhóm (Group Activity Log)

Bảng dưới đây ghi chép lại vai trò và đóng góp cụ thể của cá nhân tôi (Nguyễn Gia Thiều) trong suốt 7 Phase làm việc cùng nhóm:

| Phase / Hoạt động | Tôi đã làm gì cụ thể? | Kết quả & Ảnh hưởng tới nhóm |
|---|---|---|
| **Phase 1: Scan cá nhân** | Scan 10 bài toán thực tế từ trải nghiệm làm dự án AI và thực tập, chuẩn bị 3 Problem Cards chi tiết. | Đóng góp 10 bài toán đa dạng vào ngân hàng quan sát cá nhân. |
| **Phase 2: Top 3 & Workflow** | Chọn Candidate #2 *"Viết báo cáo thực tập hàng tuần từ GitHub, Jira, Discord"* làm bài pitch chính, vẽ sơ đồ Before/After Workflow. | Chuẩn bị đầy đủ luận điểm và sơ đồ quy trình để thuyết phục nhóm trong buổi pitch. |
| **Phase 3: Group Convergence** | - **Pitch:** Trình bày Candidate #2 trước nhóm.<br>- **Lắng nghe & Gom cluster:** Nghe 11 bài toán còn lại (Minh pitch Báo cáo tiến độ dự án, Nam Hải pitch Daily Checklist, Phước pitch Báo cáo TikTok/FB...). Gom 12 ý tưởng thành 4 cluster.<br>- **Score & Đồng thuận:** Chấm điểm shortlist theo 8 tiêu chí. Candidate Báo cáo tiến độ dự án (bạn Minh) đạt 34/40 điểm (cao nhất), Candidate của tôi đạt 28/40 điểm. Tôi hoàn toàn đồng thuận chọn bài của bạn Minh. | Nhóm hội tụ thành công từ 12 bài toán cá nhân về 1 bài toán nhóm duy nhất có workflow rõ ràng và impact cao nhất đối với PM/Leadership. |
| **Phase 4: Validation & Research** | - **Phase 4.1 Validation:** Cùng nhóm thực hiện Quick Interview 3 PM/PO và Mini Poll 6 học viên trong lớp, rút ra bài học thu hẹp scope sang AI draft narrative.<br>- **Phase 4.2 Research:** Tìm hiểu 4 giải pháp (*Atlassian Jira Reports, Slack AI, Gemini in Drive, Fellow AI Meeting Notes*). | Rút ra Insight cốt lõi: *Pain thật không nằm ở khâu lấy số liệu đơn thuần, mà nằm ở việc biến dữ liệu rời rạc thành Narrative Insight đủ rõ.* |
| **Phase 5: Workflow & Problem Statement** | Cùng nhóm xây dựng sơ đồ Workflow Before/After (7 bước 90' → 5 bước 25'), lập bảng chi tiết 7 bước Current State, bảng 5 bước Phạm vi Pilot bán thủ công, so sánh Impact và làm rõ sự thay đổi từ Problem Statement v0 sang v1. | Xác định chính xác vị trí AI can thiệp (bước 3: AI draft narrative) và thiết lập Human Boundary (bước 4: PM review & edit). |
| **Phase 6: Rule/Workflow/Agent & Decision** | Lập luận so sánh 4 mức (bổ sung No AI / process fix làm fallback). Phản đối dùng Agent tự động gửi report. Thống nhất chọn mức **Workflow** cho pilot bán thủ công 2 tuần, có bảng kiểm tra 6 tiêu chí chốt quyết định và điều kiện Exit / Rollback rõ ràng. | Nhóm thống nhất chọn mức **Workflow**, ra quyết định **Go với scope nhỏ (Pilot 2 tuần dùng dữ liệu mẫu bán thủ công)**. |
| **Phase 7: Reflection** | Đánh giá toàn bộ quá trình làm việc nhóm, phân tích cách dùng AI và rút ra bài học kinh nghiệm cá nhân. | Hoàn thành bài thu hoạch phản tư cá nhân khớp 100% với Group Report của nhóm. |

---

## 2. Bảng phản tư dùng AI trong Lab (AI Usage Reflection)

| Phase | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai / hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| **Scan cá nhân** | Gợi ý thêm các góc nhìn bài toán từ vai trò sinh viên thực tập AI. | Gợi ý bài toán về tra cứu tài liệu AI Spec và setup môi trường rất đúng thực tế. | Gợi ý vài ý tưởng mang tính giải pháp kiểu "Xây bot nhắc deadline tự động". | Loại bỏ các ý tưởng dạng bot nhắc nhở (vì chỉ cần Google Calendar), giữ lại bài toán có workflow thao tác lặp lại. |
| **Problem Card & Workflow** | Chuyển mô tả Current State Workflow thành sơ đồ Mermaid. | Tạo cú pháp Mermaid nhanh, tiết kiệm thời gian vẽ tay. | AI tự động gộp bước "Lấy metrics" và "Viết Narrative" thành 1 bước, làm mờ đi bottleneck. | Tách riêng bước "Viết narrative" thành bước nghẽn độc lập (mất 25-40 phút). |
| **Research giải pháp** | Tìm các công cụ đã hỗ trợ viết Weekly Report tự động trên thị trường. | Tìm được Fellow.ai, Slack AI, Jira Reports, Gemini in Drive. | AI đưa ra một số khẳng định thổi vồng hiệu quả mà không có link trích dẫn chứng minh. | Kiểm tra lại tài liệu chính thức của Atlassian/Slack, loại bỏ các thông tin không verified. |
| **Problem Statement** | Nhờ AI đóng vai Skeptical PM để phản biện bản draft PS v0 của nhóm. | Chỉ ra Success Metric ban đầu còn chung chung ("giúp viết báo cáo tốt hơn"). | AI gợi ý cho AI tự động gửi báo cáo trực tiếp cho CEO mà không cần PM duyệt. | Giữ vững Human Boundary trong PS v1: Khẳng định AI chỉ draft, PM bắt buộc phải review và bấm gửi. Scope pilot làm bán thủ công. |
| **Decision (Go/No-Go)** | Phân tích so sánh rủi ro giữa 4 phương án (No AI, Rule, Workflow, Agent). | Phân tích rõ nguy cơ hallucination (bị số liệu) và rủi ro bảo mật permission của Agent. | AI có xu hướng khuyên nhóm nên nâng cấp lên Agent đa tính năng cho "hiện đại". | Cùng nhóm chốt giữ nguyên ở mức **Workflow** (pilot bán thủ công 2 tuần), bổ sung phương án No AI (Template + Dashboard) làm Fallback/Exit plan nếu AI draft bị sửa lại >70%. |

---

## 3. Bài học rút ra (Lessons Learned)

### 1. Học được gì khi nhóm chọn bài toán khác bài toán cá nhân mình pitch?
- Bài toán cá nhân tôi pitch là *"Viết báo cáo thực tập hàng tuần"* (đạt 28/40 điểm trong bảng chấm nhóm). Nhóm đã chọn bài toán của bạn Minh *"Tổng hợp báo cáo tiến độ dự án từ nhiều nguồn"* (đạt 34/40 điểm).
- Tôi học được rằng bài toán của bạn Minh có **Actor rõ hơn** (Junior PM làm việc trực tiếp với CEO/EM), **Impact rộng hơn** (ảnh hưởng tới quyết định của cả đội ngũ leadership) và **Workflow có tính chuẩn hóa cao hơn**.
- Việc sẵn sàng lùi lại bài toán cá nhân để hội tụ về bài toán có điểm số cao nhất và tác động lớn nhất cho nhóm là một trải nghiệm làm việc nhóm rất giá trị.

### 2. Tại sao "Problem-First" lại quan trọng hơn "AI-First"?
- Nếu bắt đầu bằng tư duy "Tôi muốn làm một Agent AI", chúng ta sẽ cố gượng ép AI vào mọi khâu bất chấp bài toán đó chỉ cần một Dashboard tự động hay một Template cố định.
- Bắt đầu từ **Actor → Workflow → Bottleneck → Success Metric** giúp nhóm thấy rõ AI chỉ nên đóng vai trò hỗ trợ ở đúng bước tắc nghẽn nhất (bước viết narrative từ raw data).

### 3. Khi nào chọn Rule, Workflow hay Agent?
- **No AI / Process Fix (Fallback):** Dùng Template report + Dashboard + Checklist khi report chỉ cần số liệu cố định và người viết tự tạo narrative, làm phương án fallback/exit nếu AI draft không đạt kỳ vọng (>70% phải viết lại).
- **Rule:** Khi quy trình cố định 100%, logic đúng/sai tuyệt đối (Ví dụ: Jira Dashboard tự động kéo số liệu velocity).
- **Workflow:** Khi quy trình gồm các bước tuyến tính cố định, nhưng có 1-2 bước cần xử lý ngôn ngữ tự nhiên (Ví dụ: Chuẩn bị input → Cấu trúc data → AI draft narrative → PM review & edit → PM gửi report). Đây là lựa chọn tối ưu cho nhóm (thử nghiệm pilot bán thủ công).
- **Agent:** Chỉ cần khi hệ thống phải tự lập kế hoạch động (dynamic planning), tự quyết định gọi công cụ và tự chạy vòng lặp mà không có quy trình cố định từ trước.

### 4. Điều khó nhất khi viết Problem Statement là gì?
- Điều khó nhất là định nghĩa **Success Metric** và **Boundary** cụ thể. Ban đầu nhóm hay ghi "tiết kiệm thời gian". Nhóm đã phải ép bản thân ghi rõ baseline hiện tại (90 phút/tuần) và mục tiêu sau cải thiện (< 30 phút/tuần).
- Về Boundary, phải ghi rất rõ "AI không tự gửi report, không tự bịa số liệu, không thay PM approve nội dung cuối" để làm ranh giới an toàn vận hành. Thêm vào đó, scope v1 thu hẹp rõ ràng: AI chỉ can thiệp sau khi dữ liệu đã gom, trước khi PM viết narrative.

### 5. Nếu làm lại Lab này, tôi sẽ thay đổi điều gì?
- Tôi sẽ cùng nhóm thiết kế sẵn 2-3 prompt mẫu chuẩn trong bước Pilot bán thủ công để đo lường chính xác thời gian PM edit và tỷ lệ PM phải sửa lại bản nháp narrative (target là PM không phải gõ lại quá 30% nội dung trong 2 tuần thử nghiệm).

### 6. Bài học lớn nhất từ Day 02:
> **"Một giải pháp Workflow đơn giản giải đúng nút thắt thật của bài toán luôn có giá trị vượt trội so với một Agent AI phức tạp cố giải một bài toán mơ hồ."**

---

## 4. Bảng tự kiểm cuối bài (Final Self-Check Checklist)

Tôi đã tự kiểm tra bài nộp cá nhân đối chiếu với Thang điểm Rubric cá nhân (40 điểm) và độ đồng bộ với bản nộp nhóm:

- [x] **Scan Problem + Top 3 Problem Cards (12/12 điểm cá nhân):**
  - [x] Đã scan đủ 10 candidate problems từ trải nghiệm thật (vượt mức 5 tối thiểu, đạt điểm bonus).
  - [x] Có ma trận chấm điểm Top 3 và lý do loại bỏ 7 bài toán không chọn.
  - [x] Top 3 Problem Cards đầy đủ 15 trường thông tin theo đúng template worksheet.
- [x] **Tham gia Pitch & Challenge (12/12 điểm cá nhân):**
  - [x] Trình bày trung thực việc pitch Candidate #2 (Báo cáo thực tập) và quá trình hội tụ về bài toán của nhóm (Báo cáo tiến độ dự án).
  - [x] Có tinh thần challenge đúng trọng tâm và đồng thuận cao với quyết định của nhóm.
- [x] **Reflection cá nhân (10/10 điểm cá nhân):**
  - [x] Nhật ký hoạt động nhóm mô tả chính xác kết quả thảo luận 12 thành viên và các bảng chi tiết mới trong `group-report.md`.
  - [x] Phân tích trung thực việc sử dụng AI (điểm tốt, điểm AI sai/hời hợt, cách con người sửa).
  - [x] Trả lời đầy đủ và sâu sắc 6 câu hỏi phản tư mở.
- [x] **Kiểm tra hiểu bài cá nhân (6/6 điểm cá nhân):**
  - [x] Tự giải thích rõ mạch tư duy: *Problem → Workflow → Metric → Boundary → Độ phù hợp với AI*.
  - [x] Thấu hiểu lý do nhóm chọn **Workflow** (Go với scope nhỏ: Pilot 2 tuần bán thủ công) thay vì **Agent**.

---
*Báo cáo phản tư cá nhân hoàn tất*
