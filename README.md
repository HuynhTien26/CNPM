# Smart Museum Audio Guide System
Hệ thống thuyết minh bảo tàng thông minh đa nền tảng, tích hợp bản đồ tương tác đa tầng, trình phát âm thanh đồng bộ văn bản thời gian thực (lyric/karaoke sync), quét mã QR hiện vật và bảng điều khiển quản trị tập trung.

---

## 🏛️ Tài liệu kiến trúc & Sơ đồ hệ thống (UML Diagrams)

Các sơ đồ phân tích và thiết kế hệ thống được lưu trữ trực tuyến để đảm bảo chất lượng hiển thị gốc. Bấm vào từng liên kết bên dưới để mở sơ đồ trong tab mới:

* 📌 [Sơ đồ ca sử dụng (Use Case Diagram)]([usecase.pdf](https://github.com/user-attachments/files/33852087/usecase.pdf) — *Mô tả các tác nhân (Khách tham quan, Ban quản trị) và tập tính năng hệ thống.*
* 📌 [Sơ đồ hoạt động (Activity Diagram)](https://raw.githubusercontent.com/HuynhTien26/smart-museum-guide/main/docs/diagrams/activity-diagram.png) — *Quy trình quét mã QR, xác thực vé/mã PIN và đồng bộ phát âm thanh theo tọa độ.*
* 📌 [Sơ đồ thành phần (Component Diagram)](https://raw.githubusercontent.com/HuynhTien26/smart-museum-guide/main/docs/diagrams/component-diagram.png) — *Cấu trúc kết nối giữa Web Client, Mobile App, Shared Packages và Server API.*
* 📌 [Sơ đồ triển khai (Deployment Diagram)](https://raw.githubusercontent.com/HuynhTien26/smart-museum-guide/main/docs/diagrams/deployment-diagram.png) — *Quy hoạch hạ tầng máy chủ, cơ sở dữ liệu, WebSocket gateway và dịch vụ lưu trữ đa phương tiện.*

---

## 📁 Cấu trúc thư mục Monorepo

```text
smart-museum-guide/
├── apps/
│   ├── server-api/             # Backend API & WebSocket realtime engine
│   ├── web-dashboard/          # Web Admin quản trị bảo tàng, cắm mốc tọa độ & cấp mã PIN
│   ├── web-visitor/            # Web dành cho khách tham quan tra cứu & nghe thuyết minh
│   └── mobile-app/             # Ứng dụng di động (React Native) quét QR & đồng bộ âm thanh
├── packages/
│   ├── shared-types/           # Khai báo TypeScript Interfaces / DTOs dùng chung
│   ├── shared-utils/           # Thuật toán thuần: xử lý tọa độ %, lyric-sync, tạo mã PIN
│   └── design-tokens/          # Hệ thống màu sắc và biến giao diện dùng chung
├── .github/workflows/          # Kịch bản CI/CD tự động kiểm tra cú pháp và build
├── pnpm-workspace.yaml         # Khai báo không gian làm việc Monorepo
├── tsconfig.base.json          # Cấu hình TypeScript gốc cho toàn hệ thống
└── turbo.json                  # Cấu hình pipeline thực thi Turborepo
