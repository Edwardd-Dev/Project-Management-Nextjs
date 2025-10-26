<div align="center">

# 🚀 Project Management Application

### Sistema completo de gerenciamento de projetos e tarefas

[![Next.js](https://img.shields.io/badge/Next.js-14.2.5-black?style=for-the-badge&logo=next.js)](https://nextjs.org/)
[![React](https://img.shields.io/badge/React-18.3.1-61DAFB?style=for-the-badge&logo=react)](https://reactjs.org/)
[![TypeScript](https://img.shields.io/badge/TypeScript-5.5.4-3178C6?style=for-the-badge&logo=typescript)](https://www.typescriptlang.org/)
[![Material-UI](https://img.shields.io/badge/Material--UI-5.16.7-007FFF?style=for-the-badge&logo=mui)](https://mui.com/)
[![Node.js](https://img.shields.io/badge/Node.js-20.19.5-339933?style=for-the-badge&logo=node.js)](https://nodejs.org/)

[Demonstração](#) • [Documentação](#) • [Reportar Bug](#) • [Solicitar Feature](#)

</div>

---

## 📋 Sobre o Projeto

Sistema moderno e intuitivo de gerenciamento de projetos desenvolvido com as tecnologias mais recentes do ecossistema React. Permite organizar tarefas, acompanhar progresso, gerenciar equipes e visualizar dados através de dashboards interativos.

### ✨ Principais Funcionalidades

- 📊 **Dashboard Interativo** - Visualização completa de métricas e KPIs
- 📅 **Gestão de Tarefas** - Crie, edite e organize tarefas com facilidade
- 👥 **Gerenciamento de Equipes** - Atribua responsáveis e acompanhe colaboradores
- 📈 **Gráficos e Relatórios** - Análise visual de dados com Recharts
- 🎯 **Gantt Chart** - Timeline visual do projeto
- 🔍 **Filtros Avançados** - Busca e filtragem inteligente de dados
- 🎨 **Interface Moderna** - Design responsivo com Material-UI e Tailwind CSS
- 🌙 **Tema Customizável** - Suporte para modo claro/escuro

---

## 🛠️ Tecnologias Utilizadas

### Frontend

| Tecnologia | Versão | Descrição |
|-----------|--------|-----------|
| **Next.js** | 14.2.5 | Framework React com SSR e SSG |
| **React** | 18.3.1 | Biblioteca para interfaces de usuário |
| **TypeScript** | 5.5.4 | Superset JavaScript com tipagem estática |
| **Material-UI** | 5.16.7 | Biblioteca de componentes React |
| **Tailwind CSS** | 3.4.9 | Framework CSS utility-first |
| **Recharts** | 2.12.7 | Biblioteca para gráficos |
| **Axios** | 1.7.3 | Cliente HTTP para requisições |
| **date-fns** | 3.6.0 | Manipulação de datas |
| **Lucide React** | 0.427.0 | Ícones modernos |

### Ferramentas de Desenvolvimento

- **ESLint** - Linter para código JavaScript/TypeScript
- **PostCSS** - Processador de CSS
- **Autoprefixer** - Adiciona prefixos CSS automaticamente

---

## 🚀 Como Começar

### Pré-requisitos

Certifique-se de ter instalado:

- **Node.js** `20.19.5` ou superior
- **npm** `10.8.2` ou superior
- **Git**

### Instalação

1. **Clone o repositório**

```bash
git clone https://github.com/Edwardd-Dev/Project-Management-NextJS.git
cd Project-Management-NextJS
```

2. **Navegue até a pasta do cliente**

```bash
cd client
```

3. **Instale as dependências**

```bash
npm install
```

4. **Configure as variáveis de ambiente**

```bash
cp .env.example .env.local
```

Edite o arquivo `.env.local` com suas configurações:

```env
NEXT_PUBLIC_API_URL=http://localhost:3001
NEXT_PUBLIC_APP_NAME=Project Management
```

5. **Inicie o servidor de desenvolvimento**

```bash
npm run dev
```

6. **Abra no navegador**

Acesse [http://localhost:3000](http://localhost:3000)

---

## 📦 Scripts Disponíveis

```bash
npm run dev      # Inicia servidor de desenvolvimento
npm run build    # Cria build de produção
npm run start    # Inicia servidor de produção
npm run lint     # Executa linter
```

---

## 📁 Estrutura do Projeto

```
Project-Management/
├── client/                      # Aplicação Frontend
│   ├── src/
│   │   ├── app/                # App Router (Next.js 14)
│   │   │   ├── layout.tsx      # Layout principal
│   │   │   ├── page.tsx        # Página inicial
│   │   │   └── globals.css     # Estilos globais
│   │   ├── components/         # Componentes reutilizáveis
│   │   ├── lib/                # Utilitários e helpers
│   │   ├── types/              # Definições TypeScript
│   │   └── hooks/              # Custom React Hooks
│   ├── public/                 # Arquivos estáticos
│   ├── .eslintrc.json         # Configuração ESLint
│   ├── next.config.js         # Configuração Next.js
│   ├── tailwind.config.js     # Configuração Tailwind
│   ├── tsconfig.json          # Configuração TypeScript
│   └── package.json           # Dependências do projeto
├── .gitignore                 # Arquivos ignorados pelo Git
└── README.md                  # Documentação (você está aqui!)
```

---

## 🎨 Componentes Principais

### Dashboard
Painel principal com cards informativos, gráficos de progresso e métricas do projeto.

### Data Grid
Tabelas interativas com ordenação, filtros e paginação usando MUI X Data Grid.

### Gantt Chart
Visualização de cronograma de tarefas com dependências e marcos.

### Task Board
Quadro Kanban drag-and-drop para gerenciamento visual de tarefas.

---

## 🔧 Configuração Avançada

### Customizar Tema Material-UI

Edite `src/app/theme.ts`:

```typescript
import { createTheme } from '@mui/material/styles';

export const theme = createTheme({
  palette: {
    primary: {
      main: '#1976d2',
    },
    secondary: {
      main: '#dc004e',
    },
  },
});
```

### Adicionar Variáveis de Ambiente

Crie `.env.local` na raiz da pasta `client/`:

```env
NEXT_PUBLIC_API_URL=sua_api_url
NEXT_PUBLIC_ANALYTICS_ID=seu_id
```

---

## 📊 Dependências Principais

```json
{
  "@mui/material": "5.16.7",
  "@mui/x-data-grid": "7.12.1",
  "@emotion/react": "11.13.0",
  "@emotion/styled": "11.13.0",
  "axios": "1.7.3",
  "date-fns": "3.6.0",
  "gantt-task-react": "0.3.9",
  "lucide-react": "0.427.0",
  "next": "14.2.5",
  "numeral": "2.0.6",
  "react": "18.3.1",
  "react-dnd": "16.0.1",
  "recharts": "2.12.7",
  "uuid": "9.0.1"
}
```

---

## 🤝 Contribuindo

Contribuições são sempre bem-vindas!

1. Fork o projeto
2. Crie uma branch para sua feature (`git checkout -b feature/MinhaFeature`)
3. Commit suas mudanças (`git commit -m 'Adiciona MinhaFeature'`)
4. Push para a branch (`git push origin feature/MinhaFeature`)
5. Abra um Pull Request

---

## 📝 Licença

Este projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

---

## 👨‍💻 Autor

**Edward**

- GitHub: [@Edwardd-Dev](https://github.com/Edwardd-Dev)
- LinkedIn: [Seu LinkedIn](#)
- Email: seu.email@example.com

---

## 🙏 Agradecimentos

- [Ed Roh](https://www.youtube.com/@EdRohDev) - Tutorial base do projeto
- [Next.js Documentation](https://nextjs.org/docs)
- [Material-UI](https://mui.com/)
- [Vercel](https://vercel.com) - Hospedagem

---

<div align="center">

### ⭐ Se este projeto foi útil, considere dar uma estrela!

**Feito com ❤️ e ☕**

</div>