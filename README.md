# Smart Museum Audio Guide System
Hệ thống thuyết minh bảo tàng thông minh đa nền tảng, tích hợp bản đồ tương tác đa tầng, trình phát âm thanh đồng bộ văn bản thời gian thực (lyric/karaoke sync), quét mã QR hiện vật và bảng điều khiển quản trị tập trung.

---

## 🏛️ Tài liệu kiến trúc & Sơ đồ hệ thống (UML Diagrams)

Các sơ đồ phân tích và thiết kế hệ thống được lưu trữ trực tuyến để đảm bảo chất lượng hiển thị gốc. Bấm vào từng liên kết bên dưới để mở sơ đồ trong tab mới:

* 📌 [Sơ đồ ca sử dụng (Use Case Diagram)](https://github.com/user-attachments/files/33852087/usecase.pdf) — *Mô tả các tác nhân (Khách tham quan, Ban quản trị) và tập tính năng hệ thống.*
<details>
<summary>👉 <b>Nhấn để xem chi tiết danh sách sơ đồ Use Case (19 ảnh)</b></summary>

<br>

#### 1. Chuyển đổi ngôn ngữ thuyết minh
<img width="2550" height="3300" alt="Image" src="https://github.com/user-attachments/assets/31933ea1-46dd-42e3-a0a7-07366bc7e06b" />

#### 2. Quét mã QR tại hiện vật
<img width="2550" height="3300" alt="Image" src="https://github.com/user-attachments/assets/30199807-79f3-44ff-bd47-600f9e4cd4ba" />

#### 3. Tra cứu hiện vật bằng mã số định danh
<img width="2550" height="3300" alt="Image" src="https://github.com/user-attachments/assets/eea91abd-d0a1-4b41-9f40-3e25af2cd1ac" />

#### 4. Phụ đề theo thời gian thực
<img width="2550" height="3300" alt="Image" src="https://github.com/user-attachments/assets/14a11964-7a53-4d9e-8624-27056637bde0" />

#### 5. Điều hướng thuyết minh
<img width="2550" height="3300" alt="Image" src="https://github.com/user-attachments/assets/35bc18e5-f4ea-4bdc-a4e9-7ccbe9c1b4e9" />

#### 6. Bản đồ lộ trình
<img width="2550" height="3300" alt="Image" src="https://github.com/user-attachments/assets/6cbaf79e-23b0-476e-82f8-a3d4d176af22" />

#### 7. Điều khiển phát và xem lịch sử nghe
<img width="2550" height="3300" alt="Image" src="https://github.com/user-attachments/assets/5cdfce52-f02c-4b4f-99fc-39e10a78d311" />

#### 8. Giám sát người dùng trực tuyến
<img width="2550" height="3300" alt="Image" src="https://github.com/user-attachments/assets/b48e6500-b85c-4bd4-90d2-24aac53f1908" />

#### 9. Thống kê ngôn ngữ thuyết minh
<img width="2550" height="3300" alt="Image" src="https://github.com/user-attachments/assets/87f01d86-6dbc-452b-b4e2-c14a0576d4e3" />

#### 10. Thống kê lượt nghe hiện vật
<img width="2550" height="3300" alt="Image" src="https://github.com/user-attachments/assets/4a3f9f0e-ed9e-4496-8ae3-e52072e73ecf" />

#### 11. Thống kê lượt nghe lại hiện vật
<img width="2550" height="3300" alt="Image" src="https://github.com/user-attachments/assets/3583c639-01ed-4f47-9e68-593ce2409f21" />

#### 12. Quản lý hiện vật và thuyết minh
<img width="2550" height="3300" alt="Image" src="https://github.com/user-attachments/assets/c6caecf1-8863-419e-b20d-bef310e406c1" />
<img width="2550" height="3300" alt="Image" src="https://github.com/user-attachments/assets/16afd30a-a787-4343-bd54-589eac7c739e" />
<img width="2550" height="3300" alt="Image" src="https://github.com/user-attachments/assets/136e5724-af4a-434f-a745-7785286df5ae" />
<img width="2550" height="3300" alt="Image" src="https://github.com/user-attachments/assets/99103f4f-f453-46d9-9362-46d7946a895a" />

#### 13. Định vị hiện vật trên bản đồ
<img width="2550" height="3300" alt="Image" src="https://github.com/user-attachments/assets/a501e3a0-80cb-4e88-882c-bb7d817ee106" />

#### 14. Tạo và xuất mã QR hiện vật
<img width="2550" height="3300" alt="Image" src="https://github.com/user-attachments/assets/edcca1db-8c67-452e-a027-2ae314147ff4" />

#### 15. Xem bộ sưu tập hiện vật
<img width="2550" height="3300" alt="Image" src="https://github.com/user-attachments/assets/ed610522-62fc-48bb-b4e6-eebce4b522d2" />
<img width="2550" height="3300" alt="Image" src="https://github.com/user-attachments/assets/56c115b5-3aad-463d-a46e-5c67800f2dad" />

</details>
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
