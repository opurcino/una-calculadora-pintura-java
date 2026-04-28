# Calculadora de Pintura

## 📝 Descrição
[cite_start]Este é um programa simples construído em Java que tem como objetivo calcular a quantidade de tinta necessária para pintar as paredes de um quarto de formato quadrado. A ferramenta faz o levantamento de áreas brutas e líquidas com base nas medidas fornecidas pelo usuário e em métricas pré-estabelecidas.

## ⚙️ Regras de Negócio e Variáveis Fixas
[cite_start]O programa solicita ao usuário o comprimento de apenas um dos lados do quarto em metros [cite: 4, 5] e, a partir dessa informação, realiza os cálculos considerando as seguintes constantes:
* [cite_start]**Altura da Parede:** Pé-direito fixado em 2,7 metros[cite: 2].
* [cite_start]**Rendimento da Tinta:** Considera-se que 1 litro de tinta cobre exatamente 10,0 m²[cite: 2].
* [cite_start]**Desconto de Aberturas:** Aplica-se uma dedução de 10% sobre a área total das paredes para compensar o espaço não pintado correspondente a portas e janelas[cite: 3, 4, 6].

## 💻 Saída / Resumo do Orçamento
Após o processamento dos dados, o console exibirá um resumo detalhado contendo:
1. [cite_start]**Área bruta das paredes:** O total da metragem das 4 paredes em m²[cite: 7].
2. [cite_start]**Área a ser pintada:** A área líquida final (em m²) após aplicar o desconto das aberturas[cite: 7].
3. [cite_start]**Total de tinta necessária:** A quantidade exata em litros de tinta exigida para o serviço[cite: 8].

## 🚀 Como Executar o Projeto

### Pré-requisitos
* Ter o **Java Development Kit (JDK)** instalado em sua máquina.

### Passo a passo
1. Faça o download ou copie o código para um arquivo chamado `CalculadoraPintura42522583.java`.
2. Abra o terminal ou prompt de comando e navegue até o diretório onde o arquivo foi salvo.
3. Compile o código executando o comando:
   ```bash
   javac CalculadoraPintura42522583.java
