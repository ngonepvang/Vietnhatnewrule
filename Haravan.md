INSTRUCTION v6.H — HARAVAN PRESENTATION LAYER (SKILL)
Phiên bản 6.H.5 · Cập nhật 03/11/2026
Tách từ Instruction v6.0 (mục 14, 14B, 15 + các dòng checklist/Quality Gate về hình thức).
File này tự chứa: đọc một mình là làm được HTML Haravan đúng chuẩn.

▶️ H0. Bản này là gì và nạp thế nào
Vai trò: v6.H sở hữu toàn bộ tầng hình thức — HTML Haravan, bảng màu, typography, khung từng khối, thứ tự khối, định mức số chữ, quy cách file đầu ra, khối biên tập, khối chốt cuối trang, bảng kiểm phong cách.

v6.H KHÔNG chứa: intent, kiến trúc URL, registry từ khoá, chống ăn thịt từ khoá, luật dữ liệu/giá/xe cũ, luật khuyết dữ liệu (v6.0 mục 10.1), sitemap, mã model. Những thứ đó ở v6.0 và các bản con 6.x.

✔️ H0.1. Luật nạp (bắt buộc — đây là phần giúp tiết kiệm tài nguyên)
Nhóm lệnh	Có cần nạp v6.H?
~ss ~ssc ~ssp ~sscl ~ssb (HTML Haravan)	✅ Bắt buộc
~S ~C ~sp ~scl ~sb (Markdown)	Chỉ nạp mục H8 (định mức số chữ) — không cần phần HTML
~A ~audit	❌ Không nạp
~~6.0 ~~6.1 ~~6.2 ~~6.3 ~~6.6 ~~load	❌ Không nạp
~~6.H	✅ Nạp bản này
Thứ tự nạp khi viết bài HTML: v6.0 (quy tắc) → v6.H (trình bày) → bản con 6.x (sitemap/slug/model).

Xác nhận nạp: trước khi xuất bài HTML, ghi đúng 1 dòng trong chat:

Đã nạp: v6.0 + v6.H (6.H.5) + 6.x — loại trang: … — định mức chữ: …
Xác nhận đầu ra: ngay sau khi xuất file, ghi đúng 1 dòng trong chat:

Đầu ra: 1 file [slug].html — khối biên tập trên cùng + nút 📋 Copy HTML + xem trước; nút chỉ copy thân bài sạch.
Nếu chưa nạp được v6.H thì không xuất HTML, ghi: ⚠️ Chưa nạp v6.H — không đủ điều kiện trình bày.

✔️ H0.2. Luật xung đột
Trình bày (màu, HTML, số chữ, thứ tự khối, quy cách file đầu ra): v6.H thắng.
Intent, vai URL, registry, dữ liệu, luật khuyết dữ liệu: v6.0 thắng.
Slug, mã model, sitemap: bản con 6.x thắng.
Bản con 6.x không được tự đặt quy tắc trình bày. Câu nào trái v6.H ⇒ vô hiệu, phải xoá.
✔️ H0.3. Trạng thái đồng bộ với v6.0
Đã hoàn tất từ v6.0.9: mục 14, 14B, 15 của v6.0 được thay bằng khối trỏ về v6.H. Bảng kiểm hình thức mang mã P1–P22; mrtu-v6.0-core.md v6.0.11 đã sửa P1–P20 → P1–P22 tại mục 0, 14, 17 (C20) và 20 ⇒ hai file hiện khớp mã, không còn phải "đọc thành".

✔️ H0.4. Lệnh cập nhật riêng
~~6.H + nội dung cần sửa. Quy trình như v6.0 mục 19: sửa tại chỗ, xoá quy tắc cũ bị thay, cập nhật chéo H8/H9/H10, ghi Nhật ký cuối bản. Đánh số: 6.H.1 → 6.H.2 → 6.H.3 → 6.H.4…

✔️ H0.5. Cảnh báo vai file
Trên gist, tên file Haravan.md phải chứa đúng nội dung v6.H này. Sự cố 09/09/2026: Haravan.md bị ghi đè bằng nội dung mrtu-v6.0-core.md ⇒ hệ mất tầng trình bày, mọi lệnh ~ss* đều không chạy được bảng kiểm P. Sự cố lặp lại 10/09/2026 (file bị đè lần hai) ⇒ phải phục hồi từ revision gist.

Cách nhận biết trong 5 giây khi vừa nạp: file mở đầu bằng # INSTRUCTION v6.H và có mục H2. Bảng màu chuẩn. Nếu mở ra thấy # INSTRUCTION v6.0 — BẢN TỔNG thì file sai vai: dừng, báo 1 dòng ⚠️ Haravan.md sai vai — đang là nội dung v6.0, không tự suy diễn quy tắc trình bày từ trí nhớ.

Phục hồi khi bị đè: lấy lại từ lịch sử gist qua https://api.github.com/gists/668ee76576360783c7ffb1e0f4401405/commits, rồi tải https://gist.githubusercontent.com/ngonepvang/668ee76576360783c7ffb1e0f4401405/raw/<version-sha>/Haravan.md. Không viết lại tầng trình bày từ trí nhớ.

▶️ H1. Luật kỹ thuật cứng của Haravan
Chỉ dùng <div> cho khung block. Haravan lọc bỏ thẻ HTML5 semantic và nuốt luôn style nền/màu → triệu chứng: khối chốt "trắng ởn", mất nền #1a3c6e.

Cấm tuyệt đối trong HTML dán lên web:

<section> <nav> <article> <header> <footer> <aside> <main>
<style> và mọi class CSS
JavaScript, onclick, mọi thuộc tính sự kiện
:hover, pseudo-class, media query
FontAwesome, Tabler, SVG CDN, icon ngoài, webfont
Schema JSON-LD (Haravan đã xử lý)
<span style="color:#000000"> bọc chữ — màu chữ đặt trực tiếp trên thẻ khối
Được dùng: <div> <p> <h2> <h3> <table> <tr> <td> <ul> <ol> <li> <a> <img> <strong> <em> <blockquote> <br>. Icon = Emoji Unicode.

Toàn bộ CSS inline trong style="..." của từng thẻ. Không có ngoại lệ.

Heading: không H1 trong nội dung, bắt đầu từ Breadcrumb. H2 tiền tố ▶️, H3 tiền tố ✔️. Không dùng ✅/🔰 làm tiền tố tiêu đề. Không đánh số heading.

Responsive: mọi flex phải có flex-wrap:wrap; bảng rộng bọc trong div overflow-x:auto + min-width trên <table>; card dùng grid auto-fit.

Nút bấm: luôn là <a> inline style, chữ trắng in đậm, min-height:44px, bo 6px, có padding rõ.

Cảnh báo quan trọng: Haravan không lọc <div>/<p> + inline CSS. Nghĩa là mọi khối phụ trợ (khối biên tập, nhãn tên file, khung xem trước) nếu lọt vào chuỗi được dán sẽ hiển thị nguyên trên web; chỉ <style> và JavaScript bị lọc, biến nút bấm thành chữ tĩnh nằm lại trang. Vì vậy chuỗi thân bài mà nút Copy lấy ra phải sạch từ gốc, và chỉ được lấy bài bằng nút Copy — xem H7 và H9.

Placeholder trong bản này là Ô ĐIỀN, không phải nội dung. Mọi […], …, DD/MM/YYYY, URL-ANH, Tên lĩnh vực trong thư viện H4–H6 bắt buộc thay bằng dữ liệu thật trước khi giao file. Còn sót một cái ⇒ lỗi chặn xuất bản P22.

Khuyết dữ liệu: v6.H không có khối nào để "báo thiếu". Thiếu dữ liệu thì bỏ dòng → bỏ khối → gỡ heading/câu dẫn/mục lục/link theo v6.0 mục 10.1, và khai ở mục 16.3 (khối biên tập). Cấm khối rỗng, cấm ô bảng trống, cấm chữ "Đang cập nhật" dưới mọi hình thức.

▶️ H2. Bảng màu chuẩn (không được đổi)
Vai trò	Mã màu
Xanh thương hiệu — header bảng, H2/H3, khối chốt	#1a3c6e
Nền xám nhạt — hàng nhóm bảng, box phụ, blockquote	#f5f7fa
Viền khung ngoài	#e0e0e0
Viền phân dòng trong bảng / FAQ	#eee
Chữ thân bài	#333
Chữ phụ (đáp án FAQ, mô tả)	#555
Ghi chú nhỏ, tên tài liệu nguồn	#666 – #888
CTA giữa bài	nền #fff3cd, viền 1px solid #ffc107
Nút Gọi	#28a745
Nút Zalo	#0068ff
Link nổi bật trong khối xanh	#ffd700
Purple Cow	nền #f3e8ff, viền 4px solid #7c3aed, tiêu đề #5b21b6
Giới hạn / cảnh báo	nền #fef3f2, viền 4px solid #dc3545, tiêu đề #dc3545
Khối biên tập (đầu file giao, ngoài chuỗi thân bài được copy)	nền #fff8e1, viền 2px solid #f9a825, chữ ≥ 15px
Card ứng dụng — 4 cặp luân phiên	#e3f2fd/#1976d2 · #e8f5e9/#388e3c · #fff8e1/#f9a825 · #fce4ec/#c2185b
Cấm: CTA hộp xanh lá nhạt chỉ có chữ không nút; khối nội dung để chữ trôi trên nền trắng không viền không nền.

▶️ H3. Typography & khoảng cách
Thành phần	Quy chuẩn
H2	font-size:19px;font-weight:bold;color:#1a3c6e;margin:0 0 12px; + tiền tố ▶️
H3	font-size:16px;font-weight:bold;color:#1a3c6e;margin:0 0 8px; + tiền tố ✔️
Thân bài	font-size:16px;line-height:1.7;color:#333;
Bảng	font-size:14px;
Ghi chú nguồn	font-size:12px;color:#888;
Bullet list	line-height:1.8;
Danh sách tự chẩn đoán	line-height:2;
Mỗi section	bọc <div style="margin-bottom:24px;">
Khối chốt	margin-top:32px;
Bo góc	khung lớn 8px–10px, nút 6px, khối màu chức năng 6px
Nguyên tắc gốc: mỗi khối nội dung là một thẻ có nền/viền/bo góc riêng.

▶️ H4. Thư viện khối — HTML chuẩn
✔️ H4.1. Breadcrumb
<div style="font-size:13px;color:#666;margin-bottom:18px;">
<a href="/" style="color:#1a3c6e;text-decoration:none;">Trang chủ</a> › <a href="/collections/…" style="color:#1a3c6e;text-decoration:none;">Tên danh mục</a> › <span style="color:#888;">Tên trang hiện tại</span>
</div>
✔️ H4.2. Bảng thông số — luôn có header màu
Cấm bảng trần chỉ có border:1px solid #dddddd. Bảng phải: khung ngoài bo góc + thanh tiêu đề xanh đậm + hàng nhóm xám + dòng kẻ nhạt #eee + (nếu có nguồn) chú thích tên tài liệu 12px.

<div style="border:1px solid #e0e0e0;border-radius:8px;overflow-x:auto;margin-bottom:24px;">
<div style="background:#1a3c6e;color:#fff;padding:10px 16px;font-weight:bold;">Bảng thông số đầy đủ</div>
<table style="width:100%;border-collapse:collapse;font-size:14px;min-width:600px;">
<tr style="background:#f5f7fa;"><td style="padding:10px 14px;border-bottom:1px solid #eee;" colspan="2"><strong>PHẦN XE NỀN — TÊN XE</strong></td></tr>
<tr><td style="padding:8px 14px;border-bottom:1px solid #eee;">Hạng mục</td><td style="padding:8px 14px;border-bottom:1px solid #eee;">Giá trị</td></tr>
<tr style="background:#f5f7fa;"><td style="padding:10px 14px;border-bottom:1px solid #eee;border-top:2px solid #1a3c6e;" colspan="2"><strong>PHẦN CẨU — TÊN CẨU</strong></td></tr>
<tr><td style="padding:8px 14px;">Hạng mục cuối</td><td style="padding:8px 14px;">Giá trị</td></tr>
</table>
<p style="font-size:12px;color:#888;padding:10px 14px;margin:0;">Nguồn: catalog Soosan SCS746L.</p>
</div>
Quy tắc: hàng cuối bỏ border-bottom; mở nhóm mới bằng border-top:2px solid #1a3c6e; gộp nhiều bảng nhỏ thành một bảng nhiều hàng nhóm, không tách 3 bảng rời.

Chú thích chân bảng. Chỉ được ghi tên tài liệu nguồn (vd Nguồn: catalog Soosan SCS746L). Cấm ghi tình trạng dữ liệu, cấm liệt kê mục nào còn thiếu, cấm chữ "Đang cập nhật". Không có tài liệu nguồn ⇒ xoá cả dòng chú thích, không viết dòng trống.

Ô trống: bảng không được có ô rỗng, không được có —/…/N/A thay số. Thiếu 1 chỉ tiêu → bỏ cả <tr>. Thiếu quá nửa chỉ tiêu → bỏ cả bảng và gỡ luôn heading dẫn vào bảng (v6.0 mục 10.1).

✔️ H4.3. Mini-table cốt lõi — dạng thẻ flex, không phải bảng
<div style="border:1px solid #e0e0e0;border-radius:8px;overflow:hidden;margin-bottom:24px;">
<div style="background:#1a3c6e;color:#fff;padding:10px 16px;font-weight:bold;">Thông số cốt lõi</div>
<div style="display:flex;flex-wrap:wrap;">
<div style="flex:1;min-width:260px;padding:12px 16px;border-bottom:1px solid #eee;"><strong>Nhãn:</strong> giá trị</div>
</div>
</div>
Mini-table phải đủ 4–6 dòng có số thật. Không đủ 4 dòng ⇒ bỏ cả mini-table, khai ở 16.3.

✔️ H4.4. Blockquote định vị
<div style="border-left:4px solid #1a3c6e;background:#f5f7fa;padding:14px 18px;margin-bottom:24px;font-style:italic;color:#333;line-height:1.7;">
Một câu định vị: xe này dành cho ai, giải quyết bài toán gì.
</div>
✔️ H4.5. Purple Cow
<div style="background:#f3e8ff;border-left:4px solid #7c3aed;border-radius:6px;padding:16px 20px;margin-bottom:24px;">
<p style="font-weight:bold;margin:0 0 8px;color:#5b21b6;">🐄 Điều khiến [tên xe] khác biệt</p>
<p style="margin:0;color:#3b0764;line-height:1.7;">[Tuyên bố khác biệt + 2–3 bằng chứng kiểm chứng được]</p>
</div>
Không đủ 4 tiêu chí của v6.0 mục 9 ⇒ bỏ khối, không viết câu sáo, không ghi "cần bổ sung dữ liệu khác biệt" trong bài.

✔️ H4.6. Box highlight tóm tắt (Cluster / Blog)
<div style="background:#f5f7fa;border:1px solid #e0e0e0;border-radius:8px;padding:16px 20px;margin-bottom:24px;">
<p style="font-weight:bold;color:#1a3c6e;margin:0 0 8px;">📌 Trả lời nhanh</p>
<ul style="margin:0;padding-left:20px;color:#333;line-height:1.8;">
<li>Ý chốt 1</li>
<li>Ý chốt 2</li>
</ul>
</div>
✔️ H4.7. Điểm nổi bật
<div style="margin-bottom:24px;">
<ul style="margin:0;padding-left:20px;color:#333;line-height:1.8;">
<li>✅ <strong>Nhãn:</strong> nội dung cụ thể, có số.</li>
</ul>
</div>
✔️ H4.8. Giới hạn cần biết
<div style="background:#fef3f2;border-left:4px solid #dc3545;border-radius:6px;padding:16px 20px;margin-bottom:24px;">
<p style="font-weight:bold;margin:0 0 8px;color:#dc3545;">⚠️ Giới hạn cần biết trước khi mua</p>
<ul style="margin:0;padding-left:20px;color:#333;line-height:1.8;">
<li>Giới hạn 1 — nêu thẳng, không né.</li>
</ul>
</div>
Đây là khối định tính, luôn viết được kể cả khi thiếu số liệu — dùng nó thay cho thói quen ghi "Đang cập nhật".

✔️ H4.9. 4 câu tự chẩn đoán
<div style="background:#f5f7fa;border-radius:8px;padding:16px 20px;margin-bottom:24px;">
<p style="font-weight:bold;color:#1a3c6e;margin:0 0 8px;">🧭 4 câu tự kiểm trước khi chốt</p>
<ol style="margin:0;padding-left:22px;color:#333;line-height:2;">
<li>Câu hỏi 1?</li><li>Câu hỏi 2?</li><li>Câu hỏi 3?</li><li>Câu hỏi 4?</li>
</ol>
</div>
✔️ H4.10. Card ứng dụng — grid, mỗi thẻ một màu
<div style="display:grid;grid-template-columns:repeat(auto-fit,minmax(280px,1fr));gap:16px;align-items:stretch;margin-bottom:24px;">
<div style="background:#e3f2fd;border-top:4px solid #1976d2;border-radius:8px;padding:16px;display:flex;flex-direction:column;">
<div style="display:flex;align-items:center;gap:10px;margin-bottom:8px;"><span style="background:#fff;border-radius:50%;width:40px;height:40px;display:flex;align-items:center;justify-content:center;font-size:20px;">🏗️</span><strong>Tên lĩnh vực</strong></div>
<p style="text-align:justify;color:#333;margin:0;line-height:1.7;">Mô tả ứng dụng.</p>
</div>
</div>
Luân phiên 4 cặp màu ở H2. Icon emoji trong vòng tròn trắng 40px. Số card chọn để không lẻ bố cục: 4 (2×2), 6 (3+3), 8 (4×2).

✔️ H4.11. Phụ kiện / an toàn kèm theo
<div style="margin-bottom:24px;">
<ul style="margin:0;padding-left:20px;color:#333;line-height:1.8;">
<li>🛡️ Tên phụ kiện — công dụng ngắn.</li>
</ul>
</div>
✔️ H4.12. Dự án thực tế
<div style="background:#f5f7fa;border-radius:8px;padding:16px 20px;margin-bottom:24px;">
<p style="font-weight:bold;color:#1a3c6e;margin:0 0 8px;">📌 Đã bàn giao thực tế</p>
<ul style="margin:0;padding-left:20px;color:#333;line-height:1.8;">
<li>Công ty Thành Hưng — 02 xe — 2025 — Hà Nội, vận chuyển thiết bị công trình</li>
</ul>
</div>
Mỗi dòng phải đủ tên · số lượng · năm. Thiếu một trong ba ⇒ bỏ dòng. Không còn dòng nào ⇒ bỏ cả khối, khai ở 16.3. Cấm dòng dạng [Tên khách hàng] — [số lượng] — [năm] lọt ra file giao (P22).

✔️ H4.13. Ảnh + caption
<div style="margin-bottom:24px;">
<img src="URL-ANH" alt="[từ khoá chính hoặc biến thể]" style="width:100%;height:auto;border-radius:8px;display:block;">
<p style="font-size:13px;color:#666;text-align:center;margin:8px 0 0;">Caption gắn với bằng chứng khác biệt.</p>
</div>
Ảnh người dùng cung cấp bắt buộc dùng, giữ nguyên logo/watermark. Không có ảnh ⇒ bỏ khối; cấm ô ảnh trống, cấm caption "ảnh đang cập nhật".

✔️ H4.14. Mục lục (Pillar)
<div style="background:#f5f7fa;border:1px solid #e0e0e0;border-radius:8px;padding:16px 20px;margin-bottom:24px;">
<p style="font-weight:bold;color:#1a3c6e;margin:0 0 8px;">📑 Nội dung chính</p>
<ul style="margin:0;padding-left:20px;line-height:1.9;">
<li><a href="#muc-1" style="color:#1a3c6e;">Tên mục 1</a></li>
</ul>
</div>
Bỏ khối nào ở thân bài thì gỡ luôn dòng mục lục trỏ tới nó.

✔️ H4.15. Câu dẫn + link sang Cluster/Pillar
<div style="background:#f5f7fa;border-left:4px solid #1a3c6e;padding:12px 16px;margin-bottom:24px;color:#333;line-height:1.7;">
[1–2 câu dẫn.] Xem chi tiết: <a href="/blogs/news/slug-da-chot" style="color:#1a3c6e;font-weight:bold;">anchor mô tả đúng đích</a>.
</div>
Link theo slug đã chốt trong bản con 6.x kể cả khi URL chưa live. Không bỏ link, không đổi slug để chờ live, và không ghi "CẦN TẠO" trong bài — trạng thái URL khai ở 16.3.

✔️ H4.16. FAQ — từng câu một dòng có kẻ dưới
<div style="border-bottom:1px solid #eee;padding:12px 0;">
<p style="font-weight:bold;color:#333;margin:0 0 6px 0;">✔️ Câu hỏi?</p>
<p style="color:#555;margin:0;line-height:1.7;">Câu trả lời ngắn, trực tiếp.</p>
</div>
Câu cuối bỏ border-bottom.

▶️ H5. CTA giữa bài — bắt buộc có 2 nút, canh giữa
Lỗi thường gặp: CTA giữa bài chỉ là một dòng chữ trong hộp vàng. Bắt buộc hộp vàng viền #ffc107, canh giữa, một dòng dẫn in đậm gắn tên model thật, hai nút Zalo + Gọi.

<div style="background:#fff3cd;border:1px solid #ffc107;border-radius:8px;padding:16px 20px;margin-bottom:24px;text-align:center;">
<p style="margin:0 0 12px 0;font-weight:bold;color:#333;">📞 Nhận báo giá [TÊN MODEL] — Giá cập nhật theo đợt</p>
<a href="https://zalo.me/0918666480" style="display:inline-block;background:#0068ff;color:#fff;text-decoration:none;padding:10px 20px;border-radius:6px;font-weight:bold;margin:4px;min-height:44px;line-height:24px;">💬 Zalo tư vấn</a>
<a href="tel:0918666480" style="display:inline-block;background:#28a745;color:#fff;text-decoration:none;padding:10px 20px;border-radius:6px;font-weight:bold;margin:4px;min-height:44px;line-height:24px;">📞 0918 666 480</a>
</div>
[TÊN MODEL] là ô điền — phải thay bằng tên thật (P22).

Dòng dẫn biến thể theo loại trang: Product = chọn đúng cấu hình · Collection = so sánh các dòng · Cluster giá = báo giá theo cấu hình thực tế · Cluster pháp lý = kiểm tra hồ sơ, đăng kiểm · Pillar = tư vấn chọn nhóm xe · Blog = giải đáp tình huống.

Chưa có giá thật: CTA là chỗ hứng nhu cầu giá. Viết "Nhận báo giá … theo cấu hình thực tế", không viết "giá đang cập nhật".

▶️ H6. Khối chốt cuối trang — đủ 5 phần, không rút gọn
Đặt liền sau FAQ. Nền #1a3c6e, bo 10px, margin-top:32px.

<div style="background:#1a3c6e;color:#fff;border-radius:10px;padding:24px;margin-top:32px;">

<p style="font-weight:bold;font-size:18px;margin:0 0 4px 0;">[Dòng dẫn tư vấn theo intent]</p>
<p style="margin:0 0 16px 0;opacity:0.9;">Miễn phí tư vấn · Chọn đúng model theo tải trọng, tầm với và ngân sách</p>

<div style="text-align:center;margin-bottom:20px;">
<a href="https://zalo.me/0918666480" style="display:inline-block;background:#0068ff;color:#fff;text-decoration:none;padding:12px 24px;border-radius:6px;font-weight:bold;margin:6px;min-height:44px;line-height:24px;">💬 Nhận báo giá qua Zalo</a>
<a href="tel:0918666480" style="display:inline-block;background:#28a745;color:#fff;text-decoration:none;padding:12px 24px;border-radius:6px;font-weight:bold;margin:6px;min-height:44px;line-height:24px;">📞 Gọi ngay: 0918 666 480</a>
</div>

<div style="border-top:1px solid rgba(255,255,255,0.2);padding-top:16px;">
<p style="font-weight:bold;margin:0 0 10px;">Tại sao chọn VietNhatCorp</p>
<p style="margin:0 0 10px;opacity:0.92;line-height:1.7;">Công ty TNHH Ô tô Chuyên dùng Việt Nhật — thành lập 2013, hơn 10 năm kinh nghiệm, 40 Ngô Gia Tự, Long Biên, Hà Nội.</p>
<p style="margin:4px 0;">✅ Đại lý/đơn vị lắp chính hãng, CO/CQ đầy đủ</p>
<p style="margin:4px 0;">✅ Kho xe đa dạng, sẵn giao theo từng thời điểm</p>
<p style="margin:4px 0;">✅ Tư vấn miễn phí đúng model/cấu hình</p>
<p style="margin:4px 0;">✅ Hỗ trợ vay 70–80% tới 60 tháng</p>
<p style="margin:4px 0;">✅ Đăng ký–đăng kiểm trọn gói 7–15 ngày</p>
<p style="margin:4px 0;">✅ Đào tạo vận hành tận nơi</p>
<p style="margin:4px 0;">✅ Bảo hành, bảo dưỡng chính hãng, hỗ trợ kỹ thuật toàn quốc</p>
<p style="margin:10px 0 0;">📌 Kinh nghiệm thực tế: Công ty Thành Hưng — 02 xe — 2025 — Hà Nội</p>
</div>

<div style="border-top:1px solid rgba(255,255,255,0.2);margin-top:16px;padding-top:16px;">
<p style="margin:6px 0;">🌐 Website: <a href="https://www.vietnhatcorp.net" style="color:#ffd700;">www.vietnhatcorp.net</a></p>
<p style="margin:6px 0;">🎯 Zalo: <a href="https://zalo.me/0918666480" style="color:#ffd700;">0918 666 480</a></p>
<p style="margin:6px 0;">📞 Hotline: <a href="tel:0918666480" style="color:#ffd700;">0918 666 480</a></p>
<p style="margin:6px 0;">📧 Email: <a href="mailto:chuyendungvietnhat@gmail.com" style="color:#ffd700;">chuyendungvietnhat@gmail.com</a></p>
<p style="margin:6px 0;">▶️ Youtube: <a href="https://youtube.com/@chuyendungvietnhat" style="color:#ffd700;">youtube.com/@chuyendungvietnhat</a></p>
<p style="margin:6px 0;">🏢 Địa chỉ: <a href="https://maps.google.com/?q=40+Ngo+Gia+Tu+Long+Bien+Ha+Noi" style="color:#ffd700;">40 Ngô Gia Tự, Long Biên, Hà Nội</a></p>
</div>

<div style="border-top:1px solid rgba(255,255,255,0.2);margin-top:16px;padding-top:12px;font-size:13px;opacity:0.85;">
<p style="margin:4px 0;">Tags: từ khoá 1 | từ khoá 2 | từ khoá 3 | từ khoá 4 | từ khoá 5</p>
<p style="margin:4px 0;">(Trang cập nhật tháng 09/2026)</p>
<p style="margin:4px 0;">📅 Cập nhật lần cuối: 10/09/2026</p>
</div>

</div>
Sáu dòng liên hệ dùng đúng emoji 🌐 🎯 📞 📧 ▶️ 🏢, mỗi mục một dòng, giá trị/link màu #ffd700.

Dòng 📌 Kinh nghiệm thực tế. Chỉ giữ khi có tên khách hàng · số lượng · năm thật. Không có dữ liệu ⇒ xoá cả dòng <p> đó, khối chốt vẫn đủ 5 phần. Luật cũ "thiếu thì ghi CẦN BỔ SUNG DỰ ÁN THỰC TẾ" đã bị xoá, không dùng lại dưới bất kỳ hình thức nào.

Tags: viết đủ 5–8 từ khoá thật, phân tách bằng |. Cấm để …, cấm để ít hơn 5.

Ngày: (Trang cập nhật tháng MM/YYYY) và 📅 Cập nhật lần cuối: DD/MM/YYYY phải là ngày thật của lần giao bài; cấm để nguyên chữ MM/YYYY, DD/MM/YYYY.

Câu chữ dòng dẫn và Tags biến thể 30–40% theo intent giữa các URL; thông tin cố định (tên công ty, địa chỉ, hotline, email, chính sách) giữ nguyên.

</div> đóng khối này là ký tự cuối cùng của file thân bài — không viết thêm bất cứ thứ gì sau nó (xem H9).

▶️ H7. Khối "Phần dành cho biên tập" — đầu file, NGOÀI vùng copy
Năm luật cứng:

Vị trí: khối biên tập đặt trên cùng file [slug].html, phía trên nút 📋 Copy HTML và khung xem trước. Khối này không bao giờ nằm trong chuỗi thân bài mà nút Copy lấy ra (H9.1). Lọt vào chuỗi copy ⇒ lỗi chặn xuất bản (P13).
Lý do kỹ thuật, phải nhớ: Haravan chỉ lọc <style> và JavaScript, không lọc <div>/<p> + inline CSS. Nếu biên tập bôi cả trang (Ctrl+A) rồi copy, hộp vàng sẽ lên web nguyên vẹn và để lại chữ tĩnh "📋 Copy HTML" — lỗi thật bài Dongfeng B180 HLC-5014 (30/08/2026). Vì vậy: chỉ lấy bài bằng nút Copy, không Ctrl+A. Dòng nhắc này được ghi ngay trong tiêu đề khối biên tập.
Đồng thời in trong chat: sau khi giao file, in lại tóm tắt khối biên tập (9 trường) + bảng 16.3 trong chat để người dùng đọc nhanh không cần mở file.
Không viết bất kỳ lưu ý, ghi chú, cảnh báo, checklist hay chỉ dẫn biên tập vào nội dung bài viết. Các câu như "bài này viết lại…", "bỏ tên…", "theo Map…", "số cũ thiếu nguồn…", "cần sửa SEO…" chỉ đặt ở khối biên tập. Xuất hiện trong thân bài ⇒ lỗi chặn xuất bản (P14).
Khối biên tập là nơi DUY NHẤT được viết CẦN BỔ SUNG · CẦN TẠO · cần xác minh · Đang cập nhật (v6.0 mục 16.3). Trong thân bài, các chuỗi này là lỗi P21.
Mẫu chuẩn — hộp vàng HTML đầu file, đủ 9 trường:

<div style="background:#fff8e1;border:2px solid #f9a825;border-radius:10px;padding:18px 22px;margin-bottom:20px;font-size:15px;line-height:1.9;color:#333;">
<p style="font-weight:bold;font-size:17px;color:#1a3c6e;margin:0 0 12px;">📝 PHẦN DÀNH CHO BIÊN TẬP — không dán lên web · chỉ lấy bài bằng nút Copy</p>
<p style="margin:4px 0;"><strong>Slug:</strong> /products/…</p>
<p style="margin:4px 0;"><strong>Title (số ký tự):</strong> …</p>
<p style="margin:4px 0;"><strong>Meta Description (số ký tự):</strong> …</p>
<p style="margin:4px 0;"><strong>Sapo / Excerpt:</strong> …</p>
<p style="margin:4px 0;"><strong>SKU · Giá:</strong> … · nhập số thật, không để 0</p>
<p style="margin:4px 0;"><strong>ALT ảnh chính:</strong> …</p>
<p style="margin:4px 0;"><strong>Tồn kho / Variants:</strong> …</p>
<p style="margin:4px 0;"><strong>URL chưa live cần theo dõi:</strong> …</p>
<p style="margin:4px 0;"><strong>Cập nhật:</strong> DD/MM/YYYY — lý do bản này · đã bỏ gì vì thiếu dữ liệu · cần xác minh gì</p>
</div>
Bắt buộc đủ 9 trường, chữ ≥ 15px. Không áp dụng thì ghi Không áp dụng; thiếu dữ liệu ghi CẦN BỔ SUNG. Loại trang không phải Product: SKU/Giá/Tồn kho/Variants ghi Không áp dụng. Placeholder …/DD/MM/YYYY trong mẫu là ô điền, phải thay bằng dữ liệu thật.

Kèm theo khối này (trong chat) là bảng "Đã bỏ khỏi bài vì thiếu dữ liệu" theo v6.0 mục 16.3: Khối/dòng đã bỏ | Dữ liệu cần | Nguồn cần lấy | Chỗ chèn lại khi có dữ liệu.

▶️ H8. Định mức số chữ & số phần tử
Mục quyết định "nạp là ra giống nhau". Đếm từ không tính bảng thông số, khối chốt cuối trang và khối biên tập.

✔️ H8.1. Tổng thể theo loại trang
Loại trang	Tổng số từ	Số H2	Số khối màu chức năng	CTA
Product	2.000–3.000	10–14	≥ 4 (Purple Cow, blockquote, giới hạn, tự chẩn đoán)	1 giữa + khối chốt
Cluster	2.000–4.000	6–10	≥ 2	1–2 giữa + khối chốt
Pillar	4.000–8.000	8–12	≥ 2	CTA mềm + khối chốt
Collection	300–800	3–5	1–2	1 CTA + liên hệ ngắn
Blog	1.000–2.000	4–7	≥ 2	1 giữa + khối chốt
✔️ H8.2. Product — định mức từng khối
Khối	Số từ	Số phần tử
Breadcrumb	—	3–4 cấp
Hero (là gì · dùng khi nào · không phù hợp khi nào)	150–250	3 đoạn
Mini-table cốt lõi	mỗi dòng ≤ 12 từ	4–6 dòng
Blockquote định vị	25–40	1–2 câu
Purple Cow	60–120 (có /p: 120–180)	1 tuyên bố + 2–3 bằng chứng (/p: ≥ 3)
Điểm nổi bật	200–300	5–7 bullet, mỗi bullet 15–35 từ
Bảng thông số đầy đủ	không tính từ	18–35 dòng, 2–4 hàng nhóm
Phân tích WHY	300–500	3–5 đoạn, mỗi đoạn 1 thông số → 1 lợi ích
Tính năng + ảnh	150–250	2–4 ảnh có caption
CTA giữa bài	dòng dẫn 12–25 từ	2 nút
4 câu tự chẩn đoán	mỗi câu 12–25 từ	đúng 4 câu
Card ứng dụng	300–500	4 / 6 / 8 card, mỗi card 35–60 từ
Phụ kiện kèm theo	mỗi dòng 8–20 từ	6–10 bullet
Giới hạn cần biết	80–150	3–5 bullet
Dự án thực tế	60–120	2–4 dòng có tên/số lượng/năm
Câu dẫn + link Cluster so sánh	25–45	1 khối
Câu dẫn + link Cluster pháp lý	25–45	1 khối
Sản phẩm cùng series	mỗi dòng ≤ 15 từ	3–5 link
FAQ	400–800	≥ 6 câu, mỗi đáp án 40–80 từ
Khối chốt cuối trang	cố định theo H6	5 phần
✔️ H8.3. Cluster
Mở bài trả lời trực tiếp intent 90–120 từ · box highlight 40–70 từ, 3–5 bullet · mỗi H2 250–500 từ · bảng so sánh 4–8 dòng, 3–5 cột · phân tích chuyên sâu 300–600 từ · FAQ ≥ 4 câu, đáp án 40–70 từ · CTA giữa 1–2.

✔️ H8.4. Pillar
Mở bài định nghĩa 120–180 từ · mục lục 6–12 dòng · mỗi H2 300–600 từ, kết mỗi H2 có ≥ 1 link xuống cụm · tổng internal link ≥ 6 · FAQ ≥ 6 câu, đáp án 50–90 từ · CTA mềm 25–40 từ. Không bảng thông số model.

✔️ H8.5. Collection
Intro danh mục 80–120 từ · tiêu chí chọn nhanh 4–6 bullet, mỗi bullet 10–25 từ · điểm khác biệt danh mục 40–80 từ (1–2 câu, có /p thì thêm bằng chứng) · điều hướng Product ≥ 3 link · 1 CTA · liên hệ ngắn. Không vượt 800 từ, không nhồi thông số.

✔️ H8.6. Blog
Mở bài 70–100 từ · box highlight 40–70 từ · mỗi H2 200–400 từ · case study 80–150 từ · FAQ ≥ 4 câu · 1 CTA giữa.

✔️ H8.7. Trường SEO (mọi loại trang)
Title ≤ 70 ký tự, từ khoá chính đứng đầu · Meta 130–160 ký tự, bắt buộc có Gọi 0918 666 480 để có thông tin chi tiết · Sapo/Excerpt 1–2 câu, 25–45 từ · ALT ảnh 6–12 từ có từ khoá chính hoặc biến thể · Tags 5–8 · đoạn đề xuất AI Overview 1–3 câu hoặc 3–5 bullet ngắn.

✔️ H8.8. Hụt số từ vì khuyết dữ liệu
Bỏ khối theo v6.0 mục 10.1 làm tổng số từ hụt định mức là được phép — nhưng phải:

bù bằng nội dung định tính đã chắc chắn (công dụng, đối tượng dùng, giới hạn, quy trình dịch vụ) trước khi chấp nhận hụt;
hụt quá 20% ⇒ ghi lý do ở mục 16.3, không tự viết thêm chữ rỗng để lấp;
Product phải bỏ từ 3 khối bắt buộc trở lên ⇒ dừng, không xuất bài, xin dữ liệu trước (v6.0 mục 8).
Tuyệt đối không lấp chỗ trống bằng câu sáo, lặp lại đoạn trên, hay dòng "Đang cập nhật".

▶️ H9. Đầu ra của nhóm lệnh ~ss* — 1 FILE, 3 LỚP, NÚT COPY LẤY THÂN BÀI SẠCH
Luật một chuỗi một tầng: thứ được dán lên web là chuỗi thân bài do nút Copy lấy ra — chuỗi này chỉ chứa tầng nội dung. Khối biên tập, nút bấm, khung xem trước nằm trong file nhưng ngoài chuỗi đó.

✔️ H9.1. Cấu trúc file [slug].html — bắt buộc
Mỗi lệnh HTML Haravan xuất đúng 1 file [slug].html, mở bằng trình duyệt, gồm 3 lớp theo thứ tự:

Khối biên tập (H7) — trên cùng, hộp vàng.
Nút 📋 Copy HTML — dính đầu trang (sticky), bấm xong đổi chữ ✅ Đã copy 2 giây; dùng navigator.clipboard, có dự phòng execCommand('copy').
Khung xem trước — render đúng chuỗi thân bài để kiểm bố cục.
Chuỗi thân bài được giữ nguyên văn trong <textarea id="src" style="display:none;"> (đã escape HTML); nút Copy và khung xem trước cùng đọc từ một nguồn này ⇒ thứ thấy trong xem trước = thứ được dán.

Quy cách chuỗi thân bài (thứ nút Copy lấy ra):

Ký tự đầu tiên = <div của Breadcrumb (H4.1).
Ký tự cuối cùng = </div> đóng khối chốt cuối trang (H6).
Dán vào "Mã HTML" của Haravan là xong, không phải cắt gọt dòng nào.
Cấm tuyệt đối trong chuỗi thân bài:

Khối "Phần dành cho biên tập" (mọi dạng)
Tiêu đề/nhãn tên file kiểu Dongfeng B180 gắn cẩu HLC-5014 — File HTML Haravan
Nút 📋 Copy HTML, dòng ✅ Đã copy, khung xem trước bọc ngoài
<style>, class CSS, JavaScript, onclick
<!DOCTYPE html>, <html>, <head>, <meta>, <title>, <body> — thân bài là fragment
Mọi câu hướng dẫn cho người biên tập ("không dán lên web", "xoá dòng này"…)
Mọi chuỗi cấm ở v6.0 mục 10.1 và mọi placeholder chưa điền ([ ], …, DD/MM/YYYY, URL-ANH, TÊN MODEL)
<style>/JS/onclick/<!DOCTYPE> chỉ được phép ở vỏ file (lớp 2–3), không bao giờ ở chuỗi thân bài.

✔️ H9.2. Khối biên tập giao ở đâu
Trong file: lớp 1 (H7). Trong chat: in lại tóm tắt 9 trường + bảng 16.3 ngay dưới file.

✔️ H9.3. Cách dùng — ghi 1 dòng trong chat khi giao
Mở file → bấm 📋 Copy HTML → dán vào "Mã HTML" Haravan. Không Ctrl+A cả trang.

Người dùng yêu cầu riêng file thân bài trơn (không vỏ) thì xuất thêm [slug]-body.html chứa đúng chuỗi thân bài.

✔️ H9.4. Nhóm lệnh khác
Nhóm Markdown (~S ~C ~sp ~scl ~sb) xuất file .md; vì file này không dán lên web nên khối biên tập được đặt ở đầu file dạng text. ~A và ~audit xuất .md hoặc .csv.

✔️ H9.5. Cổng quét trước khi giao
Trước khi đưa file ra, quét chuỗi thân bài (nội dung textarea src) đúng 3 lượt:

Chuỗi cấm — Đang cập nhật, Chưa có dữ liệu, CẦN BỔ SUNG, CẦN TẠO, cần xác minh, chờ catalog, theo Map, TBD, N/A → P21.
Placeholder & ô trống — [, ], …, DD/MM/YYYY, MM/YYYY, URL-ANH, Tên lĩnh vực, TÊN MODEL, <td></td> → P22.
Rác lớp vỏ — File HTML Haravan, 📋 Copy HTML, ✅ Đã copy, ▼ Xem trước, không dán lên web, PHẦN DÀNH CHO BIÊN TẬP, <style, onclick → P13/P15/P20.
Thêm 1 lượt kiểm link ảnh: mọi src ảnh khớp nguyên văn URL người dùng cấp (đủ dấu _/__, hậu tố _1024x1024), có tiền tố https: → P18.

Còn 1 chỗ ⇒ không giao bài, sửa rồi giao lại.

▶️ H10. Bảng kiểm phong cách — thiếu là chặn xuất bản
Mã	Nội dung kiểm
P1	Mọi bảng có thanh tiêu đề xanh #1a3c6e; không còn <table> trần không style
P2	Bảng dài gộp bằng hàng nhóm xám, không tách nhiều bảng rời
P3	Mini-table cốt lõi dạng thẻ flex có header xanh, 4–6 dòng có số thật
P4	CTA giữa bài canh giữa, hộp #fff3cd viền #ffc107, đủ 2 nút Zalo + Gọi, dòng dẫn có tên model thật
P5	Đủ 4 khối màu: Purple Cow tím, blockquote xám, giới hạn đỏ nhạt, hộp tự chẩn đoán xám (khối nào bị bỏ theo v6.0 mục 10.1 thì đã khai ở 16.3)
P6	Card ứng dụng grid minmax(280px,1fr), mỗi thẻ một cặp màu + icon tròn trắng 40px; không phải bảng 2 cột; không lẻ card
P7	FAQ từng câu kẻ dưới #eee, câu hỏi bold #333, đáp án #555; câu cuối bỏ kẻ
P8	Khối chốt xanh bo 10px, 2 nút canh giữa, 3 đường phân cách trắng mờ, liên hệ 6 dòng vàng #ffd700, đủ 5 phần
P9	Mọi nút min-height:44px, bo 6px, chữ trắng in đậm
P10	Mọi section margin-bottom:24px; thân bài line-height:1.7; H2 ▶️ 19px, H3 ✔️ 16px, cả hai #1a3c6e
P11	Không <span style="color:#000000">; không dùng ✅/🔰 làm tiền tố tiêu đề
P12	Chỉ <div> cho khung block; không thẻ semantic bị cấm; không <style>, class, JS, hover; không Schema; CSS inline đầy đủ
P13	Khối biên tập nằm trên cùng file [slug].html, đủ 9 trường, chữ ≥ 15px, tiêu đề có nhắc "chỉ lấy bài bằng nút Copy"; không có mặt trong chuỗi thân bài nút Copy lấy ra; tóm tắt đã in lại trong chat
P14	Không có ghi chú/lưu ý/chỉ dẫn biên tập nào trong thân bài Haravan
P15	Chuỗi thân bài không chứa nút copy, khung xem trước, nhãn tên file, <style>, JS; vỏ file có đủ 3 lớp H9.1 và nút Copy + xem trước cùng đọc từ textarea src
P16	Đúng định mức số chữ mục H8; lệch quá 20% phải nêu lý do ở mục 16.3 (H8.8)
P17	Bảng rộng có overflow-x:auto + min-width; mọi flex có flex-wrap:wrap
P18	Đã dùng ảnh người dùng cung cấp, src khớp nguyên văn URL gốc (đủ _/__, có https:), ALT có từ khoá, giữ nguyên logo/watermark; không có ô ảnh trống
P19	Chuỗi thân bài mở đầu bằng <div> Breadcrumb, kết thúc bằng </div> khối chốt; không <!DOCTYPE>/<html>/<head>/<body>, không ký tự lạ trước/sau (vỏ file được phép có các thẻ này)
P20	Chuỗi thân bài không còn chuỗi rác của lớp vỏ: File HTML Haravan, 📋 Copy HTML, ✅ Đã copy, ▼ Xem trước, PHẦN DÀNH CHO BIÊN TẬP, tên slug/tên file, câu không dán lên web
P21	Đã quét và không còn chuỗi cấm của v6.0 mục 10.1 trong thân bài: Đang cập nhật · Chưa có dữ liệu · Chưa cập nhật · CẦN BỔ SUNG · CẦN TẠO · cần xác minh · chưa xác thực · chờ catalog · theo Map · TBD · N/A. Chú thích chân bảng chỉ ghi tên tài liệu nguồn (H4.2)
P22	Không còn placeholder chưa điền hay ô trống: [ ], …/— thay cho số, DD/MM/YYYY, MM/YYYY, URL-ANH, TÊN MODEL, Tên lĩnh vực, Tags: …, ô bảng rỗng, dòng dự án dạng mẫu. Tags đủ 5–8 từ khoá thật, ngày cập nhật là ngày thật
Nếu còn lỗi, ghi trong chat: ⚠️ Chưa đủ điều kiện xuất bản + liệt kê mã lỗi P.

Ánh xạ sang Quality Gate nội dung v6.0: P21 ↔ C21 · P22 ↔ C16/C21 · P13/P14/P20 ↔ C22 · P16 ↔ C9. Hai lớp kiểm độc lập, phải chạy cả hai.

▶️ H11. Áp dụng và phạm vi
Mục H1–H10 áp dụng cho mọi Instruction con 6.x (6.1 Everdigm, 6.2 Soosan, 6.3 Mâm quay toa, 6.6 Cẩu cũ…), mọi bài mới và mọi bài viết lại URL cũ, không có ngoại lệ. Bản con không được đặt quy tắc trình bày riêng; câu nào trong bản con nói về màu/HTML/bố cục/số chữ đều đọc thành "theo v6.H mục …".

Tương thích tên mục cũ: bản con ghi "v6.0 mục 14 / 14B / 15 — Design System, màu, CTA, HTML" ⇒ đọc thành H1–H10 bản này. Bản con ghi "Quality Gate lỗi 11–14 (hình thức)" ⇒ đọc thành P1–P22.

▶️ H12. Nhật ký cập nhật
03/11/2026 — v6.H.5. Theo yêu cầu người dùng: đầu ra ~ss* trở lại 1 file có nút Copy + khối biên tập trên cùng, thay cho mô hình "file thân bài trơn + khối biên tập trong chat" của 6.H.2. Giữ bài học Dongfeng B180 bằng cách tách vỏ file và chuỗi thân bài: nút Copy chỉ lấy chuỗi thân bài trong textarea src, mọi luật sạch (P13–P15, P19–P22) áp lên chuỗi đó; cấm Ctrl+A cả trang. Viết lại H7 (vị trí đầu file, mẫu hộp vàng HTML 9 trường, vẫn in tóm tắt trong chat) và H9 (cấu trúc 3 lớp, quy cách chuỗi thân bài, dòng hướng dẫn dùng, cổng quét trên chuỗi thân bài + lượt kiểm link ảnh). Lượt kiểm link ảnh thêm sau lỗi thật bài Tadano GR-120NL-1 (03/11/2026): ghép URL ảnh thiếu một dấu _ (__8_1024x1024 thay vì __8__1024x1024) ⇒ 6 ảnh không hiện. Cập nhật chéo: frontmatter (version, updated, companions thêm mrtu-v6.6-cau-cu.md, LOAD-2.4), H0.1 (~~6.6, dòng xác nhận đầu ra mới), H1 (cảnh báo áp lên chuỗi copy), H2 (màu khối biên tập), H10 (sửa P13, P15, P18, P19, P20), H11 (thêm 6.6). Ảnh hưởng file khác: 00-LOAD-mrtu.md → LOAD-2.4; mrtu-v6.0-core.md mục 3, 13 và mục 20 dòng "nút copy" còn ghi theo mô hình cũ — chờ sửa bằng ~~6.0 (đến khi sửa, theo L6 điểm 1: quy cách file đầu ra → Haravan.md thắng). Phiên bản: 6.H.4 → 6.H.5.

10/09/2026 — v6.H.4. Phục hồi file sau sự cố đè file lần hai: nội dung 6.H.3 được lấy nguyên văn từ revision gist 5e422eb8fa541fec1e9e627919944052e822dd6f, không viết lại từ trí nhớ. Frontmatter: đồng bộ companions theo phiên bản thực tế của cả bộ — 00-LOAD-mrtu.md (LOAD-2.3) · mrtu-v6.0-core.md (v6.0.11) · mrtu-v6.1-everdigm.md (6.1.3) / mrtu-v6.2-soosan.md (6.2.3) / mrtu-v6.3-mam-quay-toa.md (6.3.5) — bổ sung đuôi .md cho bản con 6.3 theo tên thật trên gist; version 6.H.3 → 6.H.4, updated 10/09/2026, description đổi số bản. H0.1: dòng xác nhận nạp ghi 6.H.4. H0.3: đổi tiêu đề thành "Trạng thái đồng bộ với v6.0" và xoá câu cũ "v6.0 mục 14 và 20 ghi P1–P20 là số cũ, đọc thành P1–P22" — v6.0.11 đã sửa thẳng thành P1–P22 nên hai file khớp mã, không còn quy ước đọc bù. H0.5: thêm ghi nhận sự cố đè file 10/09/2026 và cách phục hồi từ lịch sử gist (endpoint api.github.com/gists/…/commits + raw theo <version-sha>). H6: ngày mẫu trong khối chốt đổi sang 10/09/2026 cho khớp ngày giao. Các mục H1–H5, H7–H11 giữ nguyên 100% nội dung 6.H.3, không đổi một quy tắc trình bày nào. Ảnh hưởng file khác: 00-LOAD-mrtu.md và các bản con 6.1/6.2/6.3 không phải sửa; mrtu-v6.0-core.md không phải sửa. Phiên bản: 6.H.3 → 6.H.4.

09/09/2026 — v6.H.3. Đóng gói lại thành SKILL.md (thêm frontmatter: name · description · version · companions · update-command) và thực hiện 3 việc mà nhật ký mrtu-v6.0-core.md v6.0.10 giao cho ~~6.H. H4.2: xoá chú thích chân bảng mẫu * Nguồn tài liệu + mục nào "Đang cập nhật" — nay chỉ ghi tên tài liệu nguồn, không có nguồn thì xoá cả dòng; thêm luật cấm ô bảng trống/—/N/A. H6: xoá luật cũ "thiếu dự án thì ghi CẦN BỔ SUNG DỰ ÁN THỰC TẾ" (luật này là nguyên nhân trực tiếp làm chuỗi cấm lên web ở collection mâm quay toa 09/09/2026); nay không có dữ liệu thì xoá cả dòng 📌; mẫu điền dữ liệu thật cho Tags và ngày cập nhật thay …/MM/YYYY. H10: thêm P21 (quét chuỗi cấm v6.0 mục 10.1) và P22 (placeholder chưa điền, ô trống, Tags/ngày còn dạng mẫu); sửa P3, P4, P5, P16, P18 cho khớp luật khuyết dữ liệu; thêm bảng ánh xạ P ↔ C. Cập nhật chéo: H0.1 (thêm ~~6.3 vào bảng nạp, đổi dòng xác nhận sang 6.H.3), H0.3 (P1–P20 → P1–P22), H0.5 mới (cảnh báo file Haravan.md trên gist bị ghi đè bằng nội dung v6.0 và cách nhận biết trong 5 giây), H1 (placeholder là ô điền + trỏ luật khuyết dữ liệu), H2 (đổi nhãn "nguồn dữ liệu" → "tên tài liệu nguồn"), H4.3/H4.5/H4.12/H4.13/H4.14/H4.15 (xử lý khi thiếu dữ liệu, không ghi chú trong bài), H5 (không viết "giá đang cập nhật"), H7 (thêm luật 5: khối biên tập là nơi duy nhất được ghi CẦN BỔ SUNG/CẦN TẠO + kèm bảng 16.3), H8.8 mới (hụt số từ vì khuyết dữ liệu, ngưỡng dừng 3 khối), H9.1 và H9.5 mới (cổng quét 3 lượt trước khi giao), H11 (thêm bản con 6.3 + bảng tương thích tên mục cũ). Ảnh hưởng file khác: mrtu-v6.0-core.md nên sửa P1–P20 → P1–P22 tại mục 14, 17 (C20) và 20 bằng lệnh ~~6.0; 00-LOAD-mrtu.md và các bản con 6.1/6.2/6.3 không đổi. Phiên bản: 6.H.2 → 6.H.3.

30/08/2026 — v6.H.2. Sửa lỗi thật: file preview gộp khối biên tập + nút copy + khung xem trước vào cùng file, biên tập Ctrl+A cả file nên hộp vàng #fff8e1 và chữ tĩnh "📋 Copy HTML", "▼ Xem trước ▼" lên web (bài Dongfeng B180 gắn cẩu HLC-5014). Viết lại H7: khối biên tập chuyển sang mẫu text in trong chat, cấm nằm trong file thân bài dưới mọi hình thức, xoá mẫu hộp vàng HTML đặt đầu file preview. Viết lại H9 thành "Đầu ra — file thân bài sạch". H10: sửa P13, P15; thêm P19, P20. H0.1: thêm dòng xác nhận đầu ra. H1: thêm cảnh báo Haravan không lọc <div>/<p> + inline CSS. H2: màu khối biên tập chỉ dùng trong chat/file riêng. H6: </div> khối chốt là ký tự cuối file. Phiên bản: 6.H.1 → 6.H.2.

30/08/2026 — v6.H.1. Tách tầng trình bày khỏi Instruction v6.0 thành bản riêng. Chuyển nguyên văn mục 14, 14B (14B.1–14B.11), 15 và các dòng checklist/Quality Gate về hình thức sang bản này, giữ 100% khung HTML gốc. Bổ sung mới: H0 (luật nạp, luật xung đột, lệnh ~~6.H), H3 (typography tách riêng), H4.1/H4.4/H4.6–H4.9/H4.11–H4.15 (viết đủ HTML cho các khối trước đây chỉ mô tả rút gọn ở 14B.6), H6 (khối chốt đủ 5 phần trong một khối HTML liền), H8 — định mức số chữ và số phần tử, H9 (file preview + nút copy), H10 (bảng kiểm hợp nhất P1–P18). Phiên bản: 6.H.1.