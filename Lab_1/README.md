# Lab 1 — Các linh kiện điện tử cơ bản

*đang cập nhật...*

<!-->

## Mục tiêu lab
Trong bài lab này, mình sẽ:
- Học cách đọc giá trị trở kháng của điện trở thông qua vòng màu.
- Mô phỏng mạch điện DC đơn giản bằng phần mềm LTspice (dùng GUI và Netlist).
- Ôn lại các kiến thức cơ bản về dòng, áp của mạch DC đã học ở các buổi lý thuyết.

## Mình đã làm gì?
- Đọc giá trị điện trở thông qua vòng màu, sau đó đo lại bằng đồng hồ vạn năng và so sánh kết quả. 
- Dùng đồng hồ vạn năng để quan sát trở kháng biến thiên biến trở.
- Làm quen với KIT thực hành và mạch nguồn chuyên dụng của phòng lab.
- Tính toán lý thuyết giá trị dòng điện của mạch cho trước, sau đó mô phỏng mạch bằng LTspice để kiểm tra lại.

## Khó khăn và cách giải quyết
| Khó khăn | Cách giải quyết |
|:-------:|:-------:|
| Cắm que đo vào mạch nhưng không thấy hiển thị giá trị đo được | Phải cắm vào đúng vị trí lỗ tiếp điện trên mạch |

## Mình đã học được gì?
- Cách đọc trở kháng điện trở bằng vòng màu (cả loại 4 và 5 vòng màu).
- Các thao tác cơ bản với đồng hồ vạn năng để đo đạc các đại lượng cơ bản của mạch điện (dòng điện, điện áp, điện trở):
  - Cách cắm 2 que đo vào đúng lỗ của VOM để chọn đại lượng tương ứng cần đo,
  - Cách đặt đầu kim loại của que đo vào các vị trí phù hợp của mạch để đo (dòng thì đo nối tiếp, các đại lượng còn lại thì đo song song),
  - Cẩn thận cháy cầu chì khi đo mạch có dòng vượt quá khả năng đo của đồng hồ,
  - Vặn núm xoay và nhấn nút SELECT để chọn đại lượng mà kết quả đo sẽ hiển thị trên màn hình.
- Tầm quan trọng của việc chọn đúng điểm GND trong khâu mô phỏng bằng LTspice, và sai sót sẽ xảy ra nếu không thực hiện đúng.

## (tùy chọn) Hướng phát triển thêm