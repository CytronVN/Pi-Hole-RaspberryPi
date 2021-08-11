# Pi-Hole-RaspberryPi
**Hướng dẫn cài đặt Pi-Hole lên Raspberry Pi để chặn quảng cáo**

Ngoài tính năng chặn quảng cáo theo host-list/domain, Pi-Hole còn hoạt động như một DNS server. Vì vậy, chúng ta có thể theo dõi và biết được máy tính, điện thoại truy cập những website nào có thể đưa nó vào danh sách whitelist (cho phép) và blacklist (chặn). Tính năng này rất hữu ích nếu nhà bạn có con nhỏ.
Trong bài hướng dẫn, mình sử dụng Raspberry Pi 4 và kết nối tới router qua cáp mạng. Tuy nhiên, Pi-Hole dùng rất ít tài nguyên, bạn có thể cài nó lên Raspberry Pi Zero W nếu thích sự nhỏ gọn.

Cú pháp tự động cài đặt Pi-Hole
>curl -sSL https://install.pi-hole.net | bash

Để đặt lại mật khẩu Pi-Hole
>pihole -a -p

Video hướng dẫn chi tiết
>https://fb.watch/7jtQVGuucV/

Những sản phẩm sử dụng trong video có thể tìm thấy tại [Cửa hàng trực tuyến của Cytron Technologies](https://cytrontech.vn/?tracking=vngh)
