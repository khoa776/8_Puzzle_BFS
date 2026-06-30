# BÀI TẬP 8 PUZZLE (FILE: 8_puzzle(all))

## Giới thiệu

Dự án này là chương trình giải bài toán **8 Puzzle** bằng Python.  
Chương trình có giao diện đơn giản bằng **Tkinter**, cho phép tạo puzzle ngẫu nhiên, chọn thuật toán giải và xem từng bước di chuyển từ trạng thái bắt đầu đến trạng thái đích.

## Chức năng chính

- Tạo trạng thái bắt đầu và trạng thái đích ngẫu nhiên.
- Hiển thị bảng 8 Puzzle dạng 3x3.
- Chọn nhiều thuật toán tìm kiếm khác nhau.
- Hiển thị:
  - Số bước giải.
  - Số node đã duyệt.
  - Danh sách các trạng thái qua từng bước.

## Các thuật toán được sử dụng

Chương trình hỗ trợ các thuật toán:

- BFS
- DFS
- IDS
- UCS
- Greedy Search
- A*
- IDA*
- Hill Climbing
- Steepest Hill Climbing
- Stochastic Hill Climbing
- Random Restart Hill Climbing
- Local Beam Search
- Simulated Annealing
- Blind Search
- AND-OR Search
- Backtracking
- Forward Checking
- Min-Conflicts
- AC-3

## Cách chạy chương trình

1. Mở file notebook:

```bash
8_puzzle(all).ipynb
2. Chạy toàn bộ cell trong Jupyter Notebook hoặc Google Colab.

3. Giao diện chương trình sẽ hiển thị.

4. Chọn thuật toán muốn dùng.

5. Nhấn nút Solve để giải puzzle.

6. Nhấn New Puzzle để tạo bài toán mới.

Cách hoạt động
Chương trình tạo một trạng thái đích ngẫu nhiên, sau đó tạo trạng thái bắt đầu bằng cách di chuyển ngẫu nhiên từ trạng thái đích.

Khi người dùng chọn thuật toán và nhấn Solve, chương trình sẽ tìm đường đi từ trạng thái bắt đầu đến trạng thái đích.

Nếu tìm được lời giải, chương trình hiển thị các bước di chuyển.

Nếu không tìm được, chương trình hiển thị thông báo không tìm thấy kết quả.

Ý nghĩa các thông tin hiển thị
Start: trạng thái ban đầu.
Goal: trạng thái cần đạt được.
Steps: số bước di chuyển.
Nodes: số node/trạng thái đã duyệt.
States: danh sách các trạng thái trong quá trình giải.
Ghi chú
Ô trống trong puzzle được biểu diễn bằng số 0.
Một số thuật toán có thể không luôn tìm được lời giải tối ưu.
Các thuật toán cục bộ như Hill Climbing có thể dừng lại khi gặp điểm kẹt.
Vì trạng thái được tạo ngẫu nhiên nên kết quả mỗi lần chạy có thể khác nhau.
Mục đích
Dự án được dùng để minh họa cách các thuật toán tìm kiếm hoạt động trên bài toán 8 Puzzle, giúp dễ quan sát và so sánh kết quả giữa nhiều thuật toán khác nhau.
