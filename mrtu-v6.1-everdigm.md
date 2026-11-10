# Instruction v6.1 — Xe tải gắn cẩu Hyundai Everdigm (con của v6.0)
Phiên bản: v6.1.3 · Cập nhật 09/09/2026
Nguồn đối chiếu live: /collections/xe-tai-gan-cau-hyundai-everdigm (bản 21/08/2026)

## 0.0. Vai của bản này
- Instruction con v6.1, dành riêng cụm xe tải gắn cẩu Hyundai Everdigm.
  Site Map nằm ngay trong bản này (mục 2–6).
- Kế thừa 100%: **v6.0** (quy tắc nội dung · luật khuyết dữ liệu mục 10.1 ·
  Quality Gate C1–C22 · Luật số đếm mở mục 15) và **v6.H** (trình bày H1–H10 ·
  định mức số chữ H8 · quy cách file đầu ra H9 · bảng kiểm P1–P22).
  Bản này KHÔNG đặt quy tắc viết/trình bày/CTA riêng.
- Xung đột ba tầng: **v6.0 thắng** ở intent, vai URL, registry, luật dữ liệu ·
  **v6.H thắng** ở màu, HTML, bố cục, số chữ · **v6.1 thắng** ở slug, mã model,
  sitemap, luật 4 con số của cụm.
- Tương thích tên mục cũ: bản này từng ghi "v6.0 mục 14B Design System" ⇒ đọc thành
  **v6.H mục H1–H10**; "v6.0 mục 25B Luật số đếm mở" ⇒ đọc thành **v6.0 mục 15**;
  "Quality Gate lỗi hình thức 11–14" ⇒ đọc thành **P1–P22**.
- Lệnh cập nhật: `~~6.1` cho sitemap/slug/model · `~~6.0` cho quy tắc chung ·
  `~~6.H` cho trình bày.
- Mọi lần sửa bản này: trả về **nguyên file** để dán đè, không sửa lẻ từng dòng.
- **Không có mẫu tham chiếu trình bày riêng cho cụm này.** Mẫu duy nhất là v6.H.
  Trang Collection hãng đang live (bản 21/08/2026) **không dùng làm mẫu**: nó còn số
  đếm chốt cứng và chưa qua luật khuyết dữ liệu 10.1 — xem checklist 3.1.

---

## 0. Phạm vi cụm (29/08/2026)

Không ghi số lượng ở đây. Nguồn duy nhất là các danh sách liệt kê bên dưới.
Muốn biết số lượng thì đếm dòng trong bảng tương ứng.

| Hạng mục | Nguồn duy nhất | Ghi chú |
| --- | --- | --- |
| Product | mục 4 | Cột Trạng thái phân biệt Live / 301 / Chưa viết |
| Model cẩu | mục 8 | Bảng 4 con số = danh sách model khoá; thêm bằng `~~6.1` |
| Pillar | `/pages/xe-tai-gan-cau` | Dùng chung toàn ngành cẩu, v6.1 không sở hữu |
| Collection tổng | `/collections/xe-tai-gan-cau` | Vai thương mại, xem mục 1 |
| Collection hãng | `/collections/xe-tai-gan-cau-hyundai-everdigm` | Cần cập nhật, xem 3.1 |
| Collection tải trọng | mục 3 | Dùng chung với v6.2 |
| Blog trục model | mục 5 | |
| Blog đề xuất | mục 6 | Chờ duyệt, chưa tạo |
| Cluster pháp lý | `/blogs/news/phap-ly-dang-kiem-xe-cau-2026` | Dùng chung, cụm này không sở hữu |

## 0.1. Luật số đếm mở (BẮT BUỘC)

Danh mục còn mở rộng, không chốt cứng số lượng ở bất kỳ đâu.

Số lượng không được khai ở bất kỳ đâu ngoài chính danh sách liệt kê. Không có cột
đếm, không có câu tổng kết số. Muốn biết bao nhiêu thì đếm dòng trong bảng.

CẤM đưa số đếm cấu hình/model vào: Title · Meta · Slug · H2 · câu mở bài · CTA.
Ví dụ sai: "14 cấu hình", "5 model cẩu HLC", "trọn bộ 14 dòng xe".

Dùng thay thế: "toàn bộ cấu hình đang phân phối" · "danh mục đầy đủ dòng HLC" ·
"các model cẩu HLC hiện có".

Lý do: mỗi lần thêm model phải sửa rải rác nhiều vị trí, sót một chỗ là số liệu
mâu thuẫn ngay trên cùng một trang — hỏng EEAT.

Khi thêm model mới, chỉ cập nhật đúng 3 nơi: mục 4 (nếu có Product) · mục 8 ·
bảng model của Collection hãng.

## 0.2. Biên giới file này ↔ thân bài (BẮT BUỘC — thêm ở v6.1.3)

File này là **tài liệu nội bộ**. Các nhãn `CẦN BỔ SUNG` · `CẦN TẠO` · `chưa có nguồn`
· checklist `[ ]` · cột Trạng thái là ngôn ngữ điều hành, **không phải câu để viết vào bài**.

Cách quy đổi khi viết bài (v6.0 mục 18):

| Trong file này | Trong thân bài | Khai ở đâu |
| --- | --- | --- |
| Một chỉ tiêu ghi `CẦN BỔ SUNG` | **Bỏ hẳn dòng đó** khỏi bảng thông số | 1 dòng bảng 16.3 |
| Cả khối thiếu dữ liệu | **Bỏ cả khối** + gỡ heading/câu dẫn/mục lục trỏ tới nó | 1 dòng bảng 16.3 |
| URL ghi `CẦN TẠO` | Vẫn link theo slug đã chốt, **không ghi chữ "CẦN TẠO"** | Trường "URL chưa live cần theo dõi" |
| Checklist `[ ]`, số hiệu mục, tên file | Không xuất hiện dưới mọi hình thức | — |

Chuỗi cấm trong thân bài (v6.0 mục 10.1 · P21): `Đang cập nhật` · `Chưa có dữ liệu` ·
`CẦN BỔ SUNG` · `CẦN TẠO` · `cần xác minh` · `chờ catalogue` · `theo Map` · `TBD` · `N/A`.
Placeholder chưa điền (P22): `[ ]` · `…` · `DD/MM/YYYY` · `TÊN MODEL`.

Product phải bỏ từ **3 khối bắt buộc trở lên** ⇒ dừng, xin dữ liệu trước khi viết
(v6.0 mục 8 · H8.8).

---

## 1. Tách vai Pillar ↔ Collection tổng (BẮT BUỘC — chống ăn thịt)

Giữ cả hai URL, khoá vai cứng:

| URL | Vai | Được nhắm | CẤM nhắm |
| --- | --- | --- | --- |
| `/pages/xe-tai-gan-cau` | Pillar — kiến thức nền | "xe tải gắn cẩu là gì", "phân loại", "cấu tạo", "xe cẩu tự hành" | "mua", "giá", "báo giá", "bán" |
| `/collections/xe-tai-gan-cau` | Collection — điều hướng mua | "mua xe tải gắn cẩu", "bán xe tải gắn cẩu", "xe tải gắn cẩu giá bao nhiêu" | "là gì", "phân loại", "cấu tạo" |

- Pillar 4.000–8.000 từ, không bảng thông số model, toả link xuống toàn cụm.
- Collection tổng 300–800 từ, ≥3 link tới Collection tải trọng.
- Title hai trang khác nhau rõ; 100 từ mở bài không trùng ý.

---

## 2. Cây URL

    /pages/xe-tai-gan-cau                              [Pillar · dùng chung]
    └─ /collections/xe-tai-gan-cau                     [Collection tổng · thương mại]
       ├─ /collections/xe-tai-gan-cau-hyundai-everdigm [Collection hãng]
       ├─ /collections/xe-tai-gan-cau-3-tan            [dùng chung v6.1+v6.2]
       ├─ /collections/xe-tai-gan-cau-5-tan
       ├─ /collections/xe-tai-gan-cau-7-8-tan
       ├─ /collections/xe-tai-gan-cau-10-13-tan
       └─ /collections/xe-tai-gan-cau-15-tan
    Blog trục model  → mục 5
    Cluster pháp lý  → /blogs/news/phap-ly-dang-kiem-xe-cau-2026 (KHÔNG sở hữu)
    Product          → mục 4

**Phân loại:** `/collections/xe-tai-gan-cau-hyundai-everdigm` là **Collection**, không
phải Cluster. Cluster chỉ nằm ở `/blogs/news/`.

---

## 3. Tầng Collection

| Loại | URL | Phạm vi | Trạng thái |
| --- | --- | --- | --- |
| Tổng | `/collections/xe-tai-gan-cau` | Đa hãng | ✅ Giữ — vai thương mại (mục 1) |
| Hãng | `/collections/xe-tai-gan-cau-hyundai-everdigm` | Everdigm | ⚠️ Live 21/08 — cần cập nhật, xem 3.1 |
| Tải trọng | `/collections/xe-tai-gan-cau-3-tan` | Đa hãng | ⏸️ Có sản phẩm nhưng chưa có mẫu — CHƯA VIẾT |
| Tải trọng | `/collections/xe-tai-gan-cau-5-tan` | Đa hãng | ✅ Chứa HLC-5014, HLC-7016 |
| Tải trọng | `/collections/xe-tai-gan-cau-7-8-tan` | Đa hãng | ✅ Chứa HLC-8016 |
| Tải trọng | `/collections/xe-tai-gan-cau-10-13-tan` | Đa hãng | ✅ Chứa HLC-12015 |
| Tải trọng | `/collections/xe-tai-gan-cau-15-tan` | Đa hãng | ✅ Chứa HLC-12015 ACE, HLC-15026 |

### 3.1. Việc cần sửa trên Collection hãng
- [ ] Thêm dòng **HLC-15026** vào bảng model cẩu (15 tấn · 6 đốt · nền Chenglong LZ1310)
- [ ] Bỏ mọi số đếm chốt cứng theo mục 0.1 (dạng "14 cấu hình", "5 model cẩu")
      → "toàn bộ cấu hình đang phân phối", "các model cẩu HLC"
- [ ] Bổ sung mức 15 tấn vào phần "Tiêu chí chọn nhanh": nêu rõ hai lựa chọn
      5 đốt và 6 đốt
- [ ] Đưa `chenglong-lz1310-gan-cau-hlc-15026-15-tan` vào đúng nhóm cấu hình,
      không để riêng ở mục "Xem thêm"
- [ ] Tách HLC-8026 và HLC-8027 thành hai dòng riêng (đang gộp một dòng,
      hai model khác đốt và khác tầm với)
- [ ] **Quét chuỗi cấm P21/P22** trên toàn trang: xoá mọi ô "Đang cập nhật",
      ô bảng trống, `—`/`N/A` thay số ⇒ bỏ dòng, khai ở 16.3 (thêm ở v6.1.3)

---

## 4. Tầng Product (danh sách mở)

| # | Slug (`/products/...`) | Xe nền · Cẩu | Tải | Trạng thái |
| --- | --- | --- | --- | --- |
| 1 | `hino-fm8jw7a-gan-cau-hlc8016-8-tan` | Hino FM8JW7A · HLC-8016 | 8T | ✅ Live — slug viết liền `hlc8016`, KHÔNG đổi |
| 2 | `isuzu-fvm-gan-cau-hlc-8016-8-tan` | Isuzu FVM · HLC-8016 | 8T | ✅ Live |
| 3 | `dongfeng-n270-gan-cau-hlc-8016-8-tan` | Dongfeng N270 · HLC-8016 | 8T | ✅ Live |
| 4 | `chenglong-lz1250-gan-cau-hlc-8016-8-tan` | Chenglong LZ1250 · HLC-8016 | 8T | ✅ Live — mới viết |
| 5 | `dongfeng-b180-gan-cau-hlc-7016-6-tan` | Dongfeng B180 · HLC-7016 | 6T | ✅ Live — nền xe duy nhất của HLC-7016 |
| 6 | `dongfeng-b180-gan-cau-hlc-5014-5-tan` | Dongfeng B180 · HLC-5014 | 5T | ✅ Live |
| 7 | `dongfeng-6x4-gan-cau-hlc-5014-5-tan` | Dongfeng 6×4 · HLC-5014 | 5T | ✅ Live — xem 4.3 |
| 8 | `chenglong-m3-gan-cau-hlc-5014-5-tan` | Chenglong M3 · HLC-5014 | 5T | ✅ Live |
| 9 | `chenglong-lz1250-gan-cau-hlc-5014-5-tan` | Chenglong LZ1250 · HLC-5014 | 5T | ✅ Live — đã sửa 5104 → 5014 |
| 10 | `xe-tai-jac-9-tan-gan-cau-hyundai-5-tan-hlc5014` | JAC 9 tấn · HLC-5014 | 5T | ✅ Live — slug lệch khung, ĐÃ SỬA, không đổi nữa |
| 11 | `dongfeng-kl340-gan-cau-hlc-12015-12-tan` | Dongfeng KL340 · HLC-12015 | 12T | ✅ Live — **đích 301 của #16** |
| 12 | `chenglong-lz1310-gan-cau-hlc-12015-12-tan` | Chenglong LZ1310 · HLC-12015 | 12T | ✅ Live — mới viết |
| 13 | `hyundai-hd320-gan-cau-hlc-12015-12-tan` | Hyundai HD320 · HLC-12015 | 12T | ✅ Live |
| 14 | `hyundai-hd320-gan-cau-hlc-12015-ace-15-tan` | Hyundai HD320 · HLC-12015 ACE | 15T · 5 đốt | ✅ Live — xem 4.4 |
| 15 | `chenglong-lz1310-gan-cau-hlc-15026-15-tan` | Chenglong LZ1310 · HLC-15026 | 15T · 6 đốt | ✅ Live — xem 4.4 · thông số CẦN BỔ SUNG |
| 16 | `dongfeng-l315-gan-cau-hlc-12015-12-tan` | Dongfeng L315 · HLC-12015 | 12T | ⛔ **301 → #11**. Không link, không viết lại |

### 4.1. Quy tắc link — bám sát Map
- Link theo **đúng slug trong Map**, không phụ thuộc trạng thái live.
- Slug đã live: **chốt, không bàn lại**. Không 301 vì lý do thẩm mỹ.
- Không bao giờ đặt internal link tới #16.
- Mọi Product live phải xuất hiện đủ trong Collection hãng.
- URL chưa live: vẫn link, **không ghi chú trạng thái trong bài** (v6.H mục H4.15).

### 4.2. Việc còn lại
- [ ] Bổ sung **chiều cao nâng móc** cho toàn bộ model — CẦN BỔ SUNG (mục 8, chỉ tiêu 4)
- [ ] Bổ sung **toàn bộ thông số HLC-15026** — CẦN BỔ SUNG
- [ ] Cập nhật Collection hãng theo checklist 3.1
- [ ] Khác biệt hoá cặp #13/#14, cặp #14/#15 và cặp #12/#15 theo luật 4.4
- [ ] Rà 301 của #16 trỏ đúng #11, gỡ internal link cũ
- [ ] Nạp Kho Purple Cow (mục 9.1) — hiện gần như trống
- [ ] **Rà 15 Product live + Collection hãng để xoá chuỗi cấm P21** (các bài viết
      trước 30/08/2026 còn ô "Đang cập nhật" trong bảng thông số): bỏ dòng, không
      thay bằng gạch ngang, khai vào 16.3 khi viết lại (thêm ở v6.1.3)

### 4.3. #7 Dongfeng 6×4 — CHỐT, không bàn lại
Xe nền Trung Quốc khó xác định chính xác tên. **Chấp nhận dùng nhãn "Dongfeng 6×4"**
nhất quán ở slug, Title, H2 và thân bài. Không suy đoán mã xe. Trong bài ghi rõ
cấu hình nhận diện được: 3 trục, dẫn động 6×4.

**Nguồn thông số:** hồ sơ đăng kiểm của chính xe đang có. Chỉ tiêu nào hồ sơ không
ghi ⇒ **bỏ hẳn dòng đó khỏi bảng thông số** và khai 1 dòng ở 16.3 (v6.0 mục 10.1).
Bù bằng nội dung định tính đã chắc chắn: cấu hình trục, dẫn động, đối tượng dùng,
giới hạn cần biết. (Luật cũ "thiếu ⇒ ghi *Đang cập nhật*" **đã xoá ở v6.1.3** — nó
trái v6.0 mục 10.1 và là lỗi P21.)

### 4.4. Các cặp Product nguy cơ ăn thịt cao nhất

**Cặp A — #13 vs #14: cùng nền HD320, cùng gốc cẩu HLC-12015**
ACE là **phiên bản nâng cấp** của HLC-12015: cùng 5 đốt, cùng tầm với 21,0 m, nhưng
sức nâng 15.000 kg @2,0 m thay vì 12.000 kg @3,0 m.
- #13 sở hữu `HD320 gắn cẩu 12 tấn` · #14 sở hữu `HD320 gắn cẩu 15 tấn`.
- #13 KHÔNG nhắc "15 tấn" ở Title/Meta. #14 KHÔNG nhắc "12 tấn" ở Title/Meta.
- #14 phải nêu "bản nâng cấp ACE" trong 100 từ đầu, giải thích rõ chênh lệch sức nâng.

**Cặp B — #14 vs #15: cùng mức 15 tấn, khác model cẩu và khác nền xe**
Mức 15 tấn nay có hai lựa chọn:

| | #14 HLC-12015 ACE | #15 HLC-15026 |
| --- | --- | --- |
| Số đốt | 5 đốt | 6 đốt |
| Nền xe | Hyundai HD320 | Chenglong LZ1310 |
| Góc kể | Bản nâng cấp từ dòng 12015 quen thuộc, chung phụ tùng | Dòng 15 tấn thiết kế riêng, nhiều đốt hơn ⇒ với xa hơn ở cùng mức tải |

- Cả hai **cùng được nhắm** cụm "gắn cẩu 15 tấn", nhưng **bắt buộc kèm tên nền xe**
  trong Title: "HD320 gắn cẩu 15 tấn…" vs "Chenglong LZ1310 gắn cẩu 15 tấn…".
- **CẤM** cả hai nhắm cụm "xe tải gắn cẩu 15 tấn" trần — cụm đó thuộc
  `/collections/xe-tai-gan-cau-15-tan`.
- Purple Cow hai bài phải khác góc hoàn toàn: #14 kể chuyện nâng cấp và tương thích
  phụ tùng; #15 kể chuyện số đốt và tầm với.
- **Lưu ý dữ liệu:** #15 chưa có tầm với ⇒ chưa chứng minh được góc "với xa hơn".
  Purple Cow không đủ 4 tiêu chí (v6.0 mục 9) ⇒ **bỏ khối**, không viết câu suy đoán.
  Chỉ nạp lại khi có catalogue (thêm ở v6.1.3).
- Khi có bài so sánh 5 đốt vs 6 đốt ⇒ đặt ở Blog, không nhét vào Product (v6.0 mục 4).

**Cặp C — #12 vs #15: cùng nền Chenglong LZ1310, khác cẩu**
Tách theo mức tải: #12 giữ "12 tấn", #15 giữ "15 tấn". Không bài nào được nhắc mức
tải của bài kia trong Title/Meta.

---

## 5. Tầng Blog trục model

| URL | Vai | Ghi chú |
| --- | --- | --- |
| `/blogs/news/cau-hyundai-everdigm-5-tan-hlc-5014` | Hub kỹ thuật HLC-5014 | So sánh các nền xe |
| `/blogs/news/cau-8-tan-7-dot-hyundai-everdigm-hlc-8027` | Hub kỹ thuật HLC-8027 | Đặt hàng, chưa Product nào dùng |
| `/blogs/news/xe-tai-gan-cau-co-khoan-hyundai-everdigm` | Cẩu có khoan | Đã gộp 7016 + 8026 về đây |
| `/blogs/news/bang-gia-xe-tai-gan-cau-hyundai-everdigm` | Trục giá theo hãng | |

**Không sở hữu:** `/blogs/news/phap-ly-dang-kiem-xe-cau-2026` — Cluster pháp lý dùng
chung mọi hãng. v6.1 chỉ link tới, không tạo bài pháp lý riêng cho Everdigm.

**Không nhắm lại** các cụm giá theo mức tải đã thuộc blog đa hãng của v6.2:
`gia-cau-12-tan`, `bang-gia-xe-cau-8-tan`, `gia-cau-15-tan-cu`.

---

## 6. Đề xuất viết thêm — chưa tạo, chờ duyệt

| Ưu tiên | Slug đề xuất | Vai | Giải vấn đề gì |
| --- | --- | --- | --- |
| 🔴 1 | `/blogs/news/cau-everdigm-15-tan-hlc-12015-ace-va-hlc-15026` | So sánh trong hãng | Mức 15 tấn có hai model, 5 đốt vs 6 đốt — chưa URL nào giải thích |
| 🔴 1 | `/blogs/news/cau-hyundai-everdigm-hlc-8016-8-tan` | Hub kỹ thuật | Nhiều Product dùng HLC-8016, chưa có trục kỹ thuật |
| 🔴 1 | `/blogs/news/cau-hyundai-everdigm-hlc-12015-12-tan` | Hub kỹ thuật | Nhiều Product dùng HLC-12015, gồm bản ACE |
| 🟡 2 | `/blogs/news/so-sanh-cau-soosan-va-hyundai-everdigm` | So sánh hai hãng | Truy vấn lớn, chưa URL nào đáp |
| 🟡 2 | `/blogs/news/cau-hyundai-everdigm-cua-nuoc-nao-co-tot-khong` | EEAT thương hiệu | Gỡ vai tìm hiểu hãng khỏi Collection |
| 🟢 3 | `/blogs/news/cau-hyundai-everdigm-hlc-7016` | Hub kỹ thuật | Ít nền xe dùng, ưu tiên thấp |

### 6.1. Duyệt từng bài
- [ ] E1 `cau-everdigm-15-tan-hlc-12015-ace-va-hlc-15026`
- [ ] E2 `cau-hyundai-everdigm-hlc-8016-8-tan`
- [ ] E3 `cau-hyundai-everdigm-hlc-12015-12-tan`
- [ ] E4 `so-sanh-cau-soosan-va-hyundai-everdigm`
- [ ] E5 `cau-hyundai-everdigm-cua-nuoc-nao-co-tot-khong`
- [ ] E6 `cau-hyundai-everdigm-hlc-7016`

**Điều kiện mở E1:** cần tầm với và chiều cao nâng móc của HLC-15026, vì trục bài là
so sánh 5 đốt vs 6 đốt. Chưa có hai số này ⇒ chưa viết E1, không viết bằng suy đoán.

---

## 7. Luật phân vai

| Tầng | Được nhắm | CẤM nhắm |
| --- | --- | --- |
| Pillar | "xe tải gắn cẩu là gì", "phân loại", "xe cẩu tự hành" | Từ mua/giá, tên hãng, mã model |
| Collection tổng | "mua/bán xe tải gắn cẩu" | "là gì", "phân loại", mã model |
| Collection hãng | "xe tải gắn cẩu Hyundai Everdigm", "cẩu Everdigm" | Mức tải cụ thể, mã model đơn lẻ |
| Collection tải trọng | "xe tải gắn cẩu X tấn" | Tên hãng, mã model |
| Blog hub model | "cẩu Everdigm {mã}", "cẩu Everdigm X tấn" | Tên xe nền cụ thể |
| Product | "{hãng} {mã xe} gắn cẩu {mã cẩu}" | "xe tải gắn cẩu X tấn" trần |

**Quy tắc khi nhiều model cùng một mức tải:** Product bắt buộc kèm tên nền xe trong
Title để phân biệt. Cụm mức tải trần luôn thuộc Collection tải trọng.

---

## 8. Luật 4 con số — dữ liệu đã khoá

Bảng này là **danh sách model khoá** của cụm. Thêm model mới chỉ bằng lệnh `~~6.1`
kèm số liệu có nguồn và ngày cập nhật.

### 8.1. Ba số cốt lõi — thiếu là chặn xuất bản
Mọi Product và Blog hub model **bắt buộc có đủ 3 số**: (1) sức nâng @tầm với gần ·
(2) tầm với tối đa (+ tải còn lại nếu nguồn có) · (3) số đốt.
Thiếu một trong ba ⇒ **chưa đủ điều kiện xuất bản**, xin dữ liệu trước khi viết.

### 8.2. Số thứ 4 — chiều cao nâng móc
Chỉ tiêu (4) chiều cao nâng móc: **hiện chưa có nguồn cho bất kỳ model nào**.
Xử lý theo v6.0 mục 10.1: **bỏ hẳn dòng "chiều cao nâng móc" khỏi bảng thông số** của
bài, khai 1 dòng ở 16.3, **không chặn xuất bản**, không ghi "Đang cập nhật".
Khi có catalogue ⇒ nạp vào bảng dưới bằng `~~6.1` rồi chèn lại dòng vào bảng thông số.

*(Sửa ở v6.1.3: luật cũ "thiếu một trong 4 con số ⇒ chưa đủ điều kiện xuất bản" khiến
toàn bộ model đều bị chặn trong khi 15 Product đã live — mâu thuẫn tự thân, nay tách
3 số cốt lõi và số thứ 4.)*

| Model cẩu | Sức nâng lớn nhất | Tầm với tối đa | Số đốt | Cao nâng móc | Trạng thái |
| --- | --- | --- | --- | --- | --- |
| HLC-5014 | 5.000 kg @ 2,5 m | 10,7 m — còn 990 kg | 4 đốt lục giác | CẦN BỔ SUNG | Đang bán |
| HLC-7016 | 6.000 kgf @ 2,4 m | 16,2 m | 6 đoạn lục giác | CẦN BỔ SUNG | Đang bán |
| HLC-8016 | 8.000 kgf @ 2,0 m | 19,8 m — còn 630 kgf | 6 đốt | CẦN BỔ SUNG | Đang bán |
| HLC-8026 | 8 tấn | CẦN BỔ SUNG | 6 đốt + khoan | CẦN BỔ SUNG | Đặt hàng — chưa xe demo tại kho |
| HLC-8027 | 8 tấn | 22,8 m — còn 400 kg | 7 đốt | CẦN BỔ SUNG | Đặt hàng — chưa xe demo tại kho |
| HLC-12015 | 12.000 kg @ 3,0 m | 20,98 m hồ sơ · 21,0 m catalogue | 5 đốt | CẦN BỔ SUNG | Đang bán |
| HLC-12015 ACE | 15.000 kg @ 2,0 m | 21,0 m | 5 đốt | CẦN BỔ SUNG | Đang bán |
| HLC-15026 | 15 tấn — CẦN BỔ SUNG tầm với gần | CẦN BỔ SUNG | 6 đốt | CẦN BỔ SUNG | Đang bán |

**Hai model chưa đủ 3 số cốt lõi ⇒ chưa viết bài trục model:** HLC-8026 (thiếu tầm với)
và HLC-15026 (thiếu tầm với, thiếu tầm với gần). Product #15 đã live thì viết lại theo
đúng dữ liệu có thật, bỏ các dòng thiếu, không suy diễn.

**Nguồn:** giấy chứng nhận kiểu loại + catalogue Hyundai Everdigm bản Việt Nam.
**Hai nguồn lệch nhau ⇒ ưu tiên hồ sơ đăng kiểm**, ghi rõ cả hai như cách HLC-12015
đang làm (20,98 m hồ sơ · 21,0 m catalogue). Cách ghi song nguồn này **được phép trong
thân bài** vì cả hai số đều thật — nó khác hoàn toàn với ghi chú thiếu dữ liệu.

---

## 9. Registry từ khoá

| Từ khoá | Intent | Loại trang | URL sở hữu |
| --- | --- | --- | --- |
| xe tải gắn cẩu là gì / phân loại | Thông tin | Pillar | `/pages/xe-tai-gan-cau` |
| mua / bán xe tải gắn cẩu | Thương mại | Collection | `/collections/xe-tai-gan-cau` |
| xe tải gắn cẩu Hyundai Everdigm | Thương mại | Collection hãng | `/collections/xe-tai-gan-cau-hyundai-everdigm` |
| xe tải gắn cẩu 3 / 5 / 7-8 / 10-13 / 15 tấn | Thương mại | Collection tải trọng | Các URL ở mục 3 |
| giá xe tải gắn cẩu Everdigm | Giá | Blog | `/blogs/news/bang-gia-xe-tai-gan-cau-hyundai-everdigm` |
| cẩu Everdigm HLC-5014 | Kỹ thuật | Blog | `/blogs/news/cau-hyundai-everdigm-5-tan-hlc-5014` |
| cẩu Everdigm HLC-8027 7 đốt | Kỹ thuật | Blog | `/blogs/news/cau-8-tan-7-dot-hyundai-everdigm-hlc-8027` |
| xe tải gắn cẩu có khoan | Kỹ thuật | Blog | `/blogs/news/xe-tai-gan-cau-co-khoan-hyundai-everdigm` |
| cẩu Everdigm 15 tấn 5 đốt vs 6 đốt | So sánh | Blog | CẦN TẠO — E1 |
| đăng kiểm xe cẩu | Pháp lý | Cluster | `/blogs/news/phap-ly-dang-kiem-xe-cau-2026` (không sở hữu) |
| {hãng} {mã xe} gắn cẩu {mã cẩu} | Giao dịch | Product | Các URL live ở mục 4 |

⚠️ Volume và vị trí GSC: **CẦN BỔ SUNG** — chưa có dữ liệu, không suy đoán.
Nhãn `CẦN TẠO` ở cột URL là ngôn ngữ nội bộ; trong bài chỉ đặt link theo slug đã chốt
(mục 0.2 · H4.15).

### 9.1. Kho Purple Cow
| Model/URL | Điểm đáng kể lại | Bằng chứng | Đối thủ có nói chưa |
| --- | --- | --- | --- |
| Collection hãng | Cùng một hãng cẩu, nhiều nền xe đã hoàn thiện hồ sơ kiểu loại — đổi nền xe mà giữ nguyên model cẩu đã quen vận hành và quen phụ tùng | Trang Collection live 21/08/2026 | Chưa |
| #14 HD320 · ACE | Nâng lên 15 tấn nhưng giữ nguyên khung 5 đốt của dòng 12015 ⇒ dùng chung phụ tùng và thói quen vận hành | CẦN BỔ SUNG catalogue | Chưa |
| #15 LZ1310 · HLC-15026 | 6 đốt ở mức 15 tấn — thêm một đốt so với bản ACE | CẦN BỔ SUNG thông số tầm với để chứng minh | Chưa |
| (các Product khác — trống, nạp dần bằng `/p!`) | | | |

**Luật dùng kho này:** dòng nào cột Bằng chứng còn `CẦN BỔ SUNG` ⇒ Purple Cow **chưa
đủ 4 tiêu chí** (v6.0 mục 9) ⇒ **bỏ khối tím khỏi bài**, khai ở 16.3. Không viết tuyên
bố khác biệt dựa trên số chưa có nguồn. Hiện chỉ dòng Collection hãng đủ điều kiện dùng.

---

## 10. Nguyên tắc chốt
- Slug đã live và các 301 (22/08/2026): **chốt, không bàn lại**.
- Product live vẫn sửa được theo checklist 4.2; Product chưa live vẫn link theo slug
  trong Map, cập nhật GSC sau khi xuất bản.
- Danh sách ở mục 3, 4, 5, 6, 8: mở, thêm dòng bằng lệnh `~~6.1` kèm ngày.
- Không khai số lượng ngoài bảng — xem mục 0 và 0.1.
- Không mang ngôn ngữ nội bộ của file này vào thân bài — xem mục 0.2.

## 11. Nhật ký
- **09/09/2026 (v6.1.3)** — Đồng bộ với v6.0.10 (luật khuyết dữ liệu 10.1) và v6.H.3
  (P21/P22). **Mục 4.3:** xoá câu `Thông số lấy từ hồ sơ đăng kiểm, thiếu ⇒ "Đang cập
  nhật"` — luật cũ trái v6.0 mục 10.1 và là lỗi chặn xuất bản P21; nay thiếu chỉ tiêu
  ⇒ bỏ dòng + khai 16.3 + bù nội dung định tính. **Mục 8:** tách thành 8.1 (ba số cốt
  lõi, thiếu là chặn xuất bản) và 8.2 (chiều cao nâng móc — chưa có nguồn cho model
  nào ⇒ bỏ dòng khỏi bảng, không chặn); gỡ mâu thuẫn luật cũ "thiếu 1 trong 4 số ⇒
  chặn" trong khi 15 Product đã live; thêm dòng chốt HLC-8026 và HLC-15026 chưa đủ 3
  số cốt lõi nên chưa viết bài trục model; ghi rõ cách ghi song nguồn 20,98 m/21,0 m là
  hợp lệ, khác ghi chú thiếu dữ liệu. **Mục 0.0:** sửa tham chiếu chết "v6.0 mục 14B
  Design System" → v6.H H1–H10 và "mục 25B" → v6.0 mục 15; thêm luật xung đột ba tầng
  và bảng tương thích tên mục cũ; **xoá dòng "Mẫu tham chiếu trình bày: chính trang
  Collection hãng đang live"** vì trang đó chưa qua 10.1 và còn số đếm cứng, dùng làm
  mẫu là trái H11. **Mục 0.2 mới:** bảng quy đổi ngôn ngữ nội bộ (`CẦN BỔ SUNG`,
  `CẦN TẠO`, checklist `[ ]`) sang cách xử lý trong thân bài + danh sách chuỗi cấm
  P21/P22 + ngưỡng dừng 3 khối. **Cập nhật chéo:** 3.1 thêm việc quét chuỗi cấm trên
  Collection hãng · 4.1 thêm luật URL chưa live không ghi chú trạng thái · 4.2 thêm
  việc rà 15 Product live để xoá ô "Đang cập nhật" · 4.4 cặp B thêm luật bỏ Purple Cow
  của #15 khi chưa có tầm với · 6.1 thêm điều kiện mở E1 · 9 ghi rõ `CẦN TẠO` là nhãn
  nội bộ · 9.1 thêm luật bỏ khối tím khi cột Bằng chứng còn trống · 10 thêm dòng biên
  giới file/bài. Ảnh hưởng file khác: **không đổi** `Haravan.md`, `00-LOAD-mrtu.md`;
  `mrtu-v6.2-soosan.md` cần soát cùng lỗi bằng `~~6.2` (mục 0.0 còn trỏ "mục 14B/25B",
  cần kiểm câu về thiếu dữ liệu); `mrtu-v6.0-core.md` còn ghi `P1–P20`, sửa bằng `~~6.0`.
- **29/08/2026 (v6.1.2)** — Bỏ hẳn mục 0 "Trạng thái tổng quan" kiểu bảng đếm
  (15 · 1 · 6 · 2 · 5 · 4 · 1); thay bằng **mục 0 Phạm vi cụm** chỉ trỏ nguồn duy nhất,
  không có cột số lượng. Chuyển thông tin "đang bán / đặt hàng" của model vào cột
  Trạng thái ở mục 8 để không mất dữ liệu. Siết mục 0.1: cấm khai số lượng ở mọi nơi
  ngoài danh sách liệt kê; sửa "cập nhật đúng 4 nơi" → 3 nơi (mục 4 · mục 8 ·
  Collection hãng). Bọc backtick toàn bộ lệnh `~~6.0`/`~~6.1` để Markdown không render
  gạch ngang. Bỏ số đếm Product trong cột lý do ở mục 6. Thêm mục 10 Nguyên tắc chốt;
  Nhật ký dời thành mục 11.
- **29/08/2026 (v6.1.1)** — Chốt HLC-15026 là **model chính thức** (15 tấn · 6 đốt),
  không phải hàng đặt. Thêm **mục 0.1 Luật số đếm mở**: cấm chốt số lượng cấu hình
  trong Title/Meta/slug/H2/mở bài. Thêm **luật cặp B** (mục 4.4): mức 15 tấn có hai
  model, Product bắt buộc kèm tên nền xe trong Title. Thêm checklist 3.1 cập nhật
  Collection hãng. Thêm đề xuất bài E1 so sánh 5 đốt vs 6 đốt. Tách HLC-8026 và
  HLC-8027 thành hai dòng ở mục 8.
- **29/08/2026 (v6.1.0)** — Lập v6.1 chuẩn theo khung v6.2. Chốt giữ
  `/collections/xe-tai-gan-cau` vai thương mại, tách vai cứng với Pillar (mục 1).
  Xác nhận 301 L315 → KL340. Đổi nhãn Collection hãng từ "Cluster mẹ" thành Collection.
  Ghi rõ Cluster pháp lý dùng chung. Chốt #7 giữ nhãn "Dongfeng 6×4". Chốt #14 ACE là
  bản nâng cấp lên 15 tấn. Nạp bảng 4 con số từ trang live. Collection 3 tấn: có sản
  phẩm, chưa có mẫu ⇒ chưa viết.
