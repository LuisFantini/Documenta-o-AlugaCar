📘 Documentação do Sistema AlugaCar

Este repositório contém toda a documentação oficial do Sistema AlugaCar, incluindo diagramas UML, modelo de dados, artefatos do projeto e demais elementos exigidos para o trabalho acadêmico.
Aqui você encontrará arquivos PlantUML, imagens e descrições formais da arquitetura, do domínio e dos processos internos do sistema.

📌 Sobre o Sistema

O AlugaCar é um sistema voltado para administração de aluguel de veículos, permitindo que clientes realizem pedidos de locação e agentes façam análise financeira para aprovação.

O sistema permite:

Cadastro e autenticação de usuários

Solicitação de pedidos de aluguel

Consulta, modificação e cancelamento de pedidos

Avaliação e aprovação de pedidos por agentes

Geração automática de contratos

Associação de contrato de crédito bancário (quando necessário)

Registro completo de clientes, agentes, automóveis e contratos

O objetivo geral é fornecer uma solução digital que gerencie todo o fluxo de aluguel, desde a solicitação inicial até a formalização contratual.

📁 Estrutura da Documentação

Este repositório inclui os seguintes artefatos:

🔹 Diagramas UML

Diagrama de Casos de Uso

Diagrama de Classes

Diagrama de Sequência

Diagrama de Comunicação

Diagrama de Estados

Diagrama de Componentes

Diagrama de Implantação (Deployment)

Arquitetura em C4 Model (Nível 2)

🔹 Modelagem de Dados

Modelo Relacional (Tabelas, PK e FK)

Descrição textual completa do modelo de dados

🔹 Arquivos-Fonte dos Diagramas

Arquivos .puml para todos os diagramas

Imagens exportadas em PNG/SVG

Artefatos utilizados no relatório final

🛠️ Tecnologias e Arquitetura

O sistema segue uma arquitetura baseada no padrão MVC, distribuída da seguinte forma:

Frontend

HTML, CSS e JavaScript

Comunicação via Fetch API com JSON

Interface responsiva hospedada na Vercel

Backend

Java + Spring Boot

Controllers REST

Services com regras de negócio

Repositórios usando Spring Data JPA / Hibernate

Banco de Dados

MySQL

Modelo relacional baseado nas entidades do domínio

Persistência via JPA/Hibernate

🔗 Repositório do Código-Fonte

O código completo do sistema (frontend + backend + banco) pode ser encontrado no repositório:

👉https://github.com/RafaelLopes1810/sistema-aluguel-de-carros
