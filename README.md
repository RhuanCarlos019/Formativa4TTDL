# Projeto: Desenvolvimento de Aplicação To-Do List

## Visão Geral do Projeto

### Objetivo
Desenvolver uma aplicação web de To-Do List utilizando tecnologias modernas e práticas de mercado, garantindo segurança, escalabilidade e uma experiência de usuário fluida.

## Escopo do Projeto

### Escopo Funcional
- **Cadastro de Usuários:** Implementar funcionalidades para registro, login e logout utilizando autenticação JWT.
- **Gestão de Tarefas:** Permitir que os usuários criem, editem, visualizem, marquem como concluídas e excluam tarefas.
- **Organização de Tarefas:** Possibilitar a categorização e priorização das tarefas, permitindo também a busca e filtragem.
- **Integração com Banco de Dados:** Persistir dados de usuários e tarefas utilizando MongoDB.

### Escopo Não Funcional
- **Segurança:** Implementar autenticação e autorização via JWT, garantindo que apenas usuários autenticados possam acessar suas tarefas.
- **Escalabilidade:** Estruturar a aplicação para suportar o aumento de usuários e tarefas sem comprometer a performance.
- **Usabilidade:** Garantir uma interface intuitiva e responsiva para uma experiência de usuário fluida.
- **Manutenibilidade:** Adotar boas práticas de desenvolvimento, como componentização no React e modularização do código no Node.js, facilitando futuras manutenções e expansões.

## Objetivos SMART

- **Específico:** Desenvolver uma aplicação de To-Do List que permita aos usuários gerenciar suas tarefas de forma eficiente e segura, utilizando tecnologias como React, Node.js, MongoDB e JWT.
- **Mensurável:** A aplicação deve ser capaz de suportar 100 usuários ativos simultâneos e armazenar até 10.000 tarefas sem degradação de performance.
- **Alcançável:** Utilizando a equipe e recursos disponíveis, o projeto será dividido em fases, com a meta de lançar uma versão beta em 3 meses e uma versão final em 4 meses.
- **Relevante:** A aplicação atenderá à necessidade da Escola SENAI, fornecendo uma ferramenta útil para a organização de tarefas pelos colaboradores.
- **Temporal:** A versão final da aplicação será lançada em 4 meses, com marcos de desenvolvimento definidos para cada mês.

## Cronograma

| Mês        | Atividade                                                                                  |
|------------|---------------------------------------------------------------------------------------------|
| **1º Mês** | Planejamento do projeto, levantamento de requisitos, definição da arquitetura e prototipagem de baixa fidelidade. |
| **2º Mês** | Desenvolvimento da estrutura básica da aplicação, incluindo cadastro de usuários e autenticação JWT. |
| **3º Mês** | Implementação da gestão de tarefas, incluindo criação, edição, exclusão, categorização e priorização. |
| **4º Mês** | Testes, otimização de performance, implementação de segurança e lançamento da versão final. |

## Recursos

- **Equipe de Desenvolvimento:**
  - Desenvolvedor Front-End: 1
  - Desenvolvedor Back-End: 1
  - Designer de UI/UX: 1
  - Gerente de Projetos: 1

- **Ferramentas:**
  - **Next.js:** Para desenvolvimento front-end.
  - **Node.js:** Para desenvolvimento back-end.
  - **MongoDB:** Banco de dados NoSQL.
  - **JWT:** Para autenticação.
  - **Figma/Adobe XD:** Para prototipagem e design.
  - **GitHub:** Para versionamento e colaboração de código.

## Análise de Risco

- **Risco:** Atraso na entrega devido a complexidades técnicas inesperadas.
  - **Mitigação:** Revisões semanais de progresso e ajustes de cronograma conforme necessário.
- **Risco:** Falhas de segurança que podem comprometer os dados dos usuários.
  - **Mitigação:** Implementação de boas práticas de segurança desde o início e realização de testes de penetração.
- **Risco:** Escalabilidade insuficiente para suportar o crescimento do número de usuários.
  - **Mitigação:** Planejamento de arquitetura escalável e testes de carga antes do lançamento.
- **Risco:** Falta de adesão dos usuários à nova ferramenta.
  - **Mitigação:** Envolvimento dos usuários finais durante o processo de desenvolvimento para garantir que suas necessidades sejam atendidas.
 

## Diagrama: 
<img width="397" alt="image" src="https://github.com/user-attachments/assets/e181d5c0-7d3a-4a2d-ac0e-e63d3eb11c35">


## Resultado Esperado

Uma aplicação de To-Do List funcional, segura e escalável que atenda às necessidades da Escola SENAI, com uma interface intuitiva e responsiva, pronta para ser utilizada pelos colaboradores. O projeto será documentado no GitHub, com o escopo em Markdown, e os diagramas criados para representar a arquitetura e o fluxo do sistema.
