# Placeholder

Welcome! This page exists to test the rendering capabilities of the site.

---

# Header 1
## Header 2
### Header 3
#### Header 4
##### Header 5
###### Header 6

# Text

Normal text.

**Bold**

*Italic*

***Bold + Italic***

~~Strikethrough~~

`inline code`

> This is a blockquote.
>
> It supports multiple paragraphs.

---

# Lists

## Unordered

* Apple
* Banana

  * Nested item
  * Another nested item
* Cherry

## Ordered

1. First
2. Second

   1. Nested
   2. Nested
3. Third

## Task List

* [x] Markdown
* [x] Syntax Highlighting
* [x] MathJax
* [ ] Actual content

---

# Table

| Language   | Purpose      | Rating |
| ---------- | ------------ | :----: |
| C          | Systems      |  ⭐⭐⭐⭐⭐ |
| C++        | Applications |  ⭐⭐⭐⭐☆ |
| JavaScript | Web          |  ⭐⭐⭐☆☆ |

---

# Code

```cpp
#include <iostream>

int main() {
	std::cout << "Hello, World!\n";

	for (int i = 0; i < 5; ++i) {
		std::cout << i << '\n';
	}

	return 0;
}
```

```js
const square = (x) => x * x;

console.log(square(12));
```

```bash
git clone https://github.com/example/repo
cd repo
npm install
npm run dev
```

---

# Links

* [GitHub](https://github.com/)
* https://example.com

---

# Images

![Placeholder](Posts/images/picture_2026-05-09_14-14-27.jpg)

# MathJax

## Inline Math

Euler's identity:

$e^{i\pi}+1=0$

Pythagorean theorem:

$a^2+b^2=c^2$

---

## Fractions

$$
\frac{a+b}{c+d}
$$

---

## Summation

$$
\sum_{k=1}^{n}k=\frac{n(n+1)}{2}
$$

---

## Integral

$$
\int_{0}^{1}x^2,dx=\frac13
$$

---

## Derivative

$$
\frac{d}{dx}(x^3)=3x^2
$$

---

## Limit

$$
\lim_{x\to0}\frac{\sin x}{x}=1
$$

---

## Matrix

$$
A=
\begin{bmatrix}
1 & 2 & 3 \
4 & 5 & 6 \
7 & 8 & 9
\end{bmatrix}
$$

---

## Determinant

$$
\det(A)=
\begin{vmatrix}
a & b \
c & d
\end{vmatrix}
=ad-bc
$$

---

## Piecewise Function

$$
f(x)=
\begin{cases}
x^2, & x\ge0 \
-x, & x<1
\end{cases}
$$

---

## Greek Letters

$$
\alpha,;
\beta,;
\gamma,;
\delta,;
\epsilon,;
\theta,;
\lambda,;
\mu,;
\pi,;
\sigma,;
\phi,;
\omega
$$

---

## Vector

$$
\vec{v}=
\begin{bmatrix}
x\
y\
z
\end{bmatrix}
$$

---

## Maxwell's Equation

$$
\nabla\cdot\mathbf{E}=\frac{\rho}{\varepsilon_0}
$$

---

## Escaping (Doesn't work yet)

These should **not** become math: \$100\$