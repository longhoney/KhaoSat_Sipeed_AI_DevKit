Các example này được tham khảo từ [github của hãng](https://github.com/sipeed/MaixPy-v1_scripts/tree/master)
- Firmware gốc (v0.6.2/ MicroPython v0.6.2-68): Hiển thị phiên bản firmware MaixPy lên LCD, kiểm tra kit đã nhận thẻ nhớ micro SD hay chưa.
- **hello_word.py**: Chương trình mẫu có sẵn trong phần mềm MaixPy IDE. Chương trình này test khả năng stream hình ảnh từ camera lên LCD
- **Test_SD_wout_LCD.py**: Chỉnh sửa chương trình "main_SD-card.py": Kiểm tra phiên bản firmware MaixPy, phiên bản ngôn ngữ MicroPython và kiểm tra kit đã nhận thẻ nhớ micro SD chưa
- **audio.py**: Khi chạy chương trình, kit sẽ ghi âm thông qua microphone tích hợp trên kit trong khoảng xx giây (có thể sửa trong code). Sau đó lưu file âm thanh. wav vào thẻ nhớ. [_Chương trình này có thể dùng để test microphone và test khả năng ghi thẻ nhớ._]
- capture_image_tool.py: Lưu file chứa chương trình vào thẻ nhớ. Sau khi cấp nguồn, bấm nút Boot 1 lần để chụp hình. Giữ lâu nút Boot để tạo thư mục mới. Các hình chụp được sẽ lưu vào thẻ nhớ [_Chương trình này có thể dùng để test camera và test khả năng ghi vào thẻ_]
