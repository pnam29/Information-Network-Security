# Chương 1: Giới thiệu

_(Chương 1 Network Security Essentials)_

Các yêu cầu về bảo mật thông tin trong một tổ chức đã được thay đổi một cách lớn trong vài thập kỷ qua. Trước khi sử dụng rộng rãi các thiết bị xử lý dữ liệu, việc bảo mật thông tin được cho là hiệu quả chính là sử dụng các vật dụng vật lý như các tủ hồ sơ chắc chắn với khóa kết hợp để lưu trữ các tài liệu nhạy cảm.

Với sự xuất hiện của máy tính, nhu cầu về một công cụ tự động bảo vệ các tệp cùng các thông tin khác được lưu trữ trong máy tính là hiển nhiên. Điều này đặc biệt đúng với các hệ thống chia sẻ thông tin, và đặc biệt hơn nữa với các hệ thống có thể truy cập bằng hệ thống điên thoại công cộng hoặc Internet. Các công cụ, các thiết kế nhằm mục đích bảo vệ dữ liệu và phòng chống “hacker” được gọi chung là An toàn máy tính - Computer Security.

Thay đổi lơn thứ hai trong ngành an toàn thông tin là sự ra của các hệ thống mạng. Để bảo vệ dữ liệu trong khi truyền tải giữa các máy tính với nhau, các biện pháp bảo mật mạng - network security là cần thiết. Thực ra, thuật ngữ bảo mật mạng không thật sự chính xác, vì rất nhiều công ty, chính phủ và trường học đều nối các thiết bị xử lý dữ liệu của họ với nhau trên một mạng. Một mạng này thường được gọi là một internet, và thuật ngữ bảo mật internet - internet security được sử dụng.

## 1.1: Các khái niệm an toàn thông tin (Computer security concepts)

### Một số khái niệm về an toàn thông tin (A Definition of Computer Security)

**Định nghĩa:**\
Sự bảo vệ cung cấp cho một hệ thống thông tin tự động để đạt được mục tiêu của việc bảo vệ tính toàn vẹn, khả dụng và bảo mật các tài nguyên của hệ thống thông tin (bao gồm phần cứng phần mềm, firmware, thông tin/ dữ liệu và viễn thông)

- **Tính bảo mật (Confidentiality):**

  - **Bảo mật dữ liệu (Data confidentiality):** Đảm bảo rằng thông tin riêng tư hoặc bí mật không được cung cấp hoặc tiết lộ cho những người không có quyền truy cập chúng.
  - **Sự riêng tư:** Chỉ rõ các các nhân có quyền điều khiển, thu thập, lưu trữ, sử dụng các tài nguyên cũng như thông tin của hệ thống

- **Tính toàn vẹn (Integrity):**

  - **Toàn vẹn dữ liệu (Data integrity)** Đảm bảo rằng thông tin và chương trình chỉ được thay đổi theo cách được chỉ định và bởi những người được cho phép.
  - **Toàn vẹn hệ thống (System integrity)** Đảm bảo rằng hệ thống hoạt động bình thường và không thể bị tác động một cách vô ý hay cố tình mà chưa được cho phép

- **Tính khả dụng (Availability)** Đảm bảo hệ thống hoạt động bình thường dối với các đối tượng đã được cấp phép

### Những thách thức của an toàn thông tin (The Challenges of Computer Security)

1. Bảo mật không đơn giản với người mới. Các yêu cầu liên quan đến công việc bảo mật thường được đánh nhãn bởi những từ nghe có vẻ khá đơn giản và trực quan như: bảo mật, xác thực, toàn vẹn...Nhưng để hiểu được hoàn các cơ chế hoạt động thì không hề dễ dàng.
2. Trong việc phát triển một cơ chế bảo mật hoặc thuật toán cụ thể, người ta luôn phải xem xét các tấn công có thể đối với những tính năng bảo mật đó. Trong nhiều trường hợp, các tấn công thành công được là nhờ xem xét kỹ lưỡng các cơ chế bằng nhiều cách làm tìm thấy lỗi hổng để rồi khai thác chúng.
3. Các cơ chế bảo mật thường khá phức tạp vì chỉ xử lý đươc một lượng vấn đề nhất định.
4. Có quá nhiều cơ chế cũng như là chuẩn liên quan đến bảo mật. Việc quyết định cái gì sẽ được dùng ở đầu là một việc cần thiết và không hề dễ dàng.
5. Các cơ chế bảo mật thường liên quan đến nhiều thuật toán hoặc giao thức cụ thể.
6. An ninh máy tính và an ninh mạng là cuộc chiến giữa người cố gắng để tìm ra các lỗ hổng của hệ thống với người luôn cố gắng để vá những lỗ hổng này. Kẻ tấn công chỉ cần và quan tâm một lỗ hổng duy nhất trong khi đó những người thiết kế cũng như duy trì hệ thổng cần quan tâm tất cả các điểm yếu để có được một hệ thống hoàn hảo.
7. Người dùng và quản lý hệ thống thường không quan tâm lắm đến bảo mật khi đến khi các lỗi liên quan đến bảo mật xảy ra
8. Bảo mật yêu cầu theo dõi thường xuyên, thậm chí là liên tục, và điều này là một khó khăn lớn trong môi trường quá tải và yêu cầu lớn về tốc độ như hiện nay.
9. Người ta vẫn cần xem xét có nên đưa có module liên quan đến bảo mật vào hệ thống thay vì suy nghĩ rằng nó là một phần không thể thiếu của hệ thống.
10. Nhiều người dùng coi bảo mật mạnh gây cản trở hiệu quả cũng như tốc độ của hệ thống.

## 1.2: Kiến trúc bảo mật OSI (The OSI security architecture)

Kiến trúc bảo mật OSI định nghĩa một cách tiếp cận có hệ thống đối với 7 tầng của mô hình OSI nhằm đảm bảo bảo mật trong quá trình truyền dữ liệu trong không gian mạng. Nó đươc phát triển như một tiêu chuẩn quốc tế và đã được cộng đồng đón nhận

Kiến trúc bảo mật OSI tâp trung vào một số khái niệm sau:
![OSI Security Architecture](/NetworkSecurityEssentials/OSISecurityArchitecture.png)

- **Tấn công bảo mật (Security attack)**: Là một hành động làm tổn hại đến bảo mật thông tin thuộc sở hữu của một tổ chức nào đó.
- **Cơ chế bảo mật (Security mechanism)**: Một tiến trình (hoặc một thiết bị được tích hợp để thực hiện tiến trình) được thiết kế để phát hiện, ngăn chặn tấn công bảo mật hoặc phục hồi tổn hại sau những cuộc tấn công.
- **Dịch vụ bảo mật (Security service)**: Một tiến trình tăng bảo mật của hệ thống xử lý và truyền phát dữ liệu trong tổ chức. Nó sẽ đếm các cuộc tấn công và đưa ra quyết định sẽ tạo ra hoặc sử dụng cơ chế bảo mật nào cho hệ thống.

## 1.3: Tấn công bảo mật (Security attacks)

### 1.3.1 Tấn công thụ động (Passive Attacks)

Các cuộc tấn công thụ động bản chất giống như nghe lén, theo dõi khi mà dữ liệu được truyền đi.
Tấn công thụ động có 2 kiểu là lấy cắp nội dung tin nhắn (release of message contents) và phân tích lưu lượng (traffic analysis).

- **Lấy cắp nội dung tin nhắn (release of message contents)**:
  ![Release of message contents](/NetworkSecurityEssentials/ReleaseOfMessageContents.png)
  Một cuộc nói chuyện qua điện thoại, một tin nhắn, một tệp tin được gửi đi có thể chứa các thông tin nhạy cảm và bảo mật. Chúng ta cần ngăn những kẻ tấn công biêt được, lấy được những thông tin này.
- **Phân tích lưu lượng (traffic analysis)**:
  ![Traffic analysis](/NetworkSecurityEssentials/TrafficAnalysis.png)
  Giả sử rằng chúng ta có cách che giấu nội dung của tin nhắn hoặc các thông tin khác để đối thủ, ngay cả khi họ bắt được tin nhắn thì cũng không thể trích xuất thông tin từ thông điệp. Kỹ thuật phổ biến để che giấu nội dung là mã hóa. Trong trường họp này kẻ tấn công không thể được được nội dung của tin nhắn mà chỉ hiểu được kiểu mẫu và độ dài của mã hóa.

Tấn công thụ động khó bị phát hiện vì không thay đổi dữ liệu hoặc tài nguyên hệ thống. Thông thường cả người gửi và người nhận tin nhắn đều không thể xác định được tin nhắn được đọc bởi bên thứ 3. Tuy nhiên mã hóa dữ liệu trước khi gửi đi là một cách hữu hiệu để ngăn chặn các cuộc tấn công thụ động thay vì cố tình tìm kiếm và phát hiện các cuộc tấn công.

### 1.3.2 Tấn công chủ động (Active Attacks)

Tấn công chủ động liên quan đến thay dổi luồng dữ liệu (data stream) hoặc tạo ra một luồng dữ liệu sai.
Có thể chia tấn công chủ động là 4 loại:

- **Giả mạo (Masquerade)**: Diễn ra khi mà một thực thể giả mạo một thực thể khác. Tấn công giả mạo thường đi kèm theo hình thức tấn công chủ động khác. Ví dụ, trình tự xác thực có thể được mô phỏng sau khi một trình tự xác thực đúng được thực hiện.
  ![Masquerade](/NetworkSecurityEssentials/Masquerade.png)
- **Phát lại (Replay)**: Kẻ tấn công bắt lấy một tin nhắn được truyền đi thông qua một kênh bị động sau đó phát lại tin nhắn gian lận hoặc trì hoãn một thời gian.
  ![Replay](/NetworkSecurityEssentials/Replay.png)
- **Sửa đổi tin nhắn (Modification of Message)**: Kẻ tấn công sửa đổi tin nhắn đã được gửi đi. Người nhận có thể nhận được tin nhắn không an toàn hoặc vô nghĩa. Kiểu tấn công này sử dụng để thao túng nội dung tin nhắn hoặc làm gián đoạn quá trình giao tiếp.
  ![Modification of Message](/NetworkSecurityEssentials/ModificationOfMessages.png)
- **Từ chối phục vụ (Denial of service - DoS)**: Kẻ tấn công gửi một lượng truy cập lớn vào hệ thống, mạng, hoặc thiết bị, khiến cho thực thể bị tấn công từ chối hoạt động kể cả đối với người dùng đã được xác thực do bị quá tải.
  ![Denial of service](/NetworkSecurityEssentials/DenialOfService.png)

Khá là khó để ngăn chặn tuyệt đối các cuộc tấn công chủ động vì có quá nhiều lỗ hổng tiềm ẩn về mặt vật lý, phần mềm và cả mạng. Chính vì thế mục tiêu là phát hiện rồi phục hồi sau bất kỳ sự gián đoạn hoặc chậm trễ nào do chúng gây ra.

X800 định nghĩa 1 dịch vụ bảo mật là 1 dịch vụ đảm bảo an toàn của hệ thống và quá trình truyền dữ liệu

# New words
| EN           | VI                       |
| ------------ | ------------------------ |
| confidential | bảo mật                  |
| influence    | ảnh hưởng                |
| novice       | người mới                |
| mechanism    | cơ chế                   |
| exploit      | khai thác                |
| typically    | tiêu biểu                |
| tendency     | khuynh hướng             |
| grocery      | cửa hàng tạp hóa         |
| enumerate    | liệt kê                  |
| assess       | đánh giá                 |
| compound     | hỗn hợp                  |
| compromises  | thỏa hiệp, làm tổn hại   |
| intend       | có dự định               |
| opponent     | phản đối, dịch thủ       |
| subtle       | tinh vi, xảo trá         |
| feasible     | khả thi                  |
| involve      | liên quan đến            |
| portion      | phần, đoạn trích, lô đất |
| legitimate   | hợp pháp                 |
| perhaps      | có lẽ                    |
