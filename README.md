firmware update: mqtt
-  firmware:https://raw.githubusercontent.com/xuanbka1/Firm7677S_LANV/main/V001.bin

uart cmd
-  firmware:https://raw.githubusercontent.com/xuanbka1/Firm7677S_LANV/main/V001.bin#
--------------------------------------------------------------------------------------------------------------------------------------------
**- version TDSK_301125**
**- ngày phát hành: 30/11/2025**
Cập nhật phiên bản 30/11/2025
+ Sửa lỗi reboot sau khi kết nối lại mạng 
+ Sửa lỗi Fota do re-factor code
+ Đã test chạy ổn định sau 1 tháng không bị reboot
+ link verrsion: https://gitlab.com/my_out_source/Sankito/-/tree/fix_fota
  
**- version TDSK_130525B**
**- ngày phát hành: 13/05/2025**
1. fix lỗi không thể đồng bộ thời gian với NTP server khi khởi động thiết bị ( nếu sau 15s thiết bị không đồng bộ được ntp, thiết bị tự khởi động lại)
2. chuyển đọc gpio từ ngắt sang đọc dùng systick
3. add thêm command lấy số điện thoại thiết bị:
4. mặc định broker về nhất nguyên, port: 1886

**sms:0912345678#**

Cập nhật bản mới nhất qua mqtt:
-  firmware:https://raw.githubusercontent.com/xuanbka1/Firm7677S_LANV/main/TDSK_301125.bin

 uart cmd:
-  firmware:https://raw.githubusercontent.com/xuanbka1/Firm7677S_LANV/main/TDSK_301125.bin#
