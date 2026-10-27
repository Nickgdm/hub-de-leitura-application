<pre>
╔═════════════════════════════════════════════════════════════════════════════════════════════════════════╗
║                                     HUB DE LEITURA — APLICAÇÃO DE APOIO                                 ║
╚═════════════════════════════════════════════════════════════════════════════════════════════════════════╝
</pre>
Aplicação educacional de gestão de biblioteca utilizada como ambiente de prática para atividades de Quality Assurance. O sistema oferece funcionalidades de aplicação e API que podem servir de alvo para diferentes tipos de teste.

## Sobre o projeto

Este repositório contém a aplicação utilizada como ambiente de apoio para exercícios de qualidade de software. Ele é distinto das suítes de teste que podem interagir com o sistema.

## Objetivos

- Disponibilizar um sistema de exemplo para praticar testes de software.
- Exercitar cenários funcionais e de integração.
- Utilizar a aplicação como alvo para projetos de automação relacionados.

## Tecnologias

Conforme indicado pela configuração e pela documentação do repositório:

- Node.js
- Express
- SQLite
- JWT
- Bootstrap
- JavaScript

Consulte os arquivos de dependências para verificar as versões efetivamente utilizadas.

## Pré-requisitos

- Node.js 18 ou versão compatível com as dependências.
- npm.
- Banco de dados e variáveis de ambiente configurados conforme a documentação e os arquivos do projeto.

## Instalação e execução

1. Clone o repositório e entre na pasta.
2. Instale as dependências:

```bash
npm install
```

3. Confira os scripts disponíveis:

```bash
npm run
```

4. Inicialize o banco de dados e execute a aplicação, conforme os scripts documentados:

```bash
npm run db
npm run setup
npm start
```

O script `db` inicializa o banco; `setup` prepara dados ou configurações iniciais conforme a implementação do projeto. Se necessário, confira os arquivos em `scripts/` e `setup.js` antes de executar.

Não execute testes contra ambientes que você não controla ou não tem autorização para utilizar.

## Estrutura do projeto

```text
teste-cy-base/
├── .github/
├── config/
├── data/
├── database/
├── public/
├── scripts/
├── src/
├── package.json
└── README.md
```

## Desafios práticos

- Compreender a arquitetura da aplicação.
- Configurar banco de dados e autenticação.
- Preparar dados e cenários adequados para validar os fluxos disponíveis.

## Boas práticas

- Separar código, dados, scripts e configuração.
- Organizar os arquivos em diretórios por responsabilidade.
- Utilizar a aplicação como ambiente de prática para testes reproduzíveis.
- Consultar a documentação e os scripts antes de executar comandos de inicialização.

## Aprendizados

O projeto oferece uma base para compreender como uma aplicação web, uma API, a autenticação e a persistência de dados se relacionam. Também permite praticar a preparação do ambiente e a identificação de cenários relevantes para automação de qualidade.


## Considerações finais

Este repositório contém a aplicação de apoio, não necessariamente a suíte de testes em si. Consulte a documentação e os scripts para confirmar como iniciar o sistema e quais funcionalidades estão disponíveis.
<pre>
╔═════════════════════════════════════════════════════════════════════════════════════════════════════════╗
║       Atividade desenvolvida durante a formação profissionalizante em Quality Assurance (QA) pela       ║
║                     EBAC — Escola Britânica de Artes Criativas e Tecnologia                             ║
╚═════════════════════════════════════════════════════════════════════════════════════════════════════════╝
</pre>
