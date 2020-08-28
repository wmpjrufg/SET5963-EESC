
<script src="https://polyfill.io/v3/polyfill.min.js?features=es6"></script> [comment]: <> (não apagar pois é a biblioteca de escrita matemática)
<script id="MathJax-script" async src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-mml-chtml.js"></script> [comment]: <> (não apagar pois é a biblioteca de escrita matemática)

### INTRODUÇÃO AO ESTUDO DAS CURVAS TENSÃO-DEFORMAÇÃO DO CONCRETO SIMPLES

<p>Para o estudo de qualquer sistema estrutural é de fundamental importância o conhecimento acerca das propriedades dos materiais que formam este sistema estrutural. Nas estruturas civis as propriedades mecânicas têm aspecto relevante para tomadas de decisão a nível de projeto. 
Sobre a ótica dos materiais estruturais conhecer propriedades como módulo de elasticidade, resistência de pico à tração, resistência de pico à compressão e tenacidade do concreto só é possível por meio da curva completa tensão-deformação do material [1].</p>

<p>Em situações de dimensionamento estrutural de obras correntes de engenharia é inviável a experimentação de todos os lotes do material estrutural empregado, logo é muito comum que projetistas recorram a curvas numéricas que simulem determinado comportamento experimental tensão-deformação. Tais curvas são descritas nas normas de projeto e no caso deste trabalho que se refere ao concreto armado, essas curvas podem ser encontradas em manuais de projeto como a norma brasileira NBR 6118 [2] e a norma europeia fib Model Code 2010 [3].</p>

<p>A seguir é apresentado o comportamento experimental em situação de compressão uniaxial e em seguida esse resultado será comparado à normativas de projeto como NBR 6118 [2] e Model Code 2010 [3].</p>

$$
\tilde x=\left\{ 
\begin{array}{ll}
 x_{\Bigl(\dfrac{n+1}{2}\Bigl)},  & \text{se $n$ for impar} \\
 \dfrac{ x_{\Bigl(\dfrac{n}{2}\Bigl)} + x_{\Bigl(\dfrac{n}{2}+1\Bigl)} }{2}, & \text{se $n$ for par}
\end{array}
\right
$$

$$
\begin{bmatrix}a & b \\c & d \end{bmatrix}\frac{-b\pm\sqrt{b^2-4ac}}{2a}\prod_a^b\bigvee_a^b\left(\begin{array}{c}a\\ b\end{array}\right)\begin{cases}a & x = 0\\b & x > 0\end{cases}
$$
