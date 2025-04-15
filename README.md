# baitap4
Bài tập 04 của SV: K225480106054-Nguyễn Thị Xuân Phương - HQTCSDL
bai tap 4: (sql server)
yêu cầu bài toán:
 - Tạo csdl cho hệ thống TKB (đã nghe giảng, đã xem cách làm)
 - Nguồn dữ liệu: TMS.tnut.edu.vn
 - Tạo các bảng tuỳ ý (3nf)
 - Tạo được query truy vấn ra thông tin gồm 4 cột: họ tên gv, môn dạy, giờ vào lớp, giờ ra.
   trả lời câu hỏi: trong khoảng thời gian từ datetime1 tới datetime2 thì có những gv nào đang bận giảng dạy.

các bước thực hiện:
1. Tạo github repo mới: đặt tên tuỳ ý (có liên quan đến bài tập này)
2. tạo file readme.md, edit online nó:
   paste những ảnh chụp màn hình
   gõ text mô tả cho ảnh đó

Gợi ý:
  sử dung tms => dữ liệu thô => tiền xử lý => dữ liệu như ý (3nf)
  tạo các bảng với struct phù hợp
  insert nhiều rows từ excel vào cửa sổ edit dữ liệu 1 table (quan sát thì sẽ làm đc)
  

deadline: 15/4/2025



-------------------------------------------------------------------------------------------------------------


- B1: Tạo các bảng: GV,LOP,MONHOC,PHONG,TT_KB và chuẩn hóa các bảng dưới dạng 3NF ta được sơ đồ liên kết:

 ![Ảnh chụp màn hình (812)](https://github.com/user-attachments/assets/d3c2795e-8646-48fc-813a-c090ab58b966)


- B2: Thực hiện đặt khóa chính và các khóa ngoại liên kết với khóa chính như trên sơ đồ liên kết

- B3: Copy dữ liệu từ nguồn :TMS.tnut.edu.vn, paste vào excel sau đó thực hiện dán các dữ liệu cần thiết vào các bảng ở mục edit bảng trong sql

![Ảnh chụp màn hình (809)](https://github.com/user-attachments/assets/d39c757e-41d7-4f23-b4a9-2f51dc4cd08c)
![Ảnh chụp màn hình (808)](https://github.com/user-attachments/assets/71fbb07f-ea7b-4f65-99f9-6b0a7760a674)


- B4: Truy vấn ra thông tin gồm 4 cột: TenGV,TenMon,Tietbandau,Tietketthuc:
![image](https://github.com/user-attachments/assets/43a0dac0-eec7-436d-b41b-626435fb4815)

- trả lời câu hỏi: trong khoảng thời gian từ datetime1 tới datetime2 thì có những gv nào đang bận giảng dạy.
![image](https://github.com/user-attachments/assets/8bab52ea-83f3-4016-8619-24a760d8f56c)





