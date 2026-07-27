# KOVIA · HANGIL 한길 — Nền tảng hành lang Việt – Hàn

Bộ tài liệu và bản demo của **KOVIA** — hạ tầng số của hành lang Việt – Hàn: nơi một người Việt xây dựng năng lực và uy tín để sang Hàn, và một người Hàn tìm được người, đất, hàng, giấy tờ để vào Việt Nam — trên cùng một lớp danh tính.

> Repo này để **đối tác và đội ngũ cùng nghiên cứu và góp ý**. Số liệu trong tài liệu là ước tính, không phải cam kết.

## Bắt đầu ở đâu

**→ [Trang tổng hợp (index.html)](index.html)** — bản giới thiệu khái quát, có đường dẫn tới tất cả những thứ bên dưới.

## Hai bản demo

| Demo | Dành cho | File |
|---|---|---|
| **KOVIA APP** | Người dùng cuối — Khám phá · Học · Chợ · Tôi | [`kovia-app-prototype.html`](kovia-app-prototype.html) |
| **KOVIA Management Portal** | Vận hành — luồng sản xuất nội dung AI, phê duyệt, quản trị | [`kovia-admin-prototype.html`](kovia-admin-prototype.html) |

Cả hai là prototype giao diện: dữ liệu minh hoạ, chưa nối backend thật.

## Tài liệu

| Tài liệu | Nội dung | File |
|---|---|---|
| **KOVIA Branding** | Sổ tay nhận diện song ngữ VI–KO · logo, màu, chữ, SORI, file xuất | [`Branding/`](Branding/) · [HTML](Branding/KOVIA%20Brand%20Book%20(VI-KO).html) · [PDF](Branding/KOVIA%20Brand%20Book%20(VI-KO).pdf) |
| **KOVIA Tổng quan** | Đề án v2.5 — 17 chương: chiến lược, thị trường, kiến trúc sản phẩm, BETA, Portal, Chợ, kỹ thuật, lộ trình 30 tháng, tài chính, pháp lý | [HTML](kovia-hangil-v2.html) · [Markdown](kovia-hangil-v2.md) |
| **Chi tiết Phase 1** | Kế hoạch thực thi BETA 9 tháng: 5 nhóm việc, 3 nhịp, đường găng, lịch đầu ra, bảng chỉ số | [HTML](kovia-g1-chi-tiet.html) · [Markdown](kovia-g1-chi-tiet.md) |
| Nhận diện v2.1 (bản rút gọn) | Bản trình bày nhanh phương án "Con dấu" | [`kovia-hangil-nhan-dien.html`](kovia-hangil-nhan-dien.html) |

## Tóm tắt một trang

**Ba luận điểm.** ① Không bán dịch vụ — bán niềm tin có thể kiểm chứng. ② Bất đối xứng hai chiều: miễn phí chiều Việt → Hàn để xây mật độ và dữ liệu, bán đắt cho chiều Hàn → Việt. ③ Vòng tròn khép kín — người hồi hương là tài sản bị bỏ quên.

**Kiến trúc sản phẩm.** P1 Learn · P2 Culture · P3 Market — bật trong BETA. P4 Store — cuối BETA. P5 Passport · P6 Rights · P7 Career · P8 Business · P9 Return — giai đoạn sau.

**BETA 9 tháng, quảng cáo 0 đồng.** Mục tiêu tháng thứ 9: 150.000 người theo dõi · 30.000 Zalo OA · 5.000 WAU · D30 > 22% · 500 đơn Chợ/tháng · 25–40 cửa hàng riêng.

**Tài chính 12 tháng đầu.** Ngân sách ~234k USD · doanh thu dự kiến ~138k USD · đốt tiền ròng ~96k USD · 0 USD quảng cáo. Nhu cầu vốn khuyến nghị 300–350k USD cho 18 tháng.

**North Star.** *Verified Successful Connections* — chỉ tính khi có đủ 3 dấu hiệu độc lập: giao dịch qua nền tảng có bản ghi, xác nhận hai chiều, và một dấu vết bên ngoài.

## Chạy tại máy

Toàn bộ là HTML tĩnh, mở trực tiếp bằng trình duyệt là được. Nếu muốn chạy qua máy chủ cục bộ:

```bash
python3 -m http.server 8000
```

Rồi mở `http://localhost:8000`.

## Bảng màu thương hiệu

| Vai trò | Màu | Mã |
|---|---|---|
| Chủ đạo | Xanh đêm | `#142B5F` |
| Nhấn ấm | Vàng lúa | `#BA7517` |
| AI / tương tác | Bạc hà | `#35C6A5` |
| Nền | Giấy | `#F1EFE8` |
| Chữ | Mực | `#2C2C2A` |

---

Đề án v2.5 · Bộ nhận diện v2.0 · 27.07.2026
