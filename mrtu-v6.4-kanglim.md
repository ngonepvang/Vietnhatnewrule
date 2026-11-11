# Instruction v6.4 — Xe tải gắn cẩu Kanglim (bản con của v6.0) — Site Map / Audit Baseline
Phiên bản: v6.4.0 · Cập nhật 11/11/2026
Nguồn đối chiếu: crawl 11/11/2026 — `/collections/kanglim` (đủ 2 trang lưới sản phẩm) · Product `xe-tai-chenglong-m3-gan-cau-kanglim-7-tan-ks1256g` · Product `dongfeng-b180-gan-kanglim-ks1056-5-tan` · Blog `/blogs/news/kanglim-ks1256g-ii-6-tan`. Chưa có dữ liệu GSC / GA4 / tồn kho.

> **Bản nháp chờ Mr Tú duyệt.** Slug đang live ở mục 4 và 6.1 giữ nguyên. Slug mới ở mục 6.2 **chưa khoá** cho tới khi tick duyệt ở 6.3. Mọi gộp / 301 ở trạng thái **chờ GSC** — chưa làm gì trên website.

## 0.0. Vai của bản này

- Đây là **Instruction con v6.4**, dành riêng cho cụm **xe tải gắn cẩu Kanglim** (hãng cẩu Kanglim gắn trên các xe nền). **Site Map nằm ngay trong bản này** (mục 3 → 6).
- Kế thừa 100% **`mrtu-v6.0-core.md` (v6.0.11)** — tầng nội dung, và **`Haravan.md` (v6.H)** — tầng trình bày.
- Bản này **không** đặt quy tắc viết, trình bày hay CTA riêng. Chỉ giữ: sitemap, slug, mã model, registry, luật phân vai, luật số cốt lõi, bảng audit. Mọi thứ về màu · HTML · CTA · bảng · khối chốt · số chữ · quy cách file đầu ra: **theo v6.H**.
- Xung đột: trình bày → v6.H thắng · intent / vai URL / registry / dữ liệu / luật khuyết dữ liệu → v6.0 thắng · slug / mã model / sitemap → bản này thắng.
- Ranh giới với bản con khác (không ghi đè quyết định của nhau):
  - **6.2 Soosan** — Collection tải trọng, Pillar chung, Cluster pháp lý là **dùng chung**, 6.4 không sở hữu.
  - **6.3 Mâm quay toa** — `/products/mam-quay-toa-kanglim` và bài so sánh mâm quay toa thuộc 6.3.
  - **6.6 Cẩu cũ** — Product xe đã qua sử dụng Hyundai HD320 gắn Kanglim KS5206 thuộc 6.6 (6.6 đã ghi "giữ vai Product theo v6.4").
- Không tồn tại bản Instruction Kanglim nào khác.
- Lệnh cập nhật: `~~6.4` cho sitemap / slug / model / registry / audit · `~~6.0` cho quy tắc nội dung · `~~6.H` cho trình bày.
- Mọi lần sửa bản này: trả về **nguyên file** để dán đè (v6.0 mục 19).

### 0.0.1. Luật khuyết dữ liệu — đọc trước khi viết bài cụm này

Bản con **được phép** ghi "CẦN BỔ SUNG" / "CẦN TẠO" trong chính file này (đây là sổ theo dõi). Các chuỗi đó **không bao giờ chảy vào bài viết**.

| Trong file này ghi | Khi viết bài thì làm gì |
| --- | --- |
| Ô "CẦN BỔ SUNG" trong bảng mục 8.1 | Bỏ DÒNG chỉ tiêu đó khỏi bảng thông số + 1 dòng ở mục 16.3 |
| Thiếu quá nửa chỉ tiêu của một bảng / khối | Bỏ CẢ KHỐI + gỡ heading, câu dẫn, dòng mục lục, link trỏ tới nó |
| "CẦN TẠO" ở registry mục 9 / đề xuất mục 6.2 | Trong bài vẫn đặt link theo slug đã chốt, **không ghi chú cạnh link**; trạng thái URL khai ở 16.3 |
| Kho Purple Cow mục 12 còn trống | Lấy Purple Cow từ nguồn dịch vụ; vẫn không đủ 4 tiêu chí → bỏ khối, khai 16.3 |
| Mục 11 ghi một nhận định hãng/đại lý **chưa có bằng chứng** | Không đưa nhận định đó vào bài cho tới khi có bằng chứng |

Cấm tuyệt đối trong thân bài: "Đang cập nhật" · "CẦN BỔ SUNG" · "CẦN TẠO" · "cần xác minh" · "chờ catalog" · "theo Map" · "N/A" · `[ ]` · dấu `—` thay cho số · ô bảng trống. Chi tiết: v6.0 mục 10.1.

---

## 0. Phạm vi cụm

Không ghi số lượng ở đây. Nguồn duy nhất là các danh sách bên dưới — muốn biết bao nhiêu thì đếm dòng.

| Hạng mục | Nguồn duy nhất | Ghi chú |
| --- | --- | --- |
| Product trong lưới Collection | mục 4 | Handle lấy từ lưới sản phẩm, **không** lấy từ bảng trong thân Collection (xem 4.4) |
| Product ngoài lưới thuộc cụm | mục 4 (dòng ngoài lưới) | Xe cũ — thuộc 6.6 |
| Model cẩu | mục 2 | Quan sát trên website, chờ duyệt khoá |
| Pillar chung | `/pages/xe-tai-gan-cau` | Dùng chung toàn ngành cẩu, không nhắm hãng |
| Pillar hãng | mục 3 | Đề xuất — chờ quyết định D1 |
| Collection hãng | `/collections/kanglim` | Cần viết lại, xem mục 5 |
| Collection tải trọng | mục 3 | Dùng chung đa hãng (6.2) |
| Blog / Cluster hiện có | mục 6.1 | |
| Blog / Cluster / Page đề xuất | mục 6.2 | Chờ duyệt, chưa tạo |
| Cluster pháp lý | `/blogs/news/phap-ly-dang-kiem-xe-cau-2026` | Dùng chung, cụm này không sở hữu |

## 0.1. Luật số đếm mở (áp theo v6.0 mục 15)

- Danh sách Product · Blog · Collection của cụm này là **danh sách mở**, sẽ còn tăng.
- **Số lượng không được khai ở bất kỳ đâu ngoài chính danh sách liệt kê.** Không cột đếm, không câu tổng kết số.
- **Cấm** số đếm model / cấu hình trong Title · Meta · Slug · H2 · 100 từ mở bài · CTA.
- Câu đúng: "dải cẩu từ 5 đến 15 tấn", "nhiều lựa chọn xe nền". Câu sai: "12 cấu hình Kanglim", "trọn bộ 15 mẫu".
- **Cấm năm trong H2 / tiêu đề khối của Collection** (Collection evergreen — v6.0 mục 10). Hiện đang có "…Đang Có Tại Kho 2026" và "Nhận Báo Giá Xe Cẩu Kanglim 2026" → bỏ năm.

---

## 1. Định danh cụm & quy ước slug

**Định nghĩa chuẩn dùng lại toàn cụm (1 câu):** Cẩu Kanglim là dòng cần cẩu thủy lực gắn trên xe tải của hãng Kanglim (Hàn Quốc), hệ mã KS, được VietNhatCorp lắp trên các xe nền Dongfeng, Chenglong, UD Truck và Isuzu.

- Xuất xứ "Hàn Quốc" lấy từ bài blog live của VietNhatCorp. Năm thành lập, số quốc gia hiện diện, chứng chỉ ISO — **chưa có nguồn**, không đưa vào bài (xem mục 11).

**Slug đang live — giữ nguyên, không đổi** (v6.6 cũng ghi: không đổi slug chỉ để đẹp). Toàn bộ handle ở mục 4 là handle **canonical lấy từ lưới Collection**.

**Luật đường dẫn canonical** (đồng bộ 6.3): trong mọi nội dung **chỉ dùng dạng `/products/{handle}`**. Lưới Collection của theme xuất dạng `/collections/kanglim/products/{handle}` — không dùng dạng này làm link trong bài.

**Khung slug bài mới (đề xuất, chưa khoá):**

- Product mới: `/products/{xe-nen}-gan-cau-{model}-{X}-tan` (đồng khung 6.2, không chèn chữ `kanglim`, mã `KS…` đã nhận diện hãng).
- Blog hub model mới: `/blogs/news/cau-kanglim-{model}-{X}-tan`.
- Cluster: `/blogs/news/{chu-de}-kanglim`.
- Page hãng: `/pages/cau-kanglim`.

---

## 2. Mã model quan sát trên website (chờ duyệt khoá)

`KS1056` · `KS1256G` · `KS1256G-II` · `KS2056T-S` · `KS2825` · `KS3105` · `KS5206` · `KS5206-I`

⚠️ Chưa khoá. Ba chỗ cần xác nhận trước khi khoá bằng `~~6.4`:

1. **KS1256G và KS1256G-II là một hay hai model?** Product #4 ghi "7 tấn KS1256G" nhưng bảng thông số bên trong ghi "KS1256G II"; blog ghi KS1256G-II = 6,6 tấn. Collection gộp "KS1256G / KS1256G-II ≈ 6,6–7 tấn".
2. **KS5206 và KS5206-I:** Collection ghi `KS5206-I` cho Dongfeng KL340, nhưng handle và tiêu đề trang ghi `KS5206`. Hậu tố "-I" có phải đời cẩu khác không?
3. **Cách viết hậu tố:** `KS2056T-S` (Collection) · `KS2056T/S` (Product #5) · `KS2056T` / `KS2056` (Product #6, tag) · `KS1056T/S` (đầu mục đặc tính trong Product #1). Chốt **một** cách viết cho toàn cụm sau khi có catalogue.

Mã model mới chỉ được thêm bằng lệnh `~~6.4`, kèm đủ 3 số cốt lõi ở mục 8.

---

## 3. Tầng trên

| Tầng | URL | Vai | Trạng thái |
| --- | --- | --- | --- |
| Pillar chung | `/pages/xe-tai-gan-cau` | Tổng quan toàn ngành, không nhắm hãng | ✅ Giữ — dùng chung |
| Pillar hãng | `/pages/cau-kanglim` | Kiến thức hãng: là gì · xuất xứ · cách đọc mã KS · hub link xuống cụm | 🆕 CẦN TẠO — chờ D1 |
| Collection hãng | `/collections/kanglim` | Danh mục điều hướng mua cẩu Kanglim | ✏️ Viết lại — mục 5 |
| Collection tải trọng | `/collections/xe-tai-gan-cau-5-tan` | Đa hãng | ✅ Giữ — không sở hữu |
| Collection tải trọng | `/collections/xe-tai-gan-cau-7-8-tan` | Đa hãng | ✅ Giữ — không sở hữu |
| Collection tải trọng | `/collections/xe-tai-gan-cau-10-13-tan` | Đa hãng | ✅ Giữ — không sở hữu |
| Collection tải trọng | `/collections/xe-tai-gan-cau-15-tan` | Đa hãng | ✅ Giữ — không sở hữu |
| Cluster pháp lý | `/blogs/news/phap-ly-dang-kiem-xe-cau-2026` | Dùng chung mọi hãng | ✅ Giữ — không tạo bài pháp lý riêng cho Kanglim |
| Cluster đa hãng | `/blogs/news/so-sanh-cau-15-tan-everdigm-kanglim-dy-soosan` | So sánh 15 tấn nhiều hãng | ✅ Giữ — không sở hữu, chỉ link |

**Xếp nhóm Collection tải trọng** (Product thuộc nhóm nào thì gán đúng nhóm đó, ngoài `/collections/kanglim`):

| Nhóm | Product (theo # ở mục 4) |
| --- | --- |
| 5 tấn | #1 |
| 7–8 tấn | #2 · #3 · #4 · #5 · #6 |
| 10–13 tấn | #7 · #8 · #9 · #10 · #11 |
| 15 tấn | #12 · #13 · #14 · #15 · và Product xe cũ HD320 (6.6 đã ghi gán thêm) |

---

## 4. Tầng Product (danh sách mở)

Handle lấy từ lưới `/collections/kanglim` (trang 1 và 2), crawl 11/11/2026. Cột "Đã thấy" chỉ ghi điều **đã đọc trực tiếp**; dòng nào ghi "chưa crawl chi tiết" = mới thấy tiêu đề trên lưới.

| # | Handle (`/products/...`) | Xe nền · Cẩu | Đã thấy | Quyết định |
| --- | --- | --- | --- | --- |
| 1 | `dongfeng-b180-gan-kanglim-ks1056-5-tan` | Dongfeng B180 · KS1056 | **Đã đọc.** Meta ghi "mẫu mới nhất 2022", thân bài ghi "ra mắt năm 2023". Trường Thương hiệu = Dongfeng. Giá = 0₫. "Giá cạnh tranh" không có số. Mục ứng dụng liệt kê 8 ngành chung chung (đóng tàu, sân khấu, khai thác mỏ…). Link chéo sang slug Soosan / Everdigm khác Map 6.2 / 6.1. Có đủ số cẩu (mục 8.1) | ✏️ Viết lại |
| 2 | `cau-tu-hanh-kanglim-ks1256g-ii-6-6-tan-thong-so-ung-dung` | Kanglim KS1256G-II (cẩu rời) | Chưa crawl chi tiết. Tiêu đề kiểu blog ("Thông Số Kỹ Thuật & Ứng Dụng Chi Tiết"), **cùng intent** với blog `kanglim-ks1256g-ii-6-tan` | ⚠️ Gộp hoặc tách — chờ D2 |
| 3 | `danh-gia-xe-cau-dongfeng-b180-kanglim-ks1256g-ii-2026` | Dongfeng B180 · KS1256G-II | Chưa crawl chi tiết. Tiêu đề kiểu blog ("Đánh giá … Chất Lượng, Thông Số & Giá"), handle có `danh-gia` và năm | ✏️ Viết lại, giữ handle |
| 4 | `xe-tai-chenglong-m3-gan-cau-kanglim-7-tan-ks1256g` | Chenglong M3 4×2 · KS1256G(-II) | **Đã đọc.** Giá = 0₫. Lọt chữ nội bộ "Minh Hà Auto (hoặc Vietnhatcorp)". Có lời chuyên gia gán tên "Nguyễn Văn A" và "báo cáo Hiệp hội Vận tải Việt Nam" không nguồn. "Một khách hàng ở Bắc Ninh" không tên. Đoạn "Mua hàng ở đâu" nhắc cẩu bánh lốp Tadano / XCMG / Zoomlion — lạc chủ đề. Số cẩu **mâu thuẫn** với blog (mục 8.1). Thiếu FAQ, CTA nút, phần giới hạn | ✏️ Viết lại — **gỡ ngay** các câu bịa nguồn (đợt 0) |
| 5 | `chenglong-gan-kanglim-ks2056t-s` | Chenglong (3 chân) · KS2056T/S | Chưa crawl chi tiết. Tiêu đề kiểu blog ("Đánh giá và Thông số kỹ thuật"); tiêu đề không ghi mã xe nền | ✏️ Viết lại |
| 6 | `xe-tai-isuzu-fvz-gan-cau-kanglim-ks2056-8-tan` | Isuzu FVZ · KS2056(T) | Chưa crawl chi tiết. Tiêu đề có đuôi "\| Vietnhatcorp.net" thừa; mã cẩu viết khác #5 | ✏️ Viết lại |
| 7 | `ud-truck-4-chan-lap-cau-kanglim` | UD Truck 4 chân · cẩu Kanglim 12 tấn | Chưa crawl chi tiết. **Không ghi mã cẩu** ở tiêu đề lẫn Collection. Tiêu đề sáo ("Mạnh mẽ, Bền bỉ vượt trội") | ✏️ Viết lại — chờ D4 |
| 8 | `xe-cau-tu-hanh-12-tan-l315-lap-ks2825` | Dongfeng L315 · KS2825 | Chưa crawl chi tiết. Collection gọi "Dongfeng 315", handle gọi "L315" — thống nhất | ✏️ Viết lại |
| 9 | `xe-dongfeng-5-chan-cau-kanglim-12-tan` | Dongfeng 5 chân · cẩu Kanglim 12 tấn | Chưa crawl chi tiết. Tiêu đề hứa "& Giá"; **không ghi mã cẩu** | ✏️ Viết lại — chờ D4 |
| 10 | `xe-tai-gan-cau-chenglong-kanglim-12-tan-ks2825` | Chenglong LZ1310M5 · KS2825 | Chưa crawl chi tiết. Tiêu đề sáo ("Sức Mạnh Vượt Trội") | ✏️ Viết lại |
| 11 | `dongfeng-4-chan-cau-he-ks3105-13-tan` | Dongfeng 4 chân 340HP · KS3105 | Chưa crawl chi tiết. Tiêu đề ghi "**Hoàng Huy**" (cùng lỗi 6.2 đã chốt bỏ). Collection ghi "tầm 25 m" — chưa nguồn | ✏️ Viết lại — giữ handle |
| 12 | `xe-cau-15-tan-chenglong-gan-kanglim-ks5206` | Chenglong LZ1340 · KS5206 | Chưa crawl chi tiết. Tiêu đề sáo ("Sức Mạnh của nhà Vô địch") | ✏️ Viết lại |
| 13 | `xe-cau-15-tan-kl340-gan-ks5206` | Dongfeng KL340 · KS5206(-I) | Chưa crawl chi tiết. Collection ghi "KS5206-I", handle / tiêu đề ghi "KS5206 I" — chờ mục 2 điểm 2 | ✏️ Viết lại |
| 14 | `xe-ud-quester-gan-kanglim-ks5206-15-tan` | UD Quester 8×4 · KS5206 | Chưa crawl chi tiết. **Không có trong bảng của Collection** | ✏️ Viết lại |
| 15 | `xe-tai-dongfeng-gan-cau-kanglim-ks5206` | Dongfeng L315 (theo ALT ảnh) · KS5206 | Chưa crawl chi tiết. Tiêu đề sáo + **không ghi xe nền** ("Sự lựa chọn hàng đầu cho khách hàng Việt Nam"). Tên file ảnh chứa `ks2805` — nghi ảnh của #8 (KS2825). **Không có trong bảng của Collection** | ✏️ Viết lại — đối chiếu ảnh |
| — | `xe-hyundai-hd320-2012-cau-kanglim-ks5206-15-tan-cu` | Hyundai HD320 đời 2012 · KS5206 (đã qua sử dụng) | Thuộc **6.6** | ✅ Giữ vai Product — 6.4 chỉ link |

Chưa dòng nào đủ căn cứ để **Xoá**. Không Product nào trùng cặp (xe nền, cẩu) với Product khác. Không đề xuất 301 Product khi chưa có GSC.

### 4.1. Quy tắc link — bám sát Map

- Nội dung luôn link theo **đúng handle trong bảng mục 4 / slug trong mục 6.2**, không phụ thuộc trạng thái live.
- Mọi Product trong mục 4 đều phải được liệt kê và link từ `/collections/kanglim`. Hiện **thiếu** #14, #15 và #6 trong bảng thân Collection.
- Link chéo sang cụm khác dùng đúng slug trong Map của cụm đó (6.1, 6.2). Hiện #1 đang link tới `xe-cau-tu-hanh-5-tan-m3-gan-soosan-scs525` — khác slug Map 6.2 (`chenglong-m3-gan-cau-scs525-5-tan`).
- Product chưa có URL thật: giữ link theo Map, **không ghi chú cạnh link**; trạng thái khai ở 16.3.
- Không đổi slug trong nội dung để "chờ live". Slug cần đổi → sửa Map trước.

### 4.2. Cặp dễ ăn thịt nhau — phải tách góc kể

| Nhóm | Điểm trùng | Cách tách |
| --- | --- | --- |
| #7 · #8 · #9 · #10 (KS2825 / 12 tấn) | Cùng cẩu | Mỗi bài kể theo **xe nền** (số trục, cabin, tải thùng, hộp số). Phần cẩu 1–2 câu + link hub K1 |
| #12 · #13 · #14 · #15 (KS5206 / 15 tấn) | Cùng cẩu | Như trên. #13 = cabin mới KL340, #15 = L315 (nêu rõ đời cabin trong 100 từ đầu). Phần cẩu link hub K2 |
| #5 · #6 (KS2056) | Cùng cẩu | Tách theo hãng xe nền Chenglong / Isuzu. Phần cẩu link hub K7 |
| #2 · #3 · #4 + blog KS1256G-II | Cùng cẩu, **và #2 trùng intent trực tiếp với blog** | Blog = hub kỹ thuật. #2 = mua cẩu rời. #3, #4 kể theo xe nền (Dongfeng B180 / Chenglong M3) |
| Cụm Kanglim ↔ cụm Soosan (6.2) | Cùng xe nền: Dongfeng L315, KL340, Chenglong LZ1340, UD Quester | **Không copy đoạn mô tả xe nền giữa hai hãng cẩu.** Mỗi trang kể xe nền theo góc ghép với cẩu của chính nó |

### 4.3. Việc còn lại trên Product

- [ ]  **Đợt 0:** #4 — gỡ chữ "Minh Hà Auto (hoặc Vietnhatcorp)", lời chuyên gia "Nguyễn Văn A", "báo cáo Hiệp hội Vận tải", lời khách Bắc Ninh không tên, đoạn nhắc cẩu bánh lốp
- [ ]  Mọi Product: **Price = số thật, không để 0** (v6.0 mục 11–12). Đã thấy 0₫ ở #1 và #4; chưa kiểm các Product còn lại
- [ ]  #11: bỏ "Hoàng Huy" khỏi Title
- [ ]  #1: thống nhất năm (2022 / 2023) hoặc bỏ năm; sửa trường Thương hiệu
- [ ]  Đưa Title #3, #5, #6, #7, #9, #10, #12, #13, #14, #15 về dạng Product: `{xe nền + mã} gắn cẩu Kanglim {mã cẩu} {X} tấn` — bỏ "Đánh giá", "Mạnh mẽ", "Vượt trội", "Vô địch", "hàng đầu", "| Vietnhatcorp.net"
- [ ]  Rà toàn bộ Product theo v6.0 mục 10.1: không còn "Đang cập nhật" / ô trống / ghi chú nội bộ
- [ ]  Chuẩn hoá trường Vendor / Chủng loại: #1 ghi Thương hiệu = Dongfeng, #4 ghi Thương hiệu = Kanglim, Chủng loại = Chenglong — hai Product đảo nghĩa nhau. Chốt theo v6.0 mục 12
- [ ]  Nạp Purple Cow riêng cho từng Product (mục 12) — hiện trống
- [ ]  Bổ sung số cốt lõi (mục 8) cho mọi model còn "CẦN BỔ SUNG"

### 4.4. Link sai trong bảng thân Collection — sửa ngay (đợt 0)

Bảng "Toàn Bộ Dòng Cẩu Kanglim…" đang trỏ tới handle **không trùng handle của lưới**. Đã thử mở 2 link (dòng 1 và dòng 11): cả hai báo lỗi client. Link cũ dạng `…-5-tan-ks1056` thì còn chuyển hướng về handle đúng — tức Haravan có 301 cho một số handle cũ nhưng không có cho nhóm này. Kiểm toàn bộ trước khi sửa.

| Link đang đặt trong bảng Collection (`/products/…`) | Handle đúng (mục 4) |
| --- | --- |
| `xe-cau-tu-hanh-5-tan-mau-dongfeng-b180-gan-kanglim-5-tan-6-dot-ks1056` | #1 `dongfeng-b180-gan-kanglim-ks1056-5-tan` |
| `cau-tu-hanh-kanglim-ks1256g-ii-6-6-tan-thong-so-ky-thuat-ung-dung-chi-tiet` | #2 `cau-tu-hanh-kanglim-ks1256g-ii-6-6-tan-thong-so-ung-dung` |
| `xe-cau-dongfeng-b180-gan-cau-kanglim-ks1256g-ii-doi-2026` | #3 `danh-gia-xe-cau-dongfeng-b180-kanglim-ks1256g-ii-2026` |
| `xe-tai-chenglong-m3-gan-cau-kanglim-7-tan-ks1256g` | #4 — **đúng, giữ** |
| `xe-cau-tu-hanh-8-tan-chenglong-gan-kanglim-ks2056t-s-danh-gia-va-thong-so-ky-thuat` | #5 `chenglong-gan-kanglim-ks2056t-s` |
| `ud-truck-4-chan-lap-cau-kanglim-12-tan-manh-me-ben-bi-vuot-troi` | #7 `ud-truck-4-chan-lap-cau-kanglim` |
| `xe-cau-tu-hanh-12-tan-dongfeng-315-lap-kanglim-ks2825` | #8 `xe-cau-tu-hanh-12-tan-l315-lap-ks2825` |
| `xe-dongfeng-5-chan-gan-cau-kanglim-12-tan-thong-so-ky-thuat-gia` | #9 `xe-dongfeng-5-chan-cau-kanglim-12-tan` |
| `xe-tai-gan-cau-12-tan-suc-manh-vuot-troi-cua-chenglong-lz1310m5-va-cau-kanglim-ks2825` | #10 `xe-tai-gan-cau-chenglong-kanglim-12-tan-ks2825` |
| `xe-tai-gan-cau-13-tan-can-dai-nang-ha-hieu-qua-voi-cau-kanglim-ks-3105-tam-vuon-25-met` | #11 `dongfeng-4-chan-cau-he-ks3105-13-tan` |
| `xe-cau-tu-hanh-15-tan-chenglong-lz1340-gan-cau-kanglim-ks5206` | #12 `xe-cau-15-tan-chenglong-gan-kanglim-ks5206` |
| `xe-cau-tu-hanh-15-tan-mau-dongfeng-kl340-gan-cau-kanglim-ks5206-i-nang-cap-manh-me` | #13 `xe-cau-15-tan-kl340-gan-ks5206` |

Ba Product có trong lưới nhưng **không có** trong bảng: #6, #14, #15.

---

## 5. Collection `/collections/kanglim` — audit nội dung

**Tiêu đề / Meta hiện tại:** `<title>` chỉ ghi "KANGLIM – Vietnhatcorp.net"; meta description dài hơn nhiều so với khung 130–160 ký tự và **không có CTA hotline**. Viết lại cả hai theo v6.0 mục 11 (Title ≤ 70 ký tự; Meta 130–160 ký tự, có "Gọi 0918 666 480…"). Dòng "Cập nhật lần cuối: 29/05/2026" đã cũ.

**Độ dài:** thân bài hiện ước tính vượt khung Collection 300–800 từ (ước lượng, chưa đếm máy) vì kiêm cả vai Pillar, Cluster giá, Cluster so sánh và bảng thông số.

| Khối hiện có | Vấn đề | Xử lý | Chuyển về |
| --- | --- | --- | --- |
| Intro | "hàng đầu", "từ 1957", "hơn 80 quốc gia" không nguồn; chỉ nhắc Dongfeng / Chenglong / UD, bỏ Isuzu dù có Product | Giữ 2–3 câu đúng vai danh mục: là gì · dành cho ai. Bỏ ba nhận định chưa nguồn | — |
| "Kanglim là thương hiệu gì? Tại sao được chọn?" + 4 thẻ | Vai Pillar. "Tuổi thọ 15–20 năm", "hàn robot", "ISO" không nguồn | **Cắt** khỏi Collection | Pillar hãng `/pages/cau-kanglim` |
| Bảng "Toàn Bộ Dòng Cẩu Kanglim…" | Link sai (4.4); hai cột Tầm với / Đốt cần gần như toàn dấu `—` (vi phạm 10.1); H2 mang năm; thiếu #6 #14 #15 | **Giữ dạng bảng điều hướng** 3 cột: Xe nền + cẩu · Tải · Link. Bỏ hai cột trống, bỏ năm | — |
| "Hướng dẫn chọn theo nhu cầu" | Vai Cluster tư vấn | Thu còn vài dòng điều hướng theo nhóm tải + 1 link | Cluster K6 |
| "Ứng dụng phù hợp" 4 thẻ | "Nông nghiệp… container lạnh" không có căn cứ trong dữ liệu | Giữ tối đa 3–4 thẻ có căn cứ (mục 10) | — |
| "Thông số so sánh nhanh" | **Số sai / mâu thuẫn với Product:** KS1056 ghi "~10 m" ↔ Product ghi 15,5 m; KS1256G(-II) ghi "~12 m" ↔ blog và Product ghi 18,7 m; KS2056T-S, KS2825, KS5206 ghi số tầm với chưa có nguồn. Collection không được nhồi thông số | **Xoá cả khối** | Hub model K1, K2, K7, blog KS1256G-II; Product |
| "Nhà phân phối chính hãng Kanglim" + 6 bullet | "Hơn 15 năm" (chuẩn VietNhatCorp: thành lập 2013, hơn 10 năm); "nhập khẩu trực tiếp từ Hàn Quốc", "đào tạo tại nhà máy Kanglim", "hậu mãi trọn đời" không bằng chứng | Thay bằng khối chuẩn "Tại sao chọn VietNhatCorp" (v6.H). Bỏ các câu thiếu bằng chứng (mục 11) | — |
| FAQ — giá năm 2026 | Vai Cluster giá | Rút còn 1–2 câu + link | Cluster K3 |
| FAQ — KS5206 và KS2825 khác nhau | Vai Cluster so sánh | Rút + link | Cluster K4 |
| FAQ — đăng kiểm "QCVN 7:2012/BLĐTBXH" | Pháp lý chi tiết không ở Collection. 6.6 ghi cluster pháp lý dùng QCVN 09:2024 — **đối chiếu trước khi nhắc lại**, không tự khẳng định | **Cắt**, chỉ link | Cluster pháp lý dùng chung |
| FAQ — vay "12–60 tháng" | Lệch khung chuẩn | Dùng khung chuẩn "vay 70–80% tới 60 tháng" | — |
| FAQ — giao xe "7 ngày / 15–45 ngày" | Không nguồn | Bỏ | — |
| FAQ còn lại | — | Đổi sang góc Collection (v6.0 mục 6.4): nên chọn dòng nào · ngân sách · xe nền nào lắp được | — |
| CTA + khối chốt | Khối chốt chưa theo biến thể "so sánh các dòng trong danh mục" | Theo v6.H, góc CTA Collection | — |
| Thẻ lọc `/collections/kanglim/{tag}` | Có thẻ rác / trùng / sai chính tả: `2022`, `2023`, `nissan`, `3 chân`, `5 chân`, `ksk1256g`, `ks12565g-ii`, `xe-tai-gan-cau-7-tan` (gõ "gán"), và cặp trùng hoa–thường (`kanglim`/`Kanglim`, `ud`/`UD`, `chenglong`/`Chenglong`, `cẩu 12 tấn`/`Cẩu 12 tấn`) | Giữ thẻ theo model (`ks1056`, `ks1256g-ii`, `ks2056t-s`, `ks2825`, `ks3105`, `ks5206`) và theo xe nền; xoá phần còn lại. Kiểm GSC xem thẻ nào đang được index | — |

**Purple Cow Collection (bắt buộc 1–2 câu):** chưa có bằng chứng đủ 4 tiêu chí ⇒ lấy từ nguồn dịch vụ (v6.0 mục 9) hoặc bỏ khối.

**Internal link Collection (≥ 3):** Product mục 4 · Cluster K3 / K4 / K6 · Pillar hãng · Collection tải trọng tương ứng.

---

## 6. Tầng Blog / Cluster / Page

### 6.1. Hiện có

Chưa quét được toàn bộ blog và page. **CẦN BỔ SUNG:** danh sách URL blog / page có chữ "kanglim" từ Haravan admin hoặc GSC — để bổ sung vào bảng này trước khi chốt gộp / xoá.

| URL | Hiện trạng | Vai | Quyết định |
| --- | --- | --- | --- |
| `/blogs/news/kanglim-ks1256g-ii-6-tan` | Đăng 04/09/2026. Cấu trúc blog tốt (tóm tắt, bảng, FAQ). Lỗi: đơn vị áp suất ghi "kg/cm³"; tiêu đề phụ dùng 🔰; câu "giá thấp hơn cẩu Nhật 10–25%" không nguồn; số sức nâng lệch Product #4 (mục 8.1); không có nút CTA | **Blog hub model** — owner "cẩu Kanglim KS1256G-II" | ✏️ Giữ URL, viết lại |
| `/blogs/news/so-sanh-cau-15-tan-everdigm-kanglim-dy-soosan` | Chưa crawl nội dung | Cluster đa hãng — dùng chung | ✅ Giữ — 6.4 chỉ link từ hub K2 |
| `/blogs/news/so-sanh-mam-quay-toa-cau-tadano-unic-soosan-kanglim` | Chưa crawl nội dung | Thuộc 6.3 | ✅ Không sở hữu |

### 6.2. Đề xuất tạo — chưa tạo, chờ duyệt

| Ưu tiên | Loại | Slug đề xuất | Vai / từ khoá sở hữu | Điều kiện viết |
| --- | --- | --- | --- | --- |
| 🔴 1 | Blog hub | `/blogs/news/cau-kanglim-ks2825-12-tan` **(K1)** | Hub kỹ thuật theo mã cẩu — nhiều Product (#7–#10) dùng chung | Đủ 3 số cốt lõi KS2825 |
| 🔴 1 | Blog hub | `/blogs/news/cau-kanglim-ks5206-15-tan` **(K2)** | Hub kỹ thuật theo mã cẩu — nhiều Product (#12–#15) dùng chung; nêu rõ KS5206 và KS5206-I nếu là hai đời | Đủ 3 số cốt lõi KS5206 + chốt mục 2 điểm 2 |
| 🔴 1 | Page | `/pages/cau-kanglim` **(P1)** | Pillar hãng: "cẩu Kanglim là gì · của nước nào · có tốt không · cách đọc mã KS". Nhận khối thương hiệu cắt khỏi Collection. Link xuống toàn cụm (≥ 6) | Nguồn hãng cho lịch sử / số liệu — chờ D1 |
| 🟡 2 | Cluster giá | `/blogs/news/bang-gia-xe-tai-gan-cau-kanglim` **(K3)** | "giá cẩu Kanglim", "giá xe cẩu Kanglim" | Có ít nhất khoảng giá sàn theo cấu hình; không có thì chưa viết (v6.0 mục 11) |
| 🟡 2 | Cluster so sánh | `/blogs/news/so-sanh-cau-kanglim-ks2825-va-ks5206` **(K4)** | So sánh trong cùng hãng, nhận câu FAQ cắt khỏi Collection | Đủ 3 số cốt lõi cả hai model |
| 🟡 2 | Cluster tư vấn | `/blogs/news/chon-cau-kanglim-theo-tai-trong` **(K6)** | Nhận khối "chọn theo nhu cầu" cắt khỏi Collection. **Không** nhắm "kinh nghiệm chọn xe tải gắn cẩu" trần (thuộc blog dùng chung) | Đủ số cốt lõi các model dẫn |
| 🟢 3 | Blog hub | `/blogs/news/cau-kanglim-ks2056t-s-8-tan` **(K7)** | Hub kỹ thuật theo mã cẩu — #5, #6 | Đủ 3 số cốt lõi KS2056T-S |
| 🟢 3 | Cluster so sánh thương hiệu | `/blogs/news/so-sanh-cau-kanglim-va-soosan` **(K8)** | Trục thương hiệu tổng (xuất xứ, hệ mã, phụ tùng). **Không** theo mức 15 tấn — tránh trùng bài đa hãng 15 tấn | Dữ liệu SERP + 3 số cốt lõi hai bên (6.2) |
| 🟢 3 | Cluster tư vấn | `/blogs/news/chon-xe-nen-gan-cau-kanglim` **(K9)** | Chọn theo xe nền Dongfeng / Chenglong / UD / Isuzu | **Đối chiếu 6.2 B6** (`chon-xe-tai-gan-cau-theo-so-chan-6x2-6x4-8x4`) trước khi tạo — trùng trục xe nền thì làm **một bài dùng chung** |

**Chưa mở hub cho KS1056 và KS3105:** mỗi mã mới có một Product. Product giữ luôn vai hub; mở hub khi có ≥ 2 Product dùng chung mã.

**Không tạo trong cụm này:** bài pháp lý riêng cho Kanglim (Cluster pháp lý dùng chung) · bài phụ tùng / mâm quay toa Kanglim (thuộc 6.3 và Collection phụ tùng) · bài cẩu Kanglim đã qua sử dụng (thuộc 6.6).

### 6.3. Duyệt từng bài

- [ ]  K1 — `cau-kanglim-ks2825-12-tan`
- [ ]  K2 — `cau-kanglim-ks5206-15-tan`
- [ ]  P1 — `/pages/cau-kanglim`
- [ ]  K3 — `bang-gia-xe-tai-gan-cau-kanglim`
- [ ]  K4 — `so-sanh-cau-kanglim-ks2825-va-ks5206`
- [ ]  K6 — `chon-cau-kanglim-theo-tai-trong`
- [ ]  K7 — `cau-kanglim-ks2056t-s-8-tan`
- [ ]  K8 — `so-sanh-cau-kanglim-va-soosan`
- [ ]  K9 — `chon-xe-nen-gan-cau-kanglim`

---

## 7. Luật phân vai — áp cho cả Map này

| Tầng | Được nhắm | CẤM nhắm |
| --- | --- | --- |
| Pillar chung `/pages/xe-tai-gan-cau` | "xe tải gắn cẩu", "xe cẩu tự hành", "cẩu tự hành là gì" | Tên hãng cẩu, mã model, "báo giá" |
| Pillar hãng `/pages/cau-kanglim` | "cẩu Kanglim là gì", "Kanglim của nước nào", "cẩu Kanglim có tốt không", "mã KS" | "mua / báo giá cẩu Kanglim", tên xe nền cụ thể |
| Collection tải trọng | "xe tải gắn cẩu X tấn", "mua xe cẩu X tấn" | Tên hãng cẩu, mã model |
| Collection `/collections/kanglim` | "xe tải gắn cẩu Kanglim", "xe cẩu Kanglim", "mua cẩu Kanglim" | Mức tải cụ thể đơn lẻ, mã model đơn lẻ, "giá", "là gì", pháp lý, bảng thông số |
| Blog hub model (K1, K2, K7, blog KS1256G-II) | "cẩu Kanglim {model}", "cẩu Kanglim X tấn", "thông số {model}" | Tên xe nền cụ thể, "mua / báo giá" |
| Cluster giá (K3) | "giá cẩu Kanglim", "giá xe cẩu Kanglim" | Bảng thông số chi tiết |
| Cluster so sánh / tư vấn (K4, K6, K8, K9) | Một intent duy nhất mỗi bài | Từ khoá hub model, từ khoá Collection |
| Product | "{xe nền + mã} gắn cẩu Kanglim {model}" | "xe tải gắn cẩu X tấn" trần, "cẩu Kanglim" trần, so sánh đa hãng, mặt bằng giá, pháp lý chi tiết |

---

## 8. Luật số cốt lõi

Bốn chỉ tiêu kỹ thuật của cụm: **① sức nâng lớn nhất kèm bán kính tương ứng · ② sức nâng tại bán kính xa nhất · ③ bán kính làm việc lớn nhất · ④ chiều cao nâng lớn nhất.**

**Chặn xuất bản:** thiếu bất kỳ số nào trong **① ② ③** ⇒ Product hoặc Blog hub model **chưa đủ điều kiện xuất bản** — dừng, xin dữ liệu trước khi viết.

**Không chặn:** thiếu ④ ⇒ bỏ dòng đó khỏi bảng + khai 1 dòng ở mục 16.3, vẫn xuất bài.

Không suy diễn, không nội suy từ model gần giống. Không ghi "Đang cập nhật" trong bài (v6.0 mục 10.1).

**Nguồn hợp lệ theo thứ tự ưu tiên:** hồ sơ đăng kiểm → catalogue PDF Kanglim → ảnh biểu đồ tải gắn trên xe → website hãng. Hai nguồn lệch nhau ⇒ ưu tiên hồ sơ đăng kiểm và ghi rõ cả hai trong file này. Điền ô nào thì ghi nguồn ngay bên cạnh.

### 8.1. Bảng số cốt lõi theo model

| Model | ① Sức nâng lớn nhất @ bán kính | ② Sức nâng @ bán kính xa nhất | ③ Bán kính làm việc lớn nhất | ④ Chiều cao nâng lớn nhất | Nguồn / trạng thái |
| --- | --- | --- | --- | --- | --- |
| KS1056 | 5.000 kg @ 2,4 m | 250 kg @ 15,5 m | 15,5 m | 17,6 m | Quan sát trên Product #1 (11/11/2026). **Chưa có nguồn hợp lệ** ⇒ chưa mở khoá |
| KS1256G-II | **XUNG ĐỘT:** 6.600 kg @ 2,5 m (blog) ↔ 7.000 kg @ 2,4 m (Product #4) | 300 kg @ 18,7 m (cả hai) | 18,7 m; 21,7 m với jib (blog) | 21,7 m; 23,7 m với jib (blog) | Blog có ảnh biểu đồ tải `ks1256g-ii_spectification_chard`. Chưa đối chiếu catalogue / đăng kiểm ⇒ chưa mở khoá. Chờ D3 |
| KS1256G | CẦN BỔ SUNG | CẦN BỔ SUNG | CẦN BỔ SUNG | CẦN BỔ SUNG | Chờ D3: có phải cùng mã với KS1256G-II không |
| KS2056T-S | CẦN BỔ SUNG | CẦN BỔ SUNG | CẦN BỔ SUNG | CẦN BỔ SUNG | Collection ghi "~14 m" — chưa nguồn, **không dùng** |
| KS2825 | CẦN BỔ SUNG | CẦN BỔ SUNG | CẦN BỔ SUNG | CẦN BỔ SUNG | Collection ghi "~18 m" — chưa nguồn, **không dùng** |
| KS3105 | CẦN BỔ SUNG | CẦN BỔ SUNG | CẦN BỔ SUNG | CẦN BỔ SUNG | Collection ghi "25 m" — chưa nguồn, **không dùng** |
| KS5206 | CẦN BỔ SUNG | CẦN BỔ SUNG | CẦN BỔ SUNG | CẦN BỔ SUNG | Collection ghi "~22 m" — chưa nguồn, **không dùng** |
| KS5206-I | CẦN BỔ SUNG | CẦN BỔ SUNG | CẦN BỔ SUNG | CẦN BỔ SUNG | Chờ mục 2 điểm 2 |

**Cảnh báo trạng thái:** chưa model nào có nguồn hợp lệ ⇒ **chưa hub model nào đủ điều kiện xuất bản**. Product đang live giữ nguyên, chỉ rà theo 4.3. **Ưu tiên lấy dữ liệu: KS2825 và KS5206** (nhiều Product dùng nhất), sau đó KS1256G-II (giải xung đột), KS2056T-S.

---

## 9. Registry từ khoá cụm Kanglim

| Từ khoá | Intent | Loại trang | URL sở hữu | Trạng thái |
| --- | --- | --- | --- | --- |
| cẩu Kanglim · xe cẩu Kanglim · xe tải gắn cẩu Kanglim · cẩu tự hành Kanglim | Thương mại | Collection hãng | `/collections/kanglim` | Viết lại |
| cẩu Kanglim là gì · cẩu Kanglim của nước nào · cẩu Kanglim có tốt không · mã KS là gì | Thông tin / EEAT hãng | Pillar hãng | `/pages/cau-kanglim` | Cần tạo (D1) |
| giá cẩu Kanglim · giá xe cẩu Kanglim · bảng giá xe tải gắn cẩu Kanglim | Giá | Cluster | K3 | Cần tạo |
| cẩu Kanglim KS1256G-II · thông số KS1256G-II | Thông tin kỹ thuật | Blog hub | `/blogs/news/kanglim-ks1256g-ii-6-tan` | Viết lại |
| cẩu Kanglim KS2825 · cẩu Kanglim 12 tấn | Thông tin kỹ thuật | Blog hub | K1 | Cần tạo |
| cẩu Kanglim KS5206 · cẩu Kanglim 15 tấn | Thông tin kỹ thuật | Blog hub | K2 | Cần tạo |
| cẩu Kanglim KS2056T-S · cẩu Kanglim 8 tấn | Thông tin kỹ thuật | Blog hub | K7 | Cần tạo |
| so sánh KS2825 và KS5206 | So sánh | Cluster | K4 | Cần tạo |
| chọn cẩu Kanglim theo tải trọng | Tư vấn | Cluster | K6 | Cần tạo |
| so sánh cẩu Kanglim và Soosan | So sánh thương hiệu | Cluster | K8 | Cần tạo |
| chọn xe nền gắn cẩu Kanglim | Tư vấn | Cluster | K9 (hoặc bài chung với 6.2 B6) | Cần tạo |
| cẩu Kanglim KS1056 · cẩu Kanglim KS3105 | Kỹ thuật + giao dịch (chưa đủ ≥ 2 Product để mở hub) | Product | mục 4 #1 · #11 | Giữ |
| {xe nền + mã} gắn cẩu Kanglim {model} | Giao dịch | Product | Theo bảng mục 4 | Viết lại |
| mua cẩu rời Kanglim KS1256G-II | Giao dịch | Product | #2 (nếu giữ — D2) | Chờ D2 |
| xe tải gắn cẩu 5 / 7–8 / 10–13 / 15 tấn | Thương mại | Collection tải trọng | Dùng chung (6.2) | Không sở hữu |
| so sánh cẩu 15 tấn Everdigm Kanglim Dongyang Soosan | So sánh đa hãng | Cluster chung | `/blogs/news/so-sanh-cau-15-tan-everdigm-kanglim-dy-soosan` | Không sở hữu |
| mâm quay toa Kanglim | Giao dịch | Product (6.3) | `/products/mam-quay-toa-kanglim` | Thuộc 6.3 |
| xe cẩu Kanglim cũ · HD320 gắn KS5206 cũ | Xe đã qua sử dụng | Product (6.6) | `/products/xe-hyundai-hd320-2012-cau-kanglim-ks5206-15-tan-cu` | Thuộc 6.6 |
| đăng kiểm xe cẩu · pháp lý xe gắn cẩu | Pháp lý | Cluster chung | `/blogs/news/phap-ly-dang-kiem-xe-cau-2026` | Không sở hữu |

Volume tìm kiếm và vị trí GSC: **CẦN BỔ SUNG** — chưa có dữ liệu, không suy đoán.

---

## 10. Entity, pháp lý, ứng dụng

### 10.1. Entity & thuật ngữ riêng

- **Hãng cẩu:** Kanglim (Hàn Quốc — theo blog live). Năm thành lập / số quốc gia: CẦN BỔ SUNG nguồn.
- **Hệ mã:** `KS` + 4 chữ số; hậu tố `G`, `G-II`, `T-S`, `-I`. Ý nghĩa hậu tố: CẦN BỔ SUNG — **không suy diễn**.
- **Xe nền xuất hiện trong cụm:** Dongfeng (B180 · L315 · KL340 · 4 chân 340HP · 5 chân) · Chenglong (M3 4×2 · LZ1310M5 · LZ1340 · 3 chân) · UD Truck (4 chân · Quester 8×4) · Isuzu FVZ.
- **Thuật ngữ:** bán kính làm việc / tầm với · biểu đồ tải · đốt cần · chân chống · jib · kim chỉ tải · còi báo quá tải · phanh tời tự động.

### 10.2. Pháp lý / tiêu chuẩn

Toàn bộ nội dung pháp lý ở **Cluster dùng chung** `/blogs/news/phap-ly-dang-kiem-xe-cau-2026`. Product và Collection chỉ 1–2 câu + link. Nội dung Collection hiện nhắc "QCVN 7:2012/BLĐTBXH" phải đối chiếu với Cluster này (6.6 ghi cluster dùng QCVN 09:2024) trước khi đưa lại vào bất kỳ trang nào.

### 10.3. Ứng dụng theo lĩnh vực & khách hàng mục tiêu (card chuẩn)

Lấy từ nội dung live, **cần ví dụ thực tế cho từng thẻ** trước khi dùng trong bài:

- 🏗️ Xây dựng dân dụng, lắp kết cấu thép nhẹ
- 🏭 Công nghiệp, di chuyển máy móc trong nhà xưởng
- 🧱 Vật liệu xây dựng, phân phối vật tư
- 🚂 Đường sắt (Collection đang ghi — CẦN BỔ SUNG ví dụ)
- 🔌 Lắp đặt hạ tầng điện nước, biển quảng cáo (blog KS1256G-II đang ghi)

Thẻ "Nông nghiệp / container lạnh" trên Collection hiện **không có căn cứ** — bỏ khỏi thẻ chuẩn cho tới khi có ví dụ.

**Khách hàng mục tiêu:** nhà thầu xây dựng, đơn vị vận tải vật tư, nhà máy / xưởng sản xuất.

---

## 11. Kho tài sản EEAT

| Hạng mục | Trạng thái |
| --- | --- |
| Catalogue PDF Kanglim theo từng model | CẦN BỔ SUNG |
| Giấy ủy quyền / hợp đồng đại lý Kanglim — **cơ sở duy nhất** cho các câu "nhà phân phối chính hãng", "đại lý chính hãng", "nhập khẩu trực tiếp từ Hàn Quốc" đang có trên Collection | CẦN BỔ SUNG — thiếu thì **bỏ các câu đó khỏi bài** |
| Bằng chứng "kỹ thuật viên được đào tạo tại nhà máy Kanglim", "bảo hành chính hãng", "hậu mãi trọn đời" | CẦN BỔ SUNG — thiếu thì bỏ |
| Nguồn lịch sử hãng (năm thành lập, số quốc gia, ISO) | CẦN BỔ SUNG |
| Biểu đồ tải / ảnh bảng thông số | Có ảnh biểu đồ KS1256G-II trong blog; các model còn lại CẦN BỔ SUNG |
| Hồ sơ đăng kiểm / giấy chứng nhận của xe đã bàn giao | CẦN BỔ SUNG |
| Ảnh xe thật bàn giao (có biển số / ngày) | CẦN BỔ SUNG — chưa xác nhận ảnh hiện có là xe thật hay ảnh hãng |
| Dự án thực tế có tên · số lượng · năm | CẦN BỔ SUNG — Product #4 hiện chỉ có "một khách hàng ở Bắc Ninh", không tên ⇒ bỏ khỏi bài |
| Video riêng từng model | CẦN BỔ SUNG (kênh YouTube chung đã có) |

---

## 12. Kho Purple Cow cụm Kanglim

| Model / URL | Điểm đáng kể lại | Bằng chứng | Đối thủ có nói chưa |
| --- | --- | --- | --- |
| (trống — nạp dần bằng tham số `/p!`) | | | |

Mỗi Product một Purple Cow khác nhau. Kho còn trống ⇒ lấy Purple Cow từ **nguồn dịch vụ** (v6.0 mục 9: đăng kiểm trọn gói 7–15 ngày · đào tạo vận hành tận nơi · vay 70–80% tới 60 tháng). Vẫn không đủ 4 tiêu chí ⇒ bỏ khối và khai ở 16.3.

Lưu ý khi tìm Purple Cow theo thiết bị: "ghế ngồi làm việc trên cao" ở KS1056 **không đủ tiêu chí khác biệt trong cụm** vì blog KS1256G-II cũng liệt kê "ghế vận hành".

---

## 13. Thứ tự thực hiện

| Đợt | Việc | Cần dữ liệu mới? |
| --- | --- | --- |
| 0 | Sửa link hỏng trong bảng Collection (4.4) · gỡ câu bịa nguồn ở Product #4 · Price số thật cho mọi Product · bỏ "Hoàng Huy" ở #11 | Không |
| 1 | Viết lại Collection `/collections/kanglim` (`~sscl`) theo mục 5 — link theo Map, kể cả bài chưa tạo | Không |
| 2 | Xin dữ liệu: catalogue KS2825 + KS5206 (ưu tiên) · giải xung đột KS1256G-II · mã cẩu của #7 và #9 · giấy ủy quyền đại lý | **Có** |
| 3 | Hub K1, K2 · viết lại blog KS1256G-II (`~ssb`) | Có — đủ mục 8 |
| 4 | Viết lại Product theo nhóm cẩu: KS2825 (#7–#10) → KS5206 (#12–#15) → KS2056T-S (#5, #6) → KS1256G-II (#2–#4) → KS1056 (#1) → KS3105 (#11) | Có |
| 5 | Cluster K3, K4, K6 · Pillar hãng P1 · K7, K8, K9 | Tuỳ bài |
| 6 | Khi có GSC / GA4: quyết định gộp #2 ↔ blog, 301, dọn thẻ | GSC |

### 13.1. Quyết định cần Mr Tú chốt

- **D1 — Pillar hãng:** dùng `/pages/cau-kanglim` (page) hay blog như B5 của 6.2? Đề xuất **page**, vì v6.0 mục 4 xếp "thương hiệu & lịch sử hãng" vào Pillar. Nếu chọn page, 6.2 B5 nên đồng bộ sau.
- **D2 — Product #2 "cẩu rời":** VietNhatCorp có bán cẩu rời Kanglim KS1256G-II riêng không? **Có** ⇒ giữ Product, tách intent giao dịch khỏi blog. **Không** ⇒ gộp #2 vào blog hub, 301 `#2` → blog.
- **D3 — KS1256G và KS1256G-II:** một hay hai model? Ảnh hưởng #3, #4, blog hub và mục 8.1.
- **D4 — Mã cẩu của #7 (UD Truck 4 chân) và #9 (Dongfeng 5 chân):** có phải KS2825 không?
- **D5 — Khoá slug mới** ở mục 6.2 và mã model mục 2.

---

## 14. Nguyên tắc trạng thái

- Handle Product live: **giữ nguyên**, chỉ sửa theo 4.3.
- Gộp / xoá / 301: **chờ GSC**. Chưa URL nào đủ căn cứ xoá.
- Product / bài chưa live: vẫn link theo Map; GSC khai báo sau theo link thực tế.
- Bài ở mục 6.2: chưa tạo cho tới khi tick duyệt ở 6.3 **và** đủ điều kiện dữ liệu ở cột "Điều kiện viết".
- Mã model ở mục 2: chưa khoá cho tới D3 và mục 2 điểm 2–3.
- Danh sách ở mục 3, 4, 6: mở, thêm dòng bằng lệnh `~~6.4` kèm ngày.
- Ghi vào registry khi gộp / xoá: URL cũ → URL đích → ngày (v6.0 mục 5.4).

---

## 15. Nhật ký

- **11/11/2026 — v6.4.0.** Tạo mới. Crawl `/collections/kanglim` (2 trang lưới), Product #1 và #4, blog `kanglim-ks1256g-ii-6-tan`; đối chiếu 6.1, 6.2, 6.3, 6.6 và v6.0.11. Phát hiện chính: ① bảng thân Collection trỏ tới handle không trùng handle của lưới (đã thử 2 link, đều lỗi); ② Collection kiêm vai Pillar hãng, Cluster giá, Cluster so sánh, bảng thông số — bảng thông số có số tầm với mâu thuẫn Product; ③ Product #4 lọt chữ nội bộ và lời chuyên gia / báo cáo không nguồn; ④ Product #2 và blog KS1256G-II trùng intent; ⑤ số sức nâng KS1256G-II lệch giữa blog và Product #4; ⑥ Price = 0₫ ở các Product đã đọc; ⑦ thẻ lọc Collection có thẻ rác / sai chính tả; ⑧ chưa có đại lý ủy quyền làm bằng chứng cho câu "nhà phân phối chính hãng". Đề xuất Pillar hãng, hub model, Cluster giá / so sánh / tư vấn. **Chưa thay đổi gì trên website.**
