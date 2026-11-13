# Instruction v6.3 — Mâm quay toa xe tải gắn cẩu (bản con của v6.0) — Site Map / Revision Baseline
Phiên bản: v6.3.6 · Cập nhật 13/11/2026
Nguồn đối chiếu: 7 URL Ba cung cấp ngày 03/09/2026 · xác minh live & GSC 90 ngày ngày 13/11/2026

> **Bản sitemap chốt thành bản con v6.3.** Slug 7 URL hiện hữu giữ nguyên theo đường dẫn đang live — không bàn lại. Bài đề xuất mới (mục 9.1) chưa tạo, chờ Ba duyệt từng bài.

## 0.0. Vai của bản này

- Đây là **Instruction con v6.3**, dành riêng cho cụm **mâm quay toa xe tải gắn cẩu**, và **Site Map nằm ngay trong bản này** (mục 3, 4, 9).
- Kế thừa 100%: **`mrtu-v6.0-core.md`** — tầng nội dung (luật khuyết dữ liệu mục 10.1 · Quality Gate **C1–C22** · Luật số đếm mở mục 15) và **`Haravan.md` (v6.H · 6.H.5)** — tầng trình bày (H1–H10 · định mức số chữ H8 · quy cách file đầu ra H9 · bảng kiểm **P1–P22**).
- Bản này **không** đặt quy tắc viết, trình bày hay CTA riêng. Chỉ giữ: sitemap, slug, mã model/dòng sản phẩm, registry, luật phân vai, luật số cốt lõi của cụm.
- Xung đột ba tầng: **v6.0 thắng** ở intent · vai URL · registry · luật dữ liệu · **v6.H thắng** ở màu · HTML · bố cục · số chữ · **v6.3 thắng** ở slug · mã model · sitemap.
- Tương thích tên mục cũ: bản này từng ghi "Quality Gate C1–C20" ⇒ đọc thành **C1–C22**; "v6.0 mục 14B Design System" ⇒ đọc thành **v6.H H1–H10**; "lỗi hình thức 11–14" ⇒ đọc thành **P1–P22**.
- Không tồn tại bản Instruction mâm quay toa nào khác.
- Lệnh cập nhật: `~~6.3` cho sitemap/slug/model · `~~6.0` cho quy tắc nội dung · `~~6.H` cho trình bày.
- Mọi lần sửa bản này: trả về **nguyên file** để dán đè, không sửa lẻ từng dòng (v6.0 mục 19).
- **Đăng ký bộ nạp:** đã có trong `00-LOAD-mrtu.md` — tên thật trên gist là `mrtu-v6.3-mam-quay-toa.md` (có đuôi `.md`), lệnh `~~6.3`, nạp kèm `~load 6.3`.

### 0.0.1. Luật khuyết dữ liệu — bắt buộc đọc trước khi viết bài cụm này

Bản con **được phép** ghi "CẦN BỔ SUNG" / "CẦN TẠO" trong chính file này (đây là sổ theo dõi). Nhưng các chuỗi đó **không bao giờ được chảy vào bài viết**.

| Trong file này ghi | Khi viết bài thì làm gì |
| --- | --- |
| Ô "CẦN BỔ SUNG" trong bảng mục 6.3 | Bỏ DÒNG chỉ tiêu đó khỏi bảng thông số + 1 dòng ở mục 16.3 của bài |
| Thiếu quá nửa chỉ tiêu của một bảng/khối | Bỏ CẢ KHỐI + gỡ heading, câu dẫn, dòng mục lục, link trỏ tới nó |
| "CẦN TẠO" ở registry mục 11 / đề xuất mục 9.1 | Trong bài **không đặt link** tới URL chưa live; trạng thái khai ở 16.3. Chỉ chèn link sau khi bài đích lên sóng |
| Kho Purple Cow mục 13 còn trống | Lấy Purple Cow từ nguồn dịch vụ (mục 13); vẫn không đủ 4 tiêu chí → bỏ khối, khai 16.3 |
| Dự án thực tế mục 12 còn thiếu | **Bỏ hẳn dòng 📌 Kinh nghiệm thực tế** khỏi khối chốt (v6.H H6 · 6.H.5) — không ghi "CẦN BỔ SUNG DỰ ÁN THỰC TẾ" trong bài |

Cấm tuyệt đối trong thân bài: "Đang cập nhật" · "CẦN BỔ SUNG" · "CẦN TẠO" · "cần xác minh" · "chờ catalog" · "theo Map" · "N/A" · `[ ]` · ô bảng trống. Chi tiết: **v6.0 mục 10.1**, cổng quét ở v6.0 mục 13, mã lỗi C21/C22 và P21/P22 (v6.H H10).

---

## 0. Phạm vi cụm

Không ghi số lượng ở đây. Nguồn duy nhất là chính các danh sách bên dưới. Muốn biết bao nhiêu thì đếm dòng trong bảng.

| Hạng mục | Nguồn duy nhất | Ghi chú |
| --- | --- | --- |
| Pillar | mục 3 | Đã live — đã bổ sung 2 ảnh CDN + alt chuẩn ngày 13/11/2026 |
| Collection | mục 3 | Đã live — đã liệt kê đủ Product mục 4 bằng link canonical |
| Product | mục 4 | Đã chuẩn hoá toàn bộ 7 Product mục 4 + rà thêm 2 mã cẩu bánh xích & cẩu tháp ngày 13/11/2026 |
| Model vòng bi / dòng sản phẩm | mục 2 | Danh sách khoá, thêm bằng lệnh `~~6.3` |
| Blog đã live | mục 9.0 | Hai URL, đã gỡ chuỗi cấm & cập nhật ngày 13/11/2026 |
| Blog / Cluster đề xuất | mục 9.1 | Chưa tạo — chờ duyệt từng bài |
| Cluster pháp lý | `/blogs/news/phap-ly-dang-kiem-xe-cau-2026` | Dùng chung toàn ngành cẩu, cụm này **không sở hữu** |

## 0.1. Luật số đếm mở (áp theo v6.0 mục 15)

- Danh sách Product · Blog · Collection của cụm này là **danh sách mở**, sẽ còn tăng.
- **Số lượng không được khai ở bất kỳ đâu ngoài chính danh sách liệt kê.** Không cột đếm, không câu tổng kết số, kể cả trong bảng nội bộ của file này.
- **Cấm** số đếm model/dòng sản phẩm trong Title · Meta · Slug · H2 · 100 từ mở bài · CTA.
- Câu đúng: "nhiều lựa chọn theo hãng và tải trọng", "dải sản phẩm từ mâm quay cẩu mini đến mâm tải lớn". Câu sai: "trọn bộ 5 mẫu mâm quay".

---

## 1. Quy ước slug đã chốt

**Slug hiện hữu — giữ nguyên, không đổi** (đang live, Ba đã đặt):

- `/pages/mam-quay-toa-can-cau`
- `/collections/mam-quay-toa-xe-tai-gan-cau`
- `/products/mam-quay-toa-slewing-bearing-cau-css-hiab`
- `/products/mam-quay-toa-dongyang`
- `/products/mam-quay-toa-kanglim`
- `/products/mam-quay-toa-cau-tadano-unic-3-5-tan`
- `/products/mam-quay-toa-soosan`
- `/products/mam-quay-toa-cau-zoomlion-xcmg`
- `/products/mam-quay-toa-cau-sany`

*Ghi nhận Redirect & URL mở rộng cùng nhóm:*
- `/products/mam-quay-toa-cau-tadano-3-5-tan-shinil` → đã **301** về `/products/mam-quay-toa-cau-tadano-unic-3-5-tan`.
- Hai Product mâm quay toa ngoài nhóm xe tải gắn cẩu (đã chuẩn hoá đồng bộ 13/11/2026): `/products/mam-quay-toa-cau-banh-xich-kobelco-sumitomo-hitachi-ihi` (cẩu bánh xích) và `/products/mam-quay-toa-cau-thap-zoomlion-tc7035-16` (cẩu tháp).

**Luật đường dẫn canonical (chốt 09/09/2026).** Haravan phục vụ sản phẩm ở cả hai dạng `/products/{slug}` và `/collections/{col}/products/{slug}`. Trong mọi nội dung **chỉ dùng dạng `/products/{slug}`**. Tuyệt đối không đặt link dạng `/collections/phu-tung-phu-kien/products/...` — dạng này sinh URL trùng nội dung, chia nhỏ tín hiệu xếp hạng.

**Khung slug bài mới (đề xuất):**

- Product: `/products/mam-quay-toa-{thương hiệu}-{đặc trưng}-{mức tải nếu có}`
- Cluster/Blog: `/blogs/news/{vấn-đề}-mam-quay-toa` (xem mục 9.1)
- Chữ thường · không dấu · dùng `-` · ngắn, có từ khoá · **không nhét năm** (trừ bài giá/theo năm)

---

## 2. Model vòng bi / dòng sản phẩm đã chốt

Khoá, không bàn lại:

**CSS slewing bearing (gắn cho cẩu Hiab) · Dongyang · Kanglim · Tadano Unic (mâm 3,5 tấn) · Soosan · Zoomlion/XCMG · Sany**

- Đây là các dòng sản phẩm của cụm, khớp URL Product liệt kê ở mục 4.
- Link gộp `mam-quay-toa-soosan-kanglim-dongyang` **404, không live** — dùng 3 link riêng `mam-quay-toa-soosan`, `mam-quay-toa-kanglim`, `mam-quay-toa-dongyang`.
- Mã model kỹ thuật chi tiết từng dòng (model vòng bi, tải trọng, đường kính): **CẦN BỔ SUNG từng hãng**.
- Dòng mới chỉ được thêm bằng lệnh `~~6.3`, kèm ngày.

---

## 3. Tầng trên — đã có, không tạo mới

| Tầng | URL | Vai | Trạng thái |
| --- | --- | --- | --- |
| Pillar | `/pages/mam-quay-toa-can-cau` | Kiến thức nền: mâm quay toa là gì, cấu tạo, phân loại, thuật ngữ, cách chọn | ✅ Live — đã bổ sung 2 ảnh CDN + alt chuẩn ngày 13/11/2026 |
| Collection | `/collections/mam-quay-toa-xe-tai-gan-cau` | Danh mục thương mại toàn cụm | ✅ Live — đã liệt kê đủ Product mục 4, SEO sạch năm 2025 |
| Cluster pháp lý | `/blogs/news/phap-ly-dang-kiem-xe-cau-2026` | Dùng chung mọi hãng cẩu | ✅ Giữ — không tạo bài pháp lý riêng cho cụm này |

**Quy tắc nội dung Pillar:** giải thích (là gì, cấu tạo, phân loại), **không bán trực tiếp, không bảng thông số model**. Toả ≥ 6 internal link xuống Collection + Product + Blog của cụm.

**Quy tắc nội dung Collection:** Intro danh mục + tiêu chí chọn nhanh + điểm khác biệt danh mục (1–2 câu) + điều hướng Product (≥ 3 link) + 1 CTA + liên hệ ngắn. **Không nhồi thông số chi tiết, không viết dài như Pillar/Product** (định mức theo v6.H H8).

---

## 4. Tầng Product (danh sách mở)

| # | URL canonical | Định vị | Trạng thái |
| --- | --- | --- | --- |
| 1 | `/products/mam-quay-toa-slewing-bearing-cau-css-hiab` | Mâm quay dùng vòng bi quay (slewing bearing) CSS cho cần cẩu Hiab | ✅ Đã chuẩn hoá 13/11/2026 (6 tags, sạch năm cũ, 5 ảnh alt UI) — còn thiếu số cốt lõi mục 6 |
| 2 | `/products/mam-quay-toa-dongyang` | Mâm quay toa Dongyang | ✅ Đã chuẩn hoá 13/11/2026 (xoá `CẦN TẠO`/`chờ catalog`/`cần xác minh`, sửa link canonical, 6 tags) — còn thiếu số cốt lõi mục 6 |
| 3 | `/products/mam-quay-toa-kanglim` | Mâm quay toa Kanglim | ✅ Đã chuẩn hoá 13/11/2026 (xoá `CẦN TẠO`, 6 tags) — còn thiếu số cốt lõi mục 6 |
| 4 | `/products/mam-quay-toa-cau-tadano-unic-3-5-tan` | Mâm quay toa cho cẩu Tadano Unic, mức tải 3,5 tấn | ✅ Đã chuẩn hoá 13/11/2026 (xoá `Đang cập nhật`/`CẦN BỔ SUNG`, sửa 3 link canonical, thêm 6 tags) — còn thiếu số cốt lõi mục 6 |
| 5 | `/products/mam-quay-toa-soosan` | Mâm quay toa Soosan | ✅ Đã chuẩn hoá 13/11/2026 (gỡ năm `2023`/`2025`, thêm 6 tags) — còn thiếu số cốt lõi mục 6 |
| 6 | `/products/mam-quay-toa-cau-zoomlion-xcmg` | Mâm quay toa cẩu Zoomlion, XCMG — xe tải cẩu Trung Quốc tải lớn | ✅ Đã chuẩn hoá 13/11/2026 (gỡ mini-table/bảng `Đang cập nhật` & `CẦN BỔ SUNG`, sửa 4 link canonical, 6 tags) — còn thiếu số cốt lõi mục 6 |
| 7 | `/products/mam-quay-toa-cau-sany` | Mâm quay toa cẩu Sany — phụ tùng chính hãng | ✅ Đã chuẩn hoá 13/11/2026 (rút Title 62 ký tự, gỡ `Đang cập nhật`/`CẦN BỔ SUNG`, sửa link canonical, 6 tags) — còn thiếu số cốt lõi mục 6 |

### 4.1. Quy tắc link — bám sát Map

- Nội dung luôn link theo **đúng URL canonical trong Map** (mục 1).
- Mọi Product trong Map đều được liệt kê và link từ `/collections/mam-quay-toa-xe-tai-gan-cau`.
- URL chưa live (mục 9.1): **không chèn link trong bài**, khai ở 16.3; chèn sau khi bài đích lên sóng.
- Không đổi slug trong nội dung để "chờ live". Slug phải đổi thì sửa Map trước, rồi mới cập nhật nội dung.

### 4.2. Cặp dễ ăn thịt nhau — phải tách góc kể

| Cặp / nhóm | Điểm trùng | Cách tách |
| --- | --- | --- |
| Mọi Product với Collection | Ai cũng chứa cụm "mâm quay toa" | Collection giữ từ khoá trần "mâm quay toa" thương mại. Mỗi Product đưa **tên hãng lên đầu Title** và kể theo đặc trưng riêng. Khái niệm chung chỉ ở Pillar, Product chỉ 1–2 câu dẫn + link |
| #1 vs #4 | Cả hai gắn với một hãng cẩu (Hiab / Tadano Unic) | #1 kể theo **vòng bi quay slewing bearing CSS + hệ cẩu thủy lực châu Âu** · #4 kể theo **dòng cẩu mini Nhật Tadano Unic 3,5 tấn**. Không bài nào lặp phần "mâm quay toa là gì" |
| #2 · #3 · #5 | Ba hãng Hàn Quốc cùng chủng loại | Tách theo **đặc trưng hãng + thông số định mức** (tải trọng, đường kính bàn quay, mô-men quay). Phần chung link về Pillar |
| #6 vs #7 | Cùng nhóm cẩu Trung Quốc tải lớn | #6 gộp hai hãng Zoomlion + XCMG theo dải tải; #7 kể theo Sany và tính sẵn có của phụ tùng chính hãng |

### 4.3. Việc còn lại trên Product

- [x] Rà từng trang live: Title ≤ 70 ký tự (đã rút `mam-quay-toa-cau-sany` từ 71 → 62 ký tự); Meta có CTA hotline; không chứa bảng so sánh đa hãng và pháp lý chi tiết
- [ ] Bổ sung số cốt lõi (mục 6) — hiện vẫn thiếu catalog PDF hãng
- [ ] Rà 100 từ mở bài khác nhau giữa các trang khi bổ sung số cốt lõi
- [x] Rà `/collections/mam-quay-toa-xe-tai-gan-cau`: liệt kê đủ Product theo bảng mục 4
- [x] Rà toàn bộ trang live theo v6.0 mục 10.1: đã xoá sạch `Đang cập nhật` / `CẦN BỔ SUNG` / `CẦN TẠO` / `cần xác minh` / `chờ catalog` / năm `2023`·`2025` / dòng `📌 Kinh nghiệm thực tế` rỗng
- [x] Đổi mọi internal link dạng `/collections/phu-tung-phu-kien/products/...` trong thân bài sang `/products/...`
- [ ] Đồng bộ `alt` ảnh Gallery qua API `/admin/products/{id}/images/{img_id}.json` (UI Admin đã nhập, nhưng REST API `images[].alt` còn trả `null` — rà lại khi có đợt cập nhật tiếp theo)
- [ ] Nạp Purple Cow kỹ thuật riêng cho từng Product (mục 13) khi có catalog PDF từng hãng

---

## 5. Entity & thuật ngữ riêng của cụm

Dùng thống nhất toàn cụm, không đổi nghĩa theo bài:

- **Mâm quay toa** (rotator / turntable): cụm cơ – thủy lực lắp giữa xe nền và bệ cẩu, cho phép xoay cần cẩu (thường 360°) độc lập với hướng xe, nâng hạ đúng vị trí mà không phải dịch chuyển xe.
- **Vòng bi quay** (slewing bearing): ổ quay chịu tải dọc trục + mô-men lật; chỉ tiêu cốt lõi của mâm quay (kiểu răng trong/răng ngoài, đường kính, tải trọng định mức).
- **Bàn quay / bệ quay**: mặt bích lắp cẩu, quay trên vòng bi.
- **Mô-men quay**: mô-men xoắn dẫn động bàn quay (Nm / kN·m).
- **Tốc độ quay & góc quay**: vòng/phút và phạm vi xoay (360° liên tục hay giới hạn góc).
- **Dẫn động thủy lực**: mô-tơ thủy lực + hộp giảm tốc hành tinh; áp suất làm việc (bar).
- **Hãng trong cụm:** CSS (vòng bi quay), Hiab (cẩu thủy lực châu Âu), Dongyang · Kanglim · Soosan (Hàn Quốc), Tadano Unic (Nhật, cẩu mini), Zoomlion · XCMG · Sany (Trung Quốc).

---

## 6. Thông số bắt buộc & Luật số cốt lõi của cụm (sửa 09/09/2026)

### 6.1. Chỉ tiêu cốt lõi (mini-table + bảng thông số đầy đủ — MỌI Product)

1. Tải trọng định mức / sức nâng thiết kế (tấn)
2. Đường kính bàn quay / loại vòng bi quay (kiểu răng, đường kính mm)
3. Mô-men quay (Nm / kN·m)
4. Tốc độ quay (vòng/phút) và góc quay (360° liên tục hay giới hạn)
5. Kiểu truyền động (mô-tơ thủy lực + hộp giảm tốc hành tinh / dẫn động trực tiếp)
6. Áp suất làm việc hệ thủy lực (bar) + nguồn gốc hãng

### 6.2. Luật số cốt lõi

**Chặn xuất bản** — thiếu bất kỳ số nào trong **3 số cốt lõi**: ① tải trọng định mức · ② đường kính / loại vòng bi · ③ mô-men quay ⇒ Product chưa đủ điều kiện xuất bản mới, dừng và xin dữ liệu trước khi viết.

**Không chặn xuất bản** — thiếu ④ góc & tốc độ quay ⇒ **bỏ dòng đó** khỏi bảng thông số + khai 1 dòng ở mục 16.3 của bài, vẫn xuất bài.

Không suy diễn, không nội suy từ dòng gần giống. **Không ghi "Đang cập nhật" trong bài** — mọi khoảng trống xử lý theo v6.0 mục 10.1 (bỏ dòng → bỏ khối → gỡ heading/câu dẫn/mục lục/link).

### 6.3. Bảng số cốt lõi theo dòng sản phẩm

| Dòng | ① Tải trọng định mức | ② Đường kính / loại vòng bi | ③ Mô-men quay | ④ Góc & tốc độ quay |
| --- | --- | --- | --- | --- |
| CSS slewing bearing (Hiab) | CẦN BỔ SUNG | CẦN BỔ SUNG | CẦN BỔ SUNG | CẦN BỔ SUNG |
| Dongyang | CẦN BỔ SUNG | CẦN BỔ SUNG | CẦN BỔ SUNG | CẦN BỔ SUNG |
| Kanglim | CẦN BỔ SUNG | CẦN BỔ SUNG | CẦN BỔ SUNG | CẦN BỔ SUNG |
| Tadano Unic 3,5 tấn | CẦN BỔ SUNG | CẦN BỔ SUNG | CẦN BỔ SUNG | CẦN BỔ SUNG |
| Soosan | CẦN BỔ SUNG | CẦN BỔ SUNG | CẦN BỔ SUNG | CẦN BỔ SUNG |
| Zoomlion / XCMG | CẦN BỔ SUNG | CẦN BỔ SUNG | CẦN BỔ SUNG | CẦN BỔ SUNG |
| Sany | CẦN BỔ SUNG | CẦN BỔ SUNG | CẦN BỔ SUNG | CẦN BỔ SUNG |

Nguồn hợp lệ theo thứ tự ưu tiên (v6.0 mục 10): catalog PDF hãng → ảnh thông số/biểu đồ tải → ảnh sản phẩm → website hãng → nguồn kỹ thuật tin cậy. Hai nguồn lệch nhau ⇒ ưu tiên catalog/ảnh thông số và ghi rõ cả hai trong file này. Điền ô nào thì ghi nguồn ngay bên cạnh — tên tài liệu nguồn cũng là thứ duy nhất được ghi ở chú thích chân bảng trong bài (v6.H H4.2).

**Cảnh báo trạng thái:** cả 7 dòng đang trống ⇒ **chưa dòng nào đủ điều kiện xuất bản Product mới**. Các trang đang live đã được rà sạch theo mục 4.3 và v6.0 mục 10.1. Ưu tiên lấy dữ liệu: Tadano Unic, Dongyang, Kanglim (clicks & impressions GSC cao nhất).

---

## 7. Pháp lý / tiêu chuẩn áp dụng

- Lắp mâm quay toa làm thay đổi kết cấu xe cơ giới → thuộc nhóm **cải tạo xe**, phải đăng kiểm lại theo quy định hiện hành.
- Chi tiết QCVN/NĐ/TT + quy trình hồ sơ: **do Cluster pháp lý dùng chung giữ** — `/blogs/news/phap-ly-dang-kiem-xe-cau-2026`. Cụm này **không tạo bài pháp lý riêng**.
- Trong Product/Pillar: chỉ 1–2 câu dẫn + link sang cluster pháp lý.

---

## 8. Ứng dụng theo lĩnh vực & khách hàng mục tiêu (card chuẩn của cụm)

Lĩnh vực chuẩn cho card ứng dụng **H4.10** (mỗi bài chọn 4/6/8 card, không lẻ bố cục; luân phiên 4 cặp màu theo v6.H H2):

- 🏗️ Thi công xây dựng — nâng lắp vật liệu, cấu kiện tại công trường hẹp
- ⚡ Lắp đặt thiết bị điện / trạm biến áp — đặt chính xác không phải dịch chuyển xe
- 🛣️ Hạ tầng giao thông — biển báo, lan can, hệ thống chiếu sáng
- 🏭 Bảo trì công nghiệp — thay thiết bị trong nhà xưởng, kho bãi
- 🚚 Dịch vụ cẩu thuê ngoài — đa dạng địa hình, xoay cần linh hoạt
- 🪝 Cẩu mini / cẩu tự hành — phối hợp mâm quay với cẩu Tadano Unic, Kanglim

Khách hàng mục tiêu: chủ xe tải gắn cẩu muốn nâng cấp/đóng mới, đơn vị cho thuê cẩu, nhà thầu thi công, xưởng lắp ráp xe chuyên dùng.

---

## 9. Tầng Blog / Cluster

### 9.0. Blog đã có — live (không tạo mới)

| URL | Vai | Trạng thái |
| --- | --- | --- |
| `/blogs/news/kinh-nghiem-chon-mam-quay-toa-cau-tadano-unic-3-5-tan` | Kinh nghiệm chọn mâm quay toa cẩu Tadano Unic 3–5 tấn — intent "chọn mâm quay theo tải trọng/loại cẩu" | ✅ Live — đã xoá `CẦN BỔ SUNG`, cập nhật 13/11/2026 |
| `/blogs/news/quy-trinh-lap-dat-bao-duong-mam-quay-toa-cau` | Hướng dẫn kỹ thuật lắp đặt & bảo dưỡng mâm quay toa (slewing ring): vệ sinh, định vị, siết bu-lông, khe hở sườn răng, bảo dưỡng định kỳ, dấu hiệu thay thế | ✅ Live — đã xoá `CẦN BỔ SUNG`, cập nhật 13/11/2026 |

> Quy ước: blog đã live giữ nguyên slug. Lệnh `~ssb` về lắp đặt/bảo dưỡng ⇒ cập nhật `quy-trinh-lap-dat-bao-duong-mam-quay-toa-cau`; về kinh nghiệm chọn ⇒ cập nhật `kinh-nghiem-chon-mam-quay-toa-cau-tadano-unic-3-5-tan`. **Không tạo blog trùng hai URL này.**

### 9.1. Đề xuất viết thêm (chưa tạo, chờ duyệt từng bài)

| Ưu tiên | Slug đề xuất | Vai | Giải vấn đề gì |
| --- | --- | --- | --- |
| 🔴 1 | `/blogs/news/so-sanh-mam-quay-toa-cac-hang` | Cluster so sánh đa hãng | "Mâm quay toa hãng nào tốt, khác nhau thế nào" — chưa trang nào trả lời; gỡ vai so sánh khỏi Product |
| 🟡 2 | `/blogs/news/gia-mam-quay-toa-xe-tai-gan-cau` | Cluster giá | Mặt bằng giá theo hãng/tải trọng; Product chỉ giữ CTA giá |
| 🟡 2 | `/blogs/news/mam-quay-toa-cua-nuoc-nao-tot-khong` | Blog EEAT thương hiệu | Gỡ vai "hãng này của nước nào, có tốt không" khỏi từng Product |
| 🟢 3 | `/blogs/news/mam-quay-toa-loai-nao-phu-hop-cau-mini` | Blog long-tail | Ghép nối xu hướng cẩu mini (Tadano Unic 3,5 tấn) |

*Đã loại: đề xuất "kinh nghiệm chọn mâm quay toa" (trùng intent blog live ở 9.0) và bài đăng kiểm riêng (gộp vào Cluster pháp lý dùng chung, mục 7).*

### 9.2. Duyệt từng bài

- [ ] C1 — `so-sanh-mam-quay-toa-cac-hang`
- [ ] C3 — `gia-mam-quay-toa-xe-tai-gan-cau`
- [ ] C4 — `mam-quay-toa-cua-nuoc-nao-tot-khong`
- [ ] C6 — `mam-quay-toa-loai-nao-phu-hop-cau-mini`

Giữ nguyên mã C1/C3/C4/C6 để khớp registry mục 11 — không đánh số lại. Blog chưa tạo cho tới khi Ba tick duyệt (mục 14).

---

## 10. Luật phân vai — áp cho cả Map này

| Tầng | Được nhắm | CẤM nhắm |
| --- | --- | --- |
| Pillar | "mâm quay toa là gì", "phân loại mâm quay", "cấu tạo mâm quay", thuật ngữ | Tên hãng, model, "báo giá", đặc trưng sản phẩm đơn lẻ |
| Collection | "mâm quay toa", "mua mâm quay toa", "mâm quay toa xe tải gắn cẩu" | Tên hãng đơn lẻ, thông số chi tiết từng model, viết dài như Pillar |
| Cluster so sánh (C1) | "so sánh mâm quay toa", nhiều hãng trong một bài | Giới thiệu/bán một hãng duy nhất |
| Cluster giá (C3) | "giá mâm quay toa", mặt bằng giá đa hãng | Thông số kỹ thuật chi tiết |
| Product | "{hãng} mâm quay toa {đặc trưng}" | "mâm quay toa" trần (thuộc Collection), so sánh đa hãng (C1), pháp lý chi tiết (cluster pháp lý) |

---

## 11. Registry từ khoá cụm mâm quay toa (kèm GSC 90 ngày: 15/08/2026 – 13/11/2026)

| Từ khoá | Intent | Loại trang | URL sở hữu | GSC 90 ngày (Clicks / Impr / Pos) |
| --- | --- | --- | --- | --- |
| mâm quay toa là gì · mâm quay cần cẩu là gì · rotator là gì | Thông tin | Pillar | `/pages/mam-quay-toa-can-cau` | 1 / 19 / 5,2 |
| mâm quay toa · mâm quay toa xe tải gắn cẩu · mua mâm quay toa | Thương mại | Collection | `/collections/mam-quay-toa-xe-tai-gan-cau` | 24 / 458 / 5,6 |
| mâm quay slewing bearing CSS · mâm quay toa cẩu Hiab | Giao dịch | Product | `/products/mam-quay-toa-slewing-bearing-cau-css-hiab` | 12 / 143 / 6,1 |
| mâm quay toa Dongyang | Giao dịch | Product | `/products/mam-quay-toa-dongyang` | 43 / 1.282 / 4,1 |
| mâm quay toa Kanglim | Giao dịch | Product | `/products/mam-quay-toa-kanglim` | 13 / 171 / 5,5 |
| mâm quay cẩu Tadano Unic · mâm quay toa 3,5 tấn | Giao dịch | Product | `/products/mam-quay-toa-cau-tadano-unic-3-5-tan` | 73 / 1.175 / 4,4 |
| mâm quay toa Soosan | Giao dịch | Product | `/products/mam-quay-toa-soosan` | 9 / 66 / 8,5 |
| mâm quay toa cẩu Zoomlion · mâm quay toa cẩu XCMG | Giao dịch | Product | `/products/mam-quay-toa-cau-zoomlion-xcmg` | 8 / 397 / 6,1 |
| mâm quay toa cẩu Sany | Giao dịch | Product | `/products/mam-quay-toa-cau-sany` | 2 / 415 / 5,7 |
| kinh nghiệm chọn mâm quay toa · chọn mâm quay theo tải trọng | Kinh nghiệm | Blog | `/blogs/news/kinh-nghiem-chon-mam-quay-toa-cau-tadano-unic-3-5-tan` | 4 / 112 / 4,9 |
| quy trình lắp đặt mâm quay toa · bảo dưỡng mâm quay toa · thay mâm quay toa | Hướng dẫn kỹ thuật | Blog | `/blogs/news/quy-trinh-lap-dat-bao-duong-mam-quay-toa-cau` | 12 / 185 / 5,3 |
| so sánh mâm quay toa · mâm quay toa hãng nào tốt | So sánh | Cluster | C1 — CẦN TẠO | — |
| giá mâm quay toa · báo giá mâm quay toa | Giá | Cluster | C3 — CẦN TẠO | — |
| mâm quay toa của nước nào · mâm quay toa có tốt không | EEAT hãng | Blog | C4 — CẦN TẠO | — |
| mâm quay toa cho cẩu mini | Long-tail | Blog | C6 — CẦN TẠO | — |
| lắp mâm quay toa · đăng kiểm xe gắn cẩu | Pháp lý | Cluster dùng chung | `/blogs/news/phap-ly-dang-kiem-xe-cau-2026` (cụm này không sở hữu) | — |
| {hãng} mâm quay toa {đặc trưng} | Giao dịch | Product | Theo bảng mục 4 | — |

---

## 12. Kho tài sản EEAT

| Hạng mục | Trạng thái |
| --- | --- |
| Catalog PDF từng hãng (CSS, Dongyang, Kanglim, Tadano Unic, Soosan, Zoomlion/XCMG, Sany) | CẦN BỔ SUNG |
| Ảnh thật mâm quay lắp trên xe / ảnh thông số, biểu đồ tải | CẦN BỔ SUNG — bắt buộc dùng ảnh Ba cấp, giữ logo/watermark, ALT 6–12 từ có từ khoá |
| Dự án thực tế có tên — số lượng — năm | CẦN BỔ SUNG. **Chưa có ⇒ bỏ hẳn dòng 📌 Kinh nghiệm thực tế khỏi khối chốt**, không viết chữ thay thế trong bài |
| Video lắp đặt / vận hành mâm quay | CẦN BỔ SUNG |

---

## 13. Kho Purple Cow cụm mâm quay toa

| Model / URL | Điểm đáng kể lại | Bằng chứng | Đối thủ có nói chưa |
| --- | --- | --- | --- |
| (trống — nạp dần bằng tham số `/p!`) | | | |

Mỗi Product một Purple Cow khác nhau (v6.0 mục 9). Nguồn ưu tiên: đặc tính kỹ thuật độc nhất (tải trọng / vòng bi / mô-men) → cấu hình chỉ VietNhatCorp lắp → **dịch vụ** (đăng kiểm trọn gói 7–15 ngày · đào tạo vận hành tận nơi · vay 70–80% tới 60 tháng) → dự án thực tế có tên/số lượng/năm.

Kho còn trống ⇒ khi viết bài, lấy Purple Cow từ **nguồn dịch vụ** vì nguồn này luôn có thật. Vẫn không đủ 4 tiêu chí ⇒ **bỏ khối Purple Cow khỏi bài** và ghi "cần bổ sung dữ liệu khác biệt" **chỉ ở mục 16.3**. Không viết câu sáo ("giá tốt nhất", "chất lượng hàng đầu").

---

## 14. Nguyên tắc trạng thái

- Slug hiện hữu: **giữ nguyên** — đang live, Ba đã đặt.
- Product/Blog đã live: chỉ sửa theo checklist mục 4.3.
- Blog mục 9.1: chưa tạo cho tới khi Ba tick duyệt.
- Dòng sản phẩm mục 2: khoá, không bàn lại.
- Danh sách mục 3, 4: mở, thêm dòng bằng lệnh `~~6.3` kèm ngày.
- Dữ liệu kỹ thuật (mục 6) và Purple Cow (mục 13): thiếu thì xử lý theo **mục 0.0.1** — bỏ dòng/bỏ khối + khai ở 16.3 của bài, **không** ghi chú trong thân bài, không suy diễn.

---

## 15. Nhật ký

- **13/11/2026 — v6.3.6.** Rà soát và tối ưu SEO toàn cụm mâm quay toa trên `vietnhatcorp.net` theo v6.0 + v6.H (6.H.5). ① Kéo dữ liệu GSC 90 ngày (15/08/2026 – 13/11/2026) cập nhật vào bảng Registry mục 11; xác nhận URL cũ `mam-quay-toa-cau-tadano-3-5-tan-shinil` đã 301 về `mam-quay-toa-cau-tadano-unic-3-5-tan`. ② Làm sạch 100% chuỗi cấm (`Đang cập nhật`, `CẦN BỔ SUNG`, `CẦN TẠO`, `cần xác minh`, `chờ catalog`), bỏ năm `2023`/`2025` trên toàn bộ Product, Collection, Pillar và 2 Blog. ③ Đổi toàn bộ internal link sai canonical `/collections/phu-tung-phu-kien/products/...` trong thân bài về `/products/...`; rút Title `mam-quay-toa-cau-sany` xuống 62 ký tự (≤ 70); bổ sung đủ 5–6 Tags/sản phẩm. ④ Bổ sung 2 ảnh CDN kèm alt cho Pillar `/pages/mam-quay-toa-can-cau`; chuẩn hoá thêm 2 Product ngoài nhóm xe tải gắn cẩu (`mam-quay-toa-cau-banh-xich-kobelco-sumitomo-hitachi-ihi` và `mam-quay-toa-cau-thap-zoomlion-tc7035-16`, bỏ `Default Title`); khai báo lại Sitemap lên GSC. ⑤ Ghi nhận mục 4.3: cần đồng bộ `images[].alt` qua REST API `/images/{img_id}.json` ở đợt sau do API `haravan_get_product` vẫn trả `null`.
- **09/09/2026 — v6.3.5.** Đồng bộ với v6.0 (mục 10.1 · C1–C22) và v6.H 6.H.3 (P1–P22). ① Bỏ thẻ `<aside>` đầu file, thay bằng blockquote. ② Mục 0.0: cập nhật tham chiếu C1–C22 · P1–P22, thêm dòng tương thích tên mục cũ, sửa luật xung đột thành **ba tầng** (bản cũ ghi nhầm "v6.0 thắng ở quy tắc trình bày"), xoá dòng "chưa đăng ký bộ nạp" — đã đăng ký từ LOAD-2.1, tên file trên gist nay là `mrtu-v6.3-mam-quay-toa.md`. ③ Thêm **mục 0.0.1 Luật khuyết dữ liệu** với bảng ánh xạ và danh sách chuỗi cấm. ④ Mục 1: thêm **luật đường dẫn canonical** — mọi link dùng `/products/{slug}`, cấm nhánh `/collections/phu-tung-phu-kien/products/...` (URL trùng nội dung); đưa Zoomlion/XCMG và Sany vào danh sách slug chính. ⑤ Mục 4: bảng chuyển sang cột URL canonical, thêm cặp #6–#7 vào 4.2, thêm 2 việc vào 4.3. ⑥ Mục 6: đổi "Luật 4 con số" → **Luật số cốt lõi** — chỉ ① ② ③ chặn xuất bản, ④ góc & tốc độ quay thiếu thì bỏ dòng, không chặn; **xoá câu ra lệnh ghi "Đang cập nhật"**; bảng 6.3 thêm dòng Zoomlion/XCMG và Sany; thêm cảnh báo trạng thái. ⑦ Mục 9.1: sửa bảng bị vỡ do dòng chú thích "(BỎ — …)" nằm giữa bảng, chuyển thành dòng chú thích dưới bảng; 9.2 bỏ mục C5 đã gộp. ⑧ Mục 11: registry chuyển Zoomlion/Sany sang URL canonical, thêm C6. ⑨ Mục 12: bỏ chỉ dẫn ghi "CẦN BỔ SUNG DỰ ÁN THỰC TẾ" trong khối chốt → nay bỏ hẳn dòng. ⑩ Mục 13: kho về trạng thái trống + đường thoát Purple Cow từ nguồn dịch vụ. ⑪ Mục 14: bỏ câu cho phép ghi "Đang cập nhật". Không đổi slug đang live, không đổi sitemap.
- **03/09/2026 — v6.3.4.** Viết lại Pillar `/pages/mam-quay-toa-can-cau` theo v6.H: bảng chuẩn H4.2, card phân loại H4.10, mục lục H4.14, FAQ H4.16, CTA giữa + khối chốt H6. Sửa link 404 `/collections/mam-quay-toa-xe-cau` → `/collections/mam-quay-toa-xe-tai-gan-cau`; sửa link gộp 404 soosan-kanglim-dongyang → 3 link riêng.
- **03/09/2026 — v6.3.3.** Thêm Product live `mam-quay-toa-cau-zoomlion-xcmg` và `mam-quay-toa-cau-sany` vào mục 2, 4, 11; thêm blog live `kinh-nghiem-chon-mam-quay-toa-cau-tadano-unic-3-5-tan` vào mục 9.0 và registry; xoá đề xuất trùng intent. Collection viết lại bản `~sscl` ngày 03/09/2026.
- **03/09/2026 — v6.3.2.** Bổ sung blog live `/blogs/news/quy-trinh-lap-dat-bao-duong-mam-quay-toa-cau` vào mục 9.0; registry thêm nhóm từ khoá lắp đặt/bảo dưỡng/thay mâm quay toa.
- **03/09/2026 — v6.3.1.** Tạo bản con đầu tiên từ sitemap dự thảo 03/09/2026, nguồn 7 URL Ba cung cấp. Cấu trúc theo v6.2-soosan; bổ sung mục 5 Entity & thuật ngữ, mục 6 luật số riêng của cụm, mục 8 card ứng dụng chuẩn.
