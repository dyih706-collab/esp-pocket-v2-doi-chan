# ESP Pocket V2 - Đổi chân

Bản chỉnh sửa của ESP Pocket Puter: máy tính bỏ túi nhỏ dùng ESP32-C3
có màn hình SSD1306, nút bấm, buzzer, hồng ngoại và RF CC1101.

> ⚠️ Chỉ dùng cho mục đích học tập và thử nghiệm hợp pháp.

## Nguồn gốc
Dựa trên [ESP-Pocket-Puter](https://github.com/DevEclipse1/ESP-Pocket-Puter)
của [DevEclipse1](https://github.com/DevEclipse1), giấy phép MIT.

## Thay đổi so với bản gốc
Bản chỉnh sửa bởi **Khanh_DYI** ([dyih706-collab](https://github.com/dyih706-collab)):
- Đổi chân (pin mapping) cho phù hợp mạch của mình
- Thêm tính năng: thu hồng ngoại (IR receive)

## Cách flash firmware
1. Mở web flash: https://espressif.github.io/esptool-js/
2. Cắm board, bấm **Connect**, chọn cổng COM
3. Flash Address: `0x0`
4. Chọn file `pocket-doi-chan.bin`
5. Bấm **Program** và đợi chạy xong

## Lưu ý
Dự án này **chỉ dùng cho mục đích học tập và nghiên cứu**.
Người dùng tự chịu trách nhiệm khi sử dụng. Một số tính năng
(như RF jammer) bị cấm ở nhiều quốc gia.

## Giấy phép
MIT. Bản quyền gốc thuộc DevEclipse1, bản chỉnh sửa thuộc Khanh_DYI.
