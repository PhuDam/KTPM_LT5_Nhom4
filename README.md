KTPM_LT5_Nhom5
VIVUVIETNAM - Nền tảng Đặt phòng Khách sạn
Giới thiệu
VIVUVIETNAM là một trang web đặt phòng khách sạn trực tuyến được thiết kế để giúp người dùng dễ dàng tìm kiếm, so sánh và đặt phòng tại các khách sạn trên khắp Việt Nam. Giao diện người dùng được xây dựng trực quan và thân thiện, tập trung vào trải nghiệm người dùng mượt mà từ khâu tìm kiếm đến thanh toán.

Dự án này bao gồm hai trang chính: trang chủ để khám phá và đặt phòng, và trang đăng nhập/đăng ký cho người dùng.

Công nghệ sử dụng:
Giao diện người dùng (Frontend): HTML, CSS, JavaScript

Framework CSS: TailwindCSS

Thư viện biểu tượng: FontAwesome

Tính năng nổi bật

1. Trang Chủ (home.html)
Trang chủ là trung tâm của trải nghiệm, cung cấp đầy đủ các công cụ cần thiết để người dùng tìm và đặt được phòng khách sạn ưng ý.

Tìm kiếm và Lọc thông minh
Tìm kiếm theo Từ khóa: Người dùng có thể tìm kiếm khách sạn theo địa điểm (thành phố), tên khách sạn hoặc khu vực cụ thể.
Chọn Ngày Nhận và Trả phòng: Giao diện chọn ngày tiện lợi, tự động kiểm tra tính hợp lệ (ngày trả phòng phải sau ngày nhận phòng).
Kết quả Tìm kiếm Động: Kết quả sẽ được lọc và hiển thị ngay lập tức dựa trên từ khóa người dùng nhập mà không cần tải lại trang.
Hiển thị Danh sách Khách sạn
Danh sách Khách sạn Nổi bật: Hiển thị các khách sạn hàng đầu tại các địa điểm du lịch nổi tiếng như Hà Nội, Đà Nẵng, Sapa, TP. Hồ Chí Minh, và nhiều nơi khác.
Thông tin Chi tiết: Mỗi khách sạn được hiển thị với hình ảnh, tên, địa điểm, xếp hạng (rating) và giá phòng tham khảo mỗi đêm.
Chương trình Khuyến mãi Hấp dẫn
Ưu đãi Đặc biệt: Hiển thị các chương trình khuyến mãi đang diễn ra như giảm giá cho các loại phòng, ưu đãi cuối tuần, hoặc combo tiết kiệm.
Giảm 20% cho phòng Deluxe tại các khách sạn 5 sao ở Hà Nội và Đà Nẵng.
Giảm giá đến 15% vào cuối tuần tại Đà Lạt và Nha Trang.
Tiết kiệm đến 25% với combo phòng và vé tham quan.
Quy trình Đặt phòng Chi tiết và An toàn
Cửa sổ Chi tiết Khách sạn (Modal): Khi nhấp vào một khách sạn, một cửa sổ sẽ hiện ra cung cấp thông tin toàn diện:
Thư viện hình ảnh của khách sạn.
Mô tả chi tiết về khách sạn.
Danh sách các tiện nghi (Wifi, hồ bơi, spa, v.v.).
Tùy chọn loại phòng với giá và số lượng phòng trống tương ứng.
Biểu mẫu Đặt phòng: Người dùng điền thông tin cá nhân (họ tên, SĐT, email) và chọn ngày nhận/trả phòng trực tiếp trong cửa sổ chi tiết.
Thanh toán An toàn: Sau khi điền thông tin, người dùng sẽ được chuyển đến cửa sổ thanh toán để nhập thông tin thẻ (tên chủ thẻ, số thẻ, ngày hết hạn, CVV). Biểu mẫu có tính năng xác thực đầu vào cơ bản để đảm bảo tính hợp lệ.
Xác nhận Đặt phòng: Sau khi "thanh toán" thành công (mô phỏng), hệ thống sẽ hiển thị thông báo xác nhận đặt phòng thành công với đầy đủ thông tin chi tiết.
Các phần khác
Giới thiệu: Cung cấp thông tin về sứ mệnh và địa chỉ của VIVUVIETNAM.
Liên hệ: Biểu mẫu liên hệ cho phép người dùng gửi phản hồi hoặc câu hỏi trực tiếp đến đội ngũ hỗ trợ.
Chân trang (Footer): Chứa thông tin bản quyền và các liên kết mạng xã hội.
Thiết kế đáp ứng (Responsive): Giao diện được tối ưu hóa để hiển thị tốt trên cả máy tính để bàn và thiết bị di động.
2. Trang Đăng nhập & Đăng ký (login.html)
Trang này cung cấp một giao diện hiện đại, sử dụng hiệu ứng "glassmorphism" (nền mờ như kính) để người dùng có thể đăng nhập hoặc tạo tài khoản mới.

Giao diện Tab linh hoạt
Người dùng có thể dễ dàng chuyển đổi giữa hai biểu mẫu Đăng nhập và Đăng ký chỉ với một cú nhấp chuột.
Tab đang hoạt động được làm nổi bật bằng một gạch chân màu cam với hiệu ứng phát sáng.
Biểu mẫu Thông minh và An toàn
Hiệu ứng Nhãn nổi (Floating Label): Nhãn của ô nhập liệu sẽ tự động di chuyển lên trên khi người dùng bắt đầu nhập văn bản, giúp tiết kiệm không gian và giữ giao diện gọn gàng.
Hiển thị/Ẩn Mật khẩu: Người dùng có thể nhấp vào biểu tượng con mắt để xem hoặc ẩn mật khẩu đang nhập, giúp tránh sai sót.
Xác thực Phía Người dùng:
Đăng ký: Kiểm tra các trường thông tin không được để trống, độ dài tối thiểu/tối đa cho tên người dùng và mật khẩu.
Đăng nhập: Yêu cầu người dùng nhập đầy đủ thông tin trước khi gửi.
Luồng Xác thực Người dùng (Mô phỏng)
Đăng nhập: Trang sử dụng thông tin đăng nhập giả lập (admin/123). Khi đăng nhập thành công, người dùng sẽ được thông báo và tự động chuyển hướng đến home.html.
Đăng ký: Sau khi điền thông tin và gửi biểu mẫu, hệ thống sẽ hiển thị một thông báo đăng ký thành công và tự động chuyển người dùng về tab đăng nhập.
