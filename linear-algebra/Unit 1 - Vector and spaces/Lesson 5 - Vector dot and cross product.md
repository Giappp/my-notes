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
\vec{x} \cdot \vec{y}  \le | \vec{x} \cdot \vec{y}| \le ||\vec{x}|| \cdot ||\vec{y}||
$$
Phát biểu: Giá trị tích vô hướng của 2 vector luôn bé hơn hoặc bằng tích độ dài 2 vector đó
Dấu "=" xảy ra khi 2 vector cùng phương (collinear):
$$
\vec{x} = c \vec{y}
$$
### Bất đẳng thức tam giác
$$
|\vec{x} + \vec{y}| \le ||\vec{x}|| + ||\vec{y}||
$$
Dấu "=" xảy ra khi 2 vector cùng phương

## 2. Defining the angle between vectors
Cho 2 vector $\vec{a}, \vec{b} \in \mathbb{R}^n$, khác 0. Góc giữa 2 vector được tính bằng:
$$
\cos(\theta) = \frac{\vec{a} \cdot \vec{b}}{||\vec{a}|| \cdot ||\vec{b}||}
$$
## 3. Defining a plane in $R^3$ with a point and normal vector
Cho $\vec{a} = {a_1, a_{2}, \dots a_{n}}$ bất kì và 1 vector $\vec{n}$ ta có thể viết phương trình siêu phẳng chứa điểm $\vec{a}$ và vuông góc với $\vec{n}$.  Bằng cách: Lấy 1 vector $\vec{x}$ bất kì thuộc siêu phẳng đặt là $\vec{x} = x_{1}, x_{2}, \dots x_{n}$ ta có vector nằm trọn trong siêu phẳng đó là $\vec{x} - \vec{a}$, mà $\vec{n}$ vuông góc với siêu phẳng đó -> nó vuông góc với mọi vector thuộc siêu phẳng, Nên:
$$
\vec{n} \perp (\vec{x} - \vec{a}) \to \vec{n} \cdot (\vec{x} - \vec{a}) = 0
$$
