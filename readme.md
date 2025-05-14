# WordPress

![WordPress Logo](wp-admin/images/wordpress-logo.png)

## Nền Tảng Xuất Bản Cá Nhân

### Lời Mở Đầu

Chào mừng bạn. WordPress là một dự án rất đặc biệt đối với tôi. Mỗi nhà phát triển và người đóng góp đều mang đến điều gì đó độc đáo, và cùng nhau chúng tôi tạo ra một sản phẩm tuyệt vời mà tôi tự hào được là một phần của nó. Hàng nghìn giờ đã được đổ vào WordPress, và chúng tôi cam kết làm cho nó tốt hơn mỗi ngày. Cảm ơn bạn đã làm cho nó trở thành một phần trong thế giới của bạn.

— Matt Mullenweg

### Cài Đặt: Quy trình cài đặt nổi tiếng 5 phút

1. Giải nén gói trong một thư mục trống và tải lên tất cả.
2. Mở [wp-admin/install.php](wp-admin/install.php) trong trình duyệt của bạn. Nó sẽ hướng dẫn bạn quy trình thiết lập tệp `wp-config.php` với chi tiết kết nối cơ sở dữ liệu của bạn.
   - Nếu vì lý do nào đó điều này không hoạt động, đừng lo lắng. Nó có thể không hoạt động trên tất cả các máy chủ web. Mở `wp-config-sample.php` bằng trình soạn thảo văn bản như WordPad hoặc tương tự và điền vào chi tiết kết nối cơ sở dữ liệu của bạn.
   - Lưu tệp dưới dạng `wp-config.php` và tải lên.
   - Mở [wp-admin/install.php](wp-admin/install.php) trong trình duyệt của bạn.
3. Khi tệp cấu hình được thiết lập, trình cài đặt sẽ thiết lập các bảng cần thiết cho trang web của bạn. Nếu có lỗi, hãy kiểm tra lại tệp `wp-config.php` của bạn và thử lại. Nếu nó lại thất bại, vui lòng truy cập [diễn đàn hỗ trợ WordPress](https://wordpress.org/support/forums/) với càng nhiều dữ liệu càng tốt.
4. **Nếu bạn không nhập mật khẩu, hãy ghi chú mật khẩu được cung cấp cho bạn.** Nếu bạn không cung cấp tên người dùng, nó sẽ là `admin`.
5. Trình cài đặt sau đó sẽ đưa bạn đến [trang đăng nhập](wp-login.php). Đăng nhập bằng tên người dùng và mật khẩu bạn đã chọn trong quá trình cài đặt. Nếu mật khẩu được tạo cho bạn, bạn có thể nhấp vào "Hồ sơ" để thay đổi mật khẩu.

### Cập Nhật

#### Sử Dụng Trình Cập Nhật Tự Động

1. Mở [wp-admin/update-core.php](wp-admin/update-core.php) trong trình duyệt của bạn và làm theo hướng dẫn.
2. Bạn muốn nhiều hơn? Chỉ có vậy thôi!

#### Cập Nhật Thủ Công

1. Trước khi cập nhật bất cứ thứ gì, hãy đảm bảo bạn có bản sao lưu của bất kỳ tệp nào bạn có thể đã sửa đổi như `index.php`.
2. Xóa các tệp WordPress cũ của bạn, lưu lại những tệp bạn đã sửa đổi.
3. Tải lên các tệp mới.
4. Trỏ trình duyệt của bạn đến [/wp-admin/upgrade.php](/wp-admin/upgrade.php).

### Di chuyển từ các hệ thống khác

WordPress có thể [nhập từ nhiều hệ thống khác nhau](https://developer.wordpress.org/advanced-administration/wordpress/import/). Trước tiên, bạn cần cài đặt và làm việc với WordPress như mô tả ở trên, trước khi sử dụng [công cụ nhập của chúng tôi](wp-admin/import.php).

### Yêu Cầu Hệ Thống

- [PHP](https://www.php.net/) phiên bản **7.2.24** trở lên.
- [MySQL](https://www.mysql.com/) phiên bản **5.5.5** trở lên.

#### Khuyến nghị

- [PHP](https://www.php.net/) phiên bản **7.4** trở lên.
- [MySQL](https://www.mysql.com/) phiên bản **8.0** trở lên HOẶC [MariaDB](https://mariadb.org/) phiên bản **10.5** trở lên.
- Module Apache [mod_rewrite](https://httpd.apache.org/docs/2.2/mod/mod_rewrite.html).
- Hỗ trợ [HTTPS](https://wordpress.org/news/2016/12/moving-toward-ssl/).
- Một liên kết đến [wordpress.org](https://wordpress.org/) trên trang web của bạn.

### Tài Nguyên Trực Tuyến

Nếu bạn có bất kỳ câu hỏi nào không được đề cập trong tài liệu này, vui lòng tận dụng các tài nguyên trực tuyến phong phú của WordPress:

- [HelpHub](https://wordpress.org/documentation/): HelpHub là bách khoa toàn thư về tất cả mọi thứ liên quan đến WordPress. Đây là nguồn thông tin toàn diện nhất cho WordPress hiện có.
- [Blog WordPress](https://wordpress.org/news/): Đây là nơi bạn sẽ tìm thấy các cập nhật và tin tức mới nhất liên quan đến WordPress. Tin tức WordPress gần đây xuất hiện trong bảng điều khiển quản trị của bạn theo mặc định.
- [WordPress Planet](https://planet.wordpress.org/): WordPress Planet là một trang tổng hợp tin tức mang lại các bài đăng từ các blog WordPress trên khắp web.
- [Diễn Đàn Hỗ Trợ WordPress](https://wordpress.org/support/forums/): Nếu bạn đã tìm kiếm ở mọi nơi và vẫn không thể tìm thấy câu trả lời, các diễn đàn hỗ trợ rất hoạt động và có một cộng đồng lớn sẵn sàng giúp đỡ. Để giúp họ giúp bạn, hãy đảm bảo sử dụng tiêu đề chủ đề mô tả và mô tả câu hỏi của bạn càng chi tiết càng tốt.
- [Kênh IRC của WordPress](https://make.wordpress.org/support/handbook/appendix/other-support-locations/introduction-to-irc/): Có một kênh trò chuyện trực tuyến được sử dụng để thảo luận giữa những người sử dụng WordPress và đôi khi là các chủ đề hỗ trợ. Trang wiki trên sẽ hướng dẫn bạn đúng hướng. ([irc.libera.chat #wordpress](https://web.libera.chat/#wordpress))

### Ghi Chú Cuối Cùng

- Nếu bạn có bất kỳ đề xuất, ý tưởng hoặc nhận xét nào, hoặc nếu bạn (ôi!) tìm thấy lỗi, hãy tham gia với chúng tôi trong [Diễn Đàn Hỗ Trợ](https://wordpress.org/support/forums/).
- WordPress có một API (Giao Diện Lập Trình Ứng Dụng) plugin mạnh mẽ giúp việc mở rộng mã trở nên dễ dàng. Nếu bạn là nhà phát triển quan tâm đến việc sử dụng điều này, hãy xem [Sổ Tay Nhà Phát Triển Plugin](https://developer.wordpress.org/plugins/). Bạn không nên sửa đổi bất kỳ mã cốt lõi nào.

### Chia Sẻ Tình Yêu

WordPress không có chiến dịch tiếp thị hàng triệu đô la hoặc nhà tài trợ nổi tiếng, nhưng chúng tôi có điều gì đó thậm chí còn tốt hơn—bạn. Nếu bạn thích WordPress, vui lòng cân nhắc việc nói với bạn bè, thiết lập nó cho người ít hiểu biết hơn bạn, hoặc viết cho tác giả của một bài báo truyền thông bỏ qua chúng tôi.

WordPress là sự tiếp nối chính thức của b2/cafélog, xuất phát từ Michel V. Công việc đã được tiếp tục bởi [các nhà phát triển WordPress](https://wordpress.org/about/). Nếu bạn muốn hỗ trợ WordPress, vui lòng cân nhắc [quyên góp](https://wordpress.org/donate/).

### Giấy Phép

WordPress là phần mềm miễn phí và được phát hành theo các điều khoản của GPL (Giấy Phép Công Cộng GNU) phiên bản 2 hoặc (tùy chọn của bạn) bất kỳ phiên bản nào sau này. Xem [license.txt](license.txt).
