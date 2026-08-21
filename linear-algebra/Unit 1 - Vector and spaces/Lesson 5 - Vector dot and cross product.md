## 1. Vector dot product and vector length
Cho 2 vector:  $\overrightarrow{a} = \{a_1, a_2, \dots, a_n\}$, $\overrightarrow{b} = \{b_1, b_2, \dots, b_n\}$. Dot product hay tích vô hướng của 2 vector được định nghĩa:
$$
\vec{a} \cdot \vec{b} = a_1b_1 + _2b_2 + \dots + a_nb_n = \sum_{i=1}^{n}a_{i}b_{i}
$$
Nếu $a = b$ thì sao? Chúng ta sẽ có độ dài của vector:
$$
\vec{a} \cdot \vec{a} = a_1^2 + a_2^2 + \dots + a_n^2 = || a ||^2
$$
Do đó:
$$
||\vec{a}|| = \sqrt{ \vec{a} \cdot \vec{a} }
$$

Các tính chất:
- Giao hoán: $\vec{a} \cdot \vec{b} = \vec{b} \cdot \vec{a}$ 
- Phân phối: $(\vec{a} + \vec{b}) \cdot \vec{c} = \vec{a} \cdot \vec{c} + \vec{b} \cdot \vec{c}$
- $(c \vec{a}) \cdot \vec{b} = c(\vec{a} \cdot \vec{b})$

### Bất đẳng thức Cauchy - Schwarz:
Với $\vec{x}, \vec{y} \neq 0$ ta có 
$$
| \vec{x} \cdot \vec{y}| \le ||\vec{x}|| \cdot ||\vec{y}||
$$
Dấu "=" xảy ra khi 2 vector cùng phương (collinear):
$$
\vec{x} = c \vec{y}
$$
### Bất đẳng thức tam giác
$$
|\vec{x} + \vec{y}| \le ||\vec{x}|| + ||\vec{y}||
$$
Dấu "=" xảy ra khi 2 vector cùng phương hoặc một trong hai là vector 0

## 2. Defining the angle between vectors
Từ Cauchy - Schwarz:
$$
|\vec{a} \cdot \vec{b}| \le ||\vec{a}|| \cdot ||\vec{b}||
$$
suy ra:
$$
-1 \le \frac{\vec{a} \cdot \vec{b}}{||\vec{a}|| ||\vec{b}||} \leq 1
$$
Nên ta có thể định nghĩa nó là $\cos \theta$ 
Cho 2 vector $\vec{a}, \vec{b} \in \mathbb{R}^n$, khác 0. Góc giữa 2 vector được tính bằng:
$$
\cos(\theta) = \frac{\vec{a} \cdot \vec{b}}{||\vec{a}|| \cdot ||\vec{b}||}
$$
Tính chất đặc biệt: $\vec{a} \cdot \vec{b} = \cos \theta \times ||\vec{a}|| ||\vec{b}||$
- $\vec{a} \cdot \vec{b} > 0$: $\theta$ là góc nhọn
- $\vec{a} \cdot \vec{b} < 0$: $\theta$ là góc tù
- $\vec{a} \cdot \vec{b} = 0$: $\theta$ là góc nhọn
## 3. Defining a plane in with a point and normal vector
Cho $\vec{a} = {a_1, a_{2}, \dots a_{n}}$ bất kì và 1 vector $\vec{n}$ ta có thể viết phương trình siêu phẳng chứa điểm $\vec{a}$ và vuông góc với $\vec{n}$.  Bằng cách: Lấy 1 vector $\vec{x}$ bất kì thuộc siêu phẳng đặt là $\vec{x} = x_{1}, x_{2}, \dots x_{n}$ ta có vector nằm trọn trong siêu phẳng đó là $\vec{x} - \vec{a}$, mà $\vec{n}$ vuông góc với siêu phẳng đó -> nó vuông góc với mọi vector thuộc siêu phẳng, Nên:
$$
\vec{n} \perp (\vec{x} - \vec{a}) \to \vec{n} \cdot (\vec{x} - \vec{a}) = 0
$$
