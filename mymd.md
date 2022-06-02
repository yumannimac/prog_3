
### コメント
次の内容はコメントとして処理されるのでPDFには何も表示されません．
<!-- これはコメントです -->

### pandoc-crossref を用いた相互参照
[@fig:model]のように指定することで，図表を参照することができます．

### 必要に応じて使うもの
$$
  \frac{\pi}{2} =
  \left( \int_{0}^{\infty} \frac{\sin x}{\sqrt{x}} dx \right)^2 =
  \sum_{k=0}^{\infty} \frac{(2k)!}{2^{2k}(k!)^2} \frac{1}{2k+1} =
  \prod_{k=1}^{\infty} \frac{4k^2}{4k^2 - 1}
$$

$$
\frac{\pi }{2}=\left(\int_{0}^{\infty} \frac{\sin x}{\sqrt{x}}dx\right) ^2=\sum_{k=0}^{\infty} \frac{\left(2k\right) !}{2^{2k}\left(k!\right) ^2}\frac{1}{2k+1}=\prod_{k=1}^{\infty} \frac{4k^2}{4k^2-1}
$$

$$
\lim_{n \to \infty }\sin \left(nx\right) \text{は存在しない} 
$$

### 引用
> これは引用です．  
> これも引用です．
パイプテーブル  
  
| TH 左寄せ | TH 中央寄せ | TH 右寄せ |
| :--- | :---: | ---: |
| TD | TD | TD |
| TD | TD | TD |



生命科学課題
こんにちは

$$
\sin 
x + \cos 
\int_{0}^{\infty} \frac{1}{2}dx \frac{1}{2}+ \varphi 
s
\sin \int_{0}^{1} \cos \left(x+\frac{\sin x}{\cos x}\right) 
\sin x+\sin x \frac{3w}{2}
$$

生命科学

$$
\sin x=0 \leftrightarrow x=n\pi 
$$

$
  \sin x 
$ 

$
\sin x
$

$$
\sin s+\cos t=\frac{1}{2}\cdot  \sqrt{2}
$$

となるようなものを求める。

$$
\lim_{n \to \infty}\sum_{k=1}^{n} \frac{1}{k^2}=\frac{\pi^2}{6} 
$$

みたいなことまで書ける。

$$
\sin x=0 \Leftrightarrow x=n\pi 
$$

$$
\begin{matrix}
  a&b\\ 
  c&d
\end{matrix}
$$

ここで$x=1\frac{1}{2}$のときを考えてみよう。

$$
\begin{align*}
a\\ 
b
\end{align*}
$$

# レポート
　今回の課題では
 
$$
\lim_{n \to \infty }\sum_{k=1}^{n} \frac{1}{k^2}=\frac{\pi ^2}{6} 
$$

の証明をする必要があった。それをする。

## 補題
$\mathbb{R}^2$において$C^2$級の関数を考える。これはフーリエ級数展開できる。
$C^2$級の関数の例を考える。

$$
f \left(x\right) =x^2
$$

は$C^2$級である。なぜなら

$$
f'\left(x\right) =2x
$$

$$
f''\left(x\right) =2
$$

となり確かに存在するからである。
ところで

$$
f \left(x\right) =x^2=\sum_{n=0}^{\infty } a_n \cos nx
$$

と表すことができると仮定しよう。

$$
\int_{-\pi }^{\pi } x^2 \cos nx dx= \left[ \frac{1}{n}x^2 \sin nx+\frac{1}{n^2}\cdot 2x \cos nx +\frac{1}{n^3}2 \sin nx \right]_{-\pi }^{\pi }=\left(-1\right) ^n\frac{4 \pi }{n^2}
$$

であるから

$$
f \left(x\right) = x^2=\frac{\pi ^2}{3}+4\sum_{n=1}^{\infty} \frac{\left(-1\right) ^n}{n^2}\cos nx
$$

と考えられる。
したがって

$$
f \left(0\right) =0=\frac{\pi ^2}{3}+4\sum_{n=1}^{\infty} \frac{\left(-1\right) ^n}{n^2}
$$

より

$$
\sum_{n=1}^{\infty } \frac{\left(-1\right) ^n}{n^2}
=-\frac{\pi ^2}{12}
$$
