# 🚀 Express TypeScript Boilerplate 2024

[![Build Express Application](https://github.com/edwinhern/express-typescript-2024/actions/workflows/build.yml/badge.svg?branch=master)](https://github.com/edwinhern/express-typescript-2024/actions/workflows/build.yml)
[![CodeQL](https://github.com/edwinhern/express-typescript-2024/actions/workflows/codeql.yml/badge.svg?branch=master)](https://github.com/edwinhern/express-typescript-2024/actions/workflows/codeql.yml)
[![Docker Image CI](https://github.com/edwinhern/express-typescript-2024/actions/workflows/docker-image.yml/badge.svg?branch=master)](https://github.com/edwinhern/express-typescript-2024/actions/workflows/docker-image.yml)
[![Release](https://github.com/edwinhern/express-typescript-2024/actions/workflows/release.yml/badge.svg?branch=master)](https://github.com/edwinhern/express-typescript-2024/actions/workflows/release.yml)

## 🌟 Introdução

Bem-vindo ao Express TypeScript Boilerplate 2024 – uma base simplificada, eficiente e escalável para construir serviços backend poderosos. Este boilerplate combina ferramentas e práticas modernas em Express.js e TypeScript, aumentando a produtividade, a qualidade do código e o desempenho.

## 💡 Motivação e Intenções

Desenvolvido para simplificar o desenvolvimento de backend, este boilerplate é a sua solução para:

- ✨ Reduzir o tempo de configuração para novos projetos.
- 📊 Garantir consistência e qualidade do código.
- ⚡ Facilitar o desenvolvimento rápido com ferramentas de ponta.
- 🛡️ Incentivar as melhores práticas em segurança, testes e desempenho.

## 🚀 Funcionalidades

- 📁 Estrutura Modular: Organizada por funcionalidades para fácil navegação e escalabilidade.
- 💨 Execução mais Rápida com tsx: Execução rápida do TypeScript com esbuild, complementada pelo tsc para verificação de tipos.
- 🌐 Ambiente Node Estável: Última versão LTS do Node em .nvmrc.
- 🔧 Variáveis de Ambiente Simplificadas com Envalid: Configuração centralizada e fácil de gerenciar.
- 🔗 Alias de Caminho: Código mais limpo com importações simplificadas.
- 🔄 Integração com Dependabot: Atualizações automáticas para dependências seguras e atualizadas.
- 🔒 Segurança: Helmet para segurança de cabeçalhos HTTP e configuração de CORS.
- 📊 Logging: Registro eficiente com pino-http.
- 🧪 Testes Abrangentes: Configuração robusta com Vitest e Supertest.
- 🔑 Garantia de Qualidade do Código: Husky e lint-staged para qualidade consistente.
- ✅ Estilo de Código Unificado: ESLint e Prettier para um padrão de codificação consistente.
- 📃 Padronização de Respostas da API: Classe ServiceResponse para respostas de API consistentes.
- 🐳 Suporte ao Docker: Pronto para conteinerização e implantação.
- 📝 Validação de Entrada com Zod: Validação fortemente tipada de solicitações usando Zod.
- 🧩 Geração de Especificações de API: Geração automática de especificações OpenAPI a partir de esquemas Zod para garantir documentação de API atualizada e precisa.

## 🛠️ Começando

### Passo 1: 🚀 Configuração Inicial

- Clone o repositório: `git clone https://github.com/edwinhern/express-typescript-2024.git`
- Navegue: `cd express-typescript-2024`
- Instale as dependências: `npm ci`

### Passo 2: ⚙️ Configuração do Ambiente

- Crie `.env`: Copie `.env.template` para `.env`
- Atualize `.env`: Preencha as variáveis de ambiente necessárias

### Passo 3: 🏃‍♂️ Executando o Projeto

- Modo de Desenvolvimento: `npm run dev`
- Construindo: `npm run build`
- Modo de Produção: Configure `.env` para `NODE_ENV="production"` e então `npm run build && npm run start`

## 📁 Estrutura do Projeto


```
.
├── api
│   ├── healthCheck
│   │   ├── __tests__
│   │   │   └── healthCheckRouter.test.ts
│   │   └── healthCheckRouter.ts
│   └── user
│       ├── __tests__
│       │   ├── userRouter.test.ts
│       │   └── userService.test.ts
│       ├── userModel.ts
│       ├── userRepository.ts
│       ├── userRouter.ts
│       └── userService.ts
├── api-docs
│   ├── __tests__
│   │   └── openAPIRouter.test.ts
│   ├── openAPIDocumentGenerator.ts
│   ├── openAPIResponseBuilders.ts
│   └── openAPIRouter.ts
├── common
│   ├── __tests__
│   │   ├── errorHandler.test.ts
│   │   └── requestLogger.test.ts
│   ├── middleware
│   │   ├── errorHandler.ts
│   │   ├── rateLimiter.ts
│   │   └── requestLogger.ts
│   ├── models
│   │   └── serviceResponse.ts
│   └── utils
│       ├── commonValidation.ts
│       ├── envConfig.ts
│       └── httpHandlers.ts
├── index.ts
└── server.ts

```

## 🤝 Feedback e Contribuições

Adoraria ouvir seu feedback e sugestões para melhorias futuras. Sinta-se à vontade para contribuir e se juntar a nós para tornar o desenvolvimento backend mais limpo e rápido!

🎉 Feliz codificação!
