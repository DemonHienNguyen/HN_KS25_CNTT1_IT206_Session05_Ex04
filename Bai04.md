
| # | Hạng mục                                                                                                  | Nhãn MoSCoW | Lý do                                                                                                                                                                         |
| - | ----------------------------------------------------------------------------------------------------------- | ------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| 1 | Sửa lỗi hiển thị sai cước sau khuyến mãi (đang thu sai tiền khách)                               | Must         | Thiếu nó thì có ra bản mới được không ? không vì đang thu sai tiền sẽ mất uy tín tài chính, bắt buộc phải sửa ngay                                      |
| 2 | Áp mã khuyến mãi khi đặt xe                                                                           | Must         | Thiếu nó thì có ra được bản mới không ? Không vì đây là mục tiêu của "Tháng khuyến mãi"                                                                   |
| 3 | Thanh toán bằng ví RikkeiPay (khách vẫn trả được tiền mặt)                                       | Should       | Có cách làm tạm không ? Có, khách hàng vẫn có thể trả được bằng tiền mặt                                                                                     |
| 4 | Hẹn giờ đặt xe trước (không cần cho chương trình khuyến mãi; đội chưa bàn xong cách làm) | Won't        | Có cần thiết cho bản này không ? Không vì đội chưa bàn xong cách làm và không phục vụ chương trình khuyến mãi của đợt  này                         |
| 5 | Chat với tài xế (khách vẫn gọi điện được)                                                        | Could        | Bỏ đi thì có ai bị ảnh hưởng nhiều không ? Không vì khách vẫn gọi điện trực tiếp cho tài xế được                                                      |
| 6 | Giao diện trang trí cho chương trình khuyến mãi                                                      | Could        | Bỏ đi thì có ảnh hưởng nhiều hay không ? Không vì bản giao diện mới vẫn vận hành tốt cho đặt xe, áp mã khuyến mãi bình thường dù thiếu trang trí |

## Phần 2: So sánh Cách 1 và Cách 2

| Cách                                                                            | Ưu điểm                                                                                                      | Nhược điểm                                                                                                                     |
| -------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------- |
| Cách 1 (Mỗi bộ phận tự gắn Cao / Trung Bình / Thấp)                      | Đơn giản nhanh chóng và làm hài lòng cả xúc của các bộ phận trong cuộc họp                      | Dễ dẫn đến xung đột và không giải quyết được việc thiếu hụt năng lực thực tế của đội ngũ trong một Sprint |
| Cách 2: gắn nhãn MoSCoW cho từng hạng mục bằng câu hỏi của nhãn đó. | Minh Bạch, dựa vào giá trị cốt lõi và ép các bên nhìn vào thực tế vận hành thay vì cảm tính | Sẽ dành thời gian để tranh luận để có thể làm các bộ phận chức năng cảm thấy chưa được ưu tiên             |

## Phần 3: Lựa chọn và phản hồi các bên

+ Với Marketing:
  + Đội hiểu giao diện trang trí sẽ giúp chiến dịch thêm rực rỡ nhưng thiếu đi phần đó thì ứng dụng vẫn chạy và cho phép khách hành đặt xe, nên ta sẽ cếp nó ở mức Could và để dành cho đợt tối ưu phía sau
+ Với chăm sóc khách hàng:
  + Tính năng Chat với tài xế rất tiện lợi nhưng khách vẫn có thể gọi điện cho tài xế được nên ta sẽ đặt nó ở mức Cloud để ưu tiên sửa lỗi cho hiển thị cước và áp dụng mã khuyến mại và đội sẽ hỗ trợ tài xế và khách hàng thông qua  kênh gọi điện trong thời gian này để bảo đảm trải nghiệm của khách hàng được thống suốt
