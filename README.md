# Quản Lý Thư Viện

## Mục Lục
- [Yêu Cầu Khách Hàng](#yêu-cầu-khách-hàng)
  - [Quản lý thông tin sách](#quản-lý-thông-tin-sách)
  - [Quản lý thẻ thư viện](#quản-lý-thẻ-thư-viện)
  - [Quản lý tình trạng sách](#quản-lý-tình-trạng-sách)
  - [Báo cáo hàng năm](#báo-cáo-hàng-năm)
- [Đề Xuất](#đề-xuất)
  - [Quản lý vi phạm](#quản-lý-vi-phạm)
  - [Báo cáo tình trạng](#báo-cáo-tình-trạng)
  - [Tính năng mở rộng](#tính-năng-mở-rộng)

## Yêu Cầu Khách Hàng

### Quản lý thông tin sách
- Sách được quản lý theo các thông tin: mã sách, tên sách, tác giả, thể loại, năm xuất bản, nhà xuất bản.
- Mỗi mã sách có thể có nhiều cuốn sách (đầu sách), được phân biệt bằng số kiểm soát (ví dụ: 001, 002, 003,…).
- Tình trạng của mỗi cuốn sách sẽ được cập nhật: còn, cho mượn, mất, hỏng.
- Mỗi cuốn sách có ghi chú riêng để mô tả chi tiết tình trạng hoặc những thông tin đặc biệt.

### Quản lý thẻ thư viện
- Thẻ thư viện bao gồm các thông tin: số thẻ, tên, ngày hết hạn, tình trạng sử dụng (còn sử dụng được hoặc không sử dụng).
- Mỗi thẻ thư viện có thể mượn tối đa 3 mã sách trong thời gian 15 ngày.
- Không được phép mượn thêm sách nếu đang mượn sách và chưa trả.

### Quản lý tình trạng sách
- Khi sách được mượn, hệ thống sẽ tự động cập nhật tình trạng của cuốn sách thành “cho mượn”.
- Khi sách được trả, tình trạng sẽ được cập nhật lại thành "còn".
- Nếu sách bị mất hoặc hỏng, tình trạng của sách sẽ được cập nhật thành "mất" hoặc "hỏng", và thẻ thư viện của sinh viên sẽ tạm thời không có hiệu lực cho đến khi sinh viên bồi thường.

### Báo cáo hàng năm
- Hàng năm, thư viện cần lập báo cáo về tình trạng sách bị mất hoặc hỏng để thực hiện việc thanh lý.

## Đề Xuất

### Quản lý vi phạm
- Tích hợp cơ chế quản lý các vi phạm như mất sách, làm hỏng sách và áp dụng quy trình xử phạt tự động, bao gồm tính toán mức bồi thường và kích hoạt lại thẻ thư viện sau khi bồi thường.

### Báo cáo tình trạng
- Hệ thống có thể tự động tổng hợp báo cáo về tình trạng sách (mất, hỏng, còn, cho mượn) và gửi báo cáo cho quản lý thư viện vào cuối năm, giúp việc thanh lý sách trở nên dễ dàng và chính xác hơn.

### Tính năng mở rộng
- Đề xuất phát triển thêm chức năng cho phép sinh viên tra cứu trực tuyến tình trạng sách trong thư viện, giúp tiết kiệm thời gian và nâng cao trải nghiệm người dùng.

## Liên Hệ
Nếu bạn có bất kỳ câu hỏi nào, vui lòng liên hệ với tôi qua email: [dinhgiaanforwork@gmail.com](mailto:dinhgiaanforwork@gmail.com).
