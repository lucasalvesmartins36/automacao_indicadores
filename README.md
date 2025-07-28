#  Automação de Indicadores de Lojas de Varejo

Este projeto simula um cenário real de trabalho em uma rede varejista, onde o objetivo é automatizar o processo de geração e envio de indicadores diários (OnePages) para as lojas, utilizando Python.

---

## Objetivo

Automatizar a criação de relatórios com indicadores de desempenho (OnePages) para cada loja da rede e enviá-los por e-mail de forma personalizada, junto com os dados individuais de cada loja, além de consolidar relatórios e rankings para a diretoria.

---

## 🛠️ Exemplo de email 

![alt text](image.png)

---

## 🛠️ Tecnologias Utilizadas

- Python 3.12.4
- pandas
- pathlib
- email (biblioteca para envio de e-mails)

---

## 🗂️ Estrutura do Projeto


📁 Projeto_Indicadores/
├── dados/
│ ├── Emails.xlsx # Lista de e-mails dos gerentes e diretoria
│ ├── Vendas.xlsx # Planilha com as vendas de todas as lojas
│ ├── Lojas.csv # Lista com os nomes das lojas
├── automacao_indicadores.ipynb # Script principal de automação
├── requirements.txt # Dependências do projeto
└── README.md # Descrição do projeto (este arquivo)


## Funcionalidades

- Geração automática do OnePage para cada loja
- Envio por e-mail dos relatórios:
  - Gerente recebe OnePage no corpo do e-mail e planilha da loja em anexo
  - Diretoria recebe rankings do dia e do ano
- Separação de dados por loja
- Geração de rankings com base no faturamento das lojas
