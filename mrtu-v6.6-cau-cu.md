Instruction v6.6 — Cẩu cũ (con của v6.0) — Site Map / Audit Baseline
📌 Audit baseline 02/11/2026. Đã crawl đủ 6 trang /collections/cau-cu ⇒ 62 Product duy nhất (12/12/12/12/12/2), cả 62 trả HTTP 200, canonical tự trỏ về /products/{handle}. Chưa có dữ liệu GSC/GA4/tồn kho ⇒ mọi quyết định gộp/301 ở trạng thái chờ GSC trước khi làm.

0.0. Vai của bản này
Đây là Instruction con v6.6 cho cụm cẩu cũ (cẩu lốp, cẩu xích đã qua sử dụng). Kế thừa 100% Instruction v6.0, không đặt quy tắc viết riêng.
Chỉ giữ: kiến trúc URL, registry từ khoá, bảng audit 62 Product, quyết định giữ/gộp/chuyển vai/301, nhật ký.
Liên quan: v6.3 LiuGong (cẩu lốp mới), v6.4 Kanglim (giữ Product Hyundai HD320 + KS5206). Không ghi đè quyết định của v6.3/v6.4.
Lệnh cập nhật: ~~6.6 cho sitemap/registry/audit cẩu cũ · ~~6.0 cho quy tắc chung.
0. Trạng thái tổng quan
Quyết định	Số URL	Ghi chú
✅ Giữ nguyên vai Product	28	Gồm HD320 theo v6.4
✏️ Giữ + sửa title/H1	20	Title kiểu blog: “10 lý do”, “đánh giá chi tiết”, “giá bao nhiêu”, “hiệu suất vượt trội”…
✏️ Giữ + xác minh / thu hẹp	4	Kobelco 7100 (50 hay 100 tấn), XCMG 130 tấn (2 model, rớt đời), Zoomlion 80 tấn (ôm giá nhiều đời), Tadano GR-800EX (2 đời trong 1 trang)
⚠️ Ứng viên gộp	2	Sany STC550T 2019 ↔ Sany STC550T5-1 2019
🔀 Chuyển vai (301 sau khi duyệt)	3	Tư vấn hoán cải · Tadano cũ tổng quan · Kato KR-500 catalogue
✅ Giữ + gỡ khỏi cau-cu	5	Máy khoan cọc nhồi / xi măng đất, đã có ở /collections/khoan-coc-nhoi
❌ Xoá (404/410)	0	Không có URL nào đủ căn cứ để xoá
Kết luận chính: 62 Product không trùng nội dung với nhau (độ trùng cụm 3 từ cao nhất ≈ 18%, không trùng ảnh). Rủi ro ăn thịt từ khoá nằm ở tầng trên: collection cau-cu, 1 trang bảng giá và 4–5 blog cùng nhắm “bán / giá cẩu cũ”, cộng 3 Product đang đóng vai hub. Không gộp Product chỉ vì cùng model (6 trang Kobelco RK250 là 6 máy khác đời).

1. Kiến trúc URL — cây mục tiêu
/collections/cau-cu                      ← Collection: mua/bán cẩu cũ (owner)
├── /collections/cau-lop                 ← lọc loại (mới + cũ)
├── /collections/cau-xich
├── /collections/tadano · /sany · /xcmg · /zoomlion   ← lọc hãng
│
├── Pillar giá:    /pages/bang-gia-xe-cau-cu-cap-nhat-2026      (đã có)
├── Pillar đa hãng: /blogs/news/danh-sach-xe-cau-banh-lop-banh-xich-vietnhatcorp (đã có)
│
├── Cluster
│   ├── giá cẩu xích cũ:     /blogs/news/tong-hop-gia-ban-gia-thue-cau-xich-tham-khao
│   ├── thuê cẩu xích:       /blogs/news/bao-gia-thue-cau-banh-xich-100-500-tan
│   ├── chọn cẩu lốp cũ theo tải: /blogs/news/ban-xe-cau-banh-lop-cu-25-4000-tan-toan-quoc (đổi vai)
│   ├── các đời Kato 25 tấn: /blogs/news/tong-quan-cac-doi-xe-cau-kato-25-tan
│   ├── pháp lý cẩu chuyên dùng: /blogs/news/phap-ly-dang-kiem-xe-cau-chuyen-dung
│   └── CẦN TẠO (mục 4)
│
└── Product: /products/{handle}  ← 1 máy cụ thể (mục 3)
2. Tầng trên — vai và việc cần làm
URL	Vai	Hiện trạng	Việc cần làm	Ưu tiên
/collections/cau-cu	Collection — “xe cẩu cũ, mua cẩu cũ, cẩu đã qua sử dụng”	~1.690 từ, kiêm luôn tổng quan, lợi ích, giá; câu “giá cũ bằng 50–70% giá mới” không có nguồn; lẫn máy khoan + trang dịch vụ	Rút mô tả về vai danh mục (phân loại + cách lọc + quy trình kiểm tra/mua). Bỏ/dẫn nguồn câu 50–70%. Chuyển phần giá sang Pillar giá bằng link. Gỡ 5 máy khoan + trang hoán cải	🔴 1
/pages/bang-gia-xe-cau-cu-cap-nhat-2026	Pillar giá — “giá xe cẩu cũ, bảng giá cẩu cũ”	~5.580 từ	Giữ. Nhận bảng giá theo đời từ Product Zoomlion 80 tấn. Link sang từng Product đang bán	🟡 2
/blogs/news/danh-sach-xe-cau-banh-lop-banh-xich-vietnhatcorp	Pillar đa hãng (mới + cũ)	~3.700 từ	Giữ. Không nhắm “cẩu cũ” trần. Link về collection cau-cu ở phần cũ	🟢 3
/blogs/news/ban-xe-cau-banh-lop-cu-25-4000-tan-toan-quoc	Đang tranh “bán xe cẩu bánh lốp cũ” với collection	Blog dạng bán hàng, ~2.110 từ	Đổi vai thành Cluster “chọn cẩu lốp cũ theo tải trọng”: bỏ “Bán” khỏi title/H1, giữ URL, link về cau-cu và Product. Không 301 khi chưa có GSC	🔴 1
/blogs/news/ban-cho-thue-cau-xich-moi-cu	Trùng intent “bán & cho thuê cẩu xích”	~2.200 từ	⚠️ Ứng viên gộp vào bài 35–1200 tấn (bài dài hơn). Chọn bài thắng theo GSC, gộp nội dung riêng, 301 bài thua	🟡 2
/blogs/news/ban-cho-thue-cau-xich-35-1200-tan-toan-quoc	Như trên	~3.070 từ	Xem dòng trên	🟡 2
/blogs/news/tong-hop-gia-ban-gia-thue-cau-xich-tham-khao	Cluster giá cẩu xích (cũ & thuê)	~3.720 từ	Giữ. Owner “giá cẩu xích cũ”	🟢 3
/collections/tadano	Collection hãng — “cẩu Tadano (cũ)”	~250 từ, mỏng	Nhận nội dung từ Product xe-cau-banh-lop-tadano-cu	🔴 1
/collections/khoan-coc-nhoi	Collection máy khoan	Đã chứa đủ 5 máy khoan	Giữ, là nơi duy nhất liệt kê máy khoan	🔴 1
⚠️ v6.3 đang dùng /blogs/news/phap-ly-dang-kiem-xe-cau-2026 (xe tải gắn cẩu, QCVN 09:2024) làm cluster pháp lý cho cẩu lốp. Với cẩu lốp/xích (xe máy chuyên dùng) nên link /blogs/news/phap-ly-dang-kiem-xe-cau-chuyen-dung. Cần Mr Tú chốt.

3. Audit 62 Product
Chuẩn title Product: {Loại cẩu} {X} tấn {Hãng} {Model} đời {Năm} đã qua sử dụng (+ nguồn nhập nếu xác minh). Không thêm số liệu chưa có trong bài/catalogue. Giữ nguyên slug: không đổi slug chỉ để đẹp.

#	Trang	Handle (/products/)	Title hiện tại	Nhóm	Quyết định	Việc cần làm	Ưu tiên
1	1	cau-lop-cu-kobelco-rk250-6-doi-2004	10 Lý Do Nên Mua Cẩu Lốp KOBELCO RK250-6 Đời 2004	Cẩu lốp	✏️ GIỮ + SỬA TITLE	Đổi title/H1 về dạng Product: loại · hãng · model · tải · đời · tình trạng; bỏ cụm kiểu blog.	🟡 2
2	1	can-cau-banh-xich-65-tan-sumitomo-sc650-2-cu-1995	Bán cần cẩu bánh xích 65 tấn Sumitomo SC650-2 đời 1995 cũ, nhập khẩu Nhật Bản	Cẩu xích	✅ GIỮ	Giữ title; chỉ chuẩn hoá theo mẫu khi sửa nội dung.	🟢 3
3	1	cau-80-tan-tadano-gr-800ex-cu-2017-2018	Bán Cẩu 80 tấn Tadano GR-800EX Nhập Singapore đời 2017 và 2018 cũ	Cẩu lốp	✏️ GIỮ	Title ghi 2 đời. Nếu 2 máy bán riêng ⇒ ghi rõ từng máy trong bài; không tách khi chưa có dữ liệu.	🟢 3
4	1	cau-banh-lop-tadano-gr-120nl-1-cu-2004	Bán Cẩu bánh lốp 12 tấn Tadano nhập Nhật đời 2004 cũ	Cẩu lốp	✅ GIỮ	Giữ title; chỉ chuẩn hoá theo mẫu khi sửa nội dung.	🟢 3
5	1	cau-banh-lop-13-tan-kato-krm13h-2-cu-2009	Bán Cẩu bánh lốp 13 tấn Kato KRM13H-2 nhập Nhật đời 2009 cũ	Cẩu lốp	✅ GIỮ	Giữ title; chỉ chuẩn hoá theo mẫu khi sửa nội dung.	🟢 3
6	1	cau-banh-xich-kobelco-7120-cu-2005	Bán Cẩu Bánh Xích 120 tấn cũ Kobelco 7120 đời 2005 nhập Nhật	Cẩu xích	✅ GIỮ	Giữ title; chỉ chuẩn hoá theo mẫu khi sửa nội dung.	🟢 3
7	1	cau-banh-xich-kobelco-7055-cu-1991	Bán Cẩu bánh xích 55 tấn Kobelco 7055 cũ đời 1991 nhập Nhật	Cẩu xích	✅ GIỮ	Giữ title; chỉ chuẩn hoá theo mẫu khi sửa nội dung.	🟢 3
8	1	cau-banh-xich-80-tan-kh300-3-cu-1996	Bán cẩu bánh xích 80 tấn KH300-3 đời 1996 cũ nhập Nhật	Cẩu xích	✅ GIỮ	Giữ title; chỉ chuẩn hoá theo mẫu khi sửa nội dung.	🟢 3
9	1	cau-banh-xich-kobelco-7080-cu-1996	Bán Cẩu bánh xích 80 tấn Kobelco 7080 đời 1996 cũ nhập Hàn Quốc	Cẩu xích	✅ GIỮ	Giữ title; chỉ chuẩn hoá theo mẫu khi sửa nội dung.	🟢 3
10	1	cau-lop-25-tan-cu-kobelco-rk250-3-doi-1996	Bán Cẩu lốp 25 tấn cũ Kobelco RK250-3 đời 1996 Nhập Nhật	Cẩu lốp	✅ GIỮ	Giữ title; chỉ chuẩn hoá theo mẫu khi sửa nội dung.	🟢 3
11	1	cau-lop-25-tan-kato-kr-25h-v6-cu-2007	Bán Cẩu lốp 25 tấn Kato KR-25H-V6 đời 2007 cũ nhập Nhật	Cẩu lốp	✅ GIỮ	Giữ title; chỉ chuẩn hoá theo mẫu khi sửa nội dung.	🟢 3
12	1	cau-lop-55-tan-zoomlion-qy55v-cu-2018	Bán Cẩu lốp 55 tấn cũ Zoomlion QY55V đời 2018 nhập Trung Quốc	Cẩu lốp	✅ GIỮ	Giữ title; chỉ chuẩn hoá theo mẫu khi sửa nội dung.	🟢 3
13	2	cau-lop-60-tan-tadano-gr600ex-3-cu-2015	Bán Cẩu lốp 60 tấn Tadano GR600EX-3 đời 2015 nhập Singapore	Cẩu lốp	✅ GIỮ	Giữ title; chỉ chuẩn hoá theo mẫu khi sửa nội dung.	🟢 3
14	2	cau-lop-80-tan-sany-stc800-2019-cu	Bán Cẩu Lốp 80 Tấn SANY STC800 đời 2019 Cũ – Giá Tốt	Cẩu lốp	✏️ GIỮ + SỬA TITLE	Đổi title/H1 về dạng Product: loại · hãng · model · tải · đời · tình trạng; bỏ cụm kiểu blog.	🟡 2
15	2	cau-lop-kato-50-tan-kr50h-l2-nhap-nhat-cu-2005	Bán Cẩu lốp Kato 50 tấn KR50H-L2 nhập Nhật đời 2005 cũ, giá tốt tại Vietnhatcorp	Cẩu lốp	✏️ GIỮ + SỬA TITLE	Đổi title/H1 về dạng Product: loại · hãng · model · tải · đời · tình trạng; bỏ cụm kiểu blog.	🟡 2
16	2	ban-cau-xich-100-tan-kobelco-7100-doi-1995	Bán Cẩu Xích 100 Tấn Kobelco 7100 Đời 1995 / Hiệu Suất Bền Bỉ & Giá Tốt	Cẩu xích	✏️ GIỮ + XÁC MINH	Card/alt ghi 50 tấn, title/slug 100 tấn. Xác minh tải thật rồi đồng bộ title, alt, mô tả.	🔴 1
17	2	cau-xich-130-tan-xcmg-xgc130-i-2016	Bán Cẩu Xích 130 Tấn XCMG XGC130-I Đời 2016 Nhập Khẩu Trung Quốc	Cẩu xích	✅ GIỮ	Giữ title; chỉ chuẩn hoá theo mẫu khi sửa nội dung.	🟢 3
18	2	ban-may-khoan-coc-nhoi-xcmg-xr280e-cu-2020-5000h	Bán Máy Khoan Cọc Nhồi XCMG XR280E Cũ (SX 12/2020, 5000h) - Hiệu Suất Đỉnh Cao	Máy khoan	✅ GIỮ + GỠ KHỎI cau-cu	Giữ Product; gỡ khỏi cau-cu, giữ ở /collections/khoan-coc-nhoi (đã gán). Không redirect.	🔴 1
19	2	may-khoan-xi-mang-dat-nippon-sharyo-dh658-135m-cu-1995	Bán Máy khoanxi măng đất cũ NIPPON SHARYO DH658-135M đời 1995 Nhật Bản	Máy khoan	✅ GIỮ + GỠ KHỎI cau-cu	Giữ Product; gỡ khỏi cau-cu, giữ ở /collections/khoan-coc-nhoi (đã gán). Không redirect.	🔴 1
20	2	xe-cau-banh-lop-100-tan-tadano-gr-1000ex-4-cu-2022	Bán xe cẩu bánh lốp 100 tấn TADANO GR-1000EX-4 cũ đời 2022 nhập Singapore	Cẩu lốp	✅ GIỮ	Giữ title; chỉ chuẩn hoá theo mẫu khi sửa nội dung.	🟢 3
21	2	can-cau-banh-xich-cu-100-tan-zoomlion-zcc1000	Cần cẩu Bánh xích cũ 100 tấn Zoomlion ZCC1000 đời 2020: Chi tiết & Lợi ích đầu tư	Cẩu xích	✏️ GIỮ + SỬA TITLE	Đổi title/H1 về dạng Product: loại · hãng · model · tải · đời · tình trạng; bỏ cụm kiểu blog.	🟡 2
22	2	cau-banh-lop-40-tan-sany-stc400e5	Cẩu Bánh Lốp 40 Tấn SANY STC400E5 Đời 2021: Thông Số & Giá	Cẩu lốp	✏️ GIỮ + SỬA TITLE	Đổi title/H1 về dạng Product: loại · hãng · model · tải · đời · tình trạng; bỏ cụm kiểu blog. Chưa gán /collections/cau-lop ⇒ gán.	🟡 2
23	2	cau-banh-lop-sany-stc550t-55-tan	Cẩu Bánh Lốp Sany STC550T 55 Tấn đời 2019 – Thông Số Kỹ Thuật & Báo Giá	Cẩu lốp	⚠️ ỨNG VIÊN GỘP	Cùng hãng/tải/đời với STC550T5-1 2019. Đối chiếu ảnh, số khung, giá: cùng 1 máy ⇒ gộp vào URL có GSC tốt hơn + 301; khác máy ⇒ giữ, ghi rõ khác biệt. Chưa gán /collections/cau-lop ⇒ gán.	🔴 1
24	2	cau-banh-xich-hitachi-kh150-3-40-tan-cu-1988	Cẩu Bánh Xích 40 Tấn Hitachi KH150-3 Cũ Nhập Nhật 1988	Cẩu xích	✅ GIỮ	Giữ title; chỉ chuẩn hoá theo mẫu khi sửa nội dung.	🟢 3
25	3	cau-banh-xich-thuy-luc-hitachi-kh230-3-doi-1995	Cẩu Bánh Xích 60 tấn HITACHI KH230-3 Đời 1995: Đánh Giá Chi Tiết & Ưu Điểm	Cẩu xích	✏️ GIỮ + SỬA TITLE	Đổi title/H1 về dạng Product: loại · hãng · model · tải · đời · tình trạng; bỏ cụm kiểu blog.	🟡 2
26	3	cau-banh-xich-sumitomo-sc800-80-tan-doi-1994	Cẩu Bánh Xích 80 Tấn Sumitomo SC800 (1994) – Bền Bỉ, Mạnh Mẽ / Vietnhatcorp.net	Cẩu xích	✏️ GIỮ + SỬA TITLE	Đổi title/H1 về dạng Product: loại · hãng · model · tải · đời · tình trạng; bỏ cụm kiểu blog. Chưa gán /collections/cau-xich ⇒ gán.	🟡 2
27	3	cau-banh-xich-xcmg-xgc55-55-tan-doi-2019	Cẩu Bánh Xích Cũ 55 Tấn XCMG XGC55 – Hiệu Suất Vượt Trội / Cẩu cũ đời 2019	Cẩu xích	✏️ GIỮ + SỬA TITLE	Đổi title/H1 về dạng Product: loại · hãng · model · tải · đời · tình trạng; bỏ cụm kiểu blog.	🟡 2
28	3	cau-banh-xich-cu-65-tan-kobelco-7065	Cẩu Bánh Xích Cũ 65 Tấn Kobelco 7065 (1996, Cần 36m) nhập Nhật	Cẩu xích	✅ GIỮ	Giữ title; chỉ chuẩn hoá theo mẫu khi sửa nội dung. Chưa gán /collections/cau-xich ⇒ gán.	🟢 3
29	3	cau-banh-xich-cu-kobelco-bm600-doi-1996	Cẩu bánh xích cũ Kobelco BM600 đời 1996 nhập Hàn Quốc	Cẩu xích	✅ GIỮ	Giữ title; chỉ chuẩn hoá theo mẫu khi sửa nội dung.	🟢 3
30	3	cau-banh-xich-kobelco-cke2500-2-250-tan-doi-2008	Cẩu Bánh Xích Kobelco CKE2500-2 250 Tấn Đời 2008 – Boom 73m + Jib 30m	Cẩu xích	✅ GIỮ	Giữ title; chỉ chuẩn hoá theo mẫu khi sửa nội dung. Chưa gán /collections/cau-xich ⇒ gán.	🟢 3
31	3	cau-banh-xich-kobelco-cke900g-90-tan-cu	Cẩu bánh xích Kobelco CKE900G 90 tấn cũ đời 2013 nhập khẩu	Cẩu xích	✅ GIỮ	Giữ title; chỉ chuẩn hoá theo mẫu khi sửa nội dung. Chưa gán /collections/cau-xich ⇒ gán.	🟢 3
32	3	cau-banh-xich-sany-scc2000-200-tan-cu-2017	Cẩu Bánh Xích SANY SCC2000 200 Tấn Cũ 2017 – Hàng sẵn cửa khẩu	Cẩu xích	✅ GIỮ	Giữ title; chỉ chuẩn hoá theo mẫu khi sửa nội dung.	🟢 3
33	3	cau-banh-xich-sumitomo-sc1500-2-150-tan-cu-doi-1997	Cẩu Bánh Xích Sumitomo SC1500-2 (150 Tấn) Cũ Đời 1997 / Việt Nhật	Cẩu xích	✅ GIỮ	Giữ title; chỉ chuẩn hoá theo mẫu khi sửa nội dung.	🟢 3
34	3	cau-dia-hinh-kato-25-tan-kr-25h-v2-doi-2005	Cẩu Địa Hình KATO KR-25H-V2 25 Tấn Đời 2005 / Vietnhatcorp.net	Cẩu lốp	✅ GIỮ	Giữ title; chỉ chuẩn hoá theo mẫu khi sửa nội dung. Chưa gán /collections/cau-lop ⇒ gán.	🟢 3
35	3	cau-lop-25-tan-cu-kobelco-rk250-8-doi-2013-nhap-nhat	Cẩu Lốp 25 Tấn Cũ Kobelco RK250-8 Đời 2013 Nhập Nhật / Giá Tốt, Chất Lượng Cao	Cẩu lốp	✏️ GIỮ + SỬA TITLE	Đổi title/H1 về dạng Product: loại · hãng · model · tải · đời · tình trạng; bỏ cụm kiểu blog.	🟡 2
36	3	cau-lop-50-tan-tadano-gr500n-1-nhat-bai	Cẩu Lốp 50 Tấn Tadano GR500N-1 Đời 2004 Nhật Bãi – 3,5 Tỷ	Cẩu lốp	✅ GIỮ	Giữ title; chỉ chuẩn hoá theo mẫu khi sửa nội dung. Chưa gán /collections/cau-lop ⇒ gán.	🟢 3
37	4	cau-lop-55-tan-cu-sany-stc550t5-1-doi-2019	Cẩu Lốp 55 Tấn Cũ Sany STC550T5-1 Đời 2019: Hiệu Suất Cao, Giá Tốt	Cẩu lốp	⚠️ ỨNG VIÊN GỘP	Xem dòng STC550T. Bỏ “Hiệu suất cao, giá tốt” khỏi title.	🔴 1
38	4	cau-lop-90-tan-xcmg-qy90k-doi-2011	Cẩu lốp 90 tấn XCMG QY90K đời 2011 hàng sẵn Việt Nam - Thông số và Catalogue	Cẩu lốp	✏️ GIỮ + SỬA TITLE	Đổi title/H1 về dạng Product: loại · hãng · model · tải · đời · tình trạng; bỏ cụm kiểu blog.	🟡 2
39	4	cau-kobelco-rk450-45-tan-doi-1990-nhat-bai	Cẩu lốp bánh béo 45 tấn Kobelco Rk450 đời 1990 Nhật Bãi.	Cẩu lốp	✅ GIỮ	Giữ title; chỉ chuẩn hoá theo mẫu khi sửa nội dung.	🟢 3
40	4	cau-lop-can-gian-kobelco-mk500	Cẩu Lốp Cần Giàn Kobelco MK500: Đột Phá Công Nghệ & Hiệu Suất Vượt Trội	Cẩu lốp cần giàn	✏️ GIỮ + SỬA TITLE	Xác minh tình trạng cũ/đời. Blog 5-dieu-soc-ve-sieu-can-cau-kobelco-mk500 phải link về Product, không nhắm “mua/giá MK500”.	🟡 2
41	4	cau-lop-cu-25-tan-kobelco-rk250-6-doi-2003	Cẩu lốp cũ 25 tấn KOBELCO RK250-6 đời 2003: Đánh giá chi tiết & Lợi ích đầu tư	Cẩu lốp	✏️ GIỮ + SỬA TITLE	Đổi title/H1 về dạng Product: loại · hãng · model · tải · đời · tình trạng; bỏ cụm kiểu blog.	🟡 2
42	4	cau-lop-xcmg-xct130-xca130-130-tan-doi-2023	Cẩu lốp XCMG 130 tấn mới rớt đời 2023 giá cũ	Cẩu lốp	✏️ GIỮ + XÁC MINH	2 model trong 1 Product, “mới rớt đời” ≠ đã qua sử dụng. Xác minh tình trạng; 2 máy ⇒ tách 2 Product; hàng chưa sử dụng ⇒ gỡ khỏi cau-cu, giữ ở xcmg/cau-lop.	🟡 2
43	4	cau-xich-70-tan-kobelco-doi-2008-nhap-nhat	Cẩu xích 70 tấn Kobelco 7070-1F Đời 2008 Nhập Nhật: Thông số & Đánh giá chi tiết	Cẩu xích	✏️ GIỮ + SỬA TITLE	Đổi title/H1 về dạng Product: loại · hãng · model · tải · đời · tình trạng; bỏ cụm kiểu blog.	🟡 2
44	4	cau-xich-cu-50-tan-sumitomo-sc500-doi-1995	Cẩu Xích Cũ 50 Tấn Sumitomo SC500 Đời 1995: Đánh Giá Chuyên Sâu & Báo Giá	Cẩu xích	✏️ GIỮ + SỬA TITLE	Đổi title/H1 về dạng Product: loại · hãng · model · tải · đời · tình trạng; bỏ cụm kiểu blog.	🟡 2
45	4	cau-xich-ong-long-30-tan-zoomlion-zct300v-2021	Cẩu Xích Ống Lồng 30 Tấn Zoomlion ZCT300V – Đời 2021 / Giá 1,860 Tỷ	Cẩu xích	✅ GIỮ	Giữ title; chỉ chuẩn hoá theo mẫu khi sửa nội dung. Chưa gán /collections/cau-xich ⇒ gán.	🟢 3
46	4	cau-banh-beo-25-tan-doi-1991-kobelco-rk250-2	Đánh Giá Chi Tiết Cẩu Bánh Béo 25 Tấn Đời 1991 Kobelco RK250-2	Cẩu lốp	✏️ GIỮ + SỬA TITLE	Đổi title/H1 về dạng Product: loại · hãng · model · tải · đời · tình trạng; bỏ cụm kiểu blog.	🟡 2
47	4	cau-lop-80-tan-zoomlion-doi-2018-2022	Giá bán Cẩu Lốp 80 Tấn Zoomlion Đời 2018 - Cập nhật mới nhất.	Cẩu lốp	✏️ GIỮ + THU HẸP	Đang ôm “giá cẩu lốp 80 tấn” nhiều đời. Thu về 1 máy (đời, model ZTC800V532-1); chuyển bảng giá theo đời sang /pages/bang-gia-xe-cau-cu-cap-nhat-2026. Sửa tag STC800V (mã Sany).	🔴 1
48	4	kato-kr-500-rough-terrain-crane-50-tan-thong-so	Giá cẩu Kato 50 tấn 1995 - 2012 Nhật bản - Thông số và Catalogue chi tiết	Hub dòng (giả Product)	🔀 CHUYỂN VAI	Không phải 1 máy cụ thể (tag Catalogue, title “1995–2012”). Nếu có máy thật ⇒ viết lại thành Product 1 máy; nếu không ⇒ chuyển thành blog tổng quan các đời Kato 50 tấn (CẦN TẠO) + 301.	🔴 1
49	5	khoan-xi-mang-dat-dh508-105m-cu-1990-nhap-han-quoc	Khoan Xi Măng Đất DH508-105M Cũ Đời 1990 Nhập Hàn Quốc / Máy đóng cọc toàn phần	Máy khoan	✅ GIỮ + GỠ KHỎI cau-cu	Giữ Product; gỡ khỏi cau-cu, giữ ở /collections/khoan-coc-nhoi (đã gán). Không redirect.	🔴 1
50	5	khoan-xi-mang-dat-nippon-sharyo-dh558-110m	Khoan xi măng đất NIPPON SHARYO DH558-110M: Hiệu Suất & Ổn Định Vượt Trội cho Nền Móng	Máy khoan	✅ GIỮ + GỠ KHỎI cau-cu	Giữ Product; gỡ khỏi cau-cu, giữ ở /collections/khoan-coc-nhoi (đã gán). Không redirect.	🔴 1
51	5	khoan-xi-mang-dat-nippon-sharyo-dh608-120m	Khoan Xi Măng Đất Nippon Sharyo DH608-120M đời 1991: Đánh Giá & Ứng Dụng	Máy khoan	✅ GIỮ + GỠ KHỎI cau-cu	Giữ Product; gỡ khỏi cau-cu, giữ ở /collections/khoan-coc-nhoi (đã gán). Không redirect.	🔴 1
52	5	thanh-ly-cau-banh-beo-35-tan-cu-zoomlion-rt35-doi-2015	Thanh lý Cẩu Bánh Béo 35 Tấn Cũ Zoomlion RT35 Đời 2015 – Hiệu Suất Cao, Giá Tốt	Cẩu lốp	✏️ GIỮ + SỬA TITLE	Đổi title/H1 về dạng Product: loại · hãng · model · tải · đời · tình trạng; bỏ cụm kiểu blog.	🟡 2
53	5	tu-van-hoan-cai-xe-tai-chuyen-dung	Tư vấn Hoán Cải Xe Tải Chuyên Dụng 2025 – Quy Trình Chuẩn / Vietnhatcorp.net	Dịch vụ	🔀 CHUYỂN VAI → 301	Gộp phần riêng (quy trình tư vấn, CTA) vào /blogs/news/hoan-cai-xe-tai-quy-dinh-thu-tuc-cap-nhat-moi-nhat-2026, sau đó 301 về bài này. Gỡ khỏi cau-cu ngay.	🔴 1
54	5	xe-cau-25-tan-xcmg-qy25k-doi-2021	Xe Cẩu 25 tấn XCMG QY25K Đời 2021 Giá Bao Nhiêu?	Cẩu lốp	✏️ GIỮ + SỬA TITLE	Đổi title/H1 về dạng Product: loại · hãng · model · tải · đời · tình trạng; bỏ cụm kiểu blog.	🟡 2
55	5	xe-cau-kobelco-rk250-7-25-tan-2013	Xe Cẩu Bánh Béo 25 Tấn Kobelco RK250-7 Đời 2013: Giải Pháp Nâng Hạ Tối Ưu Cho Mọi Công Trình	Cẩu lốp	✏️ GIỮ + SỬA TITLE	Đổi title/H1 về dạng Product: loại · hãng · model · tải · đời · tình trạng; bỏ cụm kiểu blog.	🟡 2
56	5	xe-cau-kobelco-rk500-2-50-tan-2005	Xe Cẩu Bánh Lốp 50 Tấn Kobelco RK500-2 (2005) – Nhập Khẩu Nhật /Hàng sẵn giao luôn	Cẩu lốp	✅ GIỮ	Giữ title; chỉ chuẩn hoá theo mẫu khi sửa nội dung. Chưa gán /collections/cau-lop ⇒ gán.	🟢 3
57	5	xe-cau-banh-lop-tadano-cu	Xe Cẩu Bánh Lốp Tadano Cũ Nhập Nhật – Tổng Quan 2026	Hub hãng (giả Product)	🔀 CHUYỂN VAI → 301	Chuyển nội dung tổng quan sang /collections/tadano (hiện ~250 từ), rồi 301 Product → /collections/tadano. Kiểm GSC trước.	🔴 1
58	5	xe-cau-banh-xich-100-tan-sumitomo-sc1000-1995	Xe cẩu bánh xích 100 tấn Sumitomo SC1000 (1995) nhập khẩu từ Hàn Quốc	Cẩu xích	✅ GIỮ	Giữ title; chỉ chuẩn hoá theo mẫu khi sửa nội dung.	🟢 3
59	5	cau-banh-xich-ihi-cch800-80-tan-doi-1993	Xe Cẩu Bánh Xích IHI CCH800 80 Tấn – Giá Tốt, Cần Dài / Vietnhatcorp.net	Cẩu xích	✏️ GIỮ + SỬA TITLE	Đổi title/H1 về dạng Product: loại · hãng · model · tải · đời · tình trạng; bỏ cụm kiểu blog.	🟡 2
60	5	xe-cau-lop-145-tan-tadano-gr-1450ex-cu-2016	Xe Cẩu Lốp 145 Tấn Tadano GR-1450EX Cũ 2016 – Nhập Nhật	Cẩu lốp	✅ GIỮ	Giữ title; chỉ chuẩn hoá theo mẫu khi sửa nội dung. Chưa gán /collections/cau-lop ⇒ gán.	🟢 3
61	6	xe-cau-lop-xcmg-55-tan-cu	Xe Cẩu Lốp XCMG 55 Tấn Cũ: Cần Dài 50m, 6 Đốt – Siêu phẩm đời 2018	Cẩu lốp	✏️ GIỮ + SỬA TITLE	Đổi title/H1 về dạng Product: loại · hãng · model · tải · đời · tình trạng; bỏ cụm kiểu blog.	🟡 2
62	6	xe-hyundai-hd320-2012-cau-kanglim-ks5206-15-tan-cu	Xe Hyundai HD320 đời 2012 gắn cẩu 15 tấn Kanglim KS5206 cũ / Giấc mơ chuyên nghiệp	Xe tải gắn cẩu	✅ GIỮ (theo v6.4)	Giữ vai Product theo v6.4. Bỏ “Giấc mơ chuyên nghiệp”. Gán thêm /collections/xe-tai-gan-cau-15-tan.	🟢 3
3.1. Nhóm cùng model — giữ riêng, phải có khác biệt rõ
Nhóm	URL	Quy tắc
Kobelco RK250 (25 tấn)	RK250-2 1991 · RK250-3 1996 · RK250-6 2003 · RK250-6 2004 · RK250-7 2013 · RK250-8 2013	6 máy khác đời ⇒ giữ cả 6. Title phải có đúng mã đời + năm. RK250-6 2003 và 2004: xác nhận 2 máy thật (ảnh, số khung); trùng máy ⇒ gộp
Kato 25 tấn	KR-25H-V2 2005 · KR-25H-V6 2007	Giữ. Hub các đời = /blogs/news/tong-quan-cac-doi-xe-cau-kato-25-tan
Kato 50 tấn	KR50H-L2 2005 · KR-500 catalogue	KR50H-L2 giữ vai Product. KR-500 chuyển vai (mục 3)
55 tấn cẩu lốp	Sany STC550T · Sany STC550T5-1 · Zoomlion QY55V 2018 · XCMG 55 tấn 2018	Sany: ứng viên gộp. XCMG 55 tấn: thêm mã model vào title khi xác minh
80 tấn cẩu xích	Hitachi KH300-3 · Kobelco 7080 · Sumitomo SC800 · IHI CCH800	4 hãng/model khác ⇒ giữ. KH300-3 thêm “Hitachi” vào title
100 tấn cẩu xích	Kobelco 7100 · Zoomlion ZCC1000 · Sumitomo SC1000	Giữ. Kobelco 7100 xác minh tải
3.2. Gán collection còn thiếu
Các Product cẩu đang chỉ nằm ở cau-cu, chưa nằm ở cau-lop/cau-xich: Sany STC400E5, Sany STC550T, Kobelco 7065, CKE2500-2, CKE900G, Sumitomo SC800, Kato KR-25H-V2, Tadano GR500N-1, Zoomlion ZCT300V, Kobelco RK500-2, Tadano GR-1450EX ⇒ gán đúng loại. HD320 ⇒ gán thêm xe-tai-gan-cau-15-tan.

4. Cluster CẦN TẠO — chỉ tạo khi có GSC/nhu cầu
Ưu tiên	Slug đề xuất	Vai	Điều kiện tạo
🟡 2	/blogs/news/kinh-nghiem-kiem-tra-cau-cu-truoc-khi-mua	Checklist giờ máy, thủy lực, cần, chân chống, hồ sơ nhập khẩu	Rút phần kinh nghiệm khỏi collection cau-cu và Product Tadano. Rà trùng với xe-tai-gan-cau-cu-co-nen-dau-tu
🟡 2	/blogs/news/tong-quan-cac-doi-xe-cau-kato-50-tan	Hub các đời Kato 50 tấn	Chỉ khi KR-500 không phải 1 máy thật; nhận 301 từ KR-500
🟢 3	/blogs/news/tong-quan-cac-doi-cau-kobelco-rk250	Hub các đời RK250 (-2 → -8)	Khi GSC có truy vấn “rk250” không gắn đời; link 6 Product
5. Registry từ khoá và luật phân vai
Từ khoá	Intent	URL sở hữu
xe cẩu cũ, mua cẩu cũ, cẩu đã qua sử dụng	Thương mại	/collections/cau-cu
giá xe cẩu cũ, bảng giá cẩu cũ	Giá	/pages/bang-gia-xe-cau-cu-cap-nhat-2026
giá cẩu xích cũ	Giá	/blogs/news/tong-hop-gia-ban-gia-thue-cau-xich-tham-khao
bán / cho thuê cẩu xích	Thương mại – dịch vụ	Chờ chọn 1 trong 2 bài mục 2
chọn cẩu lốp cũ theo tải trọng	Tư vấn	/blogs/news/ban-xe-cau-banh-lop-cu-25-4000-tan-toan-quoc
cẩu Tadano cũ	Thương mại – hãng	/collections/tadano
các đời Kato 25 tấn	Tìm hiểu	/blogs/news/tong-quan-cac-doi-xe-cau-kato-25-tan
{hãng} {model} {X} tấn đời {năm} cũ	Thương mại – 1 máy	Product tương ứng
hoán cải xe tải	Pháp lý	/blogs/news/hoan-cai-xe-tai-quy-dinh-thu-tuc-cap-nhat-moi-nhat-2026
Tầng	Được nhắm	CẤM nhắm
Collection cau-cu	“xe cẩu cũ / mua cẩu cũ”	Bảng giá chi tiết, kinh nghiệm dài, mã model đơn lẻ
Pillar giá	“giá / bảng giá cẩu cũ”	“mua cẩu cũ” trần
Product	hãng + model + tải + đời	“cẩu cũ” trần, “cẩu lốp X tấn cũ” trần, “giá cẩu X tấn” nhiều đời
Blog/Cluster	long-tail mục 4–5	Từ khoá chính của Collection/Pillar/Product
6. Quy tắc gộp / 301 / xoá cho cụm này
Gộp chỉ khi 2 URL là cùng 1 máy (cùng ảnh, số khung, giá) hoặc cùng intent và GSC cho thấy cả 2 xoay vòng thứ hạng cho cùng truy vấn.
301 chỉ về đích tương đương (Product cùng máy, collection cùng hãng, blog cùng chủ đề). Không 301 hàng loạt về /collections/cau-cu hay trang chủ.
Máy đã bán: giữ URL, ghi “Đã bán”, gợi ý máy cùng tải/hãng. Chỉ 404/410 khi URL không có traffic/backlink và không có đích tương đương.
Không dùng canonical/noindex thay cho quyết định vai. Canonical hiện tự trỏ đúng, không đổi.
Mỗi thay đổi: ghi nguồn → đích vào mục 8, sao lưu HTML trước khi sửa, Mr Tú duyệt trước khi áp dụng trên Haravan.
7. Việc cần làm
[ ] Xuất GSC 16 tháng theo trang + truy vấn cho 62 Product, collection cau-cu, trang bảng giá và 5 blog ở mục 2
[ ] Đợt 1 (🔴): gỡ 5 máy khoan + trang hoán cải khỏi cau-cu; xác minh Kobelco 7100, Sany STC550T/STC550T5-1, Kato KR-500; chuyển nội dung Tadano tổng quan sang collection; rút mô tả collection cau-cu; đổi vai blog bán cẩu lốp cũ
[ ] Đợt 2 (🟡): sửa title 20 Product; tách/thu hẹp XCMG 130 tấn, Zoomlion 80 tấn; chọn bài thắng cụm “bán & cho thuê cẩu xích”
[ ] Đợt 3 (🟢): gán collection còn thiếu (3.2); cân nhắc Cluster mục 4
[ ] Đo GSC sau 2–4 tuần và 8–12 tuần: số URL cùng nhận 1 truy vấn, CTR, vị trí, lead
8. Nhật ký
02/11/2026 — Tạo v6.6. Crawl 6 trang /collections/cau-cu ⇒ 62 Product duy nhất, đều HTTP 200, canonical tự trỏ. Đối chiếu với cau-lop (56 SP), cau-xich (28), tadano (11), khoan-coc-nhoi (6), sitemap blog/page. Lập audit 62 URL và đề xuất kiến trúc. Chưa thay đổi gì trên website.
9. Nguồn
Crawl trực tiếp vietnhatcorp.net ngày 02/11/2026: collection, /products/{handle}.js, sitemap.
Google Search Central — Consolidate duplicate URLs