# 📊 Introdução à Estatística Descritiva com Python

Este repositório contém um estudo prático e detalhado sobre os fundamentos da **estatística descritiva**. O objetivo principal é demonstrar como resumir, analisar e visualizar dados utilizando Python, aplicando os conceitos em uma base de dados estudantil.

## 🎯 Tópicos Abordados

O notebook (`Estatística_Descritiva.ipynb`) explora os seguintes conceitos fundamentais:

* **Conceitos Iniciais:** A diferença entre estatística descritiva e inferencial.
* **Terminologia:** Definição de dados, população, amostra e tipos de variáveis (qualitativas nominais/ordinais e quantitativas discretas/contínuas).
* **Medidas de Tendência Central:** Como calcular e interpretar Média, Mediana e Moda.
* **Medidas de Dispersão:** Amplitude, Variância e Desvio Padrão.
* **Forma da Distribuição:** Análise de assimetria (skewness) e visualização com Histogramas.
* **Medidas de Posição:** Divisão dos dados através de Quartis, Percentis e o Intervalo Interquartil (IQR).
* **Valores Atípicos (Outliers):** Identificação utilizando a regra de Tukey e visualização através de Box plots.

## 🛠️ Tecnologias e Bibliotecas Utilizadas

O estudo foi desenvolvido para ser executado no **Google Colab** e utiliza as seguintes ferramentas:

* **Python 3**
* **Pandas**: Manipulação e análise de tabelas de dados (DataFrames).
* **NumPy**: Cálculos matemáticos e numéricos avançados.
* **Seaborn**: Criação de gráficos estatísticos atraentes e informativos.
* **Matplotlib**: Ajustes complementares de visualização (títulos, legendas, eixos).

## 📂 Sobre a Base de Dados

* O estudo utiliza um arquivo CSV (`alunos.csv`) composto por **50 linhas (alunos)** e **13 colunas (variáveis)**.
* **Aviso de Privacidade:** Todos os dados analisados são **100% fictícios**.
* Entre as variáveis exploradas estão: `nota_final`, `horas_estudo_semana`, `numero_de_faltas`, `turno`, `tempo_de_deslocamento_min`, entre outras.

## 🚀 Como Executar o Projeto

1. Faça o clone deste repositório ou o download do arquivo `Estatística_Descritiva.ipynb`.
2. Importe o notebook para o seu **Google Colab**.
3. Execute a célula de preparação (importação de bibliotecas e conexão com o Google Drive) de cima para baixo pressionando `Shift + Enter`.
4. O script tentará buscar o arquivo `alunos.csv` no diretório `/content/drive/MyDrive/Colab Notebooks/estatistica/dados`, este arquivo também está localizado neste repositório.
5. Caso o arquivo não seja encontrado nesse caminho, o próprio código abrirá um botão de upload para que você envie o CSV, movendo-o automaticamente para a pasta correta no seu Drive.

## 📝 Conclusão do Estudo

Ao final da análise, concluímos que a turma analisada possui um desempenho mediano (nota em torno de 6.09), com uma distribuição simétrica, dispersão moderada e sem outliers. O uso conjunto das medidas de tendência central e dispersão, aliado a gráficos como histogramas e box plots, provou-se eficaz para traçar o perfil completo do conjunto de dados.
