# THHT
Tích hợp hệ thống

Công cụ cần thiết để tích hợp trello slack:
  Ultra studio: cài đặt theo hướng dẫn: https://www.adroitlogic.com/download/
  ngrok: cài đặt tại: https://ngrok.com/
  Thực hiện tạo slack webhooks và trello webhooks.
Cách chạy project.
  bước 1: Sau khi cài đặt ultra sutdio thì mở app ideaIC.
  bước 2: Chạy project.
  bước 3: Khởi tạo run/debug Configuration cửa ultraesb-x server.
  bước 4: Chạy project.
  bước 5: Public localhost bằng ngrok .
  bước 6: Gắn slack webhooks url vào slack connector để kết nối,
  bước 7: Gắn link ngrok vào callback url của trello webhook.
Thực hiện chay:
  Tạo thẻ mới trên trello ta sẽ nhận được thông báo trên slack bao gồm thông tin id,nội dung thẻ,thẻ cha ....
  Sử dụng Slack commands gắn link bằng link ngrok. Gọi lệnh Slack command để tạo thẻ trello.
