# Instruction v6.2 — Xe tải cẩu Soosan (bản con của v6.0) — Site Map / Revision Baseline
Phiên bản: v6.2.4 · Cập nhật 13/11/2026
Nguồn đối chiếu: sitemap chốt 22/08/2026 · bổ sung 26/08/2026 · rà soát & cập nhật live Haravan 13/11/2026

> **Bản chốt sitemap 22/08/2026 & hợp nhất KL270 ngày 13/11/2026.** Slug đang live và 301 đã chốt — không bàn lại. Phạm vi cụm và nguồn dữ liệu xem mục 0.

## 0.0. Vai của bản này

- Đây là **Instruction con v6.2**, dành riêng cho cụm **xe tải cẩu Soosan**, và **Site Map nằm ngay trong bản này** (mục 3, 4, 5, 6).
- Kế thừa 100% **`mrtu-v6.0-core.md` (v6.0.10)** — tầng nội dung, và **`Haravan.md` (v6.H.5)** — tầng trình bày.
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
| Product | mục 4 | Cột Trạng thái phân biệt Live / Đã ẩn (301) |
| Model cẩu | mục 2 | Danh sách khoá, thêm bằng lệnh `~~6.2` |
| Pillar | `/pages/xe-tai-gan-cau` | Dùng chung toàn ngành cẩu |
| Collection hãng | `/collections/cau-soosan` | |
| Collection tải trọng | mục 3 | Dùng chung đa hãng |
| Blog | mục 5 | |
| Blog trục model Soosan | mục 6 | Đã triển khai live theo bảng mục 6 |
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

Model mới chỉ được thêm bằng lệnh `~~6.2`, kèm đủ thông số cốt lõi ở mục 8.

---

## 3. Tầng trên — đã có, không tạo mới

| Tầng | URL | Vai | Trạng thái |
| --- | --- | --- | --- |
| Pillar | `/pages/xe-tai-gan-cau` | Tổng quan toàn ngành, không nhắm hãng | ✅ Giữ — rà bỏ mốc năm lỗi thời (13/11/2026) |
| Collection hãng | `/collections/cau-soosan` | Danh mục toàn cụm Soosan | ✅ Live — cập nhật chuẩn v6.H.5 & bỏ N270 (13/11/2026) |
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
| 1 | `chenglong-m3-gan-cau-scs525-5-tan` | Chenglong M3 · SCS525 | ✅ Live — đủ spec + link về KL270 (13/11/2026) |
| 2 | `hino-fl8jw-gan-cau-scs746l-8-tan` | Hino FL8JW 6×2 · SCS746L | ✅ Live — chuẩn hoá v6.H |
| 3 | `hino-fm8jw8a-gan-cau-scs746l-8-tan` | Hino FM8JW8A 6×4 · SCS746L | ✅ Live — đã cập nhật link về KL270 (13/11/2026) |
| 4 | `dongfeng-n270-gan-cau-scs746l-8-tan` | Dongfeng N270 (cabin cũ) · SCS746L | ⛔ Đã ẩn — bỏ khỏi Soosan & **301 → #14 `kl270-gan-cau-scs746l-8-tan`** (13/11/2026) |
| 5 | `isuzu-fvm-gan-cau-scs746l-8-tan` | Isuzu FVM60WE5 · SCS746L | ✅ Live — chuẩn hoá v6.H |
| 6 | `chenglong-lz1250-gan-cau-scs867ls-8-tan` | Chenglong LZ1250M5DBT · SCS867LS | ✅ Live — đủ spec SCS867LS & link KL270 (13/11/2026) |
| 7 | `dongfeng-l315-gan-cau-scs1015ls-12-tan` | Dongfeng L315 · SCS1015LS | ✅ Live — đã bỏ "Hoàng Huy", tách cặp 12 tấn |
| 8 | `chenglong-lz1310-gan-cau-scs1215ls-13-tan` | Chenglong LZ1310 · SCS1215LS | ✅ Live — đã chuẩn hoá 13 tấn + SCS1215LS |
| 9 | `chenglong-lz1340-gan-cau-scs1516s-15-tan` | Chenglong LZ1340 10×4 · SCS1516S | ✅ Live — đủ spec xe, bỏ mốc năm cũ (13/11/2026) |
| 10 | `dongfeng-kl340-gan-cau-scs1516s-15-tan` | Dongfeng KL340 cabin mới · SCS1516S | ✅ Live — chuẩn tên gọi KL340 |
| 11 | `dongfeng-l315-gan-cau-scs1516s-15-tan` | Dongfeng L315 cabin cũ · SCS1516S | ✅ Live — slug đúng khung, chốt |
| 12 | `faw-jh6-gan-cau-scs1516s-15-tan` | FAW JH6 · SCS1516S | ✅ Live |
| 13 | `ud-quester-cge350-gan-cau-scs746l-8-tan` | UD Quester CGE350 8×4 · SCS746L | ✅ Live |
| 14 | `kl270-gan-cau-scs746l-8-tan` | Dongfeng KL270 (DFL1250A13) 6×4 · SCS746L | ✅ Live — chuẩn Spec Sheet DFL1250A13, thay thế hoàn toàn N270 (13/11/2026) |
| 15 | `b180-gan-cau-scs524-5-tan` | Dongfeng B180 · SCS524 | ✅ Live — đủ ảnh Gallery/bài & spec, link về KL270 (13/11/2026) |
| 16 | `xe-tai-jac-n900-gan-cau-soosan-scs334` | JAC N900.E5 Plus · SCS334 | ✅ Live — viết 26/08/2026, **bài mẫu vàng** của v6.H |

*(Lưu ý ngoài phạm vi cụm: `mam-quay-toa-soosan` và `phu-tung-cau-soosan` thuộc nhóm phụ tùng, giữ nguyên, không nằm trong danh sách xe tải gắn cẩu Soosan.)*

### 4.1. Quy tắc link — bám sát Map

- Nội dung luôn link theo **đúng slug đang live trong Map**, không trỏ tới URL đã 301 (#4 `dongfeng-n270-gan-cau-scs746l-8-tan`); toàn bộ liên kết Dongfeng 3 chân 6×4 gắn SCS746L trong cụm Soosan phải dùng **#14 `/products/kl270-gan-cau-scs746l-8-tan`**.
- Mọi Product đang live trong Map đều được liệt kê và link canonical từ `/collections/cau-soosan`.
- Product chưa có URL thật: vẫn giữ link theo Map, **không ghi chú, không gắn nhãn gì cạnh link trong bài**; trạng thái khai ở mục 16.3. Sau khi bài live thì khai báo GSC theo link thực tế.
- Không đổi slug trong nội dung để "chờ live". Nếu slug phải đổi thì sửa trong Map trước, rồi mới cập nhật nội dung.
- Xếp nhóm Collection tải trọng: #14 KL270 ⇒ 7-8 tấn · #15 B180 · SCS524 ⇒ 5 tấn · #16 JAC N900 · SCS334 ⇒ 3 tấn.

### 4.2. Cặp dễ ăn thịt nhau — phải tách góc kể

| Cặp | Điểm trùng | Cách tách |
| --- | --- | --- |
| #7 vs #8 | SCS1015LS và SCS1215LS gần nhau về bán kính và cao móc | #7 giữ "12 tấn", #8 giữ "13 tấn". Không bài nào nhắc mức tải của bài kia trong Title/Meta |
| #9 · #10 · #11 · #12 | Cùng cẩu SCS1516S, khác xe nền | Mỗi bài kể theo **xe nền** (số trục, cabin, tải thùng), không kể lại cẩu. Phần cẩu link về hub B3 |
| #10 vs #11 | Cùng Dongfeng, khác đời cabin | #10 = cabin mới KL340, #11 = cabin cũ L315. Nêu rõ đời cabin trong 100 từ đầu |
| #2 · #3 · #5 · #13 · #14 | Cùng cẩu SCS746L | Tách theo cấu hình trục 6×2 / 6×4 / 8×4 và hãng xe nền. Phần cẩu link về hub B1 (#4 cũ đã 301 về #14 KL270) |

### 4.3. Việc trên Product (trạng thái đến 13/11/2026)

- [x] Gộp & loại bỏ Dongfeng N270 (#4 cũ) khỏi cụm Soosan; dồn chuẩn về #14 `kl270-gan-cau-scs746l-8-tan` theo Spec Sheet DFL1250A13 và tạo 301 Redirect `/products/dongfeng-n270-gan-cau-scs746l-8-tan` → `/products/kl270-gan-cau-scs746l-8-tan`
- [x] Sửa Title #7 (`dongfeng-l315-gan-cau-scs1015ls-12-tan`) và #15 (`B180`): bỏ "Hoàng Huy"
- [x] Sửa Title #8 (`chenglong-lz1310-gan-cau-scs1215ls-13-tan`): chuẩn hoá 13 tấn + SCS1215LS
- [x] Sửa thân bài #10 (`dongfeng-kl340-gan-cau-scs1516s-15-tan`): gọi đúng KL340
- [x] Bổ sung số cốt lõi (mục 8) cho các Product trong cụm, hoàn thiện #1, #2, #6, #9, #14, #15
- [x] Rà `/collections/cau-soosan`: liệt kê đủ Product live theo bảng mục 4, gỡ hoàn toàn #4 cũ & tag `Dongfeng N270`
- [x] Rà lại toàn bộ Product live theo v6.0 mục 10.1: xoá sạch chuỗi cấm, `Default Title`, bỏ kênh Haravan POS (chỉ giữ Website), chuẩn hoá Trích dẫn & ALT ảnh Gallery/thân bài
- [ ] Nạp thêm Purple Cow chứng thực riêng theo hồ sơ giao xe thực tế từng Product (mục 11) — hiện dùng nguồn dịch vụ VietNhatCorp làm chuẩn nền

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

## 6. Nhóm Blog trục Soosan (đã triển khai live)

| Ưu tiên | Slug | Vai | Giải vấn đề gì |
| --- | --- | --- | --- |
| 🔴 1 | `/blogs/news/cau-soosan-scs746l-8-tan` | Hub kỹ thuật theo mã cẩu | Giải thích model SCS746L cho nhóm Product 8 tấn |
| 🔴 1 | `/blogs/news/so-sanh-cau-soosan-scs1015ls-va-scs1215ls` | So sánh trong cùng hãng | Phân tách hai model dễ ăn thịt nhau (#7 vs #8) |
| 🟡 2 | `/blogs/news/cau-soosan-scs1516s-15-tan` | Hub kỹ thuật theo mã cẩu | Hub cho nhóm Product dùng SCS1516S (#9–#12) |
| 🟡 2 | `/blogs/news/bang-gia-xe-tai-gan-cau-soosan` | Trục giá theo hãng | Đáp ý định "giá xe tải gắn cẩu Soosan" |
| 🟢 3 | `/blogs/news/cau-soosan-cua-nuoc-nao-co-tot-khong` | EEAT thương hiệu | Gỡ vai tìm hiểu hãng khỏi Collection |
| 🟢 3 | `/blogs/news/chon-xe-tai-gan-cau-theo-so-chan-6x2-6x4-8x4` | Tư vấn theo cấu hình trục | Phân biệt 6×2, 6×4, 8×4 cho nhóm 7–15 tấn |

**Điều kiện viết B1 và B3:** hub kỹ thuật theo mã cẩu chỉ viết được khi có đủ số cốt lõi ① ② ③ của model đó (mục 8). Chưa có ⇒ giữ chờ dữ liệu, không viết bài rỗng.

### 6.1. Trạng thái từng bài

- [x] B1 — `/blogs/news/cau-soosan-scs746l-8-tan` ✅ Live (đã cập nhật dùng KL270, bỏ N270 & năm cũ 13/11/2026)
- [x] B2 — `/blogs/news/so-sanh-cau-soosan-scs1015ls-va-scs1215ls` ✅ Live (bỏ mốc năm cũ 13/11/2026)
- [x] B3 — `/blogs/news/cau-soosan-scs1516s-15-tan` ✅ Live (bỏ mốc năm cũ 13/11/2026)
- [x] B4 — `/blogs/news/bang-gia-xe-tai-gan-cau-soosan` ✅ Live (đã cập nhật link KL270, bỏ N270 & năm cũ 13/11/2026)
- [x] B5 — `/blogs/news/cau-soosan-cua-nuoc-nao-co-tot-khong` ✅ Live (gộp intent "cẩu Soosan có tốt không")
- [x] B6 — `/blogs/news/chon-xe-tai-gan-cau-theo-so-chan-6x2-6x4-8x4` ✅ Live (đã cập nhật link KL270, bỏ N270 13/11/2026)

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

Bốn chỉ tiêu kỹ thuật của cụm này: **① sức nâng @tầm với gần nhất · ② momen · ③ bán kính làm việc · ④ chiều cao nâng móc.**

**Chặn xuất bản:** thiếu bất kỳ số nào trong **3 số cốt lõi ① ② ③** ⇒ Product hoặc Blog hub model **chưa đủ điều kiện xuất bản** — dừng, xin dữ liệu trước khi viết.

**Không chặn xuất bản:** thiếu ④ chiều cao nâng móc ⇒ **bỏ dòng đó** khỏi bảng thông số + khai 1 dòng ở mục 16.3, vẫn xuất bài. Lý do: giữ ④ ở mức chặn thì phải dừng viết mới toàn cụm cho tới khi có catalogue — cái giá quá lớn so với lợi ích.

Không suy diễn, không nội suy từ model gần giống. **Không ghi "Đang cập nhật" trong bài** — mọi khoảng trống xử lý theo v6.0 mục 10.1 (bỏ dòng → bỏ khối → gỡ heading/câu dẫn/mục lục/link) và khai ở mục 16.3.

### 8.1. Bảng số cốt lõi theo model

| Model | ① Sức nâng | ② Momen | ③ Bán kính làm việc | ④ Chiều cao nâng móc | Nguồn / Ghi chú |
| --- | --- | --- | --- | --- | --- |
| SCS334 | 3.200 kgf @ 2,6 m | 8,0 ton.m | 0,4 – 9,7 m | CẦN BỔ SUNG | Spec trang Product #16 |
| SCS524 | 7.000 kgf @ 2,0 m | 14 ton.m | 0,8 – 10,7 m | 13,8 m | Spec trang Product #15 |
| SCS525 | 7.000 kgf @ 2,0 m | 14 ton.m | 0,8 – 13,2 m | 13,8 m | Spec trang Product #1 |
| SCS746L | 8.000 kg @ 2,0 m | 17,5 ton.m | 19,6 m | 21,8 m (nâng) · 22,6 m (làm việc) | Spec Sheet Soosan Vina Motor (DFL1250A13) |
| SCS867LS | 7.000 kg @ 2,4 m | 17,5 ton.m | 22,3 m (27,3 m cần phụ) | 24,5 m / 25,2 m | Spec trang Product #6 |
| SCS1015LS | 12.000 kgf @ 2,0 m | 36 ton.m | 2,0 – 20,7 m | 23 m | Tài liệu Soosan · Product #7 |
| SCS1215LS | 13.000 kgf @ 2,0 m | 36 ton.m | 2,0 – 20,7 m | 23 m | Tài liệu Soosan Cebotics · Product #8 |
| SCS1516S | 15.000 kgf @ 2,0 m | 47 ton.m | 1,25 – 25,0 m | 28,5 m | Spec trang Product #9 |

Nguồn hợp lệ theo thứ tự ưu tiên: hồ sơ đăng kiểm → catalog PDF Soosan / Spec Sheet Soosan Vina Motor → ảnh bảng tải gắn trên xe → website hãng. Hai nguồn lệch nhau ⇒ ưu tiên hồ sơ đăng kiểm và ghi rõ cả hai trong file này. Điền ô nào thì ghi nguồn ngay bên cạnh — tên tài liệu nguồn này cũng là thứ duy nhất được ghi ở chú thích chân bảng trong bài (v6.H H4.2).

---

## 9. Registry từ khoá cụm Soosan

| Từ khoá | Intent | Loại trang | URL sở hữu |
| --- | --- | --- | --- |
| xe tải gắn cẩu là gì · cẩu tự hành là gì | Thông tin | Pillar | `/pages/xe-tai-gan-cau` |
| xe tải gắn cẩu Soosan · xe cẩu Soosan | Thương mại | Collection hãng | `/collections/cau-soosan` |
| xe tải gắn cẩu 8 tấn | Thương mại | Collection tải trọng | `/collections/xe-tai-gan-cau-7-8-tan` |
| xe tải gắn cẩu 15 tấn | Thương mại | Collection tải trọng | `/collections/xe-tai-gan-cau-15-tan` |
| cẩu Soosan SCS746L | Thông tin kỹ thuật | Blog hub | `/blogs/news/cau-soosan-scs746l-8-tan` (B1) |
| cẩu Soosan SCS1516S | Thông tin kỹ thuật | Blog hub | `/blogs/news/cau-soosan-scs1516s-15-tan` (B3) |
| so sánh SCS1015LS và SCS1215LS | So sánh | Blog | `/blogs/news/so-sanh-cau-soosan-scs1015ls-va-scs1215ls` (B2) |
| giá xe cẩu Soosan · bảng giá xe tải gắn cẩu Soosan | Giá | Blog | `/blogs/news/bang-gia-xe-tai-gan-cau-soosan` (B4) |
| cẩu Soosan của nước nào · cẩu Soosan có tốt không | EEAT hãng | Blog | `/blogs/news/cau-soosan-cua-nuoc-nao-co-tot-khong` (B5) |
| chọn xe tải gắn cẩu theo số chân 6×2 6×4 8×4 | Tư vấn cấu hình | Blog | `/blogs/news/chon-xe-tai-gan-cau-theo-so-chan-6x2-6x4-8x4` (B6) |
| đăng kiểm xe cẩu · pháp lý xe gắn cẩu | Pháp lý | Cluster | `/blogs/news/phap-ly-dang-kiem-xe-cau-2026` (dùng chung, Soosan không sở hữu) |
| {hãng} {mã xe} gắn cẩu {model} | Giao dịch | Product | Theo bảng mục 4 |

Volume tìm kiếm và vị trí GSC theo từng kỳ đối chiếu trực tiếp qua Google Search Console (`sc-domain:vietnhatcorp.net`).

---

## 10. Nguyên tắc trạng thái

- Slug đang live và 301 đã chốt (kể cả 301 `#4 → #14`): **không bàn lại**.
- Product/Blog đã live: sửa theo checklist mục 4.3, kiểm chứng 0 mojibake, 0 `Default Title`, 0 mốc năm cũ, 0 chuỗi cấm 10.1 và đủ ALT ảnh.
- Product chưa live: vẫn link theo Map; GSC khai báo sau theo link thực tế.
- Bài mới trong mục 6: chưa tạo cho tới khi duyệt **và** đủ số cốt lõi ① ② ③.
- Mã model ở mục 2: khoá, không bàn lại.
- Danh sách ở mục 3, 4, 5, 6: mở, thêm dòng bằng lệnh `~~6.2` kèm ngày.

---

## 11. Kho Purple Cow cụm Soosan

| Model / URL | Điểm đáng kể lại | Bằng chứng | Đối thủ có nói chưa |
| --- | --- | --- | --- |
| (nạp dần bằng tham số `/p!`; hiện các bài dùng nguồn dịch vụ thực của VietNhatCorp) | | | |

Mỗi Product một Purple Cow khác nhau. Kho còn trống ⇒ khi viết bài, lấy Purple Cow từ **nguồn dịch vụ** theo v6.0 mục 9 (đăng kiểm trọn gói 7–15 ngày · đào tạo vận hành tận nơi · vay 70–80% tới 60 tháng) vì nguồn này luôn có thật. Vẫn không đủ 4 tiêu chí ⇒ **bỏ khối Purple Cow khỏi bài** và ghi "cần bổ sung dữ liệu khác biệt" **chỉ ở mục 16.3**. Tuyệt đối không viết câu sáo và không viết câu đó trong thân bài.

---

## 12. Nhật ký

- **13/11/2026 — v6.2.4.** Cập nhật trạng thái live toàn cụm sau đợt rà soát & tối ưu SEO Haravan + GSC: ① Bỏ hẳn Dongfeng N270 (#4 cũ `dongfeng-n270-gan-cau-scs746l-8-tan`) khỏi cụm Soosan vì là cabin cũ; ẩn sản phẩm cũ trên Website & POS, gỡ khỏi collection `cau-soosan` và thiết lập **301 Redirect** sang #14 `/products/kl270-gan-cau-scs746l-8-tan`. ② Cập nhật #14 Dongfeng KL270 theo Spec Sheet Soosan Vina Motor (`DFL1250A13` 6×4, động cơ `ISD270 50`, tải hàng `8.950 kg`, thùng `8.080 × 2.385 × 650 mm`, tổng tải `24.000 kg`, giữ đủ 2 biến thể Cơ bản & Cảnh báo quá tải) và cập nhật toàn bộ internal link từ `cau-soosan`, các Product Soosan & Blog B1/B4/B6 về KL270. ③ Hoàn thiện live #15 `b180-gan-cau-scs524-5-tan` và toàn bộ các bài Blog trục B1–B6; đồng bộ mục 8.1 với thông số đã xác minh của các model Soosan; bỏ các mốc năm lỗi thời, `Default Title`, chuỗi cấm 10.1 và bổ sung đủ ALT ảnh.
- **09/09/2026 — v6.2.3.** Đồng bộ với v6.0.10 + v6.H (6.H.3). ① Mục 0.0: bỏ tham chiếu "mục 14B Design System" và "mục 25B" (không còn tồn tại) → trỏ v6.H H1–H10 và v6.0 mục 15; ghi rõ phiên bản file mẹ. ② Thêm **mục 0.0.1 Luật khuyết dữ liệu** — bảng ánh xạ "CẦN BỔ SUNG trong file này → bỏ dòng/bỏ khối trong bài", danh sách chuỗi cấm, trỏ C21/C22 + P1–P22. ③ Mục 8: đổi "Luật 4 con số" → **Luật số cốt lõi**; chỉ ① ② ③ chặn xuất bản, ④ chiều cao nâng móc thiếu thì bỏ dòng không chặn (đồng bộ quyết định đã chốt ở 6.1); **xoá câu ra lệnh ghi "Đang cập nhật"** — đây là nguồn gốc lỗi lọt chữ nội bộ vào bài đã đăng. ④ Mục 4.1: bổ sung "không ghi chú cạnh link" cho URL chưa live. ⑤ Mục 4.3: thêm việc rà lại Product live theo mục 10.1. ⑥ Mục 6: thêm điều kiện đủ số cốt lõi mới viết B1/B3. ⑦ Mục 8.1: thêm cảnh báo trạng thái + ưu tiên lấy dữ liệu SCS746L/SCS1516S. ⑧ Mục 11: bổ sung đường thoát Purple Cow từ nguồn dịch vụ. ⑨ Vô hiệu câu "mọi file HTML xuất ra phải có nút copy" ở nhật ký 22/08 — trái v6.H H9 (đầu ra là 1 file thân bài sạch, không nút copy, không khung xem trước). ⑩ Bỏ thẻ `<aside>` ở đầu file, thay bằng blockquote. Không đổi slug, mã model, sitemap, registry.
- **29/08/2026** — v6.2.2. Bỏ hẳn mục 0 "Trạng thái tổng quan" có cột Số lượng; mục 0 nay là "Phạm vi cụm", chỉ trỏ nguồn, không khai số. Siết mục 0.1: cấm khai số ở mọi nơi kể cả bảng nội bộ. Sửa aside và mục 10 cho khớp. Gộp đề xuất blog `cau-soosan-co-tot-khong` vào B5. Bổ sung thứ tự ưu tiên nguồn ở mục 8.1. Lý do gốc: hai chỗ cùng khai một con số đã gây sai lệch 13/14.
- **29/08/2026** — v6.2.1. Viết lại toàn bộ file theo khung chuẩn. Thêm dòng phiên bản đầu file, mục 0.1, SCS334 vào mục 2, ngoại lệ slug #16, mục 4.2, 8.1, 9, 11. Phát hiện bảng đếm cũ ghi 13 Product live trong khi danh sách có 14 dòng — bỏ sót #16 JAC N900.
- **26/08/2026** — Chốt vai: bản này là Instruction con v6.2 của Soosan, chứa Site Map bên trong. Gộp nội dung từ bản trùng lặp (thêm Product #16 JAC N900 · SCS334) rồi đóng bản trùng.
- **22/08/2026** — Chốt sitemap chuẩn: thêm FAW JH6 và UD Quester, KL270 và B180 · SCS524 chưa live, slug #5 và #11 đúng khung `-gan-cau-`, đóng toàn bộ tranh luận về slug/301.
- **22/08/2026 (bổ sung)** — Nguyên tắc **bám sát Map**: nội dung link theo slug trong Map bất kể trạng thái live, GSC khai báo sau. *(Câu "mọi file HTML xuất ra phải có nút copy" trong bản gốc đã bị vô hiệu từ 09/09/2026 — theo v6.H H9.)*
- **19/08/2026** — Chốt `/collections/cau-soosan` làm Collection hãng.
