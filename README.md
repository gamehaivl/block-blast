# Tải Block Blast Hack (Mod Menu, No Ads) v10.0.6

Bộ code tĩnh tối ưu cho GitHub Pages, được chuyển từ HTML WordPress gốc của GAMEHAIVL.

## File chính

- `index.html`: trang chính
- `block-blast/index.html`: đường dẫn theo slug gốc
- `404.html`: trang lỗi
- `.nojekyll`: tránh GitHub Pages xử lý Jekyll
- `robots.txt`, `sitemap.xml`: hỗ trợ SEO cơ bản

## Tối ưu đã làm

- Loại bỏ WordPress/PHP/jQuery/Flatsome/wpDiscuz runtime.
- Nhúng CSS và JS trực tiếp để hạn chế lỗi asset không load.
- Giữ title, meta description, canonical, OG, Twitter Card và schema gốc.
- Bổ sung SoftwareApplication schema.
- Chuyển ảnh `/wp-content/...` thành URL tuyệt đối `https://gamehaivl.com/...`.
- Có fallback ảnh khi ảnh gốc không tải được.

## Cách deploy

Upload toàn bộ file trong thư mục này lên root repo GitHub, sau đó bật GitHub Pages ở `Settings → Pages → Deploy from branch → main / root`.
