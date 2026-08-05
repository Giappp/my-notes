# 1. Khái niệm
Vector là một dạng biểu thị cả độ lớn (magnitude) và hướng (direction), là phần tử thuộc một **không gian vector** - bất kỳ đối tượng nào tuân theo phép Cộng Vector và Nhân với một số (Scalar Multiplication) và thỏa mãn các tiên đề đại số (giao hoán, kết hợp, phân phối, có phần tử trung tính) đều là vector
Trong CNTT và KHMT: 
- Vector là mảng 1 chiều có thứ tự (Ordered Array): Biểu diễn/đại diện cho một chuỗi dữ liệu.
### Ví dụ về Vector trong thực tế
- Vận tốc: biểu diễn tốc độ và hướng 
## 2. Biểu diễn vector
### Vector 1 chiều:
Được biểu diễn thành 1 trục trên trục số (e.g. Ox, Oy, Oz)
### Vector 2 chiều:
Được biểu diễn trên mặt phẳng tọa độ 2 chiều Oxy
### Vector 3 chiều:
Được biểu diễn trên hệ tọa độ không gian 3 chiều Oxyz
### Vector n chiều:
- Về lý thuyết, vector có thể mở rộng lên vô hạn chiều, nhưng con người chúng ta chỉ hình dung được không gian 3 chiều. Nên việc biểu diễn 1 vector n-chiều dưới dạng hình học là không khả thi.
- Với n > 3 chiều, chúng ta thường biểu diễn theo 3 dạng chính:
	- Biểu diễn đại số (Algebra Representation): Một vector n chiều $x \in R^n$ được biểu diễn thành 1 bộ số có n phần tử có thứ tự:
$$
x = (x_1, x_2, x_3, ..., x_n) \text{hoặc dạng cột}
$$