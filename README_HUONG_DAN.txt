E104A - THI TRẮC NGHIỆM
BỘ VỎ PWA ĐA THIẾT BỊ

Tệp:
- index.html: vỏ ứng dụng nhúng Web App Apps Script hiện có
- manifest.webmanifest: tên và cấu hình cài đặt
- service-worker.js: cache vỏ tĩnh; không cache dữ liệu thi
- icons/: biểu tượng E104A
- CODE_GS_PATCH.txt: hướng dẫn cấu hình doGet

Apps Script hiện tại:
https://script.google.com/macros/s/AKfycbw21mPD_1pE1oS5DOeviHVm3SPopT29JRTle8v6o5dxsyyFGBhEoSTBVCOIMQrlTgwYWg/exec

Triển khai:
1. Cấu hình doGet theo CODE_GS_PATCH.txt; không chạy setupDatabase().
2. Deploy phiên bản mới của Apps Script, giữ nguyên Google Sheets.
3. Bật GitHub Pages: Settings > Pages > Deploy from a branch > main > /(root).
4. Android: Chrome > menu > Install app.
5. Windows: Edge/Chrome > Install this site as an app.
6. iPhone/iPad: Safari > Chia sẻ > Add to Home Screen.

Yêu cầu Internet để tải Apps Script và đồng bộ Google Sheets.
Chưa phải APK/EXE native. Có thể cài dạng PWA trên trình duyệt hỗ trợ.
Đăng nhập Google trong iframe có thể bị giới hạn bởi cookie/chính sách trình duyệt; cần kiểm thử trước khi sử dụng rộng rãi.
