# 00-LOAD-mrtu.md — BỘ NẠP hệ Instruction Mr Tú
Phiên bản: LOAD-2.5 · 11/11/2026 · Đọc file này TRƯỚC MỌI VIỆC

File này KHÔNG chứa quy tắc viết bài. Nhiệm vụ duy nhất: nạp file nào, thứ tự nào, xung đột xử lý ra sao.

## ▶️ L1. BASE (gist — luôn trả bản mới nhất)

BASE = https://gist.githubusercontent.com/ngonepvang/668ee76576360783c7ffb1e0f4401405/raw/

Ghép: BASE + tên file. Tên file phải khớp tuyệt đối, sai 1 ký tự = 404.

## ▶️ L2. Bảng file (tên thật trên gist)

| Tên thật trên gist | Vai | Sửa bằng lệnh |
| --- | --- | --- |
| `00-LOAD-mrtu.md` | Bộ nạp — file này | `~~load` |
| `mrtu-v6.0-core.md` | Bản TỔNG v6.0: intent · kiến trúc URL · registry · dữ liệu · giá · luật khuyết dữ liệu (mục 10.1) · EEAT · thứ tự khối · Quality Gate C1–C22 | `~~6.0` |
| `Haravan.md` | Tầng TRÌNH BÀY v6.H (SKILL): thẻ/CSS inline · bảng màu · typography · thư viện HTML · CTA · khối chốt · khối biên tập · định mức số chữ · quy cách file đầu ra · bảng kiểm **P1–P22** | `~~6.H` |
| `mrtu-v6.1-everdigm.md` | Bản con 6.1 — cụm Hyundai Everdigm: sitemap · slug · model · registry | `~~6.1` |
| `mrtu-v6.2-soosan.md` | Bản con 6.2 — cụm Soosan: sitemap · slug · model · registry | `~~6.2` |
| `mrtu-v6.3-mam-quay-toa.md` | Bản con 6.3 — cụm mâm quay toa xe tải gắn cẩu: sitemap · slug · dòng sản phẩm · registry | `~~6.3` |
| `mrtu-v6.4-kanglim.md` | Bản con 6.4 — cụm xe tải gắn cẩu Kanglim: site map · slug · mã model · registry · luật số cốt lõi · bảng audit Product / Collection | `~~6.4` |
| `mrtu-v6.6-cau-cu.md` | Bản con 6.6 — cụm cẩu cũ (cẩu bánh lốp · cẩu địa hình · cẩu bánh xích đã qua sử dụng): site map · slug · mã model · registry · luật số cốt lõi · bảng audit | `~~6.6` |

Cả 8 file đều mang đuôi `.md`. Không tồn tại file nào khác, không tự suy ra tên file mới.

Đổi tên bất kỳ file nào ⇒ phải cập nhật đồng thời: bảng L2 này (`~~load`) **và** dòng `companions` trong frontmatter `Haravan.md` (`~~6.H`).

### ✔️ L2.1. Kiểm vai file ngay khi nạp (bắt buộc — 5 giây)

Sự cố thật 09/09/2026: `Haravan.md` bị ghi bằng nội dung của `mrtu-v6.0-core.md`, hệ mất tầng trình bày mà không ai biết.

| File | Dòng đầu phải là | Nếu sai |
| --- | --- | --- |
| `Haravan.md` | `# INSTRUCTION v6.H — HARAVAN PRESENTATION LAYER (SKILL)` + có mục `H2. Bảng màu chuẩn` | Dừng, báo 1 dòng `⚠️ Haravan.md sai vai`, **không** tự suy diễn quy tắc trình bày từ trí nhớ, không xuất HTML |
| `mrtu-v6.0-core.md` | `# INSTRUCTION v6.0 — BẢN TỔNG (content layer)` | Dừng, báo `⚠️ v6.0-core sai vai`, không viết bài |
| Bản con 6.x | `# Instruction v6.x — …` kèm dòng Phiên bản | Dừng, báo file nào sai |

## ▶️ L3. Nạp theo lệnh — chỉ nạp đúng thứ cần

| Lệnh | Nạp |
| --- | --- |
| `~ss` `~ssc` `~ssp` `~sscl` `~ssb` (xuất HTML Haravan) | `mrtu-v6.0-core.md` + `Haravan.md` + bản con của cụm |
| `~S` `~C` `~sp` `~scl` `~sb` (xuất markdown) | `mrtu-v6.0-core.md` + bản con + chỉ mục **H8** của `Haravan.md` |
| `~A` (nghiên cứu từ khoá) · `~audit` | `mrtu-v6.0-core.md` + bản con |
| `~~6.0` / `~~6.H` / `~~6.1` / `~~6.2` / `~~6.3` / `~~6.4` / `~~6.6` / `~~load` | đúng 1 file tương ứng |
| `~1` (dịch) | không nạp gì |

**Bản con của cụm:** bài về Hyundai Everdigm → 6.1 · bài về Soosan → 6.2 · bài về Kanglim → 6.4 · bài về mâm quay toa xe tải gắn cẩu → 6.3 · bài về cẩu cũ (cẩu bánh lốp, cẩu địa hình, cẩu bánh xích đã qua sử dụng — không gồm xe tải gắn cẩu) → 6.6 · cụm khác → chưa có bản con, ghi rõ "chưa có bản con 6.x cho cụm này" và chỉ dùng v6.0 + v6.H.

**Thứ tự nạp:** v6.0-core → Haravan → bản con 6.x.

## ▶️ L4. Lệnh `~load`

- `~load` = nạp v6.0-core + Haravan.
- `~load 6.1` / `~load 6.2` / `~load 6.3` / `~load 6.4` / `~load 6.6` = nạp thêm bản con tương ứng.
- `~load nhẹ` = chỉ v6.0-core (dùng cho `~A`, `~audit`).

## ▶️ L5. Báo cáo sau khi nạp — đúng 1 dòng, chưa viết gì

    Đã nạp: v6.0 (bản) + v6.H (bản) + 6.x (bản) — sẵn sàng nhận lệnh.

Trước mỗi lần xuất bài, ghi thêm 1 dòng:

    Đã nạp: v6.0 + v6.H + 6.x — loại trang: … — định mức chữ: …

Lệnh HTML mà chưa nạp được `Haravan.md`, hoặc `Haravan.md` sai vai theo L2.1 → KHÔNG xuất HTML, ghi:
`⚠️ Chưa nạp v6.H — không đủ điều kiện trình bày`.

## ▶️ L6. Luật xung đột

1. Trình bày (màu · HTML · số chữ · thứ tự khối · quy cách file đầu ra) → **Haravan.md thắng**.
2. Intent · vai URL · registry · dữ liệu · giá · **luật khuyết dữ liệu (v6.0 mục 10.1)** → **v6.0-core thắng**.
3. Slug · mã model · sitemap · trạng thái Product → **bản con 6.x thắng**.
4. Bản con không được đặt quy tắc trình bày riêng; câu nào trái Haravan.md ⇒ vô hiệu.
5. Bản con được ghi "CẦN BỔ SUNG"/"CẦN TẠO" trong file Instruction, nhưng **không bao giờ** cho các chuỗi đó chảy vào bài — theo v6.0 mục 10.1.

## ▶️ L7. Fetch lỗi

Báo rõ file nào lỗi + URL đã thử. KHÔNG tự viết bù nội dung file thiếu, KHÔNG đoán quy tắc, KHÔNG viết bài khi thiếu file bắt buộc.

404 thì thử đúng 2 khả năng trước khi báo: (a) thiếu/thừa đuôi `.md`; (b) sai hoa–thường. Vẫn 404 ⇒ báo và dừng.

## ▶️ L8. Kỷ luật

Không in lại nội dung file đã nạp ra chat. Không tự tóm tắt/rút gọn file khi đọc — đọc hết rồi mới làm. Sửa Instruction: sửa đúng file, đúng mục, giữ nguyên phần còn lại. Người dùng yêu cầu sửa ⇒ **trả nguyên file để dán đè**, không đưa danh sách tìm–thay lắt nhắt.

## ▶️ L9. Nhật ký

- **11/11/2026 — LOAD-2.5.** Thêm bản con **6.4 — cụm xe tải gắn cẩu Kanglim** (`mrtu-v6.4-kanglim.md`, bản 6.4.0) vào bảng L2, lệnh `~~6.4` ở L3, quy tắc chọn bản con ở L3 (bài về Kanglim → 6.4), `~load 6.4` ở L4; L2 đổi "7 file" → "8 file". Không đổi luật nạp, luật xung đột, xử lý fetch lỗi. Nhắc: cập nhật dòng `companions` trong frontmatter `Haravan.md` (`~~6.H`) để thêm 6.4 và LOAD-2.5.
- **03/11/2026 — LOAD-2.4.** Thêm bản con **6.6 — cụm cẩu cũ** (`mrtu-v6.6-cau-cu.md`, bản 6.6) vào bảng L2, lệnh `~~6.6` ở L3, quy tắc chọn bản con ở L3 (cẩu cũ → 6.6, xe tải gắn cẩu vẫn thuộc 6.1/6.2/6.3), `~load 6.6` ở L4; L2 đổi "6 file" → "7 file". Đồng bộ `Haravan.md` lên **6.H.5** (frontmatter `companions` đã thêm 6.6 và LOAD-2.4; đầu ra `~ss*` đổi thành 1 file có khối biên tập trên cùng + nút Copy lấy thân bài sạch). Không đổi luật nạp, luật xung đột, xử lý fetch lỗi.
- **09/09/2026 — LOAD-2.3.** File 6.3 trên gist đã đổi tên thành `mrtu-v6.3-mam-quay-toa.md`; sửa L2 theo tên mới và **xoá cảnh báo ngược của LOAD-2.2** (bản đó ghi "không có đuôi .md, thêm .md sẽ 404" — kiểm tra lại 09/09/2026: có `.md` → HTTP 200, không `.md` → 404). Cả 6 file nay thống nhất đuôi `.md`. Rút gọn L1 và L7 cho khớp. Thêm vào L8 luật **trả nguyên file để dán đè**.
- **09/09/2026 — LOAD-2.2.** Mô tả `Haravan.md` đổi `P1–P18` → P1–P22 (bản SKILL 6.H.3); mô tả `mrtu-v6.0-core.md` bổ sung mục 10.1 + Quality Gate C1–C22. Thêm **L2.1 Kiểm vai file ngay khi nạp** sau sự cố `Haravan.md` bị ghi đè bằng nội dung v6.0. Bổ sung L5 (chặn xuất HTML khi file sai vai), L6 điểm 2 và 5, L7 (xử lý 404).
- **03/09/2026 — LOAD-2.1.** Thêm bản con **6.3 — cụm mâm quay toa xe tải gắn cẩu** vào bảng file L2, lệnh `~~6.3` ở L3, lệnh `~load 6.3` ở L4.
- **30/08/2026 — LOAD-2.0.** Sửa BASE từ `raw.githubusercontent.com/<user>/<repo>/main/` sang đường raw gist thật. Sửa tên file theo tên thật trên gist. Thêm bản con 6.2. Gộp lệnh `~load` từ bộ nạp trùng trong `mrtu-v6.0-core.md` về đây.
