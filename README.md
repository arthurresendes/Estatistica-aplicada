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

## Descrição dos diretórios

### Pasta `Introdução/`

Contém notebooks iniciais para quem está começando em Python e quer entender os fundamentos necessários para análise de dados e estatística.

#### Arquivos principais

- **`primeirosPassos.ipynb`** — primeiro contato com Python, operações básicas, variáveis e exemplos simples.
- **`libs.ipynb`** — introdução às bibliotecas `numpy` e `math`, além de exemplos com arrays e matrizes.
- **`vetores.ipynb`** — comparação entre listas Python e arrays NumPy, com operações matemáticas e cálculo de determinante.
- **`lambda.ipynb`** — exploração de funções lambda e conceitos básicos de programação funcional em Python.

Esses notebooks funcionam como base para quem está se familiarizando com o ambiente de análise de dados.

### Pasta `Enem/`

Diretório com aplicações estatísticas em um conjunto de dados do ENEM, incluindo dados tabulados e notebooks de análise.

#### Arquivos principais

- **`enem_tratado.csv`** — base de dados tratada para uso em análise estatística.
- **`estrutura.ipynb`** — estudo da estrutura da base de dados, colunas e organização da tabela.
- **`frequencias.ipynb`** — exploração de frequências e distribuições dos dados.
- **`medidas_centrais.ipynb`** — cálculo e interpretação de média, mediana e moda.
- **`medidas_dispersao_posicao.ipynb`** — análise de dispersão, quartis e medidas de posicionamento.
- **`probabilidade.ipynb`** — aplicação de conceitos de probabilidade sobre os dados.
- **`amostragem.ipynb`** — discussão sobre amostragem, representatividade e inferência.

Esse conjunto de materiais mostra como a estatística pode ser aplicada em um cenário real e com dados estruturados.

### Pasta `blog/`

Área com material complementar em HTML para visualizar conceitos estatísticos de forma mais didática.

O conteúdo inclui páginas sobre:

- estatística descritiva;
- distribuição normal;
- probabilidade;
- correlação e regressão linear;
- variáveis aleatórias;
- histogramas e dispersão.

Além disso, há imagens e arquivos de estilo para melhorar a apresentação visual dos conteúdos.

## Bibliotecas e tecnologias utilizadas

As principais tecnologias e bibliotecas utilizadas ou abordadas no projeto são:

- Python;
- Jupyter Notebook;
- pandas;
- numpy;
- math;
- análise exploratória de dados.

## Arquivo `Limpeza.txt`

O arquivo `Limpeza.txt` funciona como um guia de referência rápida para manipulação de dados com pandas.

Ele inclui exemplos de:

- leitura e exportação de dados;
- visualização de colunas;
- contagem de valores;
- remoção e renomeação de colunas;
- substituição de valores;
- consultas condicionais;
- verificação de valores nulos;
- concatenação de dados.

Esse material é especialmente útil para quem está aprendendo a manipular DataFrames em Python.

## Como executar o projeto

### 1. Clonar o repositório

```bash
git clone https://github.com/arthurresendes/Estatistica-aplicada.git
cd Estatistica-aplicada
```

### 2. Criar um ambiente virtual

A criação de um ambiente virtual é opcional, mas recomendada.

```bash
python -m venv venv
```

No Linux ou macOS:

```bash
source venv/bin/activate
```

No Windows:

```bash
venv\Scripts\activate
```

### 3. Instalar as dependências

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

### 4. Abrir os notebooks

Inicie o Jupyter Notebook:

```bash
jupyter notebook
```

Ou inicie o JupyterLab:

```bash
jupyter lab
```

Depois, acesse as pastas `Introdução/` e `Enem/` para abrir e executar os notebooks.

## Conceitos abordados

O material presente no repositório cobre tópicos como:

- leitura e limpeza de dados;
- organização de tabelas;
- uso de DataFrames;
- estatística descritiva;
- média, mediana e moda;
- dispersão e variabilidade;
- frequência absoluta e relativa;
- quartis;
- probabilidade;
- amostragem;
- análise de dados em contexto real.

## Observações

- O projeto é majoritariamente composto por notebooks Jupyter.
- O foco é didático e prático.
- Os exemplos podem ser usados para estudos pessoais e revisão de conceitos.
- A pasta `blog/` funciona como material complementar visual.

## Conclusão

Este repositório funciona como uma base de estudos em estatística aplicada com Python. Ele combina fundamentos de programação, análise de dados e aplicações reais, tornando o processo de aprendizagem mais acessível e prático.

### Sequência sugerida para estudo

1. `Introdução/primeirosPassos.ipynb`
2. `Introdução/libs.ipynb`
3. `Introdução/vetores.ipynb`
4. `Enem/estrutura.ipynb`
5. `Enem/medidas_centrais.ipynb`
6. `Enem/medidas_dispersao_posicao.ipynb`
7. `Enem/probabilidade.ipynb`
8. `Enem/amostragem.ipynb`
