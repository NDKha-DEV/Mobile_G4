# Project Name

> Repository quản lý mã nguồn cho dự án nhóm.

## 1. Giới thiệu

Đây là repository được sử dụng để quản lý mã nguồn, tài liệu và quá trình phát triển của dự án nhóm.

**Tên dự án:** Chưa xác định
**Môn học:** Phát triển ứng dụng cho các thiết bị di động
**Nhóm:** Nhóm 4
**Thời gian thực hiện:** [Thời gian]

Thông tin về đề tài và phạm vi dự án sẽ được cập nhật sau khi nhóm thống nhất nội dung.

---

## 2. Công nghệ sử dụng

Các công nghệ và công cụ sử dụng trong dự án sẽ được cập nhật sau khi đề tài được xác định.

Dự kiến có thể bao gồm:

- Flutter / Dart
- Git
- GitHub
- Kotlin
- [Công nghệ khác]

---

## 3. Cấu trúc Repository

```text
project-repository/
│
├── README.md
├── .gitignore
├── lib/
├── test/
└── ...
```

### Một số thư mục chính

- `lib/`: Mã nguồn chính của ứng dụng.
- `test/`: Các mã kiểm thử.
- `README.md`: Tài liệu giới thiệu và hướng dẫn sử dụng repository.
- `.gitignore`: Danh sách các tệp/thư mục không đưa lên GitHub.

---

## 4. Cài đặt và chạy dự án

### Yêu cầu môi trường

Cài đặt các công cụ cần thiết trước khi chạy dự án:

- Git
- Flutter SDK
- Android Studio hoặc môi trường phát triển tương đương
- Visual Studio Code hoặc IDE phù hợp

### Clone repository

```bash
git clone <REPOSITORY_URL>
cd <PROJECT_FOLDER>
```

### Cài đặt dependencies

```bash
flutter pub get
```

### Chạy ứng dụng

```bash
flutter run
```

> Các bước cài đặt và chạy dự án sẽ được cập nhật khi nhóm hoàn thiện cấu hình chính thức.

---

## 5. Thành viên nhóm

| STT | Thành viên           | Vai trò     |
| --- | -------------------- | ----------- |
| 1   | Nguyễn Đình Kha      | Nhóm trưởng |
| 2   | Trịnh Quốc Bảo       | Thành viên  |
| 3   | Nguyễn Huy Hoàng     | Thành viên  |
| 4   | Nguyễn Ngọc Thành An | Thành viên  |
| 5   | Nguyễn Tùng Dương    | Thành viên  |

Vai trò của từng thành viên có thể được điều chỉnh theo yêu cầu và phạm vi dự án.

---

## 6. Quy trình làm việc với Git

Nhóm sử dụng GitHub để quản lý mã nguồn và phối hợp phát triển.

### Nhánh chính

```text
main
```

Nhánh `main` chứa phiên bản mã nguồn ổn định của dự án.

### Tạo branch để phát triển

Mỗi thành viên tạo branch riêng cho phần công việc của mình:

```bash
git checkout -b feature/<ten-chuc-nang>
```

Ví dụ:

```bash
git checkout -b feature/login
```

### Commit

Sau khi hoàn thành một phần công việc:

```bash
git add .
git commit -m "feat: add login screen"
```

### Push branch

```bash
git push origin feature/login
```

### Pull Request

Sau khi push branch lên GitHub:

1. Tạo Pull Request vào `main`.
2. Mô tả những thay đổi đã thực hiện.
3. Thành viên khác kiểm tra code.
4. Chỉ merge sau khi code đã được kiểm tra và thống nhất.

---

## 7. Quy tắc đặt tên branch

Sử dụng các tiền tố:

```text
feature/   - Phát triển chức năng mới
fix/       - Sửa lỗi
docs/      - Cập nhật tài liệu
refactor/  - Refactor code
test/      - Bổ sung hoặc sửa test
```

Ví dụ:

```text
feature/login
feature/register
fix/login-validation
docs/update-readme
```

---

## 8. Quy tắc Commit

Khuyến nghị sử dụng commit message ngắn gọn và mô tả đúng thay đổi.

Ví dụ:

```text
feat: add login screen
fix: fix login validation
docs: update README
refactor: simplify authentication service
test: add login tests
```

---

## 9. Pull Request

Mỗi Pull Request nên:

- Có tiêu đề rõ ràng.
- Mô tả những thay đổi đã thực hiện.
- Chỉ chứa các thay đổi liên quan đến nhiệm vụ.
- Được thành viên khác kiểm tra trước khi merge.
- Không commit trực tiếp vào `main` đối với các chức năng phát triển thông thường.

---

## 10. Lưu ý bảo mật

Không commit các thông tin nhạy cảm lên GitHub, bao gồm:

- API keys
- Password
- Access tokens
- File `.env`
- Private credentials
- Các thông tin cấu hình nhạy cảm

Các tệp này cần được khai báo trong `.gitignore` khi cần thiết.

---

## 11. Trạng thái dự án

> Dự án đang trong giai đoạn khởi tạo repository và thiết lập môi trường làm việc nhóm.

Thông tin về đề tài, chức năng và tiến độ sẽ được cập nhật trong quá trình phát triển.
