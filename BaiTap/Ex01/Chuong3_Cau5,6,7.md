## Câu 5: Cách đo nào sẽ được sử dụng trong hai cách bên dưới ?
<img width="982" height="549" alt="image" src="https://github.com/user-attachments/assets/81840f54-677e-4aea-8851-83b46165a8a0" />
  &emsp; Manhattan thường sẽ được sử dụng nhiều hơn trong trường hợp giải mê cung, vì mê cung có nhiều đường gấp khúc.

## Câu 6: Chi phí cần để ước lượng cho bài toán tic-toc-toe là gì ? 
  &emsp; Chi phí ước lượng chính là giá trị heuristic của một trạng thái bàn cờ, được tính dựa trên mức độ lợi thế hay bất lợi (khả năng thắng, thua, hòa) của người chơi tại trạng thái đó.

## Câu 7: Giá trị heuristic cho các bàn cờ dưới đây là bao nhiêu: <img width="1371" height="447" alt="image" src="https://github.com/user-attachments/assets/a06a198b-bbd0-474e-a5c1-6c2631102e55" />
  &emsp; Bàn cờ 1:
Hàng 1: 1 + 1 + 0 = 2 <br>
Tương tự: <br>
Hàng 2: -1 <br>
Hàng 3: -1 <br>
Cột 1: 1 + 0 + (-1) = 0 <br>
Cột 2: 0 <br>
Cột 3: 0 <br>
Đường chéo chính: 0 <br>
Đường chéo phụ: -2 <br>
Heuristic: Max(2,-2)/ 3 = 2/3 <br>
  &emsp; Bàn cờ 2:

