# HSK 2 · Sơn Thủy — Tiếng Trung Nhật Anh

Website tĩnh gồm trang mục lục và 15 bài tập tương tác. Không cần cài thư viện hoặc chạy lệnh build.

## Đưa lên GitHub Pages

1. Giải nén HSK2_GitHub_Pages.zip.
2. Tạo repository GitHub, ví dụ hsk2-baitap. Chọn Public nếu dùng GitHub Free.
3. Trong repository, chọn Add file → Upload files.
4. Kéo toàn bộ nội dung vừa giải nén, bao gồm thư mục assets, lên thư mục gốc của repository. Sau khi tải lên, phải thấy index.html ngay ở trang Code, cùng cấp với assets và 15 tệp HSK2_BaiXX.html. Không tải riêng tệp ZIP lên.
5. Chọn Commit changes.
6. Vào Settings → Pages. Ở Source, chọn Deploy from a branch; chọn nhánh main và thư mục / (root), rồi Save. Nếu repository dùng tên nhánh khác, chọn đúng nhánh chứa các tệp vừa tải lên.
7. Đợi triển khai xong, mở địa chỉ website hiển thị trong Settings → Pages. Với repository tên hsk2-baitap, địa chỉ thường là https://TEN_TAI_KHOAN.github.io/hsk2-baitap/.

Có thể mất tối đa khoảng 10 phút để thay đổi xuất hiện.

Tài liệu chính thức: https://docs.github.com/en/pages/quickstart

## Cấu trúc

- index.html: mục lục 15 bài
- HSK2_Bai01.html … HSK2_Bai15.html: các bài tập
- assets/son-thuy.css: giao diện dùng chung
- assets/son-thuy.jpg: ảnh nền đi kèm
- .nojekyll: phục vụ các tệp tĩnh trực tiếp, không cần Jekyll

Giữ nguyên tên tệp và thư mục assets để mọi liên kết hoạt động.

## Dữ liệu và chức năng

Giữ nguyên 1.362 câu hỏi, đáp án, giải thích và logic chấm điểm của bản gốc.
Hiệu ứng mờ nằm ở nền và khung giao diện; phần bài tập dùng nền sáng.
Website hoạt động hoàn toàn ở trình duyệt, không cần máy chủ xử lý bài làm.
