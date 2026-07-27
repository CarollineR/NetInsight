# 📡 NetInsight

Projeto de análise de dados de rede desenvolvido em Python.

O NetInsight tem como objetivo transformar dados de tráfego de rede em informações visuais e indicadores que auxiliem na compreensão do comportamento de uma infraestrutura de comunicação.

O projeto une conceitos de **Redes de Computadores**, **Análise de Dados** e **Desenvolvimento Backend**, utilizando uma base pública de dados de tráfego de rede.

---

## 🌐 Contexto do Projeto

Redes de computadores geram grandes volumes de dados a cada comunicação realizada entre dispositivos.

Esses registros podem revelar informações importantes sobre o funcionamento de uma infraestrutura, permitindo analisar padrões de utilização, características do tráfego e possíveis alterações fora do comportamento esperado.

O NetInsight nasce a partir da seguinte pergunta:

> **É possível identificar padrões de comportamento de rede que indiquem tráfego normal ou uma possível ameaça?**

Essa pergunta é relevante porque a análise de comportamento é uma das formas utilizadas para compreender ambientes de rede. Mudanças inesperadas podem indicar problemas de desempenho, falhas de configuração ou atividades suspeitas que precisam ser investigadas.

O objetivo do projeto não é criar uma ferramenta completa de segurança, mas desenvolver uma análise exploratória de dados de rede, aplicando conceitos de engenharia de dados, redes de computadores e desenvolvimento de software.

---

## 🎯 Objetivo

Desenvolver uma plataforma de análise de dados capaz de transformar registros de tráfego de rede em informações visuais e indicadores, permitindo explorar padrões de comunicação e compreender diferenças entre comportamentos normais e anômalos.

Durante o desenvolvimento serão explorados conceitos como:

- protocolos de rede;
- comunicação TCP/IP;
- análise de tráfego;
- estatística aplicada;
- visualização de dados;
- desenvolvimento backend.

---

## 🗂️ Base de Dados

O projeto utilizará inicialmente a base pública **UNSW-NB15**, criada para pesquisas acadêmicas relacionadas à análise de tráfego de rede e detecção de intrusões.

O dataset contém registros de comunicação de rede coletados em ambiente controlado, incluindo tráfego considerado normal e diferentes categorias de ataques.

A base possui informações como:

- protocolo utilizado;
- serviço acessado;
- duração da conexão;
- quantidade de pacotes;
- volume de dados transferidos;
- características da comunicação;
- classificação do tráfego.

Esses dados permitirão explorar padrões de comportamento e analisar quais características podem estar relacionadas a diferentes tipos de tráfego.

---

## 🛠️ Tecnologias

### Linguagem

- Python

### Análise de Dados

- Pandas
- NumPy

### Visualização

- Matplotlib
- Seaborn

### Ambiente e Versionamento

- Jupyter Notebook
- Git
- GitHub

### Backend (futuro)

- Flask

---

## 🗂️ Estrutura do Projeto

```text
NetInsight/
│
├── data/
│   └── Dados brutos e dados tratados
│
├── notebooks/
│   └── Exploração e análises dos dados
│
├── reports/
│   └── Gráficos, resultados e relatórios
│
├── src/
│   └── Código Python reutilizável
│
├── README.md
└── requirements.txt
```

---

## 🧠 Conceitos estudados

### Redes de Computadores

- Modelo TCP/IP
- Protocolos de comunicação
- Endereçamento IP
- Portas e serviços
- Características do tráfego de rede

### Análise de Dados

- Exploração de dados
- Limpeza e tratamento
- Estatística aplicada
- Visualização de informações
- Identificação de padrões

### Desenvolvimento

- Organização de projetos Python
- Estruturação de aplicações
- Criação de APIs

---

## 🚧 Roadmap

### Fase 1 — Exploração dos dados

- [x] Configuração do ambiente Python
- [x] Estrutura inicial do projeto
- [ ] Importação e análise da base UNSW-NB15

### Fase 2 — Análise de tráfego

- [ ] Tratamento dos dados
- [ ] Criação de métricas e visualizações
- [ ] Identificação de padrões

### Fase 3 — Aplicação

- [ ] Desenvolvimento da API
- [ ] Construção do dashboard

---

## 📚 Objetivo de aprendizado

O NetInsight tem como objetivo desenvolver conhecimento prático na integração entre:

- Redes de Computadores;
- Análise de Dados;
- Desenvolvimento Backend.

Mais do que construir uma aplicação, o projeto representa uma jornada de aprendizado aplicando conceitos técnicos em um cenário próximo dos desafios encontrados na área de tecnologia.