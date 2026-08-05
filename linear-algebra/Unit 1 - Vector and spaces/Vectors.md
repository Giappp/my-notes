# 1. Khái niệm
Vector là một dạng biểu thị cả độ lớn (magnitude) và hướng (direction) thường được hiểu là 1 đoạn thẳng có độ dài và hướng, là phần tử thuộc một **không gian vector** - bất kỳ đối tượng nào tuân theo phép Cộng Vector và Nhân với một số (Scalar Multiplication) và thỏa mãn các tiên đề đại số (giao hoán, kết hợp, phân phối, có phần tử trung tính) đều là vector
Trong CNTT và KHMT: 
- Vector là mảng 1 chiều có thứ tự (Ordered Array): Biểu diễn/đại diện cho một chuỗi dữ liệu.
### Ví dụ về Vector trong thực tế
- Vận tốc: biểu diễn tốc độ và hướng 
## 2. Biểu diễn vector
#### Vector 1 chiều:
Được biểu diễn thành 1 trục trên trục số (e.g. Ox, Oy, Oz)
#### Vector 2 chiều:
Được biểu diễn trên mặt phẳng tọa độ 2 chiều Oxy
#### Vector 3 chiều:
Được biểu diễn trên hệ tọa độ không gian 3 chiều Oxyz
#### Vector n chiều:
Về lý thuyết, vector có thể mở rộng lên vô hạn chiều, nhưng con người chúng ta chỉ hình dung được không gian 3 chiều. Nên việc biểu diễn 1 vector n-chiều dưới dạng hình học sẽ rất khó hiểu
Với n > 3 chiều, chúng ta thường biểu diễn theo 3 dạng chính:
- Biểu diễn đại số (Algebra Representation): Một vector n chiều $x \in R^n$ được biểu diễn thành 1 bộ số có n phần tử có thứ tự:
$$
x = (x_1, x_2, x_3, ..., x_n) \quad \text{hoặc dạng cột} \quad x = \begin{bmatrix} x_1 \\ x_2 \\ \vdots \\ x_n \end{bmatrix}
$$

- Biểu diễn trong máy tính: Đơn giản chỉ là 1 mảng 1 chiều chứa n phần tử
- Biểu diễn hình học qua phép chiếu - giảm chiều dữ liệu (PCA)
#### Không gian số thực
Trong các tài liệu toán học, ta thường thấy kí hiệu: $\mathbb{R}, \mathbb{R^2}, \mathbb{R^n}$ . Bản chất kí hiệu này mô tả vector đó chứa bao nhiêu bộ số thực.
VD: vector $\overrightarrow{x}(x_1,x_2)} \in \mathbb{R^2}$ là bộ số chứa 2 số thực: $x1 \in R \quad \text{và} \quad x2 \in R$ 
## 3. Các phép toán với Vector
#### Cộng 2 vector
Cho 2 vector $a,b \in \mathbb{R^n}$, cộng 2 vector là cộng các phần tử ở vị trí tương ứng với nhau.
$$
(a+b)_i = \sum_{i=0}^{n} a_i + b_i
$$
Tính chất:
$$
\overrightarrow{a} + \overrightarrow{b} = \overrightarrow{b} + \overrightarrow{a}
$$
#### Nhân vector với 1 số (Scalar)
Nhân vector với 1 số n được hiểu là kéo độ dài của vector lên n lần, Nên:
$$
n \overrightarrow{a(x,y)} = (n*x,n*y) 
$$
