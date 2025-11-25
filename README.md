# 🚀 Pague Safe - Landing Page

Landing page moderna e responsiva desenvolvida para a **Pague Safe**, um gateway de pagamentos de alta conversão com foco em segurança, saque rápido e alta taxa de aprovação.

## 📋 Sobre o Projeto

A Pague Safe é uma plataforma de pagamentos que oferece soluções completas para e-commerce e infoprodutos, incluindo checkout personalizável, múltiplos métodos de pagamento (PIX, Cartão de Crédito, Boleto), sistema antifraude eficiente e suporte 24/7.

Esta landing page foi desenvolvida para apresentar os serviços da empresa, destacar os benefícios e converter visitantes em clientes através de uma experiência visual atraente e otimizada.

## ✨ Funcionalidades

- **Hero Section** com mensagem de conversão impactante e CTA principal
- **Seção de Parceiros** exibindo bandeiras e instituições parceiras
- **Checkout Section** demonstrando o checkout personalizável
- **Feature Section** apresentando os principais recursos:
  - Integração transparente
  - Sistema antifraude
  - One-click buy
  - Recebimento em D+2
  - Suporte 24/7
  - Múltiplos administradores
- **Seção de Preços** mostrando taxas e tarifas para diferentes métodos de pagamento
- **Seção de Conversão** com estatísticas e resultados
- **FAQ Section** respondendo dúvidas frequentes
- **CTA Section** para negociação de taxas exclusivas
- **Footer** completo com links e informações legais

## 🛠️ Tecnologias Utilizadas

- **[Next.js 15.1.2](https://nextjs.org/)** - Framework React para produção
- **[React 18](https://react.dev/)** - Biblioteca JavaScript para interfaces
- **[TypeScript](https://www.typescriptlang.org/)** - Superset JavaScript com tipagem estática
- **[Tailwind CSS](https://tailwindcss.com/)** - Framework CSS utility-first
- **[Radix UI](https://www.radix-ui.com/)** - Componentes acessíveis e sem estilo
- **[Vercel Analytics](https://vercel.com/analytics)** - Análise de performance e métricas
- **[Google Analytics & Tag Manager](https://analytics.google.com/)** - Rastreamento e análise

## 📁 Estrutura do Projeto

```
pague-safe-project-main/
├── src/
│   ├── app/
│   │   ├── (main)/
│   │   │   └── page.tsx          # Página principal (Homepage)
│   │   ├── components/           # Componentes reutilizáveis
│   │   │   ├── Header.tsx
│   │   │   ├── Hero.tsx
│   │   │   ├── FeatureSection.tsx
│   │   │   ├── CheckoutSection.tsx
│   │   │   ├── PricingSection.tsx
│   │   │   ├── FAQSection.tsx
│   │   │   ├── Footer.tsx
│   │   │   └── ...
│   │   ├── assets/              # Imagens, ícones e recursos visuais
│   │   ├── contato/             # Página de contato
│   │   ├── termos-de-uso/       # Termos de uso
│   │   ├── politicas-de-privacidade/  # Políticas de privacidade
│   │   └── layout.tsx            # Layout raiz da aplicação
│   └── lib/
│       └── utils.ts              # Utilitários
├── public/                       # Arquivos estáticos
├── package.json
├── tailwind.config.ts
└── tsconfig.json
```

## 🚀 Como Executar

### Pré-requisitos

- Node.js 18+ instalado
- npm, yarn, pnpm ou bun

### Instalação

1. Clone o repositório:
```bash
git clone https://github.com/anthonymengottii/paguesafe_landingpage.git
cd paguesafe_landingpage
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

4. Abra [http://localhost:3000](http://localhost:3000) no navegador para ver a aplicação.

### Build para Produção

```bash
npm run build
npm start
```

## 🎨 Design e Responsividade

A landing page foi desenvolvida com foco em:

- **Design Moderno**: Interface limpa e profissional com paleta de cores verde/teal
- **Totalmente Responsiva**: Adaptação perfeita para mobile, tablet e desktop
- **Performance Otimizada**: Uso de Next.js Image para otimização automática de imagens
- **Animações Suaves**: Efeitos de fade-in e transições para melhor experiência do usuário
- **Acessibilidade**: Componentes acessíveis seguindo boas práticas

## 📱 Seções da Landing Page

1. **Header**: Navegação principal com logo e menu
2. **Hero**: Seção principal com título impactante e CTA
3. **Parceiros**: Logos de bandeiras e instituições parceiras
4. **Checkout**: Demonstração do checkout personalizável
5. **Recursos**: Grid com os principais recursos oferecidos
6. **Suporte**: Informações sobre suporte ao cliente
7. **Preços**: Cards com informações de taxas e tarifas
8. **Conversão**: Estatísticas e resultados
9. **Criar Conta**: Formulário de cadastro (desktop e mobile)
10. **FAQ**: Perguntas frequentes
11. **CTA Final**: Chamada para negociação de taxas exclusivas
12. **Footer**: Links legais e informações de contato

## 🔧 Scripts Disponíveis

- `npm run dev` - Inicia o servidor de desenvolvimento
- `npm run build` - Cria build de produção
- `npm start` - Inicia o servidor de produção
- `npm run lint` - Executa o linter ESLint

## 📄 Páginas Adicionais

- `/contato` - Página de contato
- `/termos-de-uso` - Termos de uso do serviço
- `/politicas-de-privacidade` - Políticas de privacidade
- `/termos-de-compra` - Termos de compra
- `/produtos-proibidos` - Lista de produtos proibidos
- `/cookies` - Política de cookies
- `/espaco-do-consumidor` - Espaço do consumidor

## 🌐 Deploy

O projeto está otimizado para deploy na [Vercel](https://vercel.com/), mas pode ser deployado em qualquer plataforma que suporte Next.js:

- **Vercel** (recomendado): Conecte seu repositório GitHub e faça deploy automático
- **Netlify**: Configure build command `npm run build` e publish directory `.next`
- **AWS Amplify**: Suporte nativo para Next.js
- **Docker**: Use a imagem oficial do Next.js

## 📝 Licença

Este projeto é privado e proprietário da Pague Safe.

## 👥 Contribuindo

Este é um projeto privado. Para sugestões ou problemas, entre em contato através da página de contato.

## 🎨 Créditos

- **Design e Identidade Visual**: O design e identidade visual desta landing page foram desenvolvidos pela **[Dinamite Criativa](https://dinamitecriativa.com.br/)**, um estúdio internacional de design com ampla experiência em projetos para empresas de diferentes setores e mercados.

- **Primeira Versão**: A primeira versão desta landing page foi desenvolvida e publicada no repositório **[Anderson-Soares-Martins/pague-safe-project](https://github.com/Anderson-Soares-Martins/pague-safe-project)**. Agradecimentos especiais a **Anderson Soares Martins**, que foi contratado na época para ajudar a subir o projeto, e aos demais contribuidores da versão inicial.

---

*Projeto gerenciado durante o período como CTO da Pague Safe*
