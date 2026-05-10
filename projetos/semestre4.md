# ClassiPy

## Empresa Parceira

O projeto foi desenvolvido em parceria com a empresa TecSys, voltada para soluções na área de importação e processos aduaneiros. A proposta foi baseada em um cenário real do setor, com foco na automatização do processo de classificação de produtos para registros de importação, reduzindo erros operacionais e aumentando a eficiência no preenchimento de informações fiscais.

## Problema

O processo de elaboração de registros de importação é complexo e altamente suscetível a erros, pois exige o preenchimento manual de diversas informações como Part Number, NCM, fabricante, descrição técnica e origem do produto. Essas informações precisam ser consistentes e detalhadas, já que qualquer inconsistência pode gerar dúvidas durante a fiscalização e causar problemas junto à Receita Federal.

Além disso, a análise manual de documentos, como pedidos de compra em PDF, torna o processo lento e repetitivo, aumentando o risco de falhas humanas, retrabalho e atrasos nas operações de importação. A ausência de automação também dificulta a padronização das informações utilizadas durante o processo aduaneiro.

## Solução

A equipe desenvolveu uma aplicação web chamada ClassiPy, utilizando Inteligência Artificial para automatizar o processo de classificação de produtos para importação. O sistema permite o upload de documentos em PDF, realiza a extração automática de Part Numbers e utiliza IA para sugerir informações como NCM, descrição do produto, fabricante e origem.

A plataforma também oferece visualização organizada dos resultados, possibilidade de edição manual das informações classificadas, histórico de consultas e exportação dos dados processados. Além disso, foram implementadas soluções utilizando banco vetorial para melhorar a busca e a precisão das respostas geradas pela IA, tornando o processo mais rápido, confiável e eficiente.

### Link do Repositório Git

https://github.com/Bug-Busters-F/ClassiPy

### Tecnologias Utilizadas

- **React / TypeScript:** desenvolvimento do front-end da aplicação
- **Tailwind CSS:** estilização da interface
- **Python / FastAPI:** desenvolvimento da API
- **PostgreSQL:** armazenamento e gerenciamento dos dados
- **Docker:** conteinerização da aplicação
- **Ollama:** integração com modelos de Inteligência Artificial locais
- **ChromaDB:** banco vetorial utilizado para busca semântica
- **Git e GitHub:** versionamento e colaboração em equipe
- **Jira:** organização das tarefas e gerenciamento do projeto

### Contribuições Pessoais

Atuei como desenvolvedor no projeto, trabalhando principalmente no back-end e na integração com Inteligência Artificial utilizando FastAPI, PostgreSQL, Ollama e ChromaDB. Implementei a conexão entre o banco de dados e os modelos de IA locais, permitindo que as informações processadas fossem utilizadas no fluxo de classificação dos produtos importados.

Também participei da implementação do banco vetorial com ChromaDB, contribuindo para melhorar a precisão das buscas e respostas retornadas pelo sistema. Desenvolvi funcionalidades relacionadas ao histórico de consultas, persistência de dados e paginação, melhorando a navegação e organização das informações processadas pela aplicação.

Além disso, implementei rotas específicas na API, como recuperação de Part Numbers recentes, realizei correções relacionadas à leitura completa de arquivos PDF e tratei inconsistências no processamento de dados JSON retornados pela IA.

### Hard Skills

- **Python (FastAPI)** — Faço com autonomia
- **React / TypeScript** — Faço com autonomia
- **PostgreSQL** — Faço com autonomia
- **Docker** — Faço com autonomia
- **Integração com IA (Ollama)** — Faço com ajuda
- **Banco Vetorial (ChromaDB)** — Faço com ajuda
- **Git/GitHub** — Faço com autonomia

### Soft Skills

- **Comunicação:** durante a integração com a IA, alinhei com o time como os dados deveriam ser enviados para melhorar a qualidade das respostas retornadas pelo modelo e facilitar o processamento das informações classificadas.

- **Adaptabilidade:** precisei aprender rapidamente conceitos relacionados a IA local, embeddings e banco vetorial para conseguir aplicar essas tecnologias no fluxo da aplicação.

<details>
<summary><strong>Demonstração da Evolução do Projeto</strong></summary>

### Sprint 1

<p align="center">
  <img src="../img/proj4/GifSprint1.gif" width="500"/>
</p>

### Sprint 2

<p align="center">
  <img src="../img/proj4/GifSprint2.gif" width="500"/>
</p>

### Sprint 3

<p align="center">
  <img src="../img/proj4/GifSprint3.gif" width="500"/>
</p>

</details>
