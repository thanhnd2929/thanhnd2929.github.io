# Portfolio – Nguyễn Đăng Thành

Trang portfolio tĩnh, song ngữ EN/VI, không cần build.

## Chạy thử local
```bash
python3 -m http.server 8000
# mở http://localhost:8000
```

## Deploy lên GitHub Pages
1. Tạo repo GitHub (ví dụ `portfolio`, hoặc `<username>.github.io` để có URL gốc).
2. Đẩy code lên nhánh `main`:
   ```bash
   git remote add origin git@github.com:<username>/portfolio.git
   git push -u origin main
   ```
3. Vào **Settings → Pages → Build and deployment**: Source = *Deploy from a branch*, Branch = `main`, thư mục `/ (root)`.
4. Sau khoảng 1 phút, trang có tại `https://<username>.github.io/portfolio/`.

## Chỉnh nội dung
Sửa trực tiếp `index.html`. Mỗi đoạn có hai bản: `lang="en"` và `lang="vi"`.
