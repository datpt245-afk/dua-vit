DUCK RACE — BẢN HOÀN CHỈNH

Có:
- 5 nhóm, mỗi nhóm một link chuông.
- Thành viên tự nhập tên trên điện thoại.
- Hệ thống ghi nhận đúng người bấm đầu tiên.
- MC mở từng câu hỏi.
- Câu hỏi có thể tự tạo ngay trên bảng MC: câu hỏi + 4 đáp án + đáp án đúng.
- MC chọn câu, mở câu, xem ai giành quyền.
- Đúng: mặc định +2 điểm nhóm và +1 điểm cá nhân.
- Sai: mở quyền cướp.
- Bảng tổng điểm 5 nhóm riêng.
- Bảng điểm cá nhân riêng.
- Đường đua 5 con vịt.
- Có thể đổi cách tính điểm.
- Reset chuông và reset toàn bộ.

CÁCH CHẠY:
1. Cài Node.js (nodejs.org).
2. Giải nén thư mục.
3. Mở Terminal/CMD tại thư mục.
4. Chạy: npm install
5. Chạy: npm start
6. Laptop MC mở: http://localhost:3000/mc.html
7. Tìm IP Wi-Fi của laptop MC (Windows: mở CMD -> ipconfig -> IPv4 Address).
8. Điện thoại cùng Wi-Fi mở:
   http://IP-MAY-MC:3000/?group=1
   ... đến group=5.

Ví dụ:
http://192.168.1.10:3000/?group=1

Mỗi thành viên có thể nhập tên của mình trên link nhóm đó.
MC nên mở mc.html ở laptop chiếu lên màn hình.

LƯU Ý:
- Đây là bản chạy realtime trong cùng mạng Wi-Fi.
- Nếu Windows Firewall hỏi quyền cho Node.js, cho phép trên mạng Private.
- Muốn dùng Internet khác mạng thì cần deploy server lên hosting; bản này chưa tự public Internet.
