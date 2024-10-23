# IFST Image Frequency Spectrum Tool

#### Ferramenta de análise e manipulação de imagens no domínio da frequência

Essa ferramenta permite a manipulação de imagens de forma não convencional, através da manipulação no domínio da frequência, e permite a visualização em tempo real dos resultados.

##### Atalhos:

* `q` a janela é fechada e a execução encerra
* `r` descarta todas as modificações

##### Instalação:
Dependências: `Python 3.10`, `OpenCV`, `Numpy`.
A instalação pode ser feita usando o comando: 
```cmd 
pip install opencv-python numpy
```

##### Como utilizar:

Para utilizar, carregue sua imagem na pasta `images`.
Em seguida, altere esta linha no código: `image = cv2.imread('images/nome_da_imagem.jpg', 0)`
Execute todos os blocos do Jupyter Notebook. Uma nova janela será aberta.  
A janela permite a pintura dos pixels da imagem da esquerda, que atualiza em tempo real a imagem na direita, mostrando o resultado.

<p>
  <img style="background-color:#FFFFFF" src="https://github.com/DIEGOVZK/IFST-Image-Frequency-Spectrum-Tool/blob/main/Documentation/tool.png" width="100%">

</p>

##### Menu de ferramentas:

A janela de ferramentas permite selecionar o tipo de pincel, entre `caneta`, `cículo` e `anticírculo`.  

> ##### A caneta irá pintar o canvas com a `cor` e `tamanho` selecionados nas barras inferiores. 

> ##### O círculo irá criar um círculo de centro na posição incial do clique, e raio de arrasto antes de soltar o clique.

> ##### O anticírculo irá realizar a mesma operação do círculo; porém preencherá a area externa ao círculo.


<p>
  <img style="background-color:#FFFFFF" src="https://github.com/DIEGOVZK/IFST-Image-Frequency-Spectrum-Tool/blob/main/icons/design.png" width="25%">

</p>

<p float="left">
  <img style="background-color:#FFFFFF" src="https://github.com/DIEGOVZK/IFST-Image-Frequency-Spectrum-Tool/blob/main/Documentation/lines.png" width="32.8%">
  <img style="background-color:#FFFFFF" src="https://github.com/DIEGOVZK/IFST-Image-Frequency-Spectrum-Tool/blob/main/Documentation/circles.png" width="32.8%">
  <img style="background-color:#FFFFFF" src="https://github.com/DIEGOVZK/IFST-Image-Frequency-Spectrum-Tool/blob/main/Documentation/anticircle.png" width="32.8%">
</p>
