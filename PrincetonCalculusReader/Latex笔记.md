LaTeX 中的数学公式语法丰富且强大，以下是详细总结：

**一、基本运算符**

1. 加减乘除
   - 加法：`+`，例如`a + b`。
   - 减法：`-`，例如`a - b`。
   - 乘法：直接相邻表示，如`ab`表示\(a\times b\)；也可用`\times`明确表示，如`a\times b`。
   - 除法：用`\frac{numerator}{denominator}`表示，例如`\frac{a}{b}`。

2. 等于、不等于及其他关系符号
   - 等于：`=`，如`a = b`。
   - 不等于：`\neq`，如`a\neq b`。
   - 大于：`>`，如`a > b`。
   - 小于：`<`，如`a < b`。
   - 大于等于：`\geq`，如`a\geq b`。
   - 小于等于：`\leq`，如`a\leq b`。

**二、上下标**

1. 上标
   - 使用`^`表示上标，例如`a^2`表示\(a^{2}\)；多个上标可以依次叠加，如`a^{b^c}`表示\(a^{b^{c}}\)。

2. 下标
   - 使用`_`表示下标，例如`a_n`表示\(a_{n}\)；多个下标同样依次叠加，如`a_{m,n}`表示\(a_{m,n}\)。

**三、括号**

1. 小括号`()`、中括号`[]`和大括号`{}`
   - 直接输入即可，如`(a+b)`, `[a+b]`, `{a+b}`。

2. 花括号在公式环境中的特殊用途
   - 在数学环境中，如果需要大括号包围多行公式，可以使用`\begin{cases}...\end{cases}`，例如：
   ```latex
   \begin{cases}
   a+b = c \\
   d-e = f
   \end{cases}
   ```
   显示效果为：
   $$
   \begin{cases}
   a+b = c \\
   d-e = f
   \end{cases}
   $$

**四、分式**

使用`\frac{numerator}{denominator}`表示分式，例如`\frac{a}{b}`表示\(\frac{a}{b}\)。

**五、根号**

使用`\sqrt[n]{expression}`表示 n 次方根，例如`\sqrt{a}`表示\(\sqrt{a}\)，`\sqrt[3]{b}`表示\(\sqrt[3]{b}\)。

**六、积分与求和**

1. 积分
   - 使用`\int_{lower}^{upper} expression`表示积分，例如`\int_{a}^{b} x dx`表示\(\int_{a}^{b} x dx\)。

2. 求和
   - 使用`\sum_{lower}^{upper} expression`表示求和，例如`\sum_{n = 1}^{10} n`表示\(\sum_{n = 1}^{10} n\)。

**七、矩阵**

1. 基本矩阵
   - 使用`\begin{matrix}...\end{matrix}`创建矩阵，元素之间用`&`分隔，行与行之间用`\\`分隔，例如：
   ```latex
   \begin{matrix}
   a & b \\
   c & d
   \end{matrix}
   ```
   显示效果为：

   $$
   \begin{matrix}
   a & b \\
   c & d
   \end{matrix}
   $$

2. 带括号的矩阵
   - 可以使用`\begin{pmatrix}...\end{pmatrix}`表示小括号矩阵，`\begin{bmatrix}...\end{bmatrix}`表示中括号矩阵，`\begin{Bmatrix}...\end{Bmatrix}`表示大括号矩阵。

**八、希腊字母**

直接输入对应的命令即可表示希腊字母，例如：
   - `\alpha`表示\(\alpha\)。
   - `\beta`表示\(\beta\)。
   - `\gamma`表示\(\gamma\)等。

**九、特殊符号**

1. 无穷大：`\infty`表示\(\infty\)。

2. 向量：使用`\vec{vector}`表示向量，例如`\vec{a}`表示\(\vec{a}\)。

3. 点乘：`\cdot`表示点乘，例如`\vec{a}\cdot\vec{b}`表示\(\vec{a}\cdot\vec{b}\)。

4. 叉乘：`\times`表示叉乘，例如`\vec{a}\times\vec{b}`表示$(\vec{a}\times\vec{b}\)$。

例如，要表示 ，可以这样写：$\lim\limits_{x\to a}f(x)$。