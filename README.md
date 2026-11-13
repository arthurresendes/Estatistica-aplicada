# Estatística Aplicada

Repositório dedicado ao estudo e à prática de estatística aplicada com Python, focado em análise de dados, manipulação de tabelas e uso de notebooks Jupyter. O projeto reúne materiais de introdução à linguagem Python, exercícios de estatística descritiva, aplicações com dados do ENEM e materiais complementares em HTML para visualização de conceitos.

## Visão geral

Este repositório tem como objetivo oferecer um material didático para quem deseja aprender estatística aplicada de forma prática. O conteúdo inclui:

- introdução ao Python;
- uso de bibliotecas como `pandas`, `numpy` e `math`;
- manipulação de DataFrames;
- medidas de tendência central e dispersão;
- frequências e distribuições;
- probabilidade e amostragem;
- análise de dados reais do ENEM;
- materiais visuais em HTML para reforço dos conceitos.

A organização do projeto facilita o aprendizado por etapas, começando pelos fundamentos e avançando para aplicações mais concretas.

---

## Objetivos do projeto

- aprender conceitos básicos de estatística;
- aplicar Python na análise de dados;
- explorar estruturas tabulares e dados reais;
- compreender média, mediana, moda e dispersão;
- estudar frequências, probabilidade e amostragem;
- desenvolver familiaridade com notebooks Jupyter;
- consolidar conhecimento por meio de exemplos práticos.

---

## Estrutura do repositório

```text
Estatistica-aplicada/
├── Enem/
│   ├── amostragem.ipynb
│   ├── enem_tratado.csv
│   ├── estrutura.ipynb
│   ├── frequencias.ipynb
│   ├── medidas_centrais.ipynb
│   ├── medidas_dispersao_posicao.ipynb
│   └── probabilidade.ipynb
├── Introdução/
│   ├── lambda.ipynb
│   ├── libs.ipynb
│   ├── primeirosPassos.ipynb
│   └── vetores.ipynb
├── blog/
│   ├── conceitos.html
│   ├── correlacaoRegressaoLinear.html
│   ├── descritiva.html
│   ├── dispersao.png
│   ├── distribuicaoNormal.html
│   ├── histograma.png
│   ├── index.html
│   ├── probabilidade.html
│   ├── style.css
│   └── varAleatorias.html
├── .gitattributes
├── .gitignore
├── Limpeza.txt
├── README.md
```

Descrição dos diretórios
1. Pasta Introdução/
Contém notebooks iniciais para quem está começando em Python e quer entender os fundamentos necessários para análise de dados e estatística.

Arquivos principais
primeirosPassos.ipynb
Primeiro contato com Python, operações básicas, variáveis e exemplos simples.

libs.ipynb
Introdução às bibliotecas numpy e math, além de exemplos com arrays e matrizes.

vetores.ipynb
Comparação entre listas Python e arrays NumPy, com operações matemáticas e cálculo de determinante.

lambda.ipynb
Exploração de funções lambda e conceitos básicos de programação funcional em Python.

Esses notebooks funcionam como base para quem está se familiarizando com o ambiente de análise de dados.

2. Pasta Enem/
Diretório com aplicações estatísticas em um conjunto de dados do ENEM, incluindo dados tabulados e notebooks de análise.

Arquivos principais
enem_tratado.csv
Base de dados tratada para uso em análise estatística.

estrutura.ipynb
Estudo da estrutura da base de dados, colunas e organização da tabela.

frequencias.ipynb
Exploração de frequências e distribuições dos dados.

medidas_centrais.ipynb
Cálculo e interpretação de média, mediana e moda.

medidas_dispersao_posicao.ipynb
Análise de dispersão, quartis e medidas de posicionamento.

probabilidade.ipynb
Aplicação de conceitos de probabilidade sobre os dados.

amostragem.ipynb
Discussão sobre amostragem, representatividade e inferência.

Esse conjunto de materiais mostra como a estatística pode ser aplicada em um cenário real e com dados estruturados.

3. Pasta blog/
Área com material complementar em HTML para visualizar conceitos estatísticos de forma mais didática.

Conteúdo
páginas sobre:
estatística descritiva;
distribuição normal;
probabilidade;
correlação e regressão linear;
variáveis aleatórias;
histogramas e dispersão.
Além disso, há imagens e estilos para melhorar a apresentação visual dos conteúdos.

Bibliotecas e tecnologias utilizadas
As principais tecnologias e bibliotecas observadas no projeto são:

Python
Jupyter Notebook
pandas
numpy
math
análise exploratória de dados
Arquivo Limpeza.txt
Há também um arquivo chamado Limpeza.txt, que parece funcionar como uma espécie de guia de referência rápida para manipulação de dados com pandas.

Esse arquivo inclui exemplos para:

leitura de dados;
exportação de dados;
visualização de colunas;
contagem de valores;
remoção e renomeação de colunas;
troca de valores;
consultas condicionais;
verificação de nulos;
concatenação de dados.
Esse material é especialmente útil para quem está aprendendo a manipular DataFrames em Python.

Como executar o projeto
1. Clonar o repositório
bash
git clone https://github.com/arthurresendes/Estatistica-aplicada.git
cd Estatistica-aplicada
2. Criar um ambiente virtual (opcional, mas recomendado)
bash
python -m venv venv
Linux/macOS:

bash
source venv/bin/activate
Windows:

bash
venv\Scripts\activate
3. Instalar dependências
bash
pip install pandas numpy matplotlib seaborn jupyter
4. Abrir os notebooks
bash
jupyter notebook
ou

bash
jupyter lab
Depois, basta acessar as pastas Introdução e Enem para executar os notebooks.

Conceitos abordados
O material presente no repositório cobre vários tópicos, como:

leitura e limpeza de dados;
organização de tabelas;
uso de DataFrames;
estatística descritiva;
média, mediana e moda;
dispersão e variabilidade;
frequência absoluta e relativa;
quartis;
probabilidade;
amostragem;
análise de dados em contexto real.
Observações
O projeto é majoritariamente composto por notebooks Jupyter;
o foco é didático e prático;
os exemplos são úteis para estudos pessoais e revisão de conceitos;
a pasta blog funciona como material complementar visual.
Conclusão
Este repositório funciona como uma base de estudos em estatística aplicada com Python. Ele combina fundamentos de programação, análise de dados e aplicações reais, tornando o processo de aprendizagem mais acessível e prático.

Uma sequência sugerida para estudo é:

Introdução/primeirosPassos.ipynb
Introdução/libs.ipynb
Introdução/vetores.ipynb
Enem/estrutura.ipynb
Enem/medidas_centrais.ipynb
Enem/medidas_dispersao_posicao.ipynb
Enem/probabilidade.ipynb
Enem/amostragem.ipynb
