# Instruction v6.2 — Xe tải cẩu Soosan (bản con của v6.0) — Site Map / Revision Baseline
Phiên bản: v6.2.3 · Cập nhật 09/09/2026
Nguồn đối chiếu: sitemap chốt 22/08/2026 · bổ sung 26/08/2026

> **Bản chốt sitemap 22/08/2026.** Slug và 301 đã chốt — không bàn lại. Phạm vi cụm và nguồn dữ liệu xem mục 0.

## 0.0. Vai của bản này

- Đây là **Instruction con v6.2**, dành riêng cho cụm **xe tải cẩu Soosan**, và **Site Map nằm ngay trong bản này** (mục 3, 4, 5).
- Kế thừa 100% **`mrtu-v6.0-core.md` (v6.0.10)** — tầng nội dung, và **`Haravan.md` (v6.H)** — tầng trình bày.
- Bản này **không** đặt quy tắc viết, trình bày hay CTA riêng. Chỉ giữ: sitemap, slug, mã model, registry, luật phân vai, luật số cốt lõi. Mọi thứ về màu · HTML · CTA · bảng · khối chốt · số chữ · quy cách file đầu ra: **theo v6.H mục H1–H10**.
- Xung đột: trình bày → v6.H thắng · intent/vai URL/registry/dữ liệu/luật khuyết dữ liệu → v6.0 thắng · slug/mã model/sitemap → bản này thắng.
- Không tồn tại bản Instruction Soosan nào khác. Bản trùng lặp trước đây đã gộp vào đây và xoá.
- Lệnh cập nhật: `~~6.2` cho sitemap/slug/model · `~~6.0` cho quy tắc nội dung · `~~6.H` cho trình bày.
- Mọi lần sửa bản này: trả về **nguyên file** để dán đè, không sửa lẻ từng dòng (v6.0 mục 19).

### 0.0.1. Luật khuyết dữ liệu — bắt buộc đọc trước khi viết bài cụm này

Bản con **được phép** ghi "CẦN BỔ SUNG" / "CẦN TẠO" trong chính file này (đây là sổ theo dõi). Nhưng các chuỗi đó **không bao giờ được chảy vào bài viết**.

| Trong file này ghi | Khi viết bài thì làm gì |
| --- | --- |
| Ô "CẦN BỔ SUNG" trong bảng mục 8.1 | Bỏ DÒNG chỉ tiêu đó khỏi bảng thông số + 1 dòng ở mục 16.3 |
| Thiếu quá nửa chỉ tiêu của một bảng/khối | Bỏ CẢ KHỐI + gỡ heading, câu dẫn, dòng mục lục, link trỏ tới nó |
| "CẦN TẠO" ở registry mục 9 / đề xuất mục 6 | Trong bài vẫn đặt link theo slug đã chốt, **không ghi chú gì cạnh link**; trạng thái URL khai ở 16.3 |
| Kho Purple Cow mục 11 còn trống | Lấy Purple Cow từ nguồn dịch vụ; vẫn không đủ 4 tiêu chí → bỏ khối, khai 16.3 |

Cấm tuyệt đối trong thân bài: "Đang cập nhật" · "CẦN BỔ SUNG" · "CẦN TẠO" · "cần xác minh" · "chờ catalog" · "theo Map" · "N/A" · `[ ]` · ô bảng trống. Chi tiết: **v6.0 mục 10.1**, cổng quét ở v6.0 mục 13, mã lỗi C21/C22 và P1–P22 (v6.H H10).

---

## 0. Phạm vi cụm

Không ghi số lượng ở đây. Nguồn duy nhất là chính các danh sách bên dưới. Muốn biết bao nhiêu thì đếm dòng trong bảng.

| Hạng mục | Nguồn duy nhất | Ghi chú |
| --- | --- | --- |
| Product | mục 4 | Cột Trạng thái phân biệt Live / Chưa viết |
| Model cẩu | mục 2 | Danh sách khoá, thêm bằng lệnh `~~6.2` |
| Pillar | `/pages/xe-tai-gan-cau` | Dùng chung toàn ngành cẩu |
| Collection hãng | `/collections/cau-soosan` | |
| Collection tải trọng | mục 3 | Dùng chung đa hãng |
| Blog | mục 5 | |
| Blog trục model Soosan | mục 6 | Chưa có bài nào — khoảng trống lớn nhất |
| Cluster pháp lý | `/blogs/news/phap-ly-dang-kiem-xe-cau-2026` | Dùng chung, cụm này không sở hữu |

---

## 0.1. Luật số đếm mở (áp theo v6.0 mục 15)

- Danh sách Product · Blog · Collection của cụm này là **danh sách mở**, sẽ còn tăng.
- **Số lượng không được khai ở bất kỳ đâu ngoài chính danh sách liệt kê.** Không cột đếm, không câu tổng kết số, kể cả trong bảng nội bộ của file này.
- **Cấm** số đếm model/cấu hình trong Title · Meta · Slug · H2 · 100 từ mở bài · CTA.
- Câu đúng: "dải cấu hình từ 3 đến 15 tấn", "nhiều lựa chọn xe nền". Câu sai: "14 cấu hình Soosan", "trọn bộ 15 mẫu".
- Lý do: hai chỗ cùng khai một con số thì sớm muộn lệch nhau — đã xảy ra thật với con số 13/14 trong chính file này.

---

## 1. Quy ước slug đã chốt

`/products/{chassis}-gan-cau-{model}-{X}-tan`

- Chữ thường
- Không chèn chữ `soosan`
- Mức tải có gạch nối
- Bắt buộc đủ cụm `-gan-cau-`
- Toàn bộ slug trong Map này đã đúng khung ⇒ **đóng phần slug, không đổi nữa**
- Ngoại lệ đã live: `xe-tai-jac-n900-gan-cau-soosan-scs334` (#16) lệch khung nhưng đang live và có thứ hạng ⇒ **giữ nguyên, không đổi**. Không lấy làm mẫu cho slug mới.

---

## 2. Mã model đã chốt

Khoá, không bàn lại: **SCS334 · SCS524 · SCS525 · SCS746L · SCS867LS · SCS1015LS · SCS1215LS · SCS1516S**

Model mới chỉ được thêm bằng lệnh `~~6.2`, kèm đủ 3 số cốt lõi ở mục 8.

---

## 3. Tầng trên — đã có, không tạo mới

| Tầng | URL | Vai | Trạng thái |
| --- | --- | --- | --- |
| Pillar | `/pages/xe-tai-gan-cau` | Tổng quan toàn ngành, không nhắm hãng | ✅ Giữ |
| Collection hãng | `/collections/cau-soosan` | Danh mục toàn cụm Soosan | ✅ Chốt 19/08 · Nội dung viết lại 22/08 |
| Collection tải trọng | `/collections/xe-tai-gan-cau-3-tan` | Đa hãng theo mức tải | ✅ Giữ |
| Collection tải trọng | `/collections/xe-tai-gan-cau-5-tan` | Đa hãng | ✅ Giữ |
| Collection tải trọng | `/collections/xe-tai-gan-cau-7-8-tan` | Đa hãng — giữ từ khoá "xe tải gắn cẩu 8 tấn" | ✅ Giữ |
| Collection tải trọng | `/collections/xe-tai-gan-cau-10-13-tan` | Đa hãng | ✅ Giữ |
| Collection tải trọng | `/collections/xe-tai-gan-cau-15-tan` | Đa hãng | ✅ Giữ |
| Cluster pháp lý | `/blogs/news/phap-ly-dang-kiem-xe-cau-2026` | Dùng chung mọi hãng | ✅ Giữ — không tạo bài pháp lý riêng cho Soosan |

---

## 4. Tầng Product (danh sách mở)

| # | Slug (`/products/...`) | Xe nền · Cẩu | Trạng thái |
| --- | --- | --- | --- |
| 1 | `chenglong-m3-gan-cau-scs525-5-tan` | Chenglong M3 · SCS525 | ✅ Live — cần spec xe + cẩu |
| 2 | `hino-fl8jw-gan-cau-scs746l-8-tan` | Hino FL8JW 6×2 · SCS746L | ✅ Live — cần spec xe |
| 3 | `hino-fm8jw8a-gan-cau-scs746l-8-tan` | Hino FM8JW8A 6×4 · SCS746L | ✅ Live — viết lại 26/08/2026 |
| 4 | `dongfeng-n270-gan-cau-scs746l-8-tan` | Dongfeng DFL1250A13 6×4 · SCS746L | ✅ Live — sửa Title (đang ghi "Hoàng Huy") |
| 5 | `isuzu-fvm-gan-cau-scs746l-8-tan` | Isuzu FVM60WE5 · SCS746L | ✅ Live — slug đã chốt đúng khung |
| 6 | `chenglong-lz1250-gan-cau-scs867ls-8-tan` | Chenglong LZ1250M5DBT · SCS867LS | ✅ Live — cần spec cẩu SCS867LS |
| 7 | `dongfeng-l315-gan-cau-scs1015ls-12-tan` | Dongfeng L315 · SCS1015LS | ✅ Live — sửa Title ("Hoàng Huy") |
| 8 | `chenglong-lz1310-gan-cau-scs1215ls-13-tan` | Chenglong LZ1310 · SCS1215LS | ✅ Live — sửa Title (đang ghi 12 tấn + SCS1215) |
| 9 | `chenglong-lz1340-gan-cau-scs1516s-15-tan` | Chenglong LZ1340 10×4 · SCS1516S | ✅ Live — cần spec xe |
| 10 | `dongfeng-kl340-gan-cau-scs1516s-15-tan` | Dongfeng KL340 cabin mới · SCS1516S | ✅ Live — thân bài gọi lẫn "L340", sửa lại |
| 11 | `dongfeng-l315-gan-cau-scs1516s-15-tan` | Dongfeng L315 cabin cũ · SCS1516S | ✅ Live — slug đúng khung, chốt |
| 12 | `faw-jh6-gan-cau-scs1516s-15-tan` | FAW JH6 · SCS1516S | ✅ Live |
| 13 | `ud-quester-cge350-gan-cau-scs746l-8-tan` | UD Quester CGE350 8×4 · SCS746L | ✅ Live |
| 14 | `kl270-gan-cau-scs746l-8-tan` | Dongfeng KL270 cabin mới · SCS746L | ⏳ Chưa viết — vẫn link theo Map |
| 15 | `b180-gan-cau-scs524-5-tan` | Dongfeng B180 · SCS524 | ⏳ Chưa viết — vẫn link theo Map |
| 16 | `xe-tai-jac-n900-gan-cau-soosan-scs334` | JAC N900.E5 Plus · SCS334 | ✅ Live — viết 26/08/2026, **bài mẫu vàng** của v6.H |

### 4.1. Quy tắc link — bám sát Map

- Nội dung luôn link theo **đúng slug trong Map**, không phụ thuộc trạng thái live.
- Mọi Product trong Map đều được liệt kê và link từ `/collections/cau-soosan`.
- Product chưa có URL thật: vẫn giữ link theo Map, **không ghi chú, không gắn nhãn gì cạnh link trong bài**; trạng thái khai ở mục 16.3. Sau khi bài live thì khai báo GSC theo link thực tế.
- Không đổi slug trong nội dung để "chờ live". Nếu slug phải đổi thì sửa trong Map trước, rồi mới cập nhật nội dung.
- Xếp nhóm Collection tải trọng: #14 KL270 ⇒ 7-8 tấn · #15 B180 · SCS524 ⇒ 5 tấn · #16 JAC N900 · SCS334 ⇒ 3 tấn.

### 4.2. Cặp dễ ăn thịt nhau — phải tách góc kể

| Cặp | Điểm trùng | Cách tách |
| --- | --- | --- |
| #7 vs #8 | SCS1015LS và SCS1215LS gần nhau về bán kính và cao móc | #7 giữ "12 tấn", #8 giữ "13 tấn". Không bài nào nhắc mức tải của bài kia trong Title/Meta |
| #9 · #10 · #11 · #12 | Cùng cẩu SCS1516S, khác xe nền | Mỗi bài kể theo **xe nền** (số trục, cabin, tải thùng), không kể lại cẩu. Phần cẩu link về hub B3 |
| #10 vs #11 | Cùng Dongfeng, khác đời cabin | #10 = cabin mới KL340, #11 = cabin cũ L315. Nêu rõ đời cabin trong 100 từ đầu |
| #2 · #3 · #4 · #5 · #13 | Cùng cẩu SCS746L | Tách theo cấu hình trục 6×2 / 6×4 / 8×4 và hãng xe nền. Phần cẩu link về hub B1 |

### 4.3. Việc còn lại trên Product

- [ ]  Sửa Title #4 và #7: bỏ "Hoàng Huy"
- [ ]  Sửa Title #8: 13 tấn + SCS1215LS
- [ ]  Sửa thân bài #10: gọi đúng KL340
- [ ]  Bổ sung số cốt lõi (mục 8) cho #1, #2, #6, #9
- [ ]  Rà `/collections/cau-soosan`: liệt kê đủ Product live theo bảng mục 4
- [ ]  Rà lại toàn bộ Product live theo v6.0 mục 10.1: xoá mọi chỗ còn chữ "Đang cập nhật" / ô bảng trống trong thân bài đã đăng
- [ ]  Nạp Purple Cow riêng cho từng Product (mục 11) — hiện đang trống

---

## 5. Tầng Blog — theo sitemap 22/08

| URL | Vai |
| --- | --- |
| `/blogs/news/tong-quan-ve-xe-tai-gan-cau-xe-cau-tu-hanh` | Tổng quan — trên tầng Pillar |
| `/blogs/news/kinh-nghiem-chon-xe-tai-gan-cau` | Tư vấn chọn xe |
| `/blogs/news/gia-cau-12-tan` | Giá theo mức tải, đa hãng |
| `/blogs/news/bang-gia-xe-cau-8-tan` | Giá theo mức tải, đa hãng |
| `/blogs/news/xe-tai-gan-cau-cu-co-nen-dau-tu` | Xe cũ, ngoài cụm |
| `/blogs/news/gia-cau-15-tan-cu` | Xe cũ |

Soosan không nhắm lại các từ khoá giá theo mức tải đã thuộc các blog trên.

---

## 6. Đề xuất viết thêm — chưa tạo, chờ duyệt

Cụm Soosan **chưa có bài trục model nào** — đây là khoảng trống lớn nhất.

| Ưu tiên | Slug đề xuất | Vai | Giải vấn đề gì |
| --- | --- | --- | --- |
| 🔴 1 | `/blogs/news/cau-soosan-scs746l-8-tan` | Hub kỹ thuật theo mã cẩu | Nhiều Product dùng SCS746L, chưa bài nào giải thích model |
| 🔴 1 | `/blogs/news/so-sanh-cau-soosan-scs1015ls-va-scs1215ls` | So sánh trong cùng hãng | Hai model cùng bán kính và cao móc, dễ ăn thịt nhau |
| 🟡 2 | `/blogs/news/cau-soosan-scs1516s-15-tan` | Hub kỹ thuật theo mã cẩu | Nhiều Product dùng SCS1516S trên các xe nền khác nhau |
| 🟡 2 | `/blogs/news/bang-gia-xe-tai-gan-cau-soosan` | Trục giá theo hãng | Chưa trang nào đáp "giá xe cẩu Soosan" |
| 🟢 3 | `/blogs/news/cau-soosan-cua-nuoc-nao-co-tot-khong` | EEAT thương hiệu | Gỡ vai tìm hiểu hãng khỏi Collection |
| 🟢 3 | `/blogs/news/chon-xe-tai-gan-cau-theo-so-chan-6x2-6x4-8x4` | Tư vấn theo cấu hình trục | Nhóm 7–8 tấn có cả 6×2, 6×4, 8×4 |

**Điều kiện viết B1 và B3:** hub kỹ thuật theo mã cẩu chỉ viết được khi có đủ 3 số cốt lõi của model đó (mục 8). Chưa có ⇒ giữ ở mục 6, không viết bài rỗng.

### 6.1. Duyệt từng bài

- [ ]  B1 — `cau-soosan-scs746l-8-tan`
- [ ]  B2 — `so-sanh-cau-soosan-scs1015ls-va-scs1215ls`
- [ ]  B3 — `cau-soosan-scs1516s-15-tan`
- [ ]  B4 — `bang-gia-xe-tai-gan-cau-soosan`
- [ ]  B5 — `cau-soosan-cua-nuoc-nao-co-tot-khong` (gộp luôn intent "cẩu Soosan có tốt không", không tách bài riêng)
- [ ]  B6 — `chon-xe-tai-gan-cau-theo-so-chan-6x2-6x4-8x4`

---

## 7. Luật phân vai — áp cho cả Map này

| Tầng | Được nhắm | CẤM nhắm |
| --- | --- | --- |
| Pillar | "xe tải gắn cẩu", "xe cẩu tự hành", "cẩu tự hành là gì" | Tên hãng cẩu, mã model, "báo giá" |
| Collection tải trọng | "xe tải gắn cẩu X tấn", "mua xe cẩu X tấn" | Tên hãng, mã model |
| Collection `cau-soosan` | "xe tải gắn cẩu Soosan", "xe cẩu Soosan" | Mức tải cụ thể, mã model đơn lẻ |
| Blog hub model (B1, B3) | "cẩu Soosan {model}", "cẩu Soosan X tấn" | Tên xe nền cụ thể |
| Product | "{hãng} {mã xe} gắn cẩu {model}" | "xe tải gắn cẩu X tấn" trần, "cẩu Soosan" trần |

---

## 8. Luật số cốt lõi (sửa 09/09/2026)

Bốn chỉ tiêu kỹ thuật của cụm này: **① sức nâng @2m · ② momen · ③ bán kính làm việc · ④ chiều cao nâng móc.**

**Chặn xuất bản:** thiếu bất kỳ số nào trong **3 số cốt lõi ① ② ③** ⇒ Product hoặc Blog hub model **chưa đủ điều kiện xuất bản** — dừng, xin dữ liệu trước khi viết.

**Không chặn xuất bản:** thiếu ④ chiều cao nâng móc ⇒ **bỏ dòng đó** khỏi bảng thông số + khai 1 dòng ở mục 16.3, vẫn xuất bài. Lý do: giữ ④ ở mức chặn thì phải dừng viết mới toàn cụm cho tới khi có catalogue — cái giá quá lớn so với lợi ích.

Không suy diễn, không nội suy từ model gần giống. **Không ghi "Đang cập nhật" trong bài** — mọi khoảng trống xử lý theo v6.0 mục 10.1 (bỏ dòng → bỏ khối → gỡ heading/câu dẫn/mục lục/link) và khai ở mục 16.3.

### 8.1. Bảng số cốt lõi theo model

| Model | ① Sức nâng @2m | ② Momen | ③ Bán kính làm việc | ④ Chiều cao nâng móc |
| --- | --- | --- | --- | --- |
| SCS334 | CẦN BỔ SUNG | CẦN BỔ SUNG | CẦN BỔ SUNG | CẦN BỔ SUNG |
| SCS524 | CẦN BỔ SUNG | CẦN BỔ SUNG | CẦN BỔ SUNG | CẦN BỔ SUNG |
| SCS525 | CẦN BỔ SUNG | CẦN BỔ SUNG | CẦN BỔ SUNG | CẦN BỔ SUNG |
| SCS746L | CẦN BỔ SUNG | CẦN BỔ SUNG | CẦN BỔ SUNG | CẦN BỔ SUNG |
| SCS867LS | CẦN BỔ SUNG | CẦN BỔ SUNG | CẦN BỔ SUNG | CẦN BỔ SUNG |
| SCS1015LS | CẦN BỔ SUNG | CẦN BỔ SUNG | CẦN BỔ SUNG | CẦN BỔ SUNG |
| SCS1215LS | CẦN BỔ SUNG | CẦN BỔ SUNG | CẦN BỔ SUNG | CẦN BỔ SUNG |
| SCS1516S | CẦN BỔ SUNG | CẦN BỔ SUNG | CẦN BỔ SUNG | CẦN BỔ SUNG |

Nguồn hợp lệ theo thứ tự ưu tiên: hồ sơ đăng kiểm → catalog PDF Soosan → ảnh bảng tải gắn trên xe → website hãng. Hai nguồn lệch nhau ⇒ ưu tiên hồ sơ đăng kiểm và ghi rõ cả hai trong file này. Điền ô nào thì ghi nguồn ngay bên cạnh — tên tài liệu nguồn này cũng là thứ duy nhất được ghi ở chú thích chân bảng trong bài (v6.H H4.2).

**Cảnh báo trạng thái:** hiện cả 8 model đều trống ⇒ theo luật trên, **chưa model nào đủ điều kiện xuất bản bài mới**. Các Product đang live giữ nguyên, chỉ rà theo mục 4.3. Ưu tiên lấy dữ liệu: SCS746L và SCS1516S (nhiều Product dùng nhất).

---

## 9. Registry từ khoá cụm Soosan

| Từ khoá | Intent | Loại trang | URL sở hữu |
| --- | --- | --- | --- |
| xe tải gắn cẩu là gì · cẩu tự hành là gì | Thông tin | Pillar | `/pages/xe-tai-gan-cau` |
| xe tải gắn cẩu Soosan · xe cẩu Soosan | Thương mại | Collection hãng | `/collections/cau-soosan` |
| xe tải gắn cẩu 8 tấn | Thương mại | Collection tải trọng | `/collections/xe-tai-gan-cau-7-8-tan` |
| xe tải gắn cẩu 15 tấn | Thương mại | Collection tải trọng | `/collections/xe-tai-gan-cau-15-tan` |
| cẩu Soosan SCS746L | Thông tin kỹ thuật | Blog hub | B1 — CẦN TẠO |
| cẩu Soosan SCS1516S | Thông tin kỹ thuật | Blog hub | B3 — CẦN TẠO |
| so sánh SCS1015LS và SCS1215LS | So sánh | Blog | B2 — CẦN TẠO |
| giá xe cẩu Soosan · bảng giá xe tải gắn cẩu Soosan | Giá | Blog | B4 — CẦN TẠO |
| cẩu Soosan của nước nào · cẩu Soosan có tốt không | EEAT hãng | Blog | B5 — CẦN TẠO |
| đăng kiểm xe cẩu · pháp lý xe gắn cẩu | Pháp lý | Cluster | `/blogs/news/phap-ly-dang-kiem-xe-cau-2026` (dùng chung, Soosan không sở hữu) |
| {hãng} {mã xe} gắn cẩu {model} | Giao dịch | Product | Theo bảng mục 4 |

Volume tìm kiếm và vị trí GSC: **CẦN BỔ SUNG** — chưa có dữ liệu, không suy đoán.

---

## 10. Nguyên tắc trạng thái

- Slug và 301: **đã chốt 22/08/2026, không bàn lại**.
- Product/Blog đã live: chỉ sửa theo checklist mục 4.3.
- Product chưa live: vẫn link theo Map; GSC khai báo sau theo link thực tế.
- Bài trong mục 6: chưa tạo cho tới khi Ba tick duyệt **và** đủ 3 số cốt lõi.
- Mã model ở mục 2: khoá, không bàn lại.
- Danh sách ở mục 3, 4, 5: mở, thêm dòng bằng lệnh `~~6.2` kèm ngày.

---

## 11. Kho Purple Cow cụm Soosan

| Model / URL | Điểm đáng kể lại | Bằng chứng | Đối thủ có nói chưa |
| --- | --- | --- | --- |
| (trống — nạp dần bằng tham số `/p!`) | | | |

Mỗi Product một Purple Cow khác nhau. Kho còn trống ⇒ khi viết bài, lấy Purple Cow từ **nguồn dịch vụ** theo v6.0 mục 9 (đăng kiểm trọn gói 7–15 ngày · đào tạo vận hành tận nơi · vay 70–80% tới 60 tháng) vì nguồn này luôn có thật. Vẫn không đủ 4 tiêu chí ⇒ **bỏ khối Purple Cow khỏi bài** và ghi "cần bổ sung dữ liệu khác biệt" **chỉ ở mục 16.3**. Tuyệt đối không viết câu sáo và không viết câu đó trong thân bài.

---

## 12. Nhật ký

- **09/09/2026 — v6.2.3.** Đồng bộ với v6.0.10 + v6.H (6.H.3). ① Mục 0.0: bỏ tham chiếu "mục 14B Design System" và "mục 25B" (không còn tồn tại) → trỏ v6.H H1–H10 và v6.0 mục 15; ghi rõ phiên bản file mẹ. ② Thêm **mục 0.0.1 Luật khuyết dữ liệu** — bảng ánh xạ "CẦN BỔ SUNG trong file này → bỏ dòng/bỏ khối trong bài", danh sách chuỗi cấm, trỏ C21/C22 + P1–P22. ③ Mục 8: đổi "Luật 4 con số" → **Luật số cốt lõi**; chỉ ① ② ③ chặn xuất bản, ④ chiều cao nâng móc thiếu thì bỏ dòng không chặn (đồng bộ quyết định đã chốt ở 6.1); **xoá câu ra lệnh ghi "Đang cập nhật"** — đây là nguồn gốc lỗi lọt chữ nội bộ vào bài đã đăng. ④ Mục 4.1: bổ sung "không ghi chú cạnh link" cho URL chưa live. ⑤ Mục 4.3: thêm việc rà lại Product live theo mục 10.1. ⑥ Mục 6: thêm điều kiện đủ số cốt lõi mới viết B1/B3. ⑦ Mục 8.1: thêm cảnh báo trạng thái + ưu tiên lấy dữ liệu SCS746L/SCS1516S. ⑧ Mục 11: bổ sung đường thoát Purple Cow từ nguồn dịch vụ. ⑨ Vô hiệu câu "mọi file HTML xuất ra phải có nút copy" ở nhật ký 22/08 — trái v6.H H9 (đầu ra là 1 file thân bài sạch, không nút copy, không khung xem trước). ⑩ Bỏ thẻ `<aside>` ở đầu file, thay bằng blockquote. Không đổi slug, mã model, sitemap, registry.
- **29/08/2026** — v6.2.2. Bỏ hẳn mục 0 "Trạng thái tổng quan" có cột Số lượng; mục 0 nay là "Phạm vi cụm", chỉ trỏ nguồn, không khai số. Siết mục 0.1: cấm khai số ở mọi nơi kể cả bảng nội bộ. Sửa aside và mục 10 cho khớp. Gộp đề xuất blog `cau-soosan-co-tot-khong` vào B5. Bổ sung thứ tự ưu tiên nguồn ở mục 8.1. Lý do gốc: hai chỗ cùng khai một con số đã gây sai lệch 13/14.
- **29/08/2026** — v6.2.1. Viết lại toàn bộ file theo khung chuẩn. Thêm dòng phiên bản đầu file, mục 0.1, SCS334 vào mục 2, ngoại lệ slug #16, mục 4.2, 8.1, 9, 11. Phát hiện bảng đếm cũ ghi 13 Product live trong khi danh sách có 14 dòng — bỏ sót #16 JAC N900.
- **26/08/2026** — Chốt vai: bản này là Instruction con v6.2 của Soosan, chứa Site Map bên trong. Gộp nội dung từ bản trùng lặp (thêm Product #16 JAC N900 · SCS334) rồi đóng bản trùng.
- **22/08/2026** — Chốt sitemap chuẩn: thêm FAW JH6 và UD Quester, KL270 và B180 · SCS524 chưa live, slug #5 và #11 đúng khung `-gan-cau-`, đóng toàn bộ tranh luận về slug/301.
- **22/08/2026 (bổ sung)** — Nguyên tắc **bám sát Map**: nội dung link theo slug trong Map bất kể trạng thái live, GSC khai báo sau. *(Câu "mọi file HTML xuất ra phải có nút copy" trong bản gốc đã bị vô hiệu từ 09/09/2026 — theo v6.H H9.)*
- **19/08/2026** — Chốt `/collections/cau-soosan` làm Collection hãng.
