# VPĐK Tam Dương

Công cụ web một trang của Chi nhánh Văn phòng đăng ký đất đai Tam Dương: Hồ sơ BPKT, Pháp luật đất đai, Bản đồ DGN.

## Đưa lên GitHub Pages
1. Tạo repository mới trên GitHub (ví dụ `vpdk-tam-duong`).
2. Add file > Upload files, kéo thả toàn bộ file trong thư mục này (index.html, manifest.webmanifest, 3 file icon, .nojekyll), bấm Commit changes.
3. Settings > Pages > Build and deployment: Source = "Deploy from a branch", Branch = `main`, thư mục `/ (root)`, bấm Save.
4. Chờ 1-2 phút, trang có địa chỉ `https://<tên-tài-khoản>.github.io/<tên-repo>/`.

## Tư vấn bằng Claude
Mỗi người dùng bấm "Kết nối Claude của tôi" trong mục Pháp luật đất đai và dán khóa API Anthropic của mình (tạo tại console.anthropic.com, tính phí theo lượng dùng). Khóa chỉ lưu trong trình duyệt của máy đó. Không kết nối thì Tư vấn dùng tra cứu từ khóa.

Không dán khóa vào file index.html: repo công khai thì ai cũng đọc được.

## Dữ liệu
Hồ sơ nạp từ Excel, bản đồ DGN, văn bản tải lên đều lưu trong trình duyệt của từng máy, không đưa lên GitHub.
