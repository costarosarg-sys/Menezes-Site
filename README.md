# Menezes Refrigeração - Landing Page

Landing page profissional e otimizada para conversão da **Menezes Refrigeração**, empresa especializada em instalação, manutenção e reparos de ar condicionado e refrigeração em Rio Grande, RS.

## 🚀 Características

- **Design Moderno e Responsivo**: Interface adaptável para todos os dispositivos
- **Otimizado para Conversão**: Múltiplos CTAs estratégicos para WhatsApp
- **Performance**: Otimização de imagens e carregamento rápido
- **Acessibilidade**: Conforme padrões WCAG 2.1
- **SEO Otimizado**: Meta tags, structured data e semântica HTML
- **Scroll Suave**: Navegação fluida entre seções

## 🛠️ Tecnologias

- **[Next.js 16](https://nextjs.org/)** - Framework React com App Router
- **[React 19](https://react.dev/)** - Biblioteca JavaScript
- **[TypeScript](https://www.typescriptlang.org/)** - Tipagem estática
- **[Tailwind CSS 4](https://tailwindcss.com/)** - Framework CSS utility-first
- **[Lucide React](https://lucide.dev/)** - Biblioteca de ícones

## 📋 Pré-requisitos

- Node.js 18+
- npm, yarn, pnpm ou bun

## 🚀 Como Executar

### Instalação

```bash
# Clone o repositório
git clone <url-do-repositorio>

# Entre no diretório
cd menezes-refrigeracao

# Instale as dependências
npm install
# ou
yarn install
# ou
pnpm install
```

### Desenvolvimento

```bash
npm run dev
# ou
yarn dev
# ou
pnpm dev
# ou
bun dev
```

Abra [http://localhost:3000](http://localhost:3000) no navegador para ver o resultado.

### Build de Produção

```bash
npm run build
npm start
```

## 📁 Estrutura do Projeto

```
menezes-refrigeracao/
├── app/
│   ├── layout.tsx          # Layout principal com metadados SEO
│   ├── page.tsx            # Página principal (landing page)
│   └── globals.css         # Estilos globais e acessibilidade
├── public/
│   ├── ar-condicionado.png # Imagem de ar condicionado
│   ├── geladeira.png       # Imagem de geladeira
│   └── freez.png           # Imagem de freezer
├── package.json
├── tsconfig.json
└── README.md
```

## ⚙️ Configuração

### Número do WhatsApp

Para configurar o número do WhatsApp, edite a variável `whatsappNumber` no arquivo `app/page.tsx`:

```typescript
const whatsappNumber = "5551999999999"; // Substitua pelo número real
```

**Formato**: Código do país + DDD + número (sem espaços ou caracteres especiais)

Exemplo: Se o número for (53) 99999-9999, use `"5553999999999"`

### Metadados SEO

Os metadados podem ser atualizados em `app/layout.tsx`:

- Título da página
- Descrição
- Keywords
- URLs canônicas
- Open Graph
- Twitter Cards

## 🎨 Seções da Landing Page

1. **Hero Section**: Apresentação principal com CTA destacado
2. **Serviços**: 6 serviços principais com ícones do Lucide React
3. **Equipamentos**: Galeria com imagens dos equipamentos trabalhados
4. **Benefícios**: Diferenciais da empresa
5. **Localização**: Destaque para Rio Grande, RS
6. **Footer**: Informações de contato e links

## ♿ Acessibilidade

- Skip links para navegação por teclado
- Atributos ARIA apropriados
- Contraste adequado em todos os elementos
- Suporte a `prefers-reduced-motion`
- Navegação por teclado otimizada

## 🔍 SEO

- Structured Data (JSON-LD) com schema LocalBusiness
- Meta tags otimizadas
- Open Graph e Twitter Cards
- Hierarquia semântica de headings
- URLs canônicas configuradas

## 📱 Responsividade

A página é totalmente responsiva com breakpoints:

- Mobile: < 640px
- Tablet: 640px - 1024px
- Desktop: > 1024px

## 🎯 Otimizações

- Imagens com lazy loading
- Componente Image do Next.js para otimização automática
- Scroll suave entre seções
- Transições suaves em hover
- Efeito de zoom nas imagens dos equipamentos

## 📝 Scripts Disponíveis

- `npm run dev` - Inicia servidor de desenvolvimento
- `npm run build` - Cria build de produção
- `npm start` - Inicia servidor de produção
- `npm run lint` - Executa o linter

## 🌐 Deploy

### Vercel (Recomendado)

A forma mais fácil de fazer deploy é usando a [Vercel Platform](https://vercel.com):

1. Conecte seu repositório GitHub
2. A Vercel detectará automaticamente o Next.js
3. Clique em Deploy

### Outras Plataformas

O projeto pode ser deployado em qualquer plataforma que suporte Next.js:

- Netlify
- AWS Amplify
- Railway
- Render

## 📄 Licença

Este projeto é privado e propriedade da Menezes Refrigeração.

## 👨‍💻 Desenvolvimento

Para contribuir ou fazer alterações:

1. Crie uma branch para sua feature
2. Faça suas alterações
3. Teste localmente
4. Faça commit e push
5. Abra um Pull Request

## 📞 Contato

Para dúvidas ou suporte, entre em contato através do WhatsApp disponível na landing page.

---

Desenvolvido com ❤️ para Menezes Refrigeração
