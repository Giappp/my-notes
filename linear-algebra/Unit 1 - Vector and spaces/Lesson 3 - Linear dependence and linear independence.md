## 1. Linear dependence - phụ thuộc tuyến tính
Cho tập vector $[S = \{ v_1, v_2, \dots, v_n \}]$ 
(S) được gọi là phụ thuộc tuyến tính nếu tồn tại các scalar $c_1, c_2, \dots, c_n$ **không đồng thời bằng 0**, sao cho:
$$
c_1v_1 + c_2v_2 + \dots + c_nv_n = 0
$$
Nói cách khác, phương trình trên có ít nhất một nghiệm không tầm thường:
$$
(c_1, c_2, \dots, c_n) \neq(0,\dots,0)
$$
### Trực giác
Có ít nhất một vector trong tập có thể biểu diễn bởi các vector còn lại
Ví dụ:
$$
v_1=(1,2), \quad v_2=(2,4)
$$
Vì $2v_1 - v_2 = 0$ nên $\{ v_1, v_2\}$ là phụ thuộc tuyến tính
## 2. Linea independence
Cho tập vector S = $\{ v_1, v_2, \dots, v_n \}$. (S) được gọi là độc lập tuyến tính nếu phương trình:
$$
c_1v_1 + c_2v_2 + \dots + c_nv_n = 0
$$
chỉ có 1 nghiệm duy nhất (nghiệm tầm thường)
### Trực giác
Không có vector nào trong tập có thể được biểu diễn bằng tổ hợp tuyến tính của các vector còn lại.
Ví dụ:
$v_1 = (1,0), \quad v_2 = (0,1)$. Nếu $c_1v_1 + c_2v_2 = 0$ thì $c_1 = c_2 = 0$. Do đó $\{ (1,0), (0,1)\}$