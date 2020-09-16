<script src="https://polyfill.io/v3/polyfill.min.js?features=es6"></script> 
<script id="MathJax-script" async src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-mml-chtml.js"></script>

## Determinação do diagrama Momento Curvatura

<p style="text-align: justify;">O diagrama momento-curvatura reflete as leis tensão-deformação não lineares do aço e do concreto. Para cálculo do diagrama momento-curvatura admite-se a hipótese de Bernoulli. Com isto a curvatura é igual ao gradiente de deformações na seção transversal, e também igual a variação da rotação por unidade de comprimento da barra [1].</p> 

Para o cálculo desse diagrama deverá ser admitido o seguintes hipóteses [1]:
1. Seções planas antes e após das deformações;
2. Na compressão e na tração antes da fissuraão há aderência rígida (sem deslizamento) entre armadura e o concreto circundante;
3. Consideração de carregamento monotônicos quase-estáticos, sem qualquer alterância ou repetição ($$\dfrac{d(\epsilon)}{dt} \approx 10_{-5} /s$$
4. Efeito de fluência é desconsiderado
5. Após a fissuração despreza-se, na seção transversal fissurada, a resistência à tração do concreto.

### Viga 2$$\phi$$12.5 mm

<p style="text-align: justify;"> Para obtenção do diagrama de momento curvatura de uma viga é necessário primeiramente definir os pontos notáveis de mudança de estádio da peça. Para isso iremos estabelecer o ponto de início do processo de fissuração na viga de concreto que corresponde ao fim do Estádio I e início do Estádio II. Portanto efetuaremos o cálculo do momento resistente e em sequência a curvatira correspondente. </p> 

O momento resistente $$Mr$$ e a curvatura da peça são dadas por:

$$M_{1} = M_{r} = \frac{\alpha.f_{ctm}.I_{I}}{y_{t}}$$    
$$\epsilon_{c} = \frac{f_{ctm}}{E_{ci}}$$  
$$\phi_{1} = \frac{\epsilon_{c}}{x_{I}}$$  

<p style="text-align: justify;"> Portanto com a determinação dos valores de momento resistente e curvatura no ponto de início de fissuração marca-se o fim do Estádio I. Nessa região os pontos notáveis da curva são: </p> 

-Momento resistente: $$M_{r} = 10284,13 kN.cm$$  
-Curvatura: $$\phi = 3,42 cm^{-1}$$  

-Deformação no concreto: $$\epsilon_{c} = 0,010 %$$  
-Área da seção: $$A_{c} = 2487,92 cm^{2}$$  
-Linha Neutra: $$x_{I} = 30,92 cm$$  
-Inércio Estádio I: $$I_{I} = 777333,60 cm^{4}$$  

### Viga 5$$\phi$$32.00 mm

<p style="text-align: justify;"> teste </p> 

### Referências

1. BUCHAIM, R. A influência da não-linearidade física do concreto armado na rigidez à flexão e na capacidade de rotação plástica. Tese de Doutorado em Engenharia de Estruturas. Universidade de São Paulo (USP), 2001.
