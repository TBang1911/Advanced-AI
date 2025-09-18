## Câu 1: Làm thế nào để chúng ta tìm ra lời giải tối ưu (chuỗi hành động/trạng thái)?
&emsp; Hãy xây dựng một cây tìm kiếm cho đồ thị không gian trạng thái. Trong cây tìm kiếm, mỗi nút biểu diễn một trạng thái, còn các cạnh biểu diễn hành động dẫn đến trạng thái tiếp theo. Bằng cách duyệt cây này theo các chiến lược tìm kiếm (ví dụ: BFS, DFS, Uniform Cost, A), có thể đánh giá các chuỗi hành động và chọn ra con đường tối ưu dẫn đến trạng thái mục tiêu.
<img width="587" height="304" alt="image" src="https://github.com/user-attachments/assets/fcde349b-cc57-4f0a-b179-df9c67bb8ab7" />
<br> 
&emsp; Trong đó: + Initial state: Trạng thái ban đầu. <br>
&emsp; &emsp; &emsp; &emsp; &emsp; + Actions: Các hành động. <br>
&emsp; &emsp; &emsp; &emsp; &emsp; + Transition model: Mô hình chuyển trạng thái. <br>
&emsp; &emsp; &emsp; &emsp; &emsp; + Goal state: Trạng thái đích. <br>
&emsp; &emsp; &emsp; &emsp; &emsp; + Path cost: chi phí đường đi.
## Câu 2: Có bao nhiêu cách để sắp xếp/thứ tự hóa n đối tượng?
&emsp; Số cách sắp xếp n đối tượng phụ thuộc vào điều kiện của bài toán: <br>
&emsp; &emsp; 1. Nếu tất cả n đối tượng đều khác nhau và sắp xếp toàn bộ: <img width="292" height="48" alt="image" src="https://github.com/user-attachments/assets/790c4f2e-b4b2-4db5-9db7-978e5585a677" /><br>
<br> Ví dụ: với n = 3, ta có 3! = 6 cách. <br>
&emsp; &emsp; 2. Nếu chỉ chọn ra k đối tượng từ n để sắp xếp (hoán vị chập k của n): <img width="213" height="79" alt="image" src="https://github.com/user-attachments/assets/30894cde-1c9d-4025-aea0-87377d8b70f6" /> <br>
<br> Ví dụ: từ 5 đối tượng, sắp xếp 3 đối tượng => p(5,3) = 60 cách. <br>
&emsp; &emsp; 3. Nếu trong n đối tượng có phần tử trùng lặp: <br> <img width="181" height="77" alt="image" src="https://github.com/user-attachments/assets/58f19384-4f66-498f-a284-ce31811ecb54" /><br>
<br>Ví dụ: với từ "MOM" (3 ký tự, trong đó M lặp 2 lần), số cách sắp xếp là 3..<br>
&emsp; &emsp; 4. Nếu cho phép lặp lại khi sắp xếp k vị trí từ n đối tượng: <img width="61" height="48" alt="image" src="https://github.com/user-attachments/assets/a57f9a29-a494-4106-b161-1d48e0c6e2ba" /><br> 
<br> Ví dụ: chọn 3 vị trí từ 2 đối tượng (A, B) cho phép lặp 8 cách.
