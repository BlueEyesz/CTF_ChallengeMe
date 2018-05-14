# RC3-2017

1. Forensic 100

Đề bài cho ta 1 file pcap. Download file về . Ta tiến hành phân tích 

Vào wireshark ->Statistic -> Conversation . Ta điều tra cuộc trò chuyện giữa 2 host A và B

Đọc vào hoa cả mắt bởi có rất nhiều được gởi đi . Đây là đâu . Tôi là ai :v ......

Sau 1 hồi phân tích , bằng phương pháp google sama , mình tiến hành export các data object ra xem trong nó chứa flag không ???

Vào File -> Export Objects -> chọn HTTP ( khả năng tiềm ẩn  chứa các flag,các plaintext rất cao  bởi các dữ liệu truyền qua giao thức này đều dưới dạng plaintext )

 Và mình tìm được 1 file hình ảnh -> cat.jpg .Sau đó tôi save file lại . Vào tiến hành mở file . -> Flag ngay trước mắt  :v 
 
 Flag is : RC3-2017{warm_kitty_12unjfea9}
 
 Đây là 1 bài khá dễ :v . *Warm up*
 
 
 2. Hello 50
 
 Đầu tiên , mình bỏ Ubuntu để xem đây là file gì ? Mình sử dụng file - tên file để hiện thị xem file đó là file gì ?? định dạng ra sao ?
 
 Mình thấy được là đây là file  ELF 64-bit LSB executable, x86-64 . Bỏ vào IDA thử -> Sử dụng phím tắt Shift + F12 để xem tất cả Strings đó 
 
thì thấy flag luôn . Quá là ez =))) 

Flag is : RC3-2017{little_ball_of_fur}
