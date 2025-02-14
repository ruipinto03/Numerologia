📦 teu-projeto/
├── 📂 public/             # Imagens, ícones e assets públicos
│   ├── logo.png
│   ├── favicon.ico
│   ├── imagens/
├── 📂 src/
│   ├── 📂 app/            # Diretório principal do App Router
│   │   ├── 📂 api/        # API Routes (Server Actions ou Route Handlers)
│   │   │   ├── 📂 auth/route.ts  # Login, registo e autenticação
│   │   │   ├── 📂 users/route.ts # CRUD de utilizadores
│   │   │   ├── 📂 reports/route.ts # Geração de relatórios
│   │   │   ├── 📂 calculations/route.ts # Cálculos numerológicos
│   │   ├── 📂 dashboard/   # Página do Dashboard
│   │   │   ├── page.tsx
│   │   │   ├── layout.tsx
│   │   ├── 📂 admin/       # Painel de administração
│   │   │   ├── page.tsx
│   │   │   ├── layout.tsx
│   │   ├── 📂 profile/     # Página de perfil do usuário
│   │   │   ├── page.tsx
│   │   ├── 📂 reports/     # Página de relatórios
│   │   │   ├── page.tsx
│   │   ├── 📂 calculations/ # Página de cálculos numerológicos
│   │   │   ├── page.tsx
│   │   ├── layout.tsx      # Layout global
│   │   ├── page.tsx        # Página inicial
│   │   ├── loading.tsx     # Página de loading global
│   │   ├── error.tsx       # Página de erro global
│   ├── 📂 components/     # Componentes reutilizáveis
│   │   ├── 📜 Navbar.tsx  # Barra de navegação
│   │   ├── 📜 Sidebar.tsx # Menu lateral
│   │   ├── 📜 Footer.tsx  # Rodapé
│   │   ├── 📜 Modal.tsx   # Componente modal reutilizável
│   │   ├── 📜 Chart.tsx   # Componente para gráficos
│   │   ├── 📜 Table.tsx   # Componente de tabela
│   │   ├── 📜 ProtectedRoute.tsx # Proteção de rotas privadas
│   ├── 📂 hooks/          # Hooks personalizados
│   │   ├── 📜 useAuth.ts  # Hook para autenticação do usuário
│   │   ├── 📜 useFetch.ts # Hook para chamadas API
│   ├── 📂 services/       # Serviços para chamadas API
│   │   ├── 📜 authService.ts # Serviço de autenticação
│   │   ├── 📜 userService.ts # Serviço para usuários
│   │   ├── 📜 reportService.ts # Serviço para relatórios
│   │   ├── 📜 calculationService.ts # Serviço para cálculos
│   ├── 📂 utils/          # Funções utilitárias
│   │   ├── 📜 helpers.ts  # Funções úteis genéricas
│   │   ├── 📜 validators.ts # Validações de formulários
│   │   ├── 📜 formatters.ts # Formatações de dados
│   ├── 📂 styles/         # Estilos globais e CSS
│   │   ├── 📜 globals.css # Estilos globais
│   │   ├── 📜 variables.css # Variáveis de cores e temas
│   ├── 📂 context/        # Context API (Global State)
│   │   ├── 📜 AuthContext.tsx # Contexto de autenticação
│   │   ├── 📜 UserContext.tsx # Contexto de usuário
│   ├── 📂 models/         # Modelos do MongoDB
│   │   ├── 📜 User.ts     # Modelo de usuário
│   │   ├── 📜 Report.ts   # Modelo de relatórios
│   │   ├── 📜 Calculation.ts # Modelo de cálculos
│   ├── 📂 repositories/   # Camada de acesso a dados (MongoDB)
│   │   ├── 📜 userRepository.ts # Repositório de usuários
│   │   ├── 📜 reportRepository.ts # Repositório de relatórios
│   │   ├── 📜 calculationRepository.ts # Repositório de cálculos
│   ├── 📂 middleware/     # Middlewares para API
│   │   ├── 📜 authMiddleware.ts # Middleware de autenticação
│   ├── 📂 config/         # Configurações globais
│   │   ├── 📜 database.ts # Conexão com MongoDB
│   │   ├── 📜 constants.ts # Constantes globais
│   ├── 📂 tests/          # Testes automatizados
│   │   ├── 📜 auth.test.ts # Testes de autenticação
│   │   ├── 📜 user.test.ts # Testes de usuários
│   ├── 📂 docs/           # Documentação do projeto
│   │   ├── 📜 README.md   # Documentação inicial
│   │   ├── 📜 API.md      # Documentação da API
│   ├── 📜 .env.local      # Variáveis de ambiente
│   ├── 📜 next.config.js  # Configuração do Next.js
│   ├── 📜 tsconfig.json   # Configuração do TypeScript
│   ├── 📜 package.json    # Dependências do projeto
│   ├── 📜 .gitignore      # Ignorar arquivos desnecessários