# Maixduino
Thông tin sản phẩm tại trang chủ nhà sản xuất: https://wiki.sipeed.com/hardware/en/maix/maixpy_develop_kit_board/maix_duino.html
https://wiki.sipeed.com/soft/maixpy/en/develop_kit_board/maix_duino.html
Kit giao tiếp TTL 3v3. ESP32 có 6 hàng chân Analog, các hàng chân còn lại của K210.

Upload Speed cho ESP32 Dev Module trong ArduinoIDE là 115200.

Github chứa các chương trình có sẵn: https://github.com/sipeed/MaixPy-v1_scripts/tree/master

Danh sách video hướng dẫn trên mạng: https://www.youtube.com/playlist?list=PL-xeeY4SfuajYw7RM1neLzEWYq91-2rxp

Github của nhà sản xuất về Maixduino: https://github.com/sipeed/Maixduino

Nếu kết nối đầy đủ với màn hình, kit K210 đã có sẵn chương trình main.py để kiểm tra khả năng đọc của thẻ nhớ.

Test khả năng giao tiếp với thẻ nhớ Micro SD bằng cách chạy chương trình ghi âm (kit tích hợp sẵn microphone) và lưu vào thẻ nhớ.
  - Định dạng FAT32: OK, LƯU được file main.py.
  - Định dạng NTFS: không hoạt động, không lưu được file main.py.
  - Định dạng exFAT: không hoạt động, không lưu được file main.py.

Thông tin định dạng thẻ nhớ kit hỗ trợ từ hãng: https://wiki.sipeed.com/soft/maixpy/en/get_started/get_started_fs.html

Kiểm tra firmware hiện tại của sản phẩm: Chạy file main.py hoặc kiểm tra trong phần mềm MaixPy IDE.

Trang web hướng dẫn update firmware và link tải : https://wiki.sipeed.com/soft/maixpy/en/get_started/upgrade_maixpy_firmware.html 
Ta cần update MaixPy firmware để kit giao tiếp với MaixPy IDE (nếu chưa có sẵn)

# Maix Dock M1W

Mắt camera không điều chỉnh được tiêu cự

Firware MaixPy v0.6.2 không hỗ trợ thẻ nhớ dung lượng từ 64GB trở lên. Xem lại thông tin định dạng thẻ nhớ được kit hỗ trợ ở trên

Firmware MaixPy v0.6.3 hỗ trợ thẻ nhớ dung lượng từ 64GB trở lên. Xem lại cách update firmware ở trên





