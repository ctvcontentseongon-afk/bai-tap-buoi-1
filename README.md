# Finly – Quản lý Tài chính Cá nhân

> Bài tập khóa học Claude Code | SEONGON

## Mô tả

**Finly** là một web app quản lý tài chính cá nhân được xây dựng hoàn toàn bằng HTML/CSS/JavaScript thuần, chạy trực tiếp trên trình duyệt mà không cần hosting hay backend.

## Tính năng

| Trang | Chức năng |
|-------|-----------|
| **Dashboard** | Tổng quan số dư, thu nhập, chi tiêu, tiết kiệm theo tháng. Biểu đồ cột 6 tháng và biểu đồ tròn danh mục |
| **Giao dịch** | Lịch sử đầy đủ với tìm kiếm, lọc theo loại / danh mục / tháng. Sửa và xóa từng giao dịch |
| **Ngân sách** | Đặt hạn mức chi tiêu theo danh mục, progress bar theo dõi với cảnh báo vượt mức |
| **Báo cáo** | Biểu đồ số dư theo thời gian, top danh mục chi tiêu, thống kê trung bình tháng |

## Công nghệ sử dụng

- **HTML5 / CSS3 / JavaScript** (Vanilla – không dùng framework)
- **Tailwind CSS** (CDN)
- **Chart.js** – biểu đồ trực quan
- **Font Awesome** – icon
- **localStorage** – lưu dữ liệu ngay trên trình duyệt

## Cách chạy

1. Clone repo về máy
2. Mở file `index.html` bằng bất kỳ trình duyệt nào
3. Không cần cài đặt gì thêm

```bash
git clone <repo-url>
# Mở index.html trong trình duyệt
```

## Cấu trúc file

```
├── index.html          # Toàn bộ app (HTML + CSS + JS)
├── README.md           # Tài liệu dự án
└── conversation.txt    # Lịch sử trò chuyện với Claude Code
```

## Phím tắt

| Phím | Hành động |
|------|-----------|
| `Cmd/Ctrl + K` | Mở form thêm giao dịch nhanh |
| `Esc` | Đóng modal |

## Công cụ xây dựng

Toàn bộ dự án được xây dựng bằng **Claude Code** (Anthropic) theo hướng dẫn của khóa học SEONGON.
