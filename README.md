# GuideMétier Web - Hướng dẫn chạy web trên GitHub Pages

Chào mừng bạn đến với **GuideMétier Web**!  
Hướng dẫn này giúp bạn **upload repo và chạy web hoàn chỉnh trên GitHub Pages** mà không cần code thêm.

---

## Bước 1: Giải nén file ZIP
1. Chọn file `guide_metier_fullstack.zip`.  
2. Giải nén vào **thư mục gốc của repo** (nơi chứa `README.md`).  
3. Kiểm tra cấu trúc thư mục, đảm bảo có:
---

## Bước 2: Commit các thay đổi lên GitHub
1. Mở **GitHub Desktop** hoặc **terminal**.  
2. Thêm các file đã giải nén:
```bash
git add .
git commit -m "Giải nén code và chuẩn bị chạy web"
git push origin main
