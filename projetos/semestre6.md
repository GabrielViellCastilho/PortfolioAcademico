# ComissionAI

## Empresa Parceira

O projeto foi desenvolvido em parceria com a empresa Dom Rock, voltada para o segmento de vendas e concessionárias. A proposta foi baseada em um cenário real da empresa, com foco na automatização e governança do processo de apuração de comissões de vendas, hoje realizado de forma manual através de planilhas.

## Problema

A gestão de incentivos da Dom Rock depende de planilhas desarticuladas, o que gera uma série de impactos operacionais e financeiros. Entre eles estão inconsistências temporais, como vendas lançadas fora do período de vigência do contrato de um colaborador, gerando comissionamentos indevidos e passivos trabalhistas; falta de rastreabilidade, pela ausência de registros imutáveis que comprovem a origem exata da taxa aplicada em cada cálculo; e insegurança orçamentária, já que gestores comerciais propõem campanhas de comissionamento sem conseguir prever o impacto financeiro real frente ao histórico de vendas, o que resulta em estouros do teto orçamentário.

## Solução

A equipe está desenvolvendo o ComissionAI, uma plataforma que unifica a ingestão de dados de RH, Vendas e Comissões sob um motor de cálculo determinístico e imutável. O sistema conta com uma barreira de validação temporal de vínculos empregatícios, proteção contra duplicidade de lançamentos e geração de logs imutáveis (append-only) para auditoria de cada cálculo realizado.

Além disso, a plataforma conta com um agente de Inteligência Artificial responsável por interpretar propostas de comissionamento em linguagem natural, estruturando-as em parâmetros executáveis e permitindo simulações orçamentárias prévias (modo sandbox) antes da ativação de uma regra em produção, com explicabilidade (Explainable AI) sobre a lógica aplicada.

### Link do Repositório Git

https://github.com/Bug-Busters-F/ComissionAI

### Tecnologias Utilizadas

- **Java / Spring Boot:** desenvolvimento da API principal e das regras de negócio do motor de cálculo
- **Python / FastAPI:** desenvolvimento do serviço de IA responsável pela interpretação de regras e simulações
- **Vue.js:** desenvolvimento do front-end da aplicação
- **PostgreSQL:** armazenamento e gerenciamento dos dados
- **Docker:** conteinerização dos serviços da aplicação
- **Git e GitHub:** versionamento e colaboração em equipe, com uso de submodules para organizar front-end, back-end e serviço de IA

### Contribuições Pessoais

Atuei como desenvolvedor no projeto, trabalhando tanto no back-end (Java/Spring Boot) quanto no serviço de Inteligência Artificial (Python/FastAPI). No back-end, implementei a integração com o serviço de IA, incluindo a correção da conexão e timeout entre os serviços e testes de integração fim a fim, além de consultas para o agente envolvendo faixa de valor, bônus e campanhas com múltiplas regras, ajustando pontos como a vigência repassada ao serviço de IA.

No serviço de IA, participei do desenvolvimento do agente responsável por interpretar regras de comissionamento em linguagem natural, implementando o endpoint de interpretação, suporte a múltiplas regras com simulação em sandbox e o tratamento de schemas estritos para os provedores de IA utilizados. Também contribuí com a adição de logging estruturado e tratamento de erros inesperados.

### Hard Skills

- **Java (Spring Boot)** — Faço com ajuda
- **Python (FastAPI)** — Faço com autonomia
- **PostgreSQL** — Faço com autonomia
- **Docker** — Faço com autonomia
- **Git/GitHub** — Faço com autonomia

### Soft Skills

- **Comunicação:** alinhei com o time os contratos de integração entre o back-end e o serviço de IA, garantindo que ambos os serviços se comunicassem corretamente.

- **Adaptabilidade:** precisei transitar entre duas stacks diferentes no mesmo projeto (Java/Spring Boot e Python/FastAPI), adaptando-me rapidamente ao contexto de cada serviço.

<details>
<summary><strong>Demonstração da Evolução do Projeto</strong></summary>

### Sprint 1

<p align="center">

https://github.com/user-attachments/assets/3d2bf9c3-1b60-414b-8e01-1c0d258c6be4

</p>

### Sprint 2

<p align="center">

https://github.com/user-attachments/assets/f865b432-0b44-4ec9-8c4a-7a9cbc3a5887

</p>

### Sprint 3

Projeto em andamento — sprint ainda não concluída.

</details>
