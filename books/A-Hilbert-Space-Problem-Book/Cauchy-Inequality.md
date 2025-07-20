# Cauchy-Schwartz 不等式

---

> Cauchy-Schwartz 不等式 (内积形式)

$$
| \lang x,y \rang | \le \| x \| \cdot \| y \|.
$$

书上提到了一个短小精悍的证明：
$$
\begin{align}
	\| x \|^2 \cdot \| y \|^2 - | \lang x,y \rang |^2 = \frac{1}{\| y \|^2} \cdot \| \| y \|^2 x - \lang x,y \rang y \|^2 \ \ (\| y \| \neq 0).
\end{align}
$$
无论 $\| y \|$ 是否为 $0$，根据内积的性质都有 $\| x \|^2 \cdot \| y \|^2 - | \lang x,y \rang |^2 \ge 0$. 并且从上式可以得到 Cauchy-Schwartz 不等式取等号的充要条件为 $x,y$ 线性相关. 紧接着作者考虑了半内积的情形，此时 Cauchy-Schwartz 不等式是否仍成立 (即 Problem 2) ？由于 $(1)$ 式的成立不依赖内积是 'Strictly Positive'，因此同样适用于半内积的情形. 当 $\| y \| > 0$ 时 Cauchy-Schwartz 不等式显然成立. 当 $\| y \| = 0$ 时，如果能证明 $\lang x,y \rang = 0 , \forall \ x$ 则大功告成. 于是 Problem 2 转化为
$$
设 \ \lang , \rang \ 是半内积,当 \ \| y \| = 0 \ 时 \lang x,y \rang = 0 \ 是否总成立?
$$
这里可以利用 $\lang x+ty , x+ty \rang \ge 0 , t \in \mathbb{R}$ 的展开式得到 $\mathrm{Re}\lang x,y \rang = 0$. 同样的，当 $t$ 取值为纯虚数时可以得到  $\mathrm{Im}\lang x,y \rang = 0$.
