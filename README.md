# PARDAL - Inteligência Regional sem Ruído

**Estado de São Paulo • Ribeirão da Mantiqueira • 25 de Dezembro de 2025**

## 📋 Sobre o Projeto

PARDAL é um sistema de inteligência regional desenvolvido no Google AI Studio que combina análise de dados, geração de conteúdo editorial e visualização de informações focadas em circuitos regionais. O projeto nasceu com o objetivo de fornecer análises técnicas sobre perspectivas de Natal no Circuito da Mantiqueira, com foco no impacto da digitalização no campo e na logística regional.

## 🎯 Funcionalidades Principais

### 1. **Análise de Dados Regionais**
- Processamento de informações sobre circuitos econômicos
- Análise de tendências de mercado local
- Mapeamento de logística e distribuição regional

### 2. **Geração de Conteúdo Editorial**
- Criação automática de artigos e análises
- Sistema de templates personalizáveis
- Suporte para diferentes formatos de publicação

### 3. **Interface Visual Moderna**
- Design responsivo e acessível
- Tipografia profissional (Crimson Pro + Inter)
- Componentes visuais otimizados para leitura

### 4. **Sistema de Navegação**
- Estrutura de páginas e artigos
- Organização por categorias e temas
- Índice dinâmico de conteúdos

## 🏗️ Arquitetura do Sistema

O projeto está estruturado em módulos principais:

```
pardal/
├── components/      # Componentes React reutilizáveis
├── constants.ts     # Configurações e constantes do sistema
├── index.html      # Estrutura HTML principal
└── index.tsx       # Ponto de entrada da aplicação
```

### Componentes Principais

- **App.tsx**: Componente raiz da aplicação
- **Organisms**: Componentes complexos de UI
- **Molecules**: Componentes intermediários
- **Atoms**: Componentes básicos reutilizáveis
- **Navigation**: Sistema de navegação e rotas
- **Ledger**: Sistema de gerenciamento de dados

## 🚀 Tecnologias Utilizadas

- **React**: Framework de interface de usuário
- **TypeScript**: Linguagem de programação tipada
- **Vite**: Build tool e bundler
- **Google AI Studio**: Plataforma de desenvolvimento
- **CSS Modules**: Estilização modular

## 📦 Estrutura de Dados

### Tipos Principais

```typescript
// Elementos básicos
Basic.createElement(tag, { style, className }, children)

// Sistema de navegação
Nav.createPage(title, { description, content })

// Geração de conteúdo
Reply.createElement(type, { style, className, children })
```

## 🎨 Design System

### Cores

- **Principal**: `#1a1a1a` (Texto principal)
- **Secundária**: `#666` (Texto secundário)
- **Destaque**: `#FFD700` (Elementos de atenção)
- **Fundo**: `#FFFFFF` (Fundo principal)

### Tipografia

- **Títulos**: Crimson Pro (serif, profissional)
- **Corpo**: Inter (sans-serif, legibilidade)
- **Código**: Monospace

### Espaçamento

- Sistema baseado em múltiplos de 8px
- Margens e paddings consistentes
- Layout responsivo com breakpoints definidos

## 📱 Responsividade

O sistema é otimizado para:

- **Desktop**: 1920px+
- **Tablet**: 768px - 1919px
- **Mobile**: 320px - 767px

## 🔧 Como Usar

### Pré-requisitos

- Conta no Google AI Studio
- Navegador moderno (Chrome, Firefox, Safari, Edge)

### Instalação

1. Acesse o Google AI Studio
2. Importe o projeto usando o código fornecido
3. Execute o preview para visualizar

### Desenvolvimento

```bash
# O projeto roda diretamente no Google AI Studio
# Não requer instalação local
```

## 📄 Licença

Este projeto é de código aberto e está disponível sob a licença MIT.

## 👥 Contribuindo

Contribuições são bem-vindas! Para contribuir:

1. Fork o projeto
2. Crie uma branch para sua feature (`git checkout -b feature/AmazingFeature`)
3. Commit suas mudanças (`git commit -m 'Add some AmazingFeature'`)
4. Push para a branch (`git push origin feature/AmazingFeature`)
5. Abra um Pull Request

## 📞 Contato

Para dúvidas ou sugestões sobre o projeto, abra uma issue no repositório.

## 🎯 Roadmap

- [ ] Integração com APIs de dados regionais
- [ ] Sistema de autenticação
- [ ] Dashboard de analytics
- [ ] Exportação de relatórios
- [ ] Modo offline
- [ ] PWA (Progressive Web App)

## 📚 Documentação Adicional

Para mais informações sobre a estrutura do código e os módulos individuais, consulte os comentários inline no código-fonte.

---

**Desenvolvido com ❤️ para análise e inteligência regional**
