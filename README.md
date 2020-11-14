# AIclassification
Câu 1:
Đầu tiên, khởi tạo vector hệ số w
Ở mỗi bước tính toán, xét các điểm bị đánh sai nhãn. Với mỗi điểm, thay đổi ma trận hệ số wy = wy+f, wy' = wy' - f
Thuật toán dừng khi không còn điểm nào đánh sai nhãn, hoặc vượt quá max_interation

Câu 2:
Lấy weights, sort lại và chọn ra 100 features đầu tiên

Câu 3:
Tính t = min(C, ((wy'-wy)f+1)/2*L2(f))
Sau đó cập nhật giống như đối với perceptron

Câu 4:
Tạo một feature mới là số region(vùng trắng) tạo bởi các digit bằng cách xét từng điểm và kiểm tra các điểm xung quanh có nét (hoặc được đánh số >0) hay không.

Câu 5:
Giống như perceptron, chỉ thêm biến l để lưu datum của pacman tại mỗi legalmove
