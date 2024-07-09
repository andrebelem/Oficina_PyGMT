  
# Oficina de PyGMT [![DOI](https://zenodo.org/badge/821008814.svg)](https://zenodo.org/doi/10.5281/zenodo.12701582)

<p align="center">
  <img src="Datasets/3D_sample.png" alt="Descrição da Imagem" width="400">
</p>


Este é o material da Oficina INTERNA: Uma introdução à exploração de dados geoespaciais com PyGMT, ministrado pelo oceanógrafo [André Belém](https://github.com/andrebelem) para o Seminário Interdisciplinar de Sustentabilidade [SIS2024](https://www.even3.com.br/sis-2024/), mas disponibilizado aqui de forma pública para outros interessados em aprender um pouco mais sobre o PyGMT além de outras técnicas de análise de dados geoespaciais. O curso foi baseado exclusivamente no [Google COLAB](https://colab.google/) e em notebooks de Python. Esse repositório está **em construção constante** ! Então, se quiser seguir o que acontece aqui, basta clicar sobre o botão "watch".

Esse material foi adaptado (e traduzido) do curso ["Criando mapas bonitos com o PyGMT"](https://www.generic-mapping-tools.org/egu22pygmt/intro.html) ministrado durante o encontro da [European Geophysical Union General Assembly 2022](https://www.egu22.eu/). Se você gostou e quiser se tornar um *PyGMTniano*, e começar a usar o `PyGMT`no seu trabalho, pedimos gentilmente que você cite o uso do PyGMT usando o seguinte [DOI](https://doi.org/10.5281/zenodo.11062720). Você pode obter mais detalhes sobre isso na [página principal do PyGMT](https://www.pygmt.org/dev/index.html). Também recomendo a leitura do excepcional trabalho de Paul Wessel ([In Memoriam](https://www.soest.hawaii.edu/soestwp/announce/news/in-memoriam-pal-wessel/)) [The Origins of the Generic Mapping Tools: From Table Tennis to Geoscience](https://agupubs.onlinelibrary.wiley.com/doi/10.1029/2023CN000231). 

## Gravação
(em breve)

## Como usar todo esse material

Como conversamos no curso, aprender python+PyGMT demanda dedicação e tempo, mas sem pressão (!). Explore os recursos, estude os códigos e pergunte ! Cada tutorial é renderizado neste repositório do github para fácil visualização 👀, mas todos são Jupyter notebooks criados no COLAB e projetados para serem executados interativamente. Basta seguir as instruções em cada notebook para começar a executar os tutoriais rapidamente! 🚀 É possível que em algum momento a estrutura do Google Colab mude (com novas atualizações), bem como o `PyGMT` que está sempre em constante atualização. Se algum dos exemplos parar de funcionar, basta me [mandar uma msg](mailto:andrebelem@id.uff.br) que eu vou tentar corrigir.

Basicamente no colab, usamos duas células de código, uma para instalar o `conda colab` e outra para instalar o `pygmt`. Você pode criar essas células em qualquer colab e a partir dai começar a programar em `pygmt`.

```
!pip install -q condacolab
import condacolab
condacolab.install()
```
Espere o sistema reiniciar e depois:
```
%%capture
!mamba install pygmt #<- note que aqui usamos o mamba, mas isso pode ser feito com o conda
# esta célula não irá produzir outputs na sua tela.
```
Não esqueça de dar `import pygmt` na primeira célula depois de instalar tudo.

## Ideias e links

Veja o documento [aqui]([Datasets/](https://github.com/andrebelem/Oficina_PyGMT/blob/main/Links%20Ideias%20Dados%20e%20outros%20materiais.md)) para mais algumas ideias interessantes.<br>
Se você tiver alguma dúvida ou quiser fazer algum comentário aqui, use o `pull request` ou mande um email para [andrebelem@id.uff.br](mailto:andrebelem@id.uff.br). Você pode ainda acessar o [Fórum do PyGMT](https://forum.generic-mapping-tools.org/) que é o principal hub para troca de informações e ajuda com os scripts.

Espero que você tenha uma excelente experiência com o Python e com o PyGMT ! ❤️

