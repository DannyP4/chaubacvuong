# Hệ Thống Tài Liệu Học Tập (Veritas)

Giao diện web đẹp cho thư viện tài liệu học thuật với hệ thống xác minh đa cấp độ.

## Yêu cầu

- Node.js 16+
- npm hoặc yarn

## Cài đặt

```bash
npm install
```

## Phát triển

```bash
npm run dev
```

Truy cập http://localhost:3000 trong trình duyệt.

## Build cho production

```bash
npm run build
```

## Triển khai

### Vercel (Khuyên dùng)

1. Push code lên GitHub
2. Truy cập [vercel.com](https://vercel.com)
3. Kết nối repo GitHub
4. Vercel sẽ tự động build và deploy

### Netlify

```bash
npm run build
```

Drag & drop folder `dist` vào [netlify.com](https://netlify.com)

### GitHub Pages

1. Sửa `vite.config.js`: thêm `base: '/repo-name/'`
2. Push lên GitHub
3. Enable GitHub Pages trong Settings

### Heroku

```bash
npm run build
git push heroku main
```

## Cấu trúc dự án

```
src/
  ├── components/
  │   └── DocumentSystem.jsx    (Component chính)
  ├── index.css                 (Styles)
  └── main.jsx                  (Entry point)
index.html                       (HTML chính)
```

## Công nghệ sử dụng

- React 18
- Vite
- Lucide Icons
- CSS-in-JS (Inline styles)

## License

MIT
# chaubacvuong
