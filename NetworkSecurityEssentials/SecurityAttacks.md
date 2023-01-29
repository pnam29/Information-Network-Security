# Tấn cộng bị động, tấn công thụ động - Passive attack

- Tấn công bị động xảy ra khi kẻ tấn công (attacker) giám sát hệ thống để tìm các lỗ hổng bảo mật (vulnerability) đang mở để lấy hoặc thu thập thông tin về mục tiêu của chúng.
- Khó bị phát hiện vì không thay đổi dữ liệu hoặc tài nguyên hệ thống.
- Thay vì gây thiệt hại cho hệ thống của tổ chức, kẻ tấn công đe dọa tính bảo mật (confidentiality) của dữ liệu của họ.

## Tấn công bị động (passive attack) bao gồm trinh sát chủ động (active reconnaissance) và trinh sát thụ động (passive reconnaissance)

- Trinh sát chủ động: Kẻ xâm nhập (intruder) tương tác với hệ thống mục tiêu để thu thập thông tin về các lỗ hổng. Những kẻ tấn công thường sử dụng các phương pháp như quét cổng (port scan) để tìm hiểu cổng nào đang mở và dịch vụ (service) nào đang chạy.
- Trinh sát bị động: Kẻ xâm nhập giám sát hệ thống để tìm các lỗ hổng mà không cần tương tác, với mục đích duy nhất là thu được thông tin. Thường thì kẻ tấn công giám sát phiên web (web session) của người dùng và sau đó sử dụng thông tin được lấy từ phiên (session) đó để tiến hành một cuộc tấn công trong tương lai.

## Các kiểu tấn công bị động (type of passive attack)

- **Phân tích lưu lượng (traffic analysis)**: Điều này liên quan đến việc phân tích lưu lượng mạng (network traffic) khi nó di chuyển đến và đi từ các hệ thống đích. Các kiểu tấn công này sử dụng các phương pháp thống kê để phân tích và diễn giải các pattern giao tiếp được trao đổi qua mạng. Các cuộc tấn công này có thể được thực hiện trên lưu lượng mạng được mã hóa (encrypt), nhưng chúng phổ biến hơn trên lưu lượng không được mã hóa.
- **Nghe lén (eavesdropping)**: Nghe lén xảy ra khi kẻ tấn công chặn thông tin nhạy cảm bằng cách nghe các cuộc gọi điện thoại (phone call) hoặc đọc các tin nhắn không được mã hóa được trao đổi trong một phương tiện liên lạc (communication medium). Mặc dù nghe lén tương tự như snooping, nhưng snooping bị hạn chế ở việc truy cập vào dữ liệu trong quá trình truyền (transmission).
- **Footprinting**: Đây là quá trình thu thập càng nhiều thông tin càng tốt về mạng, phần cứng, phần mềm và nhân viên của công ty mục tiêu. Footprinting thu thập thông tin về mục tiêu, chẳng hạn như địa chỉ IP (IP address), thông tin hệ thống phân giải tên miền (domain name system) và ID nhân viên. Footprinting cũng là bước đầu tiên để thu thập thông tin cho một bài kiểm thử thâm nhập (penetration test).
- **Gián điệp (spying)**: Kẻ xâm nhập có thể giả dạng người dùng được ủy quyền và làm gián điệp mà không cần tương tác. Với quyền truy cập (access) đó, kẻ xâm nhập có thể giám sát lưu lượng mạng bằng cách thiết lập network adapter thành chế độ quảng bá (promiscuous mode) để bắt lấy (capture) tất cả lưu lượng dữ liệu (data traffic) được mã hóa trên mạng.
- **Dumpster diving**: Trong kiểu tấn công này, những kẻ xâm nhập tìm kiếm thông tin được lưu trữ trên các thiết bị bị loại bỏ hoặc thậm chí là mật khẩu trong thùng rác. Sau đó, những kẻ xâm nhập có thể sử dụng thông tin này để tạo điều kiện cho việc xâm nhập bí mật vào mạng hoặc hệ thống.

## Khác nhau giữa tấn công chủ động (active attack) và bị động

- Không tương tác trực tiếp vào hệ thống giông như tấn công chủ động
- Thường diễn ra trước các cuộc tấn công chủ động, nhằm thăm dò, thu thập thông tin chuẩn bị cho cuộc tấn công chủ động
