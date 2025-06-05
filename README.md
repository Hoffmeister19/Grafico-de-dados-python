# 📊 Análise de Cancelamento de Clientes com Python

Este projeto visa analisar os dados de uma base de clientes para identificar os principais motivos de cancelamento e propor ações eficientes para reduzir a taxa de cancelamento. A análise é realizada utilizando a biblioteca `pandas` para manipulação e exploração dos dados.

---

## 🗂️ Estrutura do Projeto

`inicial.ipynb` – Notebook Jupyter com o ponto de partida do projeto, antes das otimizações e filtragens para a redução da taxa de cancelamento.
`cancelamentos_sample.csv` – Arquivo com a base de dados dos clientes (presume-se que seja um arquivo CSV, cujo nome exato não foi fornecido no snippet, mas é referenciado no código).

---

## 🔧 Tecnologias Utilizadas

* **Pandas** – Para leitura, manipulação e análise dos dados.
* **Jupyter Notebook** – Para o ambiente de desenvolvimento e execução da análise.

---

## 🚀 Como Executar

1.  **Certifique-se de ter o Python e o Jupyter Notebook instalados.**
2.  **Instale as dependências:**
    ```bash
    pip install pandas
    ```
3.  **Faça o download dos arquivos:**
    * `inicial.ipynb`
    * O arquivo CSV com os dados dos clientes. Certifique-se de que o arquivo CSV esteja no mesmo diretório dos notebooks ou que o caminho seja ajustado no código.
4.  **Inicie o Jupyter Notebook:**
    ```bash
    jupyter notebook
    ```
5.  **Abra o arquivo `inicial.ipynb`** e execute as células para reproduzir a análise.

---

## 📌 Funcionalidades

* **Identificação de fatores de cancelamento:** O notebook explora as colunas `duracao_contrato`, `ligacoes_callcenter` e `dias_atraso` para identificar padrões nos clientes que cancelaram.
* **Proposição de soluções:** Com base nos insights, são sugeridas ações para mitigar os cancelamentos, como:
    * Oferta de desconto em planos anuais e trimestrais para clientes de contrato mensal.
    * Criação de um processo para resolver problemas de clientes em no máximo 3 ligações para o call center.
    * Política para resolver atrasos de pagamento em até 10 dias.
* **Cálculo da taxa de cancelamento otimizada:** O código demonstra o impacto das ações propostas na redução da taxa de cancelamento ao filtrar os dados.

---

## 👨‍💻 Autor

Arthur Hoffmeister

Aspirante a engenheiro de cibersegurança e desenvolvedor em automações práticas com Python.

---

## 📍 Contato
📧 hoffmeisterarthur19@gmail.com
🔗 GitHub - @Hoffmeister19
🍳 Linkedin - https://www.linkedin.com/in/arthur-branco-2391452a7/

## ⭐ Se você achou útil, deixe uma estrela no repositório!
