# Hub de Leitura — Aplicação de Apoio para QA

Aplicação educacional de gestão de biblioteca usada como ambiente de prática para atividades de Quality Assurance. O sistema oferece funcionalidades de aplicação e API que podem servir de alvo para diferentes tipos de teste.

## Objetivos
- Disponibilizar um sistema de exemplo para praticar testes de software.
- Exercitar cenários funcionais e de integração.
- Usar a aplicação como alvo para projetos de automação relacionados.

## Tecnologias
Conforme indicado pela configuração e documentação do repositório: Node.js, Express, SQLite, JWT, Bootstrap e JavaScript. Confira os arquivos de dependências para as versões efetivamente instaladas.

## Pré-requisitos
- Node.js 18 ou versão compatível com as dependências.
- npm.
- Banco de dados e variáveis de ambiente configurados conforme a documentação e arquivos do projeto.

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
4. Inicialize o banco de dados e execute a aplicação:
```bash
npm run db
npm run setup
npm start
```
O script `db` inicializa o banco; `setup` prepara os dados/configurações iniciais conforme a implementação do projeto. Se necessário, confira os arquivos em `scripts/` e `setup.js` antes de executar. Não execute testes contra ambientes que você não controla ou não tem autorização para usar.

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
Entender a arquitetura da aplicação, configurar o banco e a autenticação e preparar dados e cenários adequados para validar os fluxos disponíveis.

## Boas práticas adotadas
- Separação de código, dados, scripts e configuração.
- Organização do projeto em diretórios por responsabilidade.
- Uso do sistema como ambiente de prática para testes reproduzíveis.

## 📚 Aprendizados
O projeto oferece uma base para compreender como uma aplicação web, uma API, autenticação e persistência de dados se relacionam. Também permite praticar a preparação de ambiente e a identificação de cenários relevantes para automação de qualidade.

## Considerações finais
Este repositório é a aplicação de apoio, não necessariamente a suíte de testes em si. Consulte a documentação e os scripts para confirmar como iniciar o sistema e quais funcionalidades estão disponíveis.

---

## 🎓 Formação
Projeto desenvolvido no contexto da formação profissionalizante em **Quality Assurance (QA) pela EBAC — Escola Britânica de Artes Criativas e Tecnologia**.