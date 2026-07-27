# KẾ HOẠCH CHI TIẾT GIAI ĐOẠN 1 — BETA / PILOT

**Dự án:** KOVIA · HANGIL 한길 — Nền tảng hành lang Việt – Hàn
**Phạm vi:** Tháng 3 → Tháng 11 (9 tháng)
**Phiên bản:** 1.2 — 27/07/2026 (bổ sung nguồn dữ liệu ngoài và mục Đi lại & du lịch)
**Đi kèm:** Đề án v2.4, Bộ nhận diện v2.0

---

## MỤC LỤC

1. Cách đọc tài liệu này
2. Tổng quan G1
3. **Nhóm A — Nội dung**
4. **Nhóm B — Studio (AI Social Media)**
5. **Nhóm C — Sản phẩm**
6. **Nhóm D — Cộng đồng & Doanh thu**
7. **Nhóm E — Vận hành & Tuân thủ**
8. Đường găng và phụ thuộc chéo
9. Lịch đầu ra theo tháng
10. Nhịp vận hành và bảng chỉ số
11. Cửa vượt sang G2
12. Checklist tuần đầu tiên

---

# 1. CÁCH ĐỌC TÀI LIỆU NÀY

Mỗi nhóm có **một người chịu trách nhiệm duy nhất** và **một con số duy nhất** phải báo cáo hằng tuần. Không có đồng chủ trì, không có chỉ số phụ trong báo cáo tuần.

Ba nhịp trong G1:

| Nhịp | Thời gian | Tên | Câu hỏi của nhịp |
|---|---|---|---|
| **Nhịp 1** | T3 – T5 | Lên sóng | Nội dung có giữ chân được không? |
| **Nhịp 2** | T6 – T8 | Giao dịch đầu tiên | Người xem có chịu mua không? |
| **Nhịp 3** | T9 – T11 | Leo hạng | Người bán giỏi có ở lại không? |

**Quy ước ưu tiên trong tài liệu:**
`★★★` không làm thì cả nhịp đứng · `★★` quan trọng, có thể trượt 2 tuần · `★` làm được thì tốt

---

# 2. TỔNG QUAN G1

## 2.1 G1 tồn tại để làm gì

Không phải để ra mắt sản phẩm. Để trả lời ba câu:

1. **Nội dung có giữ chân được không?** — đo bằng D30, không đo bằng lượt xem
2. **Người xem có chịu giao dịch không?** — đo bằng đơn hàng và buổi gia sư đầu tiên
3. **Chi phí thu hút có tiến về 0 không?** — đo bằng tỷ lệ chuyển sang Zalo OA

Mọi việc trong tài liệu này chỉ có nghĩa nếu nó phục vụ một trong ba câu trên. Việc nào không phục vụ câu nào — cắt.

## 2.2 Năm nhóm, mười hai người

| Nhóm | Người | Chịu trách nhiệm | Con số báo cáo tuần |
|---|---|---|---|
| **A · Nội dung** | Trưởng nội dung, 2 sản xuất, 1 bản ngữ Hàn (bán thời gian) | Trưởng nội dung | Số mảnh xuất bản / tuần |
| **B · Portal & Agent** | 1 kỹ sư AI (ngồi trong nhóm C) | Kỹ sư AI | Chi phí trung bình / mảnh nội dung |
| **C · Sản phẩm** | Trưởng kỹ thuật, 3 fullstack | Trưởng kỹ thuật | Số ngày trễ so với mốc ship |
| **D · Cộng đồng & Doanh thu** | CEO, 1 quản lý cộng đồng, 1 vận hành Chợ | CEO | Người theo dõi Zalo OA + doanh thu ký mới |
| **E · Vận hành & Tuân thủ** | CEO kiêm, thuê ngoài pháp lý và kế toán | CEO | Số rào cản pháp lý còn mở |

## 2.3 Nút thắt thật của G1

Với một đội phát triển mạnh và ngân sách quảng cáo bằng 0, **nút thắt không nằm ở kỹ thuật**. Nó nằm ở hai chỗ:

1. **Sản lượng nội dung** — nếu không đạt 40–60 mảnh/tuần thì phễu không đủ rộng
2. **Số người bán tuyển được** — nếu không có 30 người bán thật thì Chợ không có gì để bán

Nhưng sau khi đưa Portal agentic vào nhịp 1 và bỏ rào cản pháp lý ra khỏi đường găng, **nút thắt chuyển sang nhóm C**: Web-App + website ba ngôn ngữ + Portal bảy tác nhân trong ba tháng là khối lượng rất căng với 3 fullstack và 1 kỹ sư AI.

Hệ quả về phân bổ nguồn lực: **Portal chia làm hai đợt** (xem 4.3). Đợt 1 chỉ dựng vòng lặp tối thiểu để nhóm A đạt sản lượng; phần còn lại lùi sang nhịp 2. Không cố làm đủ bảy tác nhân trong nhịp 1.

---

# 3. NHÓM A — NỘI DUNG

## 3.1 Mục tiêu nhóm

Sản xuất **400 Scene + 36 mini-doc + 50 kịch bản AI roleplay** trong 9 tháng, đạt nhịp ổn định 40–60 mảnh/tuần từ tháng 4, với chi phí dưới 120.000 đ/mảnh.

**Con số báo cáo tuần: số mảnh xuất bản.** Không báo cáo lượt xem trong họp tuần — lượt xem xem ở bảng tháng.

## 3.2 Nhịp 1 (T3 – T5) — Dựng nền và lên sóng

| Ưu tiên | Việc | Đầu ra cụ thể |
|---|---|---|
| ★★★ | **Bản đồ 400 tình huống** theo 7 nhóm quan hệ quyền lực | Bảng backlog có phân loại, cấp độ, từ khoá, sản phẩm liên quan |
| ★★★ | **Bible nội dung** — giọng nói thương hiệu, công thức 5 nhịp, điều cấm | Tài liệu 10–15 trang, ai cũng làm theo được |
| ★★★ | **Dựng 3 bối cảnh quay cố định** — góc nhà máy, phòng trọ, quầy dịch vụ | Phông và đạo cụ tại chỗ, quay được liên tục không phải di chuyển |
| ★★★ | **Sản xuất đợt 1: 150 Scene** | Đăng đủ trên 5 nền tảng |
| ★★★ | **Quy trình kiểm duyệt bản ngữ** — mỗi Scene phải qua người Hàn duyệt kính ngữ | Checklist duyệt, thời gian quay vòng dưới 48 giờ |
| ★★ | **12 mini-doc "người thật việc thật"** | Nhân vật lấy từ mạng lưới đại sứ vùng của nhóm D |
| ★★ | **Chuẩn metadata mỗi Scene** — nhóm, cấp độ, từ khoá SEO, sản phẩm gắn kèm | Trường dữ liệu thống nhất với nhóm C |
| ★★ | **Casting** — 2 diễn viên Việt, 1 người Hàn | Hợp đồng cộng tác viên theo buổi |
| ★ | Series livestream thử nghiệm 2 số | Đo có ai xem không trước khi làm định kỳ |

**Quyết định phải chốt trong nhịp 1:** chọn **một nhóm kỹ năng duy nhất** cho AI roleplay ở nhịp 2. Đề xuất *"Với cấp trên"* — vì đó là nhóm tình huống gây sợ nhất và cũng là nhóm không app nào dạy.

## 3.3 Nhịp 2 (T6 – T8) — Nội dung sinh ra giao dịch

| Ưu tiên | Việc | Đầu ra cụ thể |
|---|---|---|
| ★★★ | **Sản xuất đợt 2: +120 Scene**, ưu tiên nhóm có D30 cao nhất từ dữ liệu nhịp 1 | Quyết định dựa trên bảng ROI, không dựa trên cảm tính |
| ★★★ | **Shoppable Scene** — gắn 1–3 sản phẩm Chợ vào mỗi Scene ẩm thực, mỹ phẩm, đời sống | Ít nhất 80 Scene có sản phẩm gắn kèm |
| ★★★ | **50 kịch bản AI roleplay** cho nhóm kỹ năng đã chọn, có phân nhánh | Bàn giao cho nhóm C dạng dữ liệu có cấu trúc |
| ★★ | **Thử thách 30 ngày đợt 1** — người học quay 15 giây mỗi ngày | Mục tiêu 1.000 video người dùng |
| ★★ | **Livestream định kỳ 1 số/tuần** | Lịch cố định, có khách mời |
| ★★ | +12 mini-doc | |
| ★ | Chuỗi "Hỏi gì đáp nấy" từ bình luận cộng đồng | 20–30 Scene/tháng, chi phí gần 0 |

## 3.4 Nhịp 3 (T9 – T11) — Nhân bản và mở sang tiếng Hàn

| Ưu tiên | Việc | Đầu ra cụ thể |
|---|---|---|
| ★★★ | **Sản xuất đợt 3: +130 Scene** | Đạt 400 Scene tổng |
| ★★★ | **Bộ công cụ nội dung cho người bán** — hướng dẫn quay, mẫu kịch bản, mẫu thumbnail | Người bán tự làm được nội dung, giảm tải cho nhóm A |
| ★★★ | **Bộ nội dung "Đi lại & du lịch"** — 40 mục: mua và nạp thẻ T-money, đọc bảng ga, đổi tuyến, gọi taxi, mua vé tàu | **T-money không có API công khai** — mảng này làm bằng nội dung hướng dẫn, không tích hợp |
| ★★ | **20 bài "Tiếng Việt công trường"** bằng tiếng Hàn cho khách B2B | Nhóm D dùng làm tài liệu bán hàng |
| ★★ | **Tái sản xuất top 20 Scene thành video dài YouTube** | Phục vụ SEO, tuổi thọ nội dung dài hơn |
| ★★ | +12 mini-doc | |
| ★ | Thử thách 30 ngày đợt 2 | |

## 3.5 Chỉ số của nhóm A

| Chỉ số | Mục tiêu cuối G1 |
|---|---|
| Mảnh xuất bản / tuần | 40 – 60 |
| Chi phí / mảnh | < 120.000 đ |
| D30 trung bình | > 22% |
| Tỷ lệ xem hết Scene | > 55% |
| Số Scene có sản phẩm gắn kèm | ≥ 150 |
| Thời gian từ ý tưởng đến đăng | < 12 giờ |

## 3.6 Phụ thuộc và rủi ro riêng

**Phụ thuộc:** cần Studio M2 + M4 (nhóm B) xong trước T4, nếu không sản lượng dừng ở 12–15 mảnh/tuần. Cần nhân vật thật từ đại sứ vùng (nhóm D) cho mini-doc.

**Rủi ro riêng — bản quyền.** Tuyệt đối không dùng clip phim Hàn, MV K-pop, nhạc có bản quyền, ảnh người nổi tiếng. Một lần vi phạm là mất kênh, và mất kênh là sập toàn bộ chiến lược quảng cáo bằng 0. Đây là điều khoản cứng trong bible nội dung, người duyệt phải ký xác nhận từng đợt.

---

# 4. NHÓM B — PORTAL & AGENT

## 4.1 Định vị lại: Portal là backend của Web-App, không phải công cụ rời

Studio không còn là một hệ thống riêng. Nó là **Backend Portal của Web-App** — chung danh tính, chung phân quyền, chung kho dữ liệu.

Ba lý do kiến trúc:

1. **Đo lường đầu–cuối không phải nối hai hệ thống.** Truy vết từ bài đăng → theo dõi OA → đăng ký → học → mua chỉ chạy được nếu nội dung và người dùng nằm chung một cơ sở dữ liệu.
2. **Phân quyền dùng chung.** Admin · Biên tập · Sản xuất · Bản ngữ duyệt · Người bán · Người dùng — một hệ vai trò, không phải hai.
3. **Đây chính là công cụ sẽ giao cho người bán ở nhịp 3.** Cùng luồng sinh nội dung, cùng hàng đợi duyệt. Store Builder không phải xây lại từ đầu — nó là Portal mở quyền cho người ngoài.

Mục tiêu vẫn như cũ: để **một đội ba người sản xuất được khối lượng của mười người**. Không có Portal thì nguyên tắc "quảng cáo bằng 0" không khả thi.

## 4.2 Luồng agentic — bảy chặng, một cổng người

```
① Ý TƯỞNG      Insight Agent    xu hướng, bình luận, câu hỏi, từ khoá SEO
                                 → kho chủ đề có điểm nhu cầu
                    ↓
② KỊCH BẢN     Script Agent     sinh theo công thức 5 nhịp,
                                 đối chiếu RAG từ nguồn đã duyệt
                    ↓
③ SẢN XUẤT     Produce Agent    lồng tiếng, phụ đề song ngữ,
                                 cắt 9:16 / 1:1 / 16:9, thumbnail, nhận diện
                    ↓
④ PHÊ DUYỆT    ███ NGƯỜI ███    hàng đợi duyệt · xem trước theo từng nền tảng
                                 · người bản ngữ Hàn duyệt kính ngữ
                                 ▲ CỔNG BẮT BUỘC — agent không được vượt
                    ↓
⑤ ĐĂNG         Publish Agent    TikTok · YouTube · Facebook · IG/Threads
                                 · Zalo OA — lịch theo múi giờ VN và KR
                    ↓
⑥ ĐO LƯỜNG     Measure Agent    thu số liệu về, ghép với hành vi trên nền tảng
                    ↓
⑦ TỐI ƯU       Optimize Agent   xếp hạng Scene theo giá trị sinh ra,
                                 đề xuất chủ đề tiếp, thử nghiệm hook
                    └──────────────→ quay lại ①
```

**Hàng rào của agent — không ngoại lệ:**

- Không tác nhân nào được tự đăng. Chặng ④ là cổng cứng.
- Không tác nhân nào trả lời câu hỏi visa, pháp lý, y tế bằng giọng chắc chắn.
- Mọi thông tin pháp lý phải truy được về văn bản gốc kèm ngày cập nhật.
- Nhật ký đầy đủ: ai duyệt, lúc nào, sửa gì.
- Nút dừng khẩn cấp: gỡ toàn bộ một chiến dịch trong 5 phút.

## 4.3 Chia hai đợt — đừng làm đủ bảy tác nhân trong nhịp 1

| Đợt | Ship | Gồm chặng | Vì sao đủ |
|---|---|---|---|
| **Đợt 1** | **T5** | ② Kịch bản · ④ Phê duyệt · ⑤ Đăng | **Vòng lặp tối thiểu** để nhóm A đạt sản lượng. Ba chặng còn lại làm tay được trong 3 tháng |
| **Đợt 2** | **T8** | ① Ý tưởng · ③ Sản xuất · ⑥ Đo lường · ⑦ Tối ưu | Khi đã có dữ liệu thật để tối ưu, và khi nhóm C rảnh tay sau nhịp 1 |

**Con số báo cáo tuần: chi phí trung bình trên một mảnh nội dung.**

## 4.4 Nhịp 1 (T3 – T5) — Vòng lặp tối thiểu

| Ưu tiên | Mô-đun | Việc cụ thể |
|---|---|---|
| ★★★ | **M2 SCRIPT** | Kho tri thức RAG từ nguồn đã duyệt (luật lao động, visa, thủ tục cư trú, thuế); sinh kịch bản đúng công thức 5 nhịp; giao diện duyệt của người; mọi thông tin pháp lý phải truy được về văn bản gốc kèm ngày cập nhật |
| ★★★ | **④ PHÊ DUYỆT** | Hàng đợi duyệt trong Portal; xem trước theo từng nền tảng; ghi chú sửa; luồng duyệt riêng cho người bản ngữ Hàn kiểm kính ngữ |
| ★★★ | **⑤ ĐĂNG (Publish Agent)** | Một tài sản gốc → 8–12 biến thể; viết lại hook riêng từng nền tảng; lịch đăng theo múi giờ VN và KR; nối API TikTok, YouTube, Meta |
| ★★★ | **Hàng rào và nhật ký** | Bộ luật nội dung máy kiểm được; nhật ký kiểm toán; nút dừng khẩn cấp |
| ★★ | Hạ tầng tài sản | Quy ước đặt tên file, thư viện bản gốc, sao lưu hai lớp |

**Nguyên tắc kiến trúc:** dùng SaaS có sẵn cho M3, M4, M7. **Chỉ tự xây M1, M2, M5, M6, M8** — đó là chỗ chứa tri thức riêng về hành lang Việt – Hàn và là chỗ tạo lợi thế.

## 4.5 Nhịp 2 (T6 – T8) — Sản xuất tự động và tương tác

| Ưu tiên | Mô-đun | Việc cụ thể |
|---|---|---|
| ★★★ | **M3 PRODUCE** | Phụ đề song ngữ tự động; lồng tiếng bản ngữ Hàn và Việt; sinh thumbnail; cắt đa tỷ lệ 9:16 / 1:1 / 16:9; chèn nhận diện |
| ★★★ | **M5 ENGAGE** | Phân loại bình luận và tin nhắn thành 4 luồng: câu hỏi ngôn ngữ (AI trả lời + gắn Scene) · câu hỏi visa/pháp lý/y tế (**bắt buộc chuyển người thật**) · ý định mua (chuyển Zalo OA) · tiêu cực và spam (ẩn, ghi log) |
| ★★ | **① INSIGHT** | Theo dõi xu hướng từ nguồn công khai và API chính thức; kho chủ đề xếp theo điểm nhu cầu |
| ★★★ | **Nối Naver Search API** | Tin ngắn, xu hướng từ khoá, bài cafe — 25.000 lượt/ngày miễn phí, chỉ cần Client ID và Secret. Đây là nguồn của mục "Tin ngắn cho người Việt ở Hàn" |
| ★★ | **Nối YouTube Data API v3** | Tuyển playlist video ngắn. **Quota 10.000 đơn vị/ngày, mỗi lệnh tìm kiếm tốn 100 đơn vị, không mua thêm được** — bắt buộc đệm kết quả và duyệt playlist thủ công, không gọi theo từng người dùng |

**Lằn ranh tuyệt đối:** không dùng công cụ không chính thức để đọc, gửi hoặc tự động hoá tin nhắn cá nhân trên Zalo hay KakaoTalk. Vi phạm điều khoản nền tảng và tiềm ẩn vi phạm luật dữ liệu ở cả hai nước.

## 4.6 Nhịp 3 (T9 – T11) — Tối ưu và mở quyền cho người bán

| Ưu tiên | Mô-đun | Việc cụ thể |
|---|---|---|
| ★★★ | **M7 MEASURE** | Truy vết bài đăng → theo dõi OA → đăng ký → học → mua; bảng ROI theo từng Scene: Scene nào sinh ra người trả tiền, Scene nào chỉ sinh lượt xem |
| ★★ | **M6 HARVEST** | Bình luận hay → Scene mới; đánh giá đơn hàng → nội dung bán hàng; gom video từ thử thách 30 ngày |
| ★★ | Tối ưu chi phí | Chọn mô hình theo tác vụ, gộp yêu cầu, đệm kết quả; mục tiêu giảm 40% chi phí API so với nhịp 1 |
| ★★ | **Mở Portal cho người bán** | Cùng luồng ②→④→⑤ nhưng phạm vi hẹp: người bán sinh nội dung cho chính cửa hàng mình. Đây là nền của Store Builder |

## 4.7 Chỉ số của nhóm B

| Chỉ số | Trước Studio | Mục tiêu cuối G1 |
|---|---|---|
| Mảnh nội dung / tuần với 3 người | 8 – 12 | **45 – 60** |
| Thời gian ý tưởng → đăng | 3 – 5 ngày | **< 12 giờ** |
| Chi phí / mảnh | 400 – 800k đ | **60 – 120k đ** |
| Số nền tảng phủ | 2 – 3 | **5 – 6** |
| Tỷ lệ bình luận được trả lời trong 2 giờ | — | > 80% |

---

# 5. NHÓM C — SẢN PHẨM

## 5.1 Mục tiêu nhóm

Ba mốc ship, mỗi nhịp một mốc. **Con số báo cáo tuần: số ngày trễ so với mốc ship.**

## 5.2 Nhịp 1 — Ship tháng 5: Ba bề mặt lên cùng lúc

| Ưu tiên | Việc | Chi tiết |
|---|---|---|
| ★★★ | **Web-App — Frontend** | Đăng ký/đăng nhập, hồ sơ người dùng, thư viện Scene, theo dõi tiến độ học, tìm kiếm, lưu Scene |
| ★★★ | **Web-App — Backend Portal (đợt 1)** | Vòng lặp ② Kịch bản → ④ Phê duyệt → ⑤ Đăng đa kênh; hệ vai trò Admin/Biên tập/Sản xuất/Bản ngữ duyệt; nhật ký và nút dừng. Chi tiết ở chương 4 |
| ★★★ | **Website giới thiệu ba ngôn ngữ** | Việt (người dùng) · **Hàn (khách B2B)** · Anh (nhà đầu tư). Kèm trung tâm nội dung SEO |
| ★★ | **Zalo OA bản cơ bản** | Đủ để nhắn tin cho người theo dõi. **Mini App đầy đủ và ZNS lùi sang khi có OA doanh nghiệp** — xem 7.2 |
| ★★★ | **Hạ tầng dữ liệu đúng ngay từ đầu** | Kho tách theo vùng (VN/KR); đồng ý riêng biệt cho thông báo / marketing / chuyển dữ liệu xuyên biên giới; nhật ký truy cập |
| ★★★ | **Đo lường và truy vết từ ngày đầu** | Không làm sau. Không có attribution thì không trả lời được câu hỏi số 3 của G1 |
| ★★ | Nền tảng thiết kế | Áp bộ nhận diện Con dấu; thư viện thành phần dùng chung cho web và Mini App |

**Thứ tự ship trong nhịp 1 — quan trọng:** Web-App Frontend và Website lên trước, Portal đợt 1 lên ngay sau. **Zalo Mini App đầy đủ không nằm trong nhịp 1** vì nó cần OA đã xác thực doanh nghiệp, mà pháp nhân đã được đưa ra khỏi đường găng.

**Lưu ý về website tiếng Hàn:** phần này nhỏ về khối lượng nhưng **mở khoá dòng doanh thu sớm nhất** — nó cho nhóm D vào khách B2B từ tháng 6 thay vì tháng 9. Không được xếp sau.

## 5.3 Nhịp 2 — Ship tháng 8: Chợ và AI luyện nói

| Ưu tiên | Việc | Chi tiết |
|---|---|---|
| ★★★ | **Chợ Pilot** | Danh mục, trang sản phẩm, giỏ hàng, đặt hàng, theo dõi đơn, đánh giá có xác thực mua hàng. **Thanh toán và hoá đơn do đối tác nhà nhập khẩu xử lý** — xem 6.2 |
| ★★★ | **Portal đợt 2** | ① Ý tưởng · ③ Sản xuất tự động · ⑥ Đo lường · ⑦ Tối ưu |
| ★★★ | **Công cụ vận hành Chợ** | Thẩm định người bán 3 tầng; kiểm duyệt sản phẩm qua 6 cổng; quản lý khiếu nại; đối soát doanh thu với đối tác |
| ★★★ | **AI roleplay** | Ghi âm, chấm phát âm và ngữ điệu, **phát hiện lỗi mức độ lịch sự**, phản hồi có thể hành động |
| ★★ | **Đặt lịch gia sư + thanh toán** | Không làm sàn mở — chỉ 20–30 gia sư tuyển tay |
| ★★ | Hồ sơ năng lực bản rút gọn | Ghi nhận dữ liệu năng lực từ bây giờ để G2 có sẵn — chưa hiển thị ra ngoài |
| ★★ | **Sẵn sàng chuyển đổi thanh toán** | Thiết kế để khi có pháp nhân thì bật cổng thanh toán và ký quỹ của chính nền tảng, không phải làm lại |

## 5.4 Nhịp 3 — Ship tháng 11: Store Builder bản mời

| Ưu tiên | Việc | Chi tiết |
|---|---|---|
| ★★★ | **Store Builder** | Tạo cửa hàng trong 5 phút; mẫu giao diện; **AI dịch mô tả Việt ↔ Hàn giữ đúng thuật ngữ ngành hàng**; sinh nội dung bán hàng từ ảnh và thông số; quản lý đơn, tồn kho, khách hàng |
| ★★★ | **Cơ chế mời và điểm tin cậy** | Ngưỡng leo hạng tự động; điểm tin cậy tích luỹ trên Chợ **đi theo người bán sang cửa hàng riêng** |
| ★★★ | **Mục "Đi lại & du lịch" trong Khám phá** | Nối **TourAPI 4.0** (điểm đến, sự kiện, lưu trú), **ODsay LAB** (tìm đường công cộng toàn quốc), **Kakao Map** (tìm địa điểm). Ba nguồn này phủ gần đủ nhu cầu tra bản đồ và đi lại |
| ★★ | **Tối ưu chuyển đổi** | Onboarding, thông báo đúng lúc, gợi ý Scene → sản phẩm, nhắc học lại |
| ★★ | **Zalo Mini App đầy đủ + ZNS** | Bật khi OA doanh nghiệp xong. Nếu pháp nhân xong ở T8–T9 thì Mini App vào nhịp 3 |
| ★★ | **Chuyển Chợ về tự thu tiền** | Khi pháp nhân và thông báo sàn TMĐT xong: bật cổng thanh toán, ví ký quỹ, hoàn tiền |
| ★ | Chuẩn bị Kakao | Kakao Login sẵn sàng bật ở G2 — chỉ dựng khung, chưa cần pháp nhân Hàn |

## 5.5 Chỉ số của nhóm C

| Chỉ số | Mục tiêu |
|---|---|
| Trễ so với mốc ship | 0 ngày |
| Thời gian tải trang chính | < 2,5 giây trên 4G |
| Tỷ lệ hoàn tất đăng ký | > 65% |
| Tỷ lệ đặt hàng thành công | > 92% |
| Thời gian hoạt động | > 99,5% |

---

# 6. NHÓM D — CỘNG ĐỒNG & DOANH THU

Nhóm này có bốn mảng việc rất khác nhau. Tách rõ để không lẫn.

## 6.1 D1 — Cộng đồng và mạng lưới đại sứ

**Người chịu trách nhiệm:** quản lý cộng đồng. **Con số tuần: người theo dõi Zalo OA.**

| Nhịp | Việc | Mục tiêu |
|---|---|---|
| **1** | Mở nhóm Facebook, Zalo OA, 5 kênh mạng xã hội; viết nội quy nhóm; đi 10 trường đại học có khoa tiếng Hàn | **60 đại sứ trường** · 8k Zalo OA · nhóm FB 15k |
| **2** | Tuyển thêm đại sứ; mở mạng lưới đại sứ vùng tại Gyeonggi và Ansan; 3 sự kiện offline; chạy thử thách 30 ngày | **110 đại sứ trường + 20 đại sứ vùng** · 18k Zalo OA |
| **3** | Lập nhóm Zalo theo địa phương; ngày hội cộng đồng; chương trình ghi nhận đại sứ xuất sắc | **150 đại sứ trường + 40 đại sứ vùng** · 30k Zalo OA |

**Cơ chế trả cho đại sứ — không trả tiền, trả bằng địa vị và cơ hội:** chứng nhận, thư giới thiệu, tài khoản Pro, ưu tiên ghép gia sư, được lên kênh chính, hoa hồng Chợ. Với sinh viên tiếng Hàn, một dòng trong CV có giá trị hơn 500.000 đ.

**KPI kỷ luật:** tỷ lệ chuyển từ "đất thuê" (TikTok, Facebook, YouTube) sang "đất của mình" (Zalo OA, tài khoản nền tảng) phải **≥ 8%/tháng**. Người theo dõi tăng mà Zalo OA không tăng là tăng trưởng ảo.

## 6.2 D2 — Chợ Hàn – Việt

**Người chịu trách nhiệm:** vận hành Chợ. **Con số tuần: số người bán đã ký + số mã hàng đạt chuẩn.**

### Mô hình Pilot: chạy qua một đối tác có pháp nhân

Vì pháp nhân Việt Nam đã được đưa ra khỏi đường găng, Chợ trong G1 **không tự thu tiền**. Nhưng cũng không lùi về chế độ giới thiệu thuần — vì như thế mất cơ chế bảo đảm, mà bảo đảm chính là định vị của Chợ.

> **Đường thứ ba: chọn MỘT nhà nhập khẩu đã có pháp nhân đóng vai người bán chính thức của Pilot.**

| Bên | Làm gì |
|---|---|
| **KOVIA** | Mang lưu lượng · tuyển chọn hàng · đặt tiêu chí · làm nội dung · vận hành giao diện Chợ · chăm sóc khách |
| **Đối tác nhà nhập khẩu** | Thanh toán · hoá đơn · kho vận · nghĩa vụ thuế và tuân thủ · là người bảo đảm pháp lý cho đơn hàng |

Được ba thứ cùng lúc: **không cần pháp nhân để bắt đầu** · **cơ chế bảo đảm vẫn sống** vì đối tác là người bảo đảm · **có số liệu chuyển đổi thật**. Khi lập pháp nhân xong thì chuyển về, hàng và người bán đã sẵn.

Điều khoản cần có trong hợp đồng đối tác: KOVIA sở hữu dữ liệu khách hàng và đánh giá · quyền chuyển đơn sang pháp nhân của KOVIA khi sẵn sàng · không độc quyền vĩnh viễn · tỷ lệ chia doanh thu giảm dần theo quy mô.

### Việc theo nhịp

| Nhịp | Việc | Mục tiêu |
|---|---|---|
| **1** | Lập bản đồ 60 nhà nhập khẩu chính hãng; **đàm phán và chốt đối tác Pilot**; hoàn thiện bộ tiêu chí 3 tầng và danh mục cấm; soạn hợp đồng mẫu và chính sách đổi trả | **Ký được 1 đối tác Pilot** · bộ tiêu chí đã qua luật sư · 20 cuộc gặp người bán |
| **2** | Đưa hàng lên qua đối tác, chạy đơn đầu tiên; dựng quy trình khiếu nại; đối soát doanh thu hằng tuần | **30 nhà cung cấp · 400 mã hàng · đơn hàng đầu tiên** |
| **3** | Mở rộng; chọn nhóm đủ ngưỡng mời mở cửa hàng; **chuyển sang tự thu tiền nếu pháp nhân đã xong** | **50 nhà cung cấp · 25–40 cửa hàng · 500 đơn/tháng** |

**Ngưỡng được mời mở cửa hàng (chốt lại sau 3 tháng chạy Chợ):** ≥ 30 đơn hoàn tất · ≥ 60 triệu đồng doanh số · điểm tin cậy ≥ 4,5/5 · tỷ lệ khiếu nại < 2% · đã eKYC tầng T1 hoặc T2.

**Ngành hàng mở đầu — theo thứ tự rủi ro pháp lý từ thấp lên:** thời trang, phụ kiện, gia dụng, văn phòng phẩm, quà lưu niệm → đồ khô có công bố → **mỹ phẩm, chỉ với người bán tầng T1 có số tiếp nhận công bố**. Tuyệt đối không: thuốc, thực phẩm chức năng chưa công bố, thiết bị y tế, sữa công thức, sản phẩm cho trẻ dưới 36 tháng.

## 6.3 D3 — Doanh thu B2B

**Người chịu trách nhiệm: CEO.** Đây là dòng tiền sớm nhất và **không vi phạm nguyên tắc quảng cáo bằng 0** — nó bán bằng quan hệ, không bằng tiền quảng cáo.

| Nhịp | Việc | Mục tiêu |
|---|---|---|
| **1** | Lập danh sách 200 doanh nghiệp Hàn tại Việt Nam; tiếp cận KOCHAM, hiệp hội DN Hàn theo tỉnh, ngân hàng Hàn (Shinhan, Woori), công ty kế toán Hàn; soạn bộ tài liệu bán hàng tiếng Hàn | 30 cuộc gặp · bộ tài liệu xong |
| **2** | Chào gói **đào tạo văn hoá và ngôn ngữ** cho phòng nhân sự nhà máy Hàn; chào gói **Hạ cánh mềm 90 ngày** đầu tiên | **3–4 khách đào tạo · 1–2 khách landing service** |
| **3** | Nhân bản; xây bộ hồ sơ năng lực để bán tiếp | **6 khách đào tạo · 4–5 khách landing · ~100.000 USD doanh thu năm** |

**Vì sao gói đào tạo văn hoá là thứ dễ bán nhất:** không cần quy mô, không cần sản phẩm hoàn chỉnh, biên lợi nhuận rất cao, và nó giải một nỗi đau có thật — quản lý Hàn không hiểu vì sao công nhân Việt "vâng" nhưng không làm.

## 6.4 D4 — Đối tác thay quảng cáo

| Đối tác | Ta cho gì | Ta nhận gì |
|---|---|---|
| Khoa và CLB tiếng Hàn các trường | Nội dung miễn phí, workshop, học bổng nhỏ | Tiếp cận hàng nghìn sinh viên mỗi trường |
| Hội sinh viên Việt Nam tại Hàn và chi hội vùng | Hỗ trợ sự kiện, nội dung, tư vấn | Tiếp cận du học sinh — nhóm chất lượng cao |
| Trung tâm tiếng Hàn (du học, phái cử) | Công cụ học miễn phí cho học viên | Học viên vào hệ sinh thái; sau này thành nguồn gia sư |
| Người sáng tạo nội dung Hàn – Việt sẵn có | Chia sẻ dữ liệu, đồng sản xuất, hoa hồng Chợ | Khán giả có sẵn |
| Hiệp hội doanh nghiệp Hàn | Báo cáo thị trường lao động miễn phí | Đường vào khách B2B |
| Nhà nhập khẩu hàng Hàn chính hãng | Kênh bán mới, nội dung miễn phí | Nguồn hàng hợp pháp cho Chợ |

---

# 7. NHÓM E — VẬN HÀNH & TUÂN THỦ

Nhóm này đã được **đưa ra khỏi đường găng**: pháp nhân Việt Nam, xác thực Zalo OA doanh nghiệp và thông báo sàn thương mại điện tử đều lùi lại, không chặn khởi động Pilot.

Đổi lại, nhóm E phải làm hai việc khác: **chuẩn bị sẵn hồ sơ để bật nhanh khi cần**, và **canh ba mốc kích hoạt**.

**Con số báo cáo tuần: số ngày cần để hoàn tất pháp nhân nếu bấm nút hôm nay.** Con số này phải giảm dần, không được đứng yên.

## 7.1 Nguyên tắc: "làm sau" cần điều kiện kích hoạt, không phải một ngày tháng

Đây là chỗ dễ trôi nhất trong cả kế hoạch. Ba mốc dưới đây, **cái nào đến trước thì bật cái đó** — không chờ hết Pilot.

| Mốc kích hoạt | Phải bật gì | Thời gian cần |
|---|---|---|
| **Khách B2B đầu tiên đồng ý ký** | Pháp nhân Việt Nam — để xuất hoá đơn | 2–4 tuần |
| Pilot Chợ đạt **150 đơn/tháng** qua đối tác | Pháp nhân + thông báo sàn TMĐT | 4–8 tuần |
| Cần **Mini App đầy đủ hoặc ZNS** | Zalo OA xác thực doanh nghiệp | 1–2 tuần sau khi có pháp nhân |

**Khả năng cao mốc thứ nhất đến trước** — có thể ngay tháng 6. Doanh nghiệp Hàn không trả tiền mà không có hoá đơn. Nghĩa là trên thực tế pháp nhân sẽ cần khoảng **tháng 6 – tháng 8**, không phải "sau Pilot".

Hệ quả với Store Builder: nếu pháp nhân xong ở T8–T9 thì Chợ tự thu tiền từ T10, dữ liệu doanh số đủ ở T12, **Store Builder bản mời lùi từ T11 sang T12–T13**. Đây là cái giá của việc hoãn, và nó chấp nhận được — miễn là không để trôi quá T9.

## 7.2 Việc theo nhịp

| Nhịp | Việc | Ưu tiên |
|---|---|---|
| **1** | **Chuẩn bị sẵn hồ sơ pháp nhân** — chọn phương án (dùng pháp nhân sẵn có + bổ sung ngành nghề, hay lập mới), soạn xong hồ sơ, chưa nộp | ★★★ |
| **1** | Rà soát pháp lý mô hình Chợ: danh mục cấm, tiêu chí 3 tầng, hợp đồng đối tác Pilot | ★★★ |
| **1** | **Soạn hợp đồng đối tác nhà nhập khẩu** — điều khoản sở hữu dữ liệu và quyền chuyển đơn về sau | ★★★ |
| **1** | Bắt đầu tìm **cố vấn hoặc đối tác người Hàn** (chưa lập pháp nhân Hàn) | ★★ |
| **1** | **Đăng ký khoá API tại data.go.kr** cho TourAPI và dữ liệu mở Seoul — duyệt mất thời gian, làm sớm | ★★ |
| **2** | Rà điều khoản TourAPI (yêu cầu dùng như chức năng chính hoặc phụ của dịch vụ) và điều khoản YouTube | ★★ |
| **2** | **Canh mốc kích hoạt** — khách B2B đầu tiên hoặc 150 đơn/tháng; bấm nút thì nộp hồ sơ ngay | ★★★ |
| **2** | Chuẩn bị hồ sơ thông báo sàn TMĐT với Bộ Công Thương — soạn trước, nộp khi có pháp nhân | ★★ |
| **2** | Hồ sơ tuân thủ Nghị định 13/2023: đánh giá tác động xử lý dữ liệu, cơ chế đồng ý riêng biệt | ★★ |
| **2** | Thiết lập kế toán, hoá đơn, hợp đồng cộng tác viên | ★★ |
| **3** | Hoàn tất pháp nhân + OA doanh nghiệp + thông báo sàn TMĐT | ★★★ |
| **3** | **Khởi động hồ sơ pháp nhân Hàn Quốc từ tháng 8** — để kịp AlimTalk ở G2 | ★★★ |
| **3** | Rà soát bảo hiểm trách nhiệm và điều khoản sử dụng | ★★ |

## 7.3 Vì sao pháp nhân Hàn để tháng 8

Pilot gần như không phụ thuộc vào nó: KakaoTalk Channel dạng thông tin cá nhân mở được; website tiếng Hàn không cần; và **hợp đồng B2B vẫn ký bằng pháp nhân Việt** vì dịch vụ thực hiện tại Việt Nam.

Nhưng AlimTalk cần chạy từ đầu G2 (T12), và chuỗi *đăng ký kinh doanh Hàn → thẩm định Kakao Channel doanh nghiệp → cấp SenderKey → duyệt mẫu tin* mất **8–12 tuần**. Khởi động tháng 8 là vừa đủ.

---

# 8. ĐƯỜNG GĂNG VÀ PHỤ THUỘC CHÉO

## 8.1 Đường găng của G1

```
C: Web-App Frontend + Backend Portal đợt 1 + Website 3 ngôn ngữ   (T3–T5)
        ↓
A: Luồng sản xuất chạy qua Portal → đạt 40 mảnh/tuần              (T5–T6)
        ↓
D2: Chốt đối tác nhà nhập khẩu cho Pilot                          (T5)
      ← song song: D2 bộ tiêu chí đã qua luật sư (T4)
      ← song song: E soạn sẵn hồ sơ pháp nhân, chưa nộp (T4)
        ↓
C+D2: Chợ Pilot chạy đơn qua đối tác                              (T7–T8)
        ↓
E: MỐC KÍCH HOẠT — khách B2B đầu tiên hoặc 150 đơn/tháng
   → nộp hồ sơ pháp nhân + OA doanh nghiệp + thông báo sàn TMĐT   (T6–T9)
        ↓
C: Chợ tự thu tiền + Mini App đầy đủ + ZNS                        (T9–T10)
        ↓
D2: Tích luỹ 3 tháng dữ liệu doanh số                             (T10–T12)
        ↓
C: Store Builder bản mời                                          (T12–T13)
```

**Đường găng đã đổi chủ.** Mắt xích đầu không còn là pháp nhân mà là **nhóm C ship được Web-App và Portal đợt 1 trong ba tháng**. Nếu Portal trượt, nhóm A không đạt sản lượng, phễu không đủ rộng, và mọi thứ phía sau trượt theo.

**Hai nhánh chạy song song, không chặn nhau:**

- **Nhánh sản phẩm và nội dung** (C → A → D1) không chạm tới pháp lý, chạy hết tốc độ từ T3.
- **Nhánh thương mại** (D2 → E → C) chạy chậm hơn, được mở khoá bằng mốc kích hoạt chứ không bằng lịch.

**Cái giá phải trả:** Store Builder lùi từ T11 sang **T12–T13**. Chấp nhận được — miễn là pháp nhân không trôi quá T9. Nếu trôi quá T9, cả G1 hụt một cửa vượt.

## 8.2 Bảng phụ thuộc chéo

| Nhóm cần | Từ nhóm | Cái gì | Hạn chót |
|---|---|---|---|
| A | B | M2 Script + M4 Distribute chạy được | T4 — trễ thì sản lượng dừng ở 12–15 mảnh/tuần |
| A | D1 | Nhân vật thật cho mini-doc | T4 |
| A | D2 | Danh sách sản phẩm để gắn Shoppable Scene | T6 |
| C | E | Pháp nhân + OA doanh nghiệp — **chỉ cần khi bật Mini App và Chợ tự thu tiền** | T9 (không phải T4) |
| C | A | 50 kịch bản AI roleplay dạng dữ liệu | T7 |
| C | D2 | Bộ tiêu chí và quy trình để dựng công cụ thẩm định | T6 |
| D2 | E | Rà soát pháp lý danh mục hàng | T4 |
| D2 | E | Hợp đồng đối tác nhà nhập khẩu | T5 |
| C | D2 | Đối tác Pilot đã ký, biết luồng thanh toán để dựng đối soát | T6 |
| D2 | C | Công cụ thẩm định người bán | T7 |
| D3 | C | Website tiếng Hàn lên sóng | T5 |
| D3 | A | Bộ bài "Tiếng Việt công trường" | T9 |
| B | C | Kết nối dữ liệu để đo lường đầu-cuối | T8 |

---

# 9. LỊCH ĐẦU RA THEO THÁNG

| Tháng | Nhóm A | Nhóm B | Nhóm C | Nhóm D | Nhóm E |
|---|---|---|---|---|---|
| **T3** | Bible + backlog 400 tình huống; dựng bối cảnh | Chặng ② Kịch bản bản đầu | Khung Web-App + Portal + website | Mở 5 kênh; 10 trường | Chọn phương án pháp nhân; rà soát Chợ |
| **T4** | 60 Scene; 4 mini-doc | **② + ④ + ⑤ chạy được** | Web-App bản nội bộ; Portal bản nội bộ | 30 đại sứ; bản đồ 60 nhà nhập khẩu | **Soạn xong hồ sơ pháp nhân, chưa nộp**; tiêu chí Chợ qua luật sư |
| **T5** | 90 Scene; livestream thử | Hàng rào + nhật ký | **SHIP: Web-App + Portal đợt 1 + website 3 ngôn ngữ** | 60 đại sứ; 8k OA; **chốt đối tác Pilot** | Hợp đồng đối tác nhập khẩu |
| **T6** | 40 Scene; Shoppable đợt 1 | Chặng ③ Sản xuất | Chợ Pilot bản nội bộ; AI roleplay bản đầu | **Chào B2B; 20 cuộc gặp nhà cung cấp** | ⚡ **Mốc kích hoạt có thể đến — khách B2B đầu tiên** |
| **T7** | 40 Scene; 50 kịch bản roleplay | Chặng ⑥ Đo lường | Công cụ thẩm định + đối soát với đối tác | **30 nhà cung cấp, 400 mã hàng** | Nộp hồ sơ pháp nhân nếu đã kích hoạt |
| **T8** | 40 Scene; thử thách 30 ngày | Chặng ① Ý tưởng | **SHIP: Chợ Pilot + AI roleplay + Portal đợt 2** | Đơn hàng đầu tiên; 3 khách B2B | Thông báo sàn TMĐT; **khởi động pháp nhân Hàn** |
| **T9** | 45 Scene; công cụ cho người bán | Chặng ⑦ Tối ưu | Zalo Mini App đầy đủ; chuyển Chợ về tự thu tiền | 40 nhà cung cấp; 18k OA | Hoàn tất OA doanh nghiệp |
| **T10** | 45 Scene; 20 bài tiếng Hàn; **40 mục Đi lại & du lịch** | Mở Portal cho người bán | Tối ưu chuyển đổi; **mục Đi lại & du lịch (TourAPI + ODsay + Kakao Map)**; Store Builder bản nội bộ | 45 nhà cung cấp; khách landing | |
| **T11** | 40 Scene; video dài YouTube | Tối ưu chi phí API | Store Builder bản thử nghiệm nội bộ | **50 nhà cung cấp; 30k OA; 500 đơn/tháng** | Rà soát điều khoản |
| **T12–T13** | — | — | **SHIP: Store Builder bản mời** | 25–40 cửa hàng | |

---

# 10. NHỊP VẬN HÀNH VÀ BẢNG CHỈ SỐ

## 10.1 Ba nhịp họp, không hơn

| Nhịp | Thời lượng | Nội dung |
|---|---|---|
| **Họp tuần** | 45 phút | Mỗi nhóm báo **đúng một con số** và **một việc đang tắc**. Không báo cáo hoạt động, không trình bày slide |
| **Rà tháng** | 2 giờ | Bảng ROI nội dung → quyết định sản xuất tháng sau. Rà dòng tiền. Rà rào cản pháp lý |
| **Rà nhịp** | Nửa ngày, cuối T5 / T8 / T11 | Đối chiếu cửa vượt. Quyết định đi tiếp hay sửa |

## 10.2 Bảng chỉ số G1

| Nhóm | Chỉ số | T5 | T8 | T11 |
|---|---|---|---|---|
| **Thu hút** | Người theo dõi 5 nền tảng | 40.000 | 90.000 | **150.000** |
| | Lượt xem / tháng | 1,5 tr | 5 tr | **8–12 tr** |
| **Sở hữu** | Người theo dõi Zalo OA | 8.000 | 18.000 | **30.000** |
| | Thành viên nhóm Facebook | 15.000 | 32.000 | **50.000** |
| | Tài khoản đăng ký | 9.000 | 22.000 | **40.000** |
| | Tỷ lệ chuyển sang "đất của mình" | ≥ 8%/tháng | ≥ 8% | ≥ 8% |
| **Gắn kết** | Người học hoạt động tuần (WAU) | 900 | 2.600 | **5.000** |
| | Retention D30 | > 15% | > 19% | **> 22%** |
| | Scene hoàn thành / người / tuần | 2,5 | 3,4 | **> 4** |
| **Giao dịch** | Đơn hàng Chợ / tháng | — | 120 | **500** |
| | GMV / tháng | — | 110 tr đ | **400–600 tr đ** |
| | Buổi gia sư / tháng | — | 60 | **200** |
| | Cửa hàng riêng đang hoạt động | — | — | **25–40** |
| **Tin cậy** | Tỷ lệ khiếu nại đơn hàng | — | < 3% | **< 2%** |
| | Người bán được kiểm định | — | 30 | **50** |
| **Sản xuất** | Mảnh nội dung / tuần | 25 | 45 | **40–60** |
| | Chi phí / mảnh | 250k | 150k | **< 120k** |
| **Doanh thu** | Doanh thu / tháng | — | 90 tr đ | **250–400 tr đ** |

---

# 11. CỬA VƯỢT SANG G2

Không đủ thì **sửa G1, không mở rộng**. Đây là kỷ luật quan trọng nhất của cả dự án.

| # | Cửa | Ngưỡng | Vì sao |
|---|---|---|---|
| 1 | **Retention D30** | **> 20%** | Dưới ngưỡng này thì nội dung là giải trí, không phải nền tảng |
| 2 | **Tỷ lệ khiếu nại đơn hàng** | **< 3%** | Trên ngưỡng này thì mở rộng Chợ là nhân bản rủi ro |
| 3 | **Người vừa học vừa mua hàng** | **≥ 100 người** | Chỉ số quan trọng nhất — nó chứng minh hai trụ thật sự nuôi nhau, không phải hai sản phẩm dán cạnh nhau |
| 4 | **Chuyển sang "đất của mình"** | **≥ 8%/tháng** | Dưới ngưỡng này thì tăng trưởng phụ thuộc thuật toán, không phải tài sản của mình |
| 5 | **Cửa hàng riêng hoạt động** | **≥ 25** (chấp nhận trượt sang T12–T13) | Chứng minh cơ chế leo hạng có hiệu lực |
| 5b | **Pháp nhân và tuân thủ hoàn tất** | **Xong trước T9** | Trôi quá T9 thì Store Builder và toàn bộ G2 trượt theo |
| 6 | **Doanh thu B2B** | **≥ 4 khách đã trả tiền** | Chứng minh chiều Hàn → Việt trả tiền được cho chiều Việt → Hàn |

**Nếu cửa 3 không đạt nhưng các cửa khác đạt:** đó không phải thất bại, mà là tín hiệu rằng nội dung và thương mại đang chạy song song chứ chưa gắn vào nhau. Việc cần làm là dồn sức vào Shoppable Scene, không phải mở rộng.

---

# 12. CHECKLIST TUẦN ĐẦU TIÊN

| # | Việc | Ai | Xong khi |
|---|---|---|---|
| 1 | **Chốt phạm vi Portal đợt 1** — ba chặng ②④⑤, không hơn | Trưởng KT + Kỹ sư AI | Hết tuần 1 — đây là mắt xích đầu đường găng mới |
| 2 | Chốt bảng phân công năm nhóm, mỗi nhóm một người chịu trách nhiệm và một con số | CEO | Hết tuần 1 |
| 3 | Đặt lịch họp tuần cố định 45 phút, một khung giờ, không đổi | CEO | Hết tuần 1 |
| 4 | Mở Zalo OA, Facebook Page và Group, 5 kênh mạng xã hội; đăng ký tên miền | Cộng đồng | Hết tuần 1 |
| 5 | Bắt đầu bản đồ 400 tình huống và bible nội dung | Trưởng nội dung | Bản nháp hết tuần 2 |
| 6 | Dựng khung M2 Script và kho tri thức RAG | Kỹ sư AI | Bản chạy được hết tuần 3 |
| 7 | Khởi tạo kho mã, hạ tầng, phân tách dữ liệu theo vùng | Trưởng kỹ thuật | Hết tuần 2 |
| 8 | Đặt lịch gặp luật sư rà soát mô hình Chợ và hợp đồng đối tác | CEO | Trong tuần 1 |
| 9 | Lập danh sách 60 nhà nhập khẩu hàng Hàn chính hãng; **chọn 5 ứng viên đối tác Pilot** | Vận hành Chợ | Hết tuần 2 |
| 11 | **Chọn phương án pháp nhân và soạn sẵn hồ sơ** — chưa nộp, để bấm nút là nộp được | CEO | Hết tuần 3 |
| 12 | Dán ba mốc kích hoạt (7.1) lên bảng theo dõi, rà mỗi tuần | CEO | Hết tuần 1 |
| 10 | Bắt đầu tìm cố vấn hoặc đối tác người Hàn | CEO | Liên tục |

---

## GHI CHÚ

Tài liệu này chi tiết hoá **Giai đoạn 1** trong lộ trình 30 tháng của Đề án v2.4. Các con số là mục tiêu đặt ra, cần thay bằng số thật sau mỗi tháng vận hành.

**Cập nhật v1.2 (27/07/2026):** bổ sung công việc nối nguồn dữ liệu ngoài — Naver Search API và YouTube Data API vào nhóm B nhịp 2; TourAPI, ODsay LAB và Kakao Map cho mục "Đi lại & du lịch" vào nhóm C nhịp 3; bộ 40 nội dung hướng dẫn đi lại vào nhóm A nhịp 3; đăng ký khoá data.go.kr vào nhóm E nhịp 1. Ghi nhận hai kết quả khảo sát: **Naver Clip và thẻ T-money đều không có API**.

**Cập nhật v1.1 (27/07/2026):** pháp nhân Việt Nam, xác thực Zalo OA doanh nghiệp và thông báo sàn TMĐT đưa ra khỏi đường găng, thay bằng **cơ chế ba mốc kích hoạt** (7.1). Chợ trong G1 chạy **Pilot qua một đối tác nhà nhập khẩu có pháp nhân** (6.2) để giữ được cơ chế bảo đảm. Studio đổi thành **Backend Portal của Web-App** với luồng agentic bảy chặng, chia hai đợt ship (chương 4). Store Builder lùi sang T12–T13.

Ba nguyên tắc bao trùm toàn bộ G1:

1. **Không mở rộng trước khi đạt cửa vượt.** Mọi cám dỗ mở thêm mảng, thêm ngành hàng, thêm nền tảng đều hoãn tới G2.
2. **Không chi một đồng quảng cáo trả phí.** Tiền chỉ vào nền tảng, nội dung, tự động hoá và con người.
3. **Không đánh đổi niềm tin lấy tăng trưởng.** Một vụ lừa đảo ở tháng thứ sáu xoá sạch chín tháng xây dựng.
4. **"Làm sau" phải có mốc kích hoạt.** Việc hoãn không có điều kiện bật lại thì không phải hoãn — là bỏ.
