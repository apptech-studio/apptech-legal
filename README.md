# apptech-legal

Trang **Privacy / Terms / Support** cho các app của AppTech Studio (GitHub Pages — project site).

- URL: https://apptech-studio.github.io/apptech-legal/
- Được link từ landing `apptech-studio.github.io` và dùng làm Privacy/Support URL khai báo trong App Store Connect.

## Cấu trúc
```
index.html                 — danh mục link policy
assets/style.css           — style chung
edugrade/ios/{privacy,terms,support}.html
motodoc/ios/{privacy,terms,support}.html
```

## Deploy
Push lên nhánh `main` → repo Settings → Pages → Source: `main` / `/ (root)`.
URL từng trang, ví dụ:
- https://apptech-studio.github.io/apptech-legal/edugrade/ios/privacy.html
- https://apptech-studio.github.io/apptech-legal/motodoc/ios/privacy.html
