Q1: Reflex Agent
  - Trả về khoảng cách mahattan vị trí pacman sau khi thực hiện hành động tới điểm TĂ gần nhất mà pac man trước khi thực hiện hành động.
  - Bài toán trả về số lớn tốt hơn => nhân với -1.

Q2: Minimax
  - Sử dụng thuật toán Minimax.
  - Có nhiều hơn 1 con ma nên để xác định Agent đang hoạt động cần dựa vào AgentIndex
  - Sau khi tất cả Agent hoạt động thì depth tăng lên 1.

Q3: Alpha-Beta Pruning
  - Giống với câu 2 nhưng có thêm 2 tham số a, b để cắt tỉa nhánh không cần thiết từ thuật toán minimax giúp thuật toán chạy nhanh hơn.

Q4: Expectimax
  - Tất cả các con ma đều đi ngẫu nhiên => xác suất chọn 1 trong các hành động là như nhau nên hàm expectFinder trả về tổng giá trị các điểm của các trạng thái sau khi đã thực các hành động chia cho tổng số hành động.

Q5: Evaluation Function
  - Câu này thực hiện đánh giá theo CurrentState
  - Dựa trên chiến thuật trạng thái nào càng gần thực ăn thì sẽ càng được đánh giá cao.
  - GIá trị trả về là điểm của trạng thái hiện tại trừ khoảng cách mahattan từ vị trí Pacman đến điểm TĂ gần nhất.
