# KOVIA · HANGIL 한길 — Bộ nhận diện v2.0 / 브랜드 아이덴티티 v2.0

Phương án **Con dấu (도장)** · 27.07.2026

## Nội dung bộ file · 파일 구성

```
KOVIA Brand Book (VI-KO).dc.html   Sổ tay nhận diện song ngữ VI–KO (in ra PDF trực tiếp)
assets/svg/                        30 file vector — nguồn chính, dùng cho mọi cỡ
assets/png/                        47 file raster — dùng ngay cho digital & mạng xã hội
assets/export-sheet.html           Bản dựng để xuất lại các PNG có chữ (mở rồi chụp lại)
```

## SVG · 벡터

| File | Dùng ở đâu |
|---|---|
| `kovia-mark-primary` | Biểu tượng chính (A) |
| `kovia-mark-inverse` | Đảo màu, nền tối (B) |
| `kovia-mark-mono` | Một màu: dập nổi, thêu, khắc (C) |
| `kovia-mark-bare`, `-bare-inverse` | Không khung (D) — khi đã có khuôn bao ngoài |
| `kovia-mark-24`, `kovia-mark-16` | Bản rút gọn cho cỡ nhỏ |
| `favicon` | = mark-16 |
| `kovia-lockup-horizontal`, `-inverse`, `-vertical` | Khoá chữ |
| `hangil-mark`, `-mark-inverse`, `hangil-lockup`, `hangil-avatar` | Tầng cộng đồng |
| `badge-verified-vi`, `-ko`, `-mark` | Nhãn kiểm định |
| `sori-full`, `-dark`, `sori-head`, `-head-dark` | Nhân vật SORI |
| `zalo-oa-avatar`, `kakao-channel-avatar`, `app-icon` | Nền tảng |
| `og-image`, `endcard-9x16`, `-1x1`, `-16x9` | Mạng xã hội, video |
| `pattern-tile` | Hoạ tiết nền, lặp 32×32 |

## PNG · 래스터

Biểu tượng 64 → 1024 px · favicon 16/24/32/48 · apple-touch-icon 180 · app-icon 512/1024 ·
avatar 500×500 · og-image 1200×630 · endcard 1080×1920 / 1080×1080 / 1920×1080 ·
khoá chữ @2x nền trong · badge @2x · SORI 512/1024 nền trong · danh thiếp 90×54 mm @300 dpi.

## Lưu ý bắt buộc · 필수 사항

1. **SVG có khoá chữ dùng chữ sống.** Trước khi gửi nhà in: chuyển chữ thành đường (outline), xuất EPS/PDF CMYK. Bản PNG kèm theo đã render đúng bộ chữ.
2. **Bộ chữ:** Archivo (khoá chữ, nhãn, số) · Be Vietnam Pro (thân bài Việt) · Noto Sans KR (tiếng Hàn) · JetBrains Mono (số liệu).
3. **Màu in:** #142B5F ≈ Pantone 289 C · #BA7517 ≈ Pantone 145 C. Bắt buộc in thử.
4. **Đã có khuôn bao ngoài → dùng biến thể D.** Không lồng khung vào khung.
5. Kiểm tra mọi thay đổi ở **40 px và 16 px** trước khi duyệt.

## Xuất PDF · PDF 내보내기

Mở `KOVIA Brand Book (VI-KO).dc.html`, dùng lệnh Export → PDF (khổ A4). Tài liệu đã tự lo lề, đầu trang, chân trang và điểm ngắt trang.
