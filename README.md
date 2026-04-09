# 📊 Tomando Decisões de Negócios Baseadas em Dados

> Projeto desenvolvido durante o **Sprint 9** do bootcamp [TripleTen](https://tripleten.com/), com foco em análise de dados aplicada à tomada de decisões estratégicas de negócios.

---

## 📌 Sobre o Projeto

Este projeto tem como objetivo demonstrar como a análise de dados pode embasar decisões de negócios de forma mais eficiente e confiável. Utilizando técnicas estatísticas e de visualização de dados, o projeto explora hipóteses de negócio e avalia resultados por meio de testes A/B e métricas de desempenho.

---

## 🎯 Objetivos

- Priorizar hipóteses de negócio com base em frameworks de análise (ICE / RICE)
- Realizar e analisar testes A/B para validar decisões estratégicas
- Interpretar métricas de receita, conversão e comportamento de usuários
- Identificar anomalias e tomar decisões baseadas em evidências estatísticas

---

## 🗂️ Estrutura do Repositório

```
📁 Tomando-Decisoes-de-Negocios-Baseadas-em-Dados/
│
├── 📓 sprint 9 - tripleten.ipynb   # Notebook principal com toda a análise
└── 📄 README.md                    # Documentação do projeto
```

---

## 🔍 Etapas da Análise

### Parte 1 — Priorização de Hipóteses
- Aplicação dos frameworks **ICE** e **RICE** para ranquear hipóteses de crescimento
- Comparação entre os dois métodos e análise das diferenças de priorização

### Parte 2 — Análise do Teste A/B
- Visualização da **receita acumulada** por grupo (A e B)
- Análise do **tamanho médio dos pedidos** ao longo do tempo
- Cálculo da **diferença relativa** entre os grupos
- Análise da **taxa de conversão** acumulada
- Identificação e tratamento de **outliers** (pedidos e usuários anômalos)
- Testes de significância estatística:
  - Dados brutos
  - Dados filtrados (sem anomalias)
- Decisão final: continuar, encerrar ou ajustar o teste

---

## 🛠️ Tecnologias Utilizadas

| Ferramenta | Finalidade |
|---|---|
| Python 3 | Linguagem principal |
| Pandas | Manipulação e análise de dados |
| NumPy | Cálculos numéricos |
| Matplotlib | Visualização de dados |
| SciPy | Testes estatísticos |
| Jupyter Notebook | Ambiente de desenvolvimento |

---

## ▶️ Como Executar

1. Clone o repositório:
```bash
git clone https://github.com/caguiar0/Tomando-Decisoes-de-Negocios-Baseadas-em-Dados.git
```

2. Acesse a pasta do projeto:
```bash
cd Tomando-Decisoes-de-Negocios-Baseadas-em-Dados
```

3. Instale as dependências necessárias:
```bash
pip install pandas numpy matplotlib scipy jupyter
```

4. Inicie o Jupyter Notebook:
```bash
jupyter notebook
```

5. Abra o arquivo `sprint 9 - tripleten.ipynb` e execute as células.

---

## 📈 Principais Resultados

- A priorização via **RICE** se mostrou mais robusta ao considerar o alcance das hipóteses
- O **Grupo B** apresentou variações relevantes nas métricas de conversão e receita
- Após a filtragem de outliers, os resultados estatísticos indicaram diferenças **[significativas / não significativas]** entre os grupos
- A análise orientou a decisão de **[encerrar / continuar / ajustar]** o teste A/B

> ⚠️ *Preencha os campos acima com os resultados reais obtidos no seu notebook.*

---

## 👤 Autor

**caguiar0**  
Projeto desenvolvido como parte do currículo de Ciência de Dados da [TripleTen](https://tripleten.com/).

---

## 📄 Licença

Este projeto é de uso educacional e está disponível para fins de estudo e portfólio.
