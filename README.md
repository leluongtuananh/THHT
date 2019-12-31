# THHT

Tích hợp hệ thống

**Phần 1**: Tích hợp Trello và Slack

  

* Công cụ cần thiết để tích hợp trello slack:

* Ultra studio: cài đặt theo hướng dẫn: https://www.adroitlogic.com/download/

* ngrok: cài đặt tại: https://ngrok.com/

* Thực hiện tạo slack webhooks và trello webhooks.

* Cách chạy project.

* bước 1: Sau khi cài đặt ultra sutdio thì mở app ideaIC.

* bước 2: Chạy project.

* bước 3: Khởi tạo run/debug Configuration cửa ultraesb-x server.

* bước 4: Chạy project.

* bước 5: Public localhost bằng ngrok .

* bước 6: Gắn slack webhooks url vào slack connector để kết nối,

* bước 7: Gắn link ngrok vào callback url của trello webhook.

* Thực hiện chay:

* Tạo thẻ mới trên trello ta sẽ nhận được thông báo trên slack bao gồm thông tin id,nội dung thẻ,thẻ cha ....

/ Sử dụng Slack commands gắn link bằng link ngrok. Gọi lệnh Slack command để tạo thẻ trello.

**Phần 2**: Đồng bộ Dropbox với máy dưới local

Cách chạy project:
1. bước 1: Sau khi cài đặt ultra sutdio thì mở app ideaIC.
2. bước 2: Chạy project.
3.   bước 3: Khởi tạo run/debug Configuration cửa ultraesb-x server.
4.  bước 4: Chạy project.

**Phân chia công việc**:
1. Nguyễn Tuấn Anh: Đồng bộ dropbox
2. Lê Lương Tuấn Anh: Thực hiện kết nối Trello với Slack
3. Phùng Đình Xuân: Tìm hiểu các public port
4. Bùi Ngọc Đăng: Làm slide, tìm hiểu về webhook
5. Lê Văn Duy: Làm doc, tìm hiểu về trello API
