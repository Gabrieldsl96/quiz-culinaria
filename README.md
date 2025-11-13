# 🚀 Quiz de Culinária

Uma aplicação web moderna de quiz interativo construída com Next.js, React e TypeScript. Este projeto apresenta um quiz de culinária com sistema de perguntas e respostas, feedback visual e tela de resultados.

## ✨ Funcionalidades

- 📝 Sistema de perguntas e respostas interativo
- ✅ Feedback visual imediato (verde para acerto, vermelho para erro)
- 📊 Tela de resultados com resumo das respostas
- 🔄 Botão para reiniciar o quiz
- 📱 Design responsivo (mobile, tablet e desktop)
- ⚡ Performance otimizada com Next.js
- 🎨 Interface moderna com Tailwind CSS

## 🛠️ Tecnologias Utilizadas

- **Next.js 15.5.6** - Framework React com App Router
- **React 19.1.0** - Biblioteca JavaScript para interfaces
- **TypeScript** - Tipagem estática para JavaScript
- **Tailwind CSS 4** - Framework CSS utilitário
- **Geist Font** - Fonte otimizada do Vercel

## 📋 Pré-requisitos

Antes de começar, certifique-se de ter instalado:

- Node.js (versão 18 ou superior)
- npm, yarn, pnpm ou bun

## 🚀 Como Executar

1. Clone o repositório:
```bash
git clone <url-do-repositorio>
cd quiz
```

2. Instale as dependências:
```bash
npm install
# ou
yarn install
# ou
pnpm install
```

3. Execute o servidor de desenvolvimento:
```bash
npm run dev
# ou
yarn dev
# ou
pnpm dev
# ou
bun dev
```

4. Abra [http://localhost:3000](http://localhost:3000) no seu navegador.

## 📁 Estrutura do Projeto

```
quiz/
├── public/              # Arquivos estáticos
├── src/
│   ├── app/
│   │   ├── layout.tsx   # Layout principal
│   │   ├── page.tsx     # Página principal
│   │   └── globals.css  # Estilos globais
│   ├── components/
│   │   ├── QuestionItem.tsx # Componente de pergunta
│   │   └── Results.tsx      # Componente de resultados
│   ├── data/
│   │   └── questions.ts     # Lista de perguntas
│   └── types/
│       └── Questions.ts     # Tipos TypeScript
├── package.json
└── README.md
```

## 🎯 Scripts Disponíveis

- `npm run dev` - Inicia o servidor de desenvolvimento com Turbopack
- `npm run build` - Cria a build de produção com Turbopack
- `npm run start` - Inicia o servidor de produção
- `npm run lint` - Executa o linter ESLint

## 📝 Como Usar

1. O quiz exibe uma pergunta por vez com múltiplas opções
2. Clique em uma opção para selecionar sua resposta
3. Após 2 segundos, o sistema mostra feedback visual (verde para acerto, vermelho para erro)
4. A próxima pergunta é carregada automaticamente
5. Ao finalizar todas as perguntas, a tela de resultados é exibida
6. Clique em "Reiniciar Quiz" para começar novamente

## 🔧 Personalização

Para adicionar novas perguntas:

1. Edite o arquivo `src/data/questions.ts` e adicione um novo objeto:

```typescript
{
    question: 'Sua pergunta aqui?',
    options: [
        'Opção 1',
        'Opção 2',
        'Opção 3',
        'Opção 4'
    ],
    answer: 0  // Índice da resposta correta (0-3)
}
```

## 👨‍💻 Autor

Gabriel Lemos
