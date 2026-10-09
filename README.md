# 🛒 Lista de Compras

Aplicativo mobile desenvolvido com **React Native, Expo e TypeScript**, com o objetivo de facilitar a organização das compras do dia a dia de forma simples e intuitiva.

## 📱 Funcionalidades

- 📝 Adicionar produtos à lista de compras.
- 🔢 Informar a quantidade de cada produto.
- 🗑️ Remover produtos da lista.
- ⚠️ Validar o nome do produto antes de adicioná-lo.
- 🔄 Definir quantidade padrão igual a 1 quando não informada.
- 📋 Exibir os produtos cadastrados.
- 🧺 Mostrar uma mensagem quando a lista estiver vazia.
- 🔢 Atualizar automaticamente a quantidade de itens na lista.

## 🛠️ Tecnologias utilizadas

- React Native
- Expo
- TypeScript
- JavaScript
- npm

## 📂 Estrutura do projeto

```text
lista-de-compras/
├── components/
│   ├── Cabecalho.tsx
│   ├── FormularioItem.tsx
│   ├── ItemCompra.tsx
│   └── ListaCompras.tsx
├── App.tsx
├── index.tsx
├── types.ts
├── app.json
├── babel.config.js
├── package.json
└── tsconfig.json
```

## ⚙️ Como executar o projeto

### 1. Pré-requisitos

- Node.js instalado.
- npm instalado.
- Expo Go no celular, caso queira testar o aplicativo em um dispositivo físico.

### 2. Clonar o repositório

```bash
git clone URL_DO_REPOSITORIO
```

### 3. Entrar na pasta do projeto

```bash
cd lista-de-compras
```

### 4. Instalar as dependências

```bash
npm install
```

### 5. Iniciar o aplicativo

```bash
npm start
```

Após iniciar, escaneie o QR Code com o Expo Go ou utilize as opções disponíveis no terminal para executar o projeto.

## 🧪 Testes realizados

- Adicionar um produto com nome e quantidade.
- Tentar adicionar um produto sem nome.
- Adicionar um produto sem informar a quantidade.
- Remover um produto da lista.
- Remover todos os produtos e verificar a mensagem de lista vazia.

Para verificar os tipos do TypeScript, execute:

```bash
npm run typecheck
```

## 🎯 Objetivo do projeto

Desenvolver um aplicativo funcional para praticar conceitos de desenvolvimento mobile, componentes reutilizáveis, gerenciamento de estado, propriedades (props), validação de formulários e tipagem com TypeScript.

## 👨‍💻 Autor

Desenvolvido como projeto de estudo de Desenvolvimento de Sistemas.
