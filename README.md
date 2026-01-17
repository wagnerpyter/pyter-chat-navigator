# Pyter Chat Navigator

Uma plataforma de análise de perfis cognitivos com IA integrada para navegação web inteligente.

## 🚀 Deploy Rápido no GitHub Pages

Este repositório está configurado para deploy automático no GitHub Pages via GitHub Actions.

### Como Usar

1. **Fork este repositório** para sua conta GitHub
2. **Ative GitHub Pages** em Settings → Pages → Source: `gh-pages` branch
3. **Faça push** de qualquer alteração para `main` ou `master`
4. **Aguarde** ~2 minutos para o deploy automático

### URLs de Acesso

- **GitHub Pages**: `https://seu-usuario.github.io/pyter-chat-navigator/`
- **Preview Local**: `pnpm dev`

## 📦 Instalação Local

```bash
# Instalar dependências
pnpm install

# Desenvolvimento
pnpm dev

# Build para produção
pnpm build

# Preview do build
pnpm preview
```

## 🏗️ Estrutura

```
client/
  src/
    pages/        # Páginas (Home, Chat, Dashboard)
    components/   # Componentes reutilizáveis
    contexts/     # React contexts
    lib/          # Utilitários
    index.css     # Estilos globais
  public/         # Arquivos estáticos
```

## 🎨 Tecnologias

- **React 19** - UI framework
- **TypeScript** - Type safety
- **Tailwind CSS 4** - Styling
- **Vite** - Build tool
- **Recharts** - Gráficos
- **Wouter** - Roteamento

## 📝 Notas

- Esta é uma versão **frontend-only** (sem backend)
- Dados são mockados para demonstração
- Perfeito para testes e validação rápida

## 📄 Licença

MIT
