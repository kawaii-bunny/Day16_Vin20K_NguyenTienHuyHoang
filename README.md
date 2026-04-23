# Day 16 Submission — Team 4

## Members
- Nguyễn Tiến Huy Hoàng 
- ID: 2A202600486

---

## 1. Idea reframed
Original idea:
> Dùng AI giúp người sale sàng lọc được khách hàng chất lượng để đẩy nhanh quá trình bán hàng.

Reframed as a product opportunity:
> Một trợ lý "AI Sales Qualifier" chuyên biệt cho môi giới BĐS cao cấp, tự động tương tác và chấm điểm khách hàng ngay khi họ vừa để lại thông tin (Lead). Sản phẩm giải quyết khoảng trống giữa việc "có data khách hàng" và "thực sự gọi điện tư vấn", giúp Sales loại bỏ 70% khách hàng rác và tập trung nguồn lực vào những nhà đầu tư có thực lực tài chính.

---

## 2. Customer / Segment Card
- **Segment name:** Cá nhân môi giới Bất động sản phân khúc Cao cấp (Luxury Real Estate Agents).
- **Operational context:** Chạy quảng cáo số (Facebook/Google Ads) đổ về Zalo/Messenger với lượng 20-50 khách mới mỗi ngày.
- **Recurring workflow:** Nhận Lead -> Cold call chào hỏi -> Khai thác nhu cầu/tài chính -> Gửi tài liệu -> Sàng lọc.
- **Pain moment:** Mất quá nhiều thời gian và năng lượng để tư vấn cho những người "hỏi cho vui" hoặc không đủ tài chính, dẫn đến bỏ lỡ "thời điểm vàng" để phản hồi các khách hàng thực sự nét.
- **Why now:** LLM hiện nay đủ thông minh để thực hiện các cuộc hội thoại sàng lọc tinh tế, không còn cứng nhắc như chatbot truyền thống, giúp giữ chân khách hàng cao cấp tốt hơn.
- **Access path:** Cộng đồng môi giới BĐS chuyên nghiệp (Realtor groups), các sàn giao dịch lớn (Vinhomes, Sun Group partners).

One-sentence description:
> Môi giới BĐS cao cấp đang bị "đắm chìm" trong dữ liệu khách hàng rác và cần một bộ lọc thông minh để biết chính xác ai là người đáng để gọi điện tư vấn ngay lập tức.

---

## 3. Need Map (2-3 needs)

### Need #1 (priority)
- **Statement (JTBD):** When I receive a new inquiry from a digital ad, I want to know their financial readiness and specific investment goal immediately, so I can prioritize my time for the top 5% of leads.
- **Current workaround:** Gọi điện thủ công cho mọi khách hàng hoặc dùng Chatbot kịch bản (Script-based) khiến khách hàng khó chịu.
- **Pain signal:** Tỷ lệ chốt đơn thấp, chi phí cơ hội cao do dành thời gian cho sai đối tượng.
- **Evidence / proxy evidence:** Phản hồi từ các Group cộng đồng: "Data quảng cáo dạo này ảo quá", "Gọi 20 khách mới được 1 khách nét".

### Need #2
- **Statement (JTBD):** When a potential lead asks basic project questions late at night, I want them to receive instant, professional answers that lead to a qualification step, so I don't lose the lead to a faster competitor.
- **Current workaround:** Để khách chờ đến sáng hôm sau hoặc dùng tin nhắn trả lời tự động đơn giản.
- **Pain signal:** Khách hàng mất hứng thú hoặc đã nhắn tin cho môi giới khác phản hồi nhanh hơn.
- **Evidence / proxy evidence:** Dữ liệu tỷ lệ rơi rụng (drop-off rate) khách hàng tăng cao sau 30 phút không phản hồi.

---

## 4. Strategy Statement
For **High-end Real Estate Agents** who struggle with **wasted time on low-quality leads from digital ads**, our product helps them **increase sales efficiency and conversion rates** through **AI-driven "soft-screening" conversations via Zalo/Messenger**, unlike **generic CRMs or stiff chatbots**, because we can leverage **deep real-estate domain logic and behavioral profiling of Vietnamese investors.**

---

## 5. Moat Hypothesis
**Moat mechanism:** Domain-learning flywheel (Học hỏi theo chiều sâu lĩnh vực).

If we deploy 50 times in the luxury real estate context, the following improve:
1. **Khả năng nhận diện tín hiệu ngầm:** AI học được các mẫu câu/cách hỏi đặc thù của nhà đầu tư "cá mập" (ví dụ: quan tâm đến dòng tiền, pháp lý hơn là giá tổng).
2. **Kịch bản sàng lọc tối ưu:** Tự động điều chỉnh bộ câu hỏi dựa trên phản hồi của thị trường đối với từng dự án cụ thể.
3. **Niềm tin của người dùng:** Dữ liệu tích lũy giúp AI tư vấn "có tâm" và đúng trọng tâm hơn, tạo ra sự khác biệt so với các bot đại trà.

Why competitors cannot easily replicate this:
> Các đối thủ lớn (như Salesforce/HubSpot) tập trung vào quy trình chung toàn cầu, không hiểu sâu tâm lý và văn hóa "chốt deal" đặc thù của thị trường BĐS Việt Nam cũng như không tích hợp sâu vào các nền tảng địa phương như Zalo.

---

## 6. Initial TAM / SAM / SOM view

| Layer | Estimate | Key assumptions | Confidence |
|---|---|---|---|
| TAM | $50M/year | 1 triệu môi giới BĐS tại VN, chi trả trung bình $50/năm. | Medium |
| SAM | $10M/year | 200,000 môi giới phân khúc cao cấp/đầu tư chuyên nghiệp. | High |
| SOM | $500K/year | Chiếm 5% thị phần môi giới cao cấp trong 12-18 tháng đầu. | Medium |

**Top 3 unknowns requiring further research:**
1. Mức độ sẵn sàng chia sẻ data khách hàng của môi giới cho một công cụ AI bên thứ ba.
2. Khả năng tích hợp API chính thức/ổn định vào Zalo.
3. Chi phí vận hành LLM (Token cost) so với mức phí người dùng sẵn sàng trả.

**Judgment:**
- [x] Worth pursuing now
- [ ] Worth pursuing but not now
- [ ] Not worth pursuing as currently framed

---

## 7. Positioning Note (2 sentences)
**What we are:**
> Một trợ lý sàng lọc thông minh giúp môi giới BĐS cao cấp tìm thấy "vàng" trong đống dữ liệu quảng cáo.

**What we are not / not yet:**
> Một công cụ thay thế con người để tư vấn sâu hoặc chốt hợp đồng pháp lý; chúng tôi chỉ là bộ lọc hiệu quả nhất ở giai đoạn đầu.

---

## 8. Self-assessment before Day 17
Mắt xích yếu nhất hiện tại: **Market Size (Sự chính xác của các giả định tài chính)**.
> Chúng tôi cần kiểm chứng lại mức phí mà một cá nhân môi giới sẵn sàng trả hàng tháng so với giá trị thời gian họ tiết kiệm được.

Open questions chúng tôi muốn khám phá thêm ở Day 17:
1. Làm thế nào để thiết kế một kịch bản AI "không gây khó chịu" mà vẫn lấy được thông tin nhạy cảm (tài chính)?
2. MVP cần những tính năng tối thiểu nào để Sales thấy hiệu quả ngay lập tức?
3. Cách đo lường hiệu quả (ROI) trực tiếp để thuyết phục khách hàng xuống tiền mua phần mềm.
