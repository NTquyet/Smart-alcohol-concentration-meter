⚡ Máy Đo Nồng Độ Cồn
Hiện nay, tình trạng lạm dụng rượu bia đang là một trong những nguyên nhân hàng đầu dẫn đến tai nạn giao thông nghiêm trọng, gây thiệt hại lớn về con người và tài sản. Việc kiểm soát nồng độ cồn của người tham gia giao thông trở thành một biện pháp quan trọng giúp giảm thiểu rủi ro và đảm bảo an toàn cho cả người lái xe và những người xung quanh. Tuy nhiên, các thiết bị đo nồng độ cồn truyền thống thường có kích thước lớn, giá thành cao và chưa thực sự tiện lợi trong việc sử dụng hàng ngày. Sự ra đời của một thiết bị đo nồng độ cồn nhỏ gọn, chính xác và dễ dàng kết nối với các thiết bị di động sẽ là giải pháp hiệu quả nhằm hỗ trợ người dùng kiểm soát tốt hơn nồng độ cồn trong cơ thể trước khi tham gia giao thông.

📋 Mục Lục
Giới Thiệu
Thông Số Kỹ Thuật
Danh Sách Linh Kiện
Sơ Đồ Nguyên Lý và PCB
Hướng Dẫn Lắp Ráp
Lập Trình Firmware
Cách Sử Dụng
Kiểm Thử
Ảnh/Video Demo
Giới Thiệu
Dự án làm gì?
Thiết bị đo nồng độ cồn trong hơi thở, hiển thị kết quả trên OLED và gửi dữ liệu qua WiFi/MQTT.

Người dùng chính?

Cá nhân kiểm tra sức khỏe.
Cơ quan giao thông, doanh nghiệp vận tải.
Mục tiêu thiết kế?

Thực tiễn: Tạo sản phẩm nhỏ gọn, chi phí thấp.
Giáo dục: Tìm hiểu ESP32 và hệ thống nhúng.
Thông Số Kỹ Thuật
Thành phần	Thông tin
MCU	ESP32-WROOM-32
Nguồn vào	3 pin Lithium 3.7V
Cảm biến	MQ3 (đo nồng độ cồn)
Màn hình	OLED SSD1306 128x64, giao tiếp I2C
Kết nối	WiFi, MQTT
Danh Sách Linh Kiện
Tên linh kiện	Số lượng	Ghi chú
ESP32 DevKit v1	1	Vi điều khiển chính
Cảm biến MQ3	1	Đo nồng độ cồn
Màn hình OLED	1	Hiển thị kết quả
Nút nhấn	5	Chọn chế độ và reset
IC ổn áp LM7805	1	Hạ áp cho đầu ra là 5v
IC ổn áp AMS1117	1	Ổn áp cho 3.3v
Tụ và trở	nhiều	Tham khảo sch và pcb
