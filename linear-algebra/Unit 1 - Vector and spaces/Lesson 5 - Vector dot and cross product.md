## 1. Vector dot product and vector length
Cho 2 vector:  $\overrightarrow{a} = \{a_1, a_2, \dots, a_n\}$, $\overrightarrow{b} = \{b_1, b_2, \dots, b_n\}$. Dot product hay tích vô hướng của 2 ma trận được định nghĩa:
$$
a \cdot b = a_1b_1 + _2b_2 + \dots + a_nb_n
$$
Nếu $a = b$ thì sao? Chúng ta sẽ có độ dài của vector:
$$
a \cdot a = || a ||^2 = a_1^2 + a_2^2 + \dots + a_n^2
$$

Các tính chất:
- Giao hoán: $a \cdot b = b \cdot a$ 
- Kết hợp: $(a + b) \cdot c = a \cdot c + b \cdot c$
### Bất đẳng thức Cauchy - Schwarz:
$$
\overrightarrow{x} \cdot \overrightarrow{y}  \le | \overrightarrow{x} \cdot \overrightarrow{y}| \le ||\overrightarrow{x}|| \cdot ||\overrightarrow{y}||
$$
Dấu "=" xảy ra khi 2 vector cùng phương (collinear):
$$
\overrightarrow{x} = c \overrightarrow{y}
$$
### Bất đẳng thức tam giác
$$
|\overrightarrow{x} + \overrightarrow{y}| \le ||\overrightarrow{x}|| + ||\overrightarrow{y}||
$$
Dấu "=" xảy ra khi 2 vector cùng phương