# AGENTS.md — VN Calendar App (Landing Page)

## Build & Run
```bash
# Không cần build — static HTML
# Mở trực tiếp:
open index.html

# Hoặc serve local:
python3 -m http.server 8080
# → http://localhost:8080
```

## Deploy
- Branch: `gh-pages` → tự động deploy GitHub Pages
- URL: https://tt88vn.github.io/vncalendar-app/

## Project info
- **Type:** Static HTML/CSS/JS (single file)
- **File duy nhất:** `index.html`
- **Language:** Tiếng Việt
- **Theme:** Dark (`#0D0D1E`), purple accent

## Conventions
- Tất cả trong một file `index.html` — không tách CSS/JS ra file riêng
- Responsive mobile-first
- Không dùng framework hay build tool

## Lưu ý
- Đây là landing page giới thiệu app Android
- Xem repo `vn-lunar-calendar` cho Android app thực tế
- Push lên branch `gh-pages`, không phải `main`
