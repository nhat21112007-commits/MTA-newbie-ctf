---
title: osint

---

Do ảnh vượt qua dung lượng nên em kh thể tải lên đc
## 1. What I Missed
![Ảnh màn hình 2026-09-15 lúc 09.36.15](https://hackmd.io/_uploads/B1PNyELFGx.png)
Flag : MSEC{VN-C482}
Cách tìm :
>Dựa trên dữ liệu chính xác về công trình biểu tượng cho lịch sử quân sự thủ đô (Bảo tàng Lịch sử Quân sự Việt Nam) và chiếc máy bay vận tải nổi tiếng được trưng bày tại đây (chuyên cơ IL-14 từng phục vụ Chủ tịch Hồ Chí Minh và Trung đoàn 919):
## 2. Sobriquet
![Ảnh màn hình 2026-09-15 lúc 09.42.16](https://hackmd.io/_uploads/SkI5g4IKzl.png)
MSEC{van_ly_truong_thanh_thu_nho}
>Nằm dưới chân núi Múa, thuộc khu vực Tam Cốc - Bích Động, Ninh Bình
>Nơi đây thường được du khách và truyền thông mệnh danh là "Vạn Lý Trường Thành thu nhỏ" của Việt Nam.

## 3.60ĐN
![Ảnh màn hình 2026-09-15 lúc 09.44.17](https://hackmd.io/_uploads/ByeGWVUYzg.png)
Flag : MSEC{ho_long_an}
>Dựa trên các dữ liệu về cảnh quan (hồ nước có sen súng, ngọn núi đá vôi nhô lên giữa lòng hồ, lan can gỗ chạm hoa văn) và danh hiệu "Vịnh Hạ Long thu nhỏ" của miền Nam, địa điểm trong ảnh chính là Hồ Long An

## 4.Dưới Ánh Hoàng Hôn
![Ảnh màn hình 2026-09-15 lúc 09.46.41](https://hackmd.io/_uploads/Hkp5Z48Fze.png)
Flag : MSEC{20.946_107.101_7PG9W4W2+FJ}
>Đây là cung cá heo ở quảng ninh nơi hay tổ chức hội chợ
>Sau khi biết tên địa điểm, mở Google Maps và tìm kiếm tên công trình.
>Nhấp chuột phải vào vị trí chính xác trên bản đồ để lấy ngay tọa độ GPS và lấy đc và làm tròn 20.946, 107.101
>Và lấy phần pluscode ở dưới chỗ mô tả của địa điểm
>Tiến hành thử flag cho đến khi connect
## 5.Countryside
![Ảnh màn hình 2026-09-15 lúc 09.53.59](https://hackmd.io/_uploads/SkXIQ4LFGx.png)
```
Đề bài :
```
![IMG_20250328_215136](https://hackmd.io/_uploads/ryidXVIKzx.jpg)
Flag: MSEC{landowning_jukeboxes_simmering}
Cách làm:
> dùng công cụ the ride atlas để có thể tìm đc gps lúc chụp ảnh 
![Ảnh màn hình 2026-09-15 lúc 09.58.50](https://hackmd.io/_uploads/HJaFVV8KMe.png)
> sau đó vào công cụ đề cho và nhập tọa độ
![Ảnh màn hình 2026-09-15 lúc 10.03.28](https://hackmd.io/_uploads/ByccrNLKGl.png)
## 6.Ành Trương Nội Thất
![Ảnh màn hình 2026-09-15 lúc 10.05.09](https://hackmd.io/_uploads/HkQxLVItMl.png)
Hint:
![Ảnh màn hình 2026-09-15 lúc 10.05.39](https://hackmd.io/_uploads/BJbMIVItfl.png)
Flag:MSEC{1_Am_4_W00dw0rk3r_Wh0_4cc1d3nt4lly_P0s4t3d_H1s_G1thub_T0k3n_Th3n_G0t_H1s_4cc0unt_Fl4gg3d_4nd_L34k3d_Th3_Auth0r_S3cr3t}
>Cách làm : ở đề bài ta có thể đọc đcs sau lê anh trương có 1 đường dẫn giống với tên 1 tài khoản và dự vào hint -> nó là tên tk x
> sau khi vào x em kiểm tra xem có gì kì lạ kh và có phát hiện 1 đường link dẫn đến 1 trang web
![Ảnh màn hình 2026-09-15 lúc 10.11.54](https://hackmd.io/_uploads/SkfqvEUYzg.png)
> mở trang web sau đó tìm và thấy trong mã nguồn của trang web có ẩn giấu 1 đường linh github https://github.com/4htru0ngno1th4t/no1th4tth4chth4t-pr0ject
> ![Ảnh màn hình 2026-09-15 lúc 10.12.45](https://hackmd.io/_uploads/SyFG_ELKMg.png)
>mở link github và thấy 
![Ảnh màn hình 2026-09-15 lúc 10.16.26](https://hackmd.io/_uploads/Skw9uVUKMl.png)
Thấy ở trong này trống không và tìm kh thấy gì nên chỉ có thể là nó đã bị ẩn hoặc xóa đi mở activity của trang web và thấy trogn đấy đã có mục bị xóa và tìm kiếm thấy 
```
TVNFQ3sxX0FtXzRfVzAwZHcwcmszcl9XaDBfNGNjMWQzbnQ0bGx5X1AwczR0M2RfSDFzX0cxdGh1Yl9UMGszbl8=
```
![Ảnh màn hình 2026-09-15 lúc 10.20.15](https://hackmd.io/_uploads/S16_Y4UYGe.png)
>ở đây có ghi a piece of flag nên theo hint có thể nó kh phải là ig của bài này sau đó thử tên của github do nãy vào bằng link nên tên rất dễ bị bỏ quên 
![Ảnh màn hình 2026-09-15 lúc 10.24.45](https://hackmd.io/_uploads/H1V95V8tfe.png)
thấy 1 chuỗi số lạ và giải nó ra là
```
52 110 100 95 76 51 52 107 51 100 95 84 104 51 95 65 117 116 104 48 114 95 83 51 99 114 51 116 125
```
>Dịch ra thì kh phải là link dẫn đến tele như đã gợi í 
>vì ảnh trong ig kh thể tải về nguyên vẹn theo như em biết nen có thể loại trừ th giấu trong ảnh nên nó chỉ có thể còn giấu ở reels của ig
![Ảnh màn hình 2026-09-15 lúc 10.29.16](https://hackmd.io/_uploads/rJDjoEUKfg.png)
> Có thể dễ dàng thấy đc nó có 1 mảng giấy kì lạ và 1 đoạn link dẫn đến con bot ở tele
> sau khi đến thì phải trả lời câu hỏi của con bot và nó sẽ bắt mình nhập từ đẻ chứng minh là admin 
> do ở bức ảnh trc có thể thấy có 1 mảnh giấy kì lạ nó đi cùng với link tele rất có thể liên quan đến nhau 
> nên em nhập thử và thấy nó đúng và trả về 1 chuỗi kí tự 
> 
![Ảnh màn hình 2026-09-15 lúc 10.31.34](https://hackmd.io/_uploads/HyVm34UKzl.png)
```
%54%68%33%6e%5f%47%30%74%5f%48%31%73%5f%34%63%63%30%75%6e%74%5f%46%6c%34%67%67%33%64%5f
```
![Ảnh màn hình 2026-09-15 lúc 10.34.31](https://hackmd.io/_uploads/SJBC3NUFzg.png)
> ở đây cho thấy là có 3 mảnh ghép nên ta có thể suy ra đc 3 mảng kí tự tìm đc là dùng cho để ghép flag 
ghép lại dùng AI để dịch và lấy flag .
## 7.NovaTech 1
![Ảnh màn hình 2026-09-15 lúc 11.34.31](https://hackmd.io/_uploads/ryHJiSIFGl.png)
```
đề bài: https://103.188.244.73:8081
```
> sau khi mở link sẽ dẫn đến web và thử các đuôi
> thấy đuôi /robots.txt có đường dẫn
![Ảnh màn hình 2026-09-15 lúc 11.38.31](https://hackmd.io/_uploads/SyHCjrLYGx.png)
thấy có link và dán nó vào công cụ wayback và ấn vào link đầu
![Ảnh màn hình 2026-09-15 lúc 11.34.51](https://hackmd.io/_uploads/HywliSLFfe.png)
> và enter vào ngày 30 và ra web
![Ảnh màn hình 2026-09-15 lúc 11.35.29](https://hackmd.io/_uploads/HkCGsHUYfe.png)
## 8.NovaTech 2
![Ảnh màn hình 2026-09-15 lúc 14.24.20](https://hackmd.io/_uploads/Hk42G_8Ffl.png)
flag: MSEC{FinTechXYZ}
Cách giải: đề bai đọc nói la đọc kĩ ở phần đầu tiêu sử![Ảnh màn hình 2026-09-15 lúc 14.23.47](https://hackmd.io/_uploads/HyJeXdUFfl.png)
tên công ty ở ngay đoạn đầu 
## 9.NovaTech 3
![Ảnh màn hình 2026-09-15 lúc 14.26.19](https://hackmd.io/_uploads/BkFQQ_UYzl.png)
Flag: MSEC{hoangphuc_le}
> Cách làm : tải file ảnh resume về máy và vào terminal 
> xử dụng exiftool để trích xuất thông tin tỏng file
![Ảnh màn hình 2026-09-15 lúc 14.54.32](https://hackmd.io/_uploads/H1XQ0FUYfl.png)
> Trong đề bài còn đề cập đến 1 tệp đính kèm trong bài 
> Để có thể tìm thấy tệp ẩn đó thì phải dùng đến em dùng trang web https://mapsoft.com/tools/Pdf/ExtractEmbeddedFiles
![Ảnh màn hình 2026-09-15 lúc 16.27.02](https://hackmd.io/_uploads/BJjsy9Utfe.png)
> Và tải đc ảnh 
![office_photo-2](https://hackmd.io/_uploads/H1wAy5LFMx.jpg)
> trích xuất thông tin từ ảnh bằng exiftool
>lấy đc gps của bức ảnh và date time original
![Ảnh màn hình 2026-09-15 lúc 16.38.49](https://hackmd.io/_uploads/HkLEz58Fzx.png)

## 10.NovaTech 4
![Ảnh màn hình 2026-09-15 lúc 16.39.29](https://hackmd.io/_uploads/SkLOf98FGg.png)
flag: MSEC{ngach_1a/1_2026-03-14_1630}
> lấy gps và thời gian ở bài trên và tra trên google map
![Ảnh màn hình 2026-09-15 lúc 15.17.32](https://hackmd.io/_uploads/H12V75IYGx.png)
## 11.NovaTech 5
![Ảnh màn hình 2026-09-15 lúc 16.44.21](https://hackmd.io/_uploads/B1mtX5IKzl.png)
Flag : MSEC{overseas_trust_bank_8842}
>Cách tìm: nhập các câu trả lời vào trang web bài cho
![Ảnh màn hình 2026-09-15 lúc 15.31.17](https://hackmd.io/_uploads/Bk1vU5UFGl.png)
dùng mã này để tìm ra bước tiếp theo
dùng AI để viết tool giải đoạn mã này
```
import base64

s = "WUZHQUEJHh1UWEZbRFAdUl1eHlZFSAZdWVocX11FUEZWUloeU1NQWlddVQ=="
data = base64.b64decode(s)   
key = b"123"                
out = bytes([data[i] ^ key[i % len(key)] for i in range(len(data))])
print(out.decode())          
```
> sau khi giải nó sẽ ra 1 link github:
https://github.com/dvy4nhh/novatech-backend
![Ảnh màn hình 2026-09-15 lúc 17.03.45](https://hackmd.io/_uploads/rJofu5IFze.png)
>Thấy phần này kh có gì đáng chú ý nên khả năng đã bị xóa 
> Vào phần acticity để xem thì thấy có 2 mục đã bị xóa 
![Ảnh màn hình 2026-09-15 lúc 17.05.38](https://hackmd.io/_uploads/rJYFOc8KMg.png)
và thấy có các dòng dẫn đến flag
## 12. MSEC 
![Ảnh màn hình 2026-09-15 lúc 17.37.06](https://hackmd.io/_uploads/BykkgoIKMe.png)
Flag : MSEC{contrived_dredged_veered}
Dùng exiftool để đc địa chỉ của ảnh
![Ảnh màn hình 2026-09-15 lúc 17.42.10](https://hackmd.io/_uploads/H11M-jLtGl.png)
rồi lên google tra thị trấn msec và tìm đến nhà như trong ảnh rồi lấy gps
![Ảnh màn hình 2026-09-15 lúc 17.29.00-2-2](https://hackmd.io/_uploads/B1qmC9Utfg.png)
sau khi lấy đc gps thì dùng trang web w3w để lấy 3 từ tiếng anh
![ầ](https://hackmd.io/_uploads/B1Z0WjIKzl.jpg)










