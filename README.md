# n8n-telegram-image-bot
# 🤖 Bot Telegram Xử Lý Ảnh Tự Động Bằng n8n

## 📌 Giới thiệu

Đây là dự án xây dựng hệ thống bot Telegram hỗ trợ xử lý ảnh tự động bằng nền tảng **n8n**. Người dùng chỉ cần gửi ảnh vào Telegram, hệ thống sẽ tự động nhận ảnh, xử lý xóa nền bằng API Remove.bg, lưu kết quả vào Google Drive và gửi ảnh lại cho người dùng.

Dự án giúp đơn giản hóa thao tác chỉnh sửa ảnh, tiết kiệm thời gian và dễ dàng sử dụng.

---

## 🎯 Mục tiêu đề tài

- Tạo bot Telegram nhận ảnh từ người dùng.
- Tự động xóa nền ảnh.
- Lưu ảnh đã xử lý lên Google Drive.
- Gửi lại kết quả cho người dùng.
- Ứng dụng workflow automation bằng n8n.

---

## 🛠 Công nghệ sử dụng

- **n8n Cloud / n8n Local**
- **Telegram Bot API**
- **Remove.bg API**
- **Google Drive API**
- **JavaScript**

---

## ⚙️ Chức năng chính

✅ Nhận ảnh từ Telegram  
✅ Tải ảnh tự động  
✅ Xóa nền ảnh bằng AI  
✅ Lưu ảnh lên Google Drive  
✅ Gửi ảnh kết quả về Telegram  

---

## 🧩 Sơ đồ hệ thống

```text
Người dùng gửi ảnh Telegram
          ↓
Telegram Trigger
          ↓
Get a file
          ↓
HTTP Request (Remove.bg)
          ↓
Google Drive Upload
          ↓
Telegram Send Photo
🚀 Hướng dẫn cài đặt
1. Clone project
git clone https://github.com/yourusername/n8n-telegram-image-bot.git
2. Import workflow
Mở n8n
Chọn Import from File
Chọn file:
workflow.json
3. Cấu hình Telegram Bot
Tạo bot bằng BotFather
Lấy Token
Gắn vào node Telegram
4. Cấu hình Google Drive
Kết nối tài khoản Google Drive trong n8n.
5. Cấu hình Remove.bg API
Tạo tài khoản tại:
https://www.remove.bg/api
Lấy API key và gắn vào node HTTP Request.
📷 Cách sử dụng
Mở Telegram bot.
Gửi ảnh cần xóa nền.
Chờ vài giây.
Nhận lại ảnh PNG nền trong suốt.
📁 Cấu trúc thư mục
project/
│── README.md
│── workflow.json
│── report.docx
│── images/
📌 Kết quả đạt được
Hệ thống hoạt động ổn định.
Tự động xử lý ảnh nhanh chóng.
Triển khai dễ dàng.
Có thể mở rộng thêm nhiều chức năng.
🔮 Hướng phát triển
Tăng nét ảnh
Resize ảnh
Ghép nền mới
Tạo avatar AI
Chỉnh màu ảnh tự động
