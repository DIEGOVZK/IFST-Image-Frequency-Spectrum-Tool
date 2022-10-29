# IFST Image Frequency Spectrum Tool

#### Ferramenta de análise e manipulação de imagens no domínio da frquência.

Essa ferramenta permite a manipualção de imagens de forma não convercional, através da manipulação no domínio da frequência, e permite a visualização em tempo real dos resultados.

##### Atalhos:

* `q` a janela é fechada e a execução para
* `r` resseta todas as modificações

##### Como utilizar:

Para utilizar, carregue sua imagem no mesmo diretório do arquivo `frequency_canvas.ipynb`, com o nome image.jpg  
Execute todos os blocos do python notebook, uma nova janela é aberta.  
A janela permite a pintura dos pixels da imagem da esquerda, que atualiza em tempo real a imagem na direita, mostrando o resultado.  

<p>
  <img style="background-color:#FFFFFF" src="https://github.com/DIEGOVZK/IFST-Image-Frequency-Spectrum-Tool/blob/main/Documentation/tool.png" width="100%">

</p>

##### Menu de ferramentas:

A janela de ferramentas permite selecionar o tipo de pincel, entre `caneta`, `cículo` e `anti-círculo`.  

> ##### A caneta irá pintar o canvas com a `cor` e `tamanho` selecionados nas barras inferiores. 

> ##### O círculo irá criar um circulo de centro na posição incial do click, e raio de arrasto antes de soltar o click.

> ##### O anti-círculo irá realizar a mesma operação do circulo, porém preencherá a area externa ao circulo.


<p>
  <img style="background-color:#FFFFFF" src="https://github.com/DIEGOVZK/IFST-Image-Frequency-Spectrum-Tool/blob/main/icons/design.png" width="100%">

</p>

<p float="left">
  <img style="background-color:#FFFFFF" src="https://github.com/DIEGOVZK/IFST-Image-Frequency-Spectrum-Tool/blob/main/Documentation/lines.png" width="32.8%">
  <img style="background-color:#FFFFFF" src="https://github.com/DIEGOVZK/IFST-Image-Frequency-Spectrum-Tool/blob/main/Documentation/circles.png" width="32.8%">
  <img style="background-color:#FFFFFF" src="https://github.com/DIEGOVZK/IFST-Image-Frequency-Spectrum-Tool/blob/main/Documentation/anticircles.png" width="32.8%">
</p>