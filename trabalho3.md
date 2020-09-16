<script src="https://polyfill.io/v3/polyfill.min.js?features=es6"></script> 
<script id="MathJax-script" async src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-mml-chtml.js"></script>

## Determinação do diagrama Momento Curvatura

<p style="text-align: justify;">O diagrama momento-curvatura reflete as leis tensão-deformação não lineares do aço e do concreto. Para cálculo do diagrama momento-curvatura admite-se a hipótese de Bernoulli. Com isto a curvatura é igual ao gradiente de deformações na seção transversal, e também igual a variação da rotação por unidade de comprimento da barra [1].</p> 

Para o cálculo desse diagrama deverá ser admitido o seguintes hipóteses [1]:  
1. Seções planas antes e após das deformações;  
2. Na compressão e na tração antes da fissuraão há aderência rígida (sem deslizamento) entre armadura e o concreto circundante;  
3. Consideração de carregamento monotônicos quase-estáticos, sem qualquer alterância ou repetição ($$\dfrac{d(\epsilon)}{dt} \approx 10{-5} /s)$$;  
4. Efeito de fluência é desconsiderado;  
5. Após a fissuração despreza-se, na seção transversal fissurada, a resistência à tração do concreto.  

<p style="text-align: justify;">Para obtenção do diagrama de momento curvatura de uma viga é necessário primeiramente definir os pontos notáveis de mudança de estádio da peça. Aseguir os passos são descritos de forma estabelecer o diagrama momento curvatura.</p>

### Passo 1: Determinação do limite entre o Estádio I e Estádio II

Deve-se estabelecer o ponto de início do processo de fissuração na viga de concreto, que corresponde ao fim do Estádio I e início do Estádio II. Esse ponto de interesse é definido pelo cálculo do Momento Resistente $$M_{r}$$. Considerando seções planas e as relações lineares entre deformação no concreto ($$\epsilon_{c}$$) e a curvatura $$\phi_{1}$$, têm-se o seguinte equacionamento.

$$M_{1} = M_{r} = \frac{\alpha.f_{ctm}.I_{I}}{y_{t}}$$
$$\epsilon_{c} = \frac{f_{ctm}}{E_{ci}}$$  
$$\phi_{1} = \frac{\epsilon_{c}}{x_{I}}$$

Onde:
- $$f_{ctm}$$: Resistência à tração média do concreto;
- $$\alpha$$: Fator majorador da resistência à tração para seção retangular;
- $$E_{ci}$$: Módulo de elasticidade tangente;
- $$I_{I}$$ e $${y_{t}$$: Inércia da peça no Estádio I e distância da linha neutra ao bordo mais tracionado.

<p style="text-align: justify;">As equações de determinação de inércia e linha neutra no Estádio I com e sem consideração da armadura podem ser encontradas em Carvalho e Figueiredo Filho [2] cap. 4.</p>

### Passo 2: Determinação da nova linha neutra para seção fissurada

Após o aumento da curvatura a peça de concreto começará a fissurar, portanto após deverá ser calculada uma nova posição da linha neutra conforme proposto em Carvalho e Figueiredo Filho [2] cap. 4.</p>.

<p style="text-align: justify;">Determinada a linha neutra para a condição a nova condição (estado de fissuração) acontece uma singularidade instantânea no diagrama momento-curvatura. O diagrama de forças resistentes passa a ser composto pelo concreto comprimido e o aço tracionado, lembrando que a seção inferior de concreto passa a ser desprezada a partir desse ponto. As equações que marcam esse trecho são: </p>

$$M_{fis} = \frac{1}{2}.\sigma_{C}.b_{w}.x_{II}.z_{II}$$

Onde $$z_{II}$$ indica o braço de alavanca das forças atuantes no concreto até o contoíde que representa as armaduras. $$z_{II}$$ é dado por:

$$z_{II} = d-\frac{x_{II}}{3}$$

O equilíbrio deforças normais é dado por:

$$A_{s}.f_{y} = \frac{1}{2}.\sigma_{c}.b_{w}.x_{II}$$   

Determina-se então a tensão no concreto comprimido $$\sigma_{C}$$:

$$\sigma_{c} = \epsilon_{c}.E_{cs}



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

1. <p style="text-align: justify;">BUCHAIM, R. A influência da não-linearidade física do concreto armado na rigidez à flexão e na capacidade de rotação plástica. Tese de Doutorado em Engenharia de Estruturas. Universidade de São Paulo (USP), 2001.</p>

2. <p style="text-align: justify;">CARVALHO, R. C. FIGUEIREDO FILHO, J R. Cálculo e Detalhamento de Estruturas Usuais de Concreto Armado: Segundo a NBR 6118:2014. Editora EduFSCar, 4º edição, São Carlos, 2014.</p>
