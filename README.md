Fresh Market - E-commerce de Supermercado - Projeto Faculdade

Pré-requisitos
- Node.js 18+ 
- pnpm (ou npm/yarn)

Passos para executar

1. Clone ou extraia o projeto
   bash
   Se usando git
   git clone <url-do-repositorio>
   cd supermercado-ecommerce
   
   Se você extraiu o ZIP e encontrou uma pasta aninhada (ex: supermercado-ecommerce/supermercado-ecommerce),
   certifique-se de navegar para a pasta mais interna onde o package.json está:
   cd supermercado-ecommerce
   

2. Instale as dependências
   bash
    Se usar pnpm (recomendado)
   pnpm install --legacy-peer-deps
   ou, se usar npm
   npm install --legacy-peer-deps
   

3. Execute em modo de desenvolvimento
   bash
   pnpm run dev
   ou
   npm run dev
   


Responsividade

O site foi desenvolvido com abordagem mobile-first e é totalmente responsivo:

- Mobile (< 768px): Layout em coluna única, menu hambúrguer
- Tablet (768px - 1024px): Grid de 2-3 colunas
- Desktop (> 1024px): Grid completo de 4 colunas

Funcionalidades Implementadas

Concluído
- [x] Navegação entre páginas
- [x] Catálogo de produtos com filtros
- [x] Sistema de carrinho funcional
- [x] Checkout com formulário completo
- [x] Cálculo de preços e descontos
- [x] Design responsivo
- [x] Animações e transições
- [x] Validação de formulários

Possíveis Melhorias Futuras
- [ ] Integração com API real
- [ ] Sistema de autenticação
- [ ] Histórico de pedidos
- [ ] Sistema de avaliações
- [ ] Integração com gateway de pagamento
- [ ] Notificações push
- [ ] Sistema de cupons

📂 Estrutura do Projeto

supermercado-ecommerce/
├── public/
│   └── favicon.ico
├── src/
│   ├── components/
│   │   └── ui/          # Componentes shadcn/ui
│   ├── hooks/           # Custom hooks
│   ├── lib/             # Utilitários
│   ├── assets/          # Imagens e recursos
│   ├── App.jsx          # Componente principal
│   ├── App.css          # Estilos globais
│   ├── index.css        # Reset CSS
│   └── main.jsx         # Entry point
├── dist/                # Build de produção
├── package.json
├── vite.config.js
└── README.md
