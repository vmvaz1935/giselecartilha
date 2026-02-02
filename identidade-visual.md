# 🎨 Identidade Visual - Cartilha de Fisioterapia

## 📋 Documento de Identidade Visual

Este documento descreve a identidade visual completa da cartilha de fisioterapia pós-operatória de hálux, baseada no estilo visual do site da Dra. Laice Cunha.

---

## 🎨 Paleta de Cores

### Cores Primárias

A identidade visual utiliza uma paleta baseada no site da Dra. Laice Cunha, com tons dourados/marrom claro que transmitem profissionalismo médico e elegância.

#### Cor Principal
- **Primary (Dourado Médico)**: `#B78B4C`
  - Uso: Botões principais, links, bordas de destaque, ícones, elementos de ação
  - Significado: Transmite confiança, profissionalismo e elegância médica

#### Variações da Cor Primária
- **Primary Dark**: `#9A7239`
  - Uso: Gradientes, hover states, elementos que precisam de mais contraste
- **Primary Light**: `#F5E6D3`
  - Uso: Backgrounds suaves, cards de informação, destaques sutis

#### Cor de Accent
- **Accent**: `#B78B4C` (mesma cor primária)
  - Uso: Elementos de destaque secundários

### Cores de Fundo

- **Background Primary**: `#F8F8F8`
  - Cor de fundo principal da página (off-white/cream)
  - Cria um ambiente suave e profissional

- **Background Secondary**: `#FFFFFF`
  - Branco puro para cards e elementos destacados
  - Contraste com o fundo principal

- **Background Card**: `#FFFFFF`
  - Fundo padrão para cards de conteúdo

### Cores de Texto

- **Text Primary**: `#212121`
  - Títulos principais e textos de alta importância
  - Preto suave para melhor legibilidade

- **Text Secondary**: `#333333`
  - Corpo de texto principal
  - Cinza escuro para leitura confortável

- **Text Muted**: `#666666`
  - Textos secundários e informações complementares
  - Cinza médio para hierarquia visual

- **Text Light**: `#999999`
  - Textos de baixa importância (rodapé, metadados)
  - Cinza claro para elementos discretos

### Cores de Destaque e Status

- **Success**: `#10B981` (Verde)
  - Mensagens de sucesso e confirmações

- **Warning**: `#F59E0B` (Amarelo/Laranja)
  - Avisos importantes e alertas

- **Error**: `#EF4444` (Vermelho)
  - Mensagens de erro (não utilizado na cartilha atual)

- **Info**: `#B78B4C` (Dourado)
  - Informações importantes

- **WhatsApp**: `#25D366` (Verde WhatsApp)
  - Botão flutuante do WhatsApp

### Sistema de Sombras

- **Shadow Small**: `0 1px 2px rgba(0,0,0,0.05)`
  - Sombras muito sutis para elementos leves

- **Shadow Medium**: `0 4px 6px rgba(0,0,0,0.08)`
  - Sombras padrão para cards e elementos elevados

- **Shadow Large**: `0 10px 15px rgba(0,0,0,0.1)`
  - Sombras mais pronunciadas para elementos de destaque (cabeçalho, modais)

---

## 📝 Tipografia

### Família de Fontes

**Fonte Principal**: Poppins (Google Fonts)
- Pesos utilizados: 400 (Regular), 500 (Medium), 600 (Semi-Bold), 700 (Bold)
- Uso: Títulos, elementos de destaque, números de exercícios

**Fonte Secundária**: Inter (Google Fonts)
- Pesos utilizados: 400 (Regular), 500 (Medium), 600 (Semi-Bold), 700 (Bold)
- Uso: Corpo de texto, descrições, conteúdo geral

**Fallback**: 
- `-apple-system, BlinkMacSystemFont, 'Segoe UI', sans-serif`
- Fontes do sistema para melhor performance

### Hierarquia Tipográfica

#### Títulos

- **H1 (Título Principal)**: 
  - Fonte: Poppins
  - Tamanho: 32px (desktop) / 24px (mobile)
  - Peso: 700 (Bold)
  - Cor: Branco (no cabeçalho) / `#212121` (em outros contextos)
  - Uso: Título principal da cartilha

- **H2 (Títulos de Seção)**:
  - Fonte: Poppins
  - Tamanho: 28px (desktop) / 22px (mobile)
  - Peso: 600 (Semi-Bold)
  - Cor: `#212121`
  - Uso: Títulos de seções principais

- **H3 (Subtítulos)**:
  - Fonte: Poppins
  - Tamanho: 20px
  - Peso: 600 (Semi-Bold)
  - Cor: `#212121`
  - Uso: Títulos de exercícios, subtítulos de seções

- **H4-H6**: Não utilizados na cartilha atual

#### Corpo de Texto

- **Texto Principal**:
  - Fonte: Inter / Poppins
  - Tamanho: 16px
  - Peso: 400 (Regular)
  - Cor: `#333333`
  - Line-height: 1.6

- **Texto Secundário**:
  - Fonte: Inter
  - Tamanho: 15px
  - Peso: 400 (Regular)
  - Cor: `#333333` ou `#666666`
  - Line-height: 1.8

- **Texto Pequeno**:
  - Fonte: Inter
  - Tamanho: 14px
  - Peso: 400 (Regular)
  - Cor: `#666666`
  - Uso: Informações complementares, rodapé

- **Texto Muito Pequeno**:
  - Fonte: Inter
  - Tamanho: 12px
  - Peso: 400 (Regular)
  - Cor: `#999999`
  - Uso: Metadados, datas no rodapé

### Características Tipográficas

- **Antialiasing**: Habilitado para melhor renderização (`-webkit-font-smoothing: antialiased`)
- **Line-height**: 1.6 para corpo de texto, 1.8 para descrições longas
- **Letter-spacing**: Padrão (sem ajustes adicionais)

---

## 📐 Sistema de Espaçamento

A cartilha utiliza um sistema de espaçamento baseado em múltiplos de 8px para consistência visual.

### Espaçamentos Padrão

- **XS (Extra Small)**: `8px`
  - Espaçamento mínimo entre elementos relacionados

- **SM (Small)**: `16px`
  - Espaçamento entre elementos próximos
  - Padding interno de elementos pequenos

- **MD (Medium)**: `24px`
  - Espaçamento padrão entre seções
  - Gap em grids e flex containers

- **LG (Large)**: `32px`
  - Espaçamento entre seções principais
  - Padding de containers grandes

- **XL (Extra Large)**: `48px`
  - Espaçamento máximo entre seções principais
  - Margem inferior de seções grandes

### Aplicação de Espaçamentos

- **Margens entre seções**: `var(--spacing-xl)` (48px)
- **Padding de cards**: `var(--spacing-lg)` (32px)
- **Gap em grids**: `var(--spacing-lg)` (32px)
- **Espaçamento interno de elementos**: `var(--spacing-md)` (24px)
- **Espaçamento entre itens de lista**: `var(--spacing-sm)` (16px)

---

## 🔲 Sistema de Bordas

### Raio de Borda (Border Radius)

- **Small**: `8px`
  - Elementos pequenos, badges, tags

- **Medium**: `12px`
  - Cards padrão, botões, elementos principais

- **Large**: `16px`
  - Cabeçalho, containers grandes, elementos de destaque

### Estilos de Borda

- **Bordas de Destaque**: 
  - `border-left: 4px solid var(--primary)` - Cards de diagnóstico e resumo
  - `border-left: 3px solid var(--primary)` - Cards de exercícios e planos

- **Bordas Sutis**:
  - `border: 1px solid rgba(183, 139, 76, 0.15)` - Cards de exercícios
  - `border-top: 1px solid rgba(183, 139, 76, 0.1)` - Divisores sutis

---

## 🧩 Componentes Visuais

### Cabeçalho (Header)

- **Background**: Gradiente linear (135deg) de `#B78B4C` para `#9A7239`
- **Cor do texto**: Branco
- **Padding**: 48px vertical, 32px horizontal
- **Border-radius**: 16px
- **Box-shadow**: `var(--shadow-lg)`
- **Layout**: Flexbox com logo no topo, título e informações do paciente lado a lado

### Cards de Exercícios

- **Background**: `#FFFFFF`
- **Border**: `1px solid rgba(183, 139, 76, 0.15)`
- **Border-radius**: `12px`
- **Padding**: `24px`
- **Box-shadow**: `var(--shadow-md)`
- **Hover**: 
  - Transform: `translateY(-4px)`
  - Box-shadow: `var(--shadow-lg)`
  - Transition: `0.3s ease`

### Número do Exercício

- **Formato**: Círculo
- **Tamanho**: 40px x 40px
- **Background**: `#B78B4C` (dourado)
- **Cor do texto**: Branco
- **Fonte**: Poppins, 18px, Bold
- **Box-shadow**: `0 2px 4px rgba(183, 139, 76, 0.3)`

### Badges de Fase

- **Background**: `#F5E6D3` (dourado claro)
- **Cor do texto**: `#9A7239` (dourado escuro)
- **Border**: `1px solid #B78B4C`
- **Padding**: `8px 24px`
- **Border-radius**: `8px`
- **Fonte**: Poppins, 14px, Semi-Bold

### Cards de Informação (Diagnóstico, Resumo, etc.)

- **Background**: `#FFFFFF`
- **Border-left**: `4px solid #B78B4C`
- **Border-top**: `1px solid rgba(183, 139, 76, 0.1)`
- **Padding**: `24px`
- **Border-radius**: `12px`
- **Box-shadow**: `var(--shadow-md)`

### Botões

#### Botão YouTube (Links de Vídeo)
- **Background**: `#F5E6D3` (dourado claro)
- **Cor do texto**: `#B78B4C` (dourado)
- **Padding**: `6px 12px`
- **Border-radius**: `8px`
- **Hover**:
  - Background: `#B78B4C`
  - Cor do texto: Branco
  - Transform: `translateY(-2px)`
  - Box-shadow: `var(--shadow-sm)`

#### Botão WhatsApp Flutuante
- **Tamanho**: 60px x 60px (desktop) / 56px x 56px (mobile)
- **Background**: `#25D366` (verde WhatsApp)
- **Border-radius**: 50% (círculo)
- **Box-shadow**: `0 4px 12px rgba(37, 211, 102, 0.4)`
- **Hover**:
  - Transform: `scale(1.1)`
  - Box-shadow: `0 6px 20px rgba(37, 211, 102, 0.6)`

### Cards de Especificações (Séries/Repetições)

- **Background**: `#F5E6D3` (dourado claro)
- **Border-left**: `3px solid #B78B4C`
- **Padding**: `16px`
- **Border-radius**: `8px`
- **Layout**: Flexbox com ícones e texto

### Seções de Avisos

- **Background**: `#FFF4E6` (amarelo muito claro)
- **Border-left**: `4px solid #F59E0B` (amarelo/laranja)
- **Padding**: `24px`
- **Border-radius**: `12px`
- **Box-shadow**: `var(--shadow-md)`

### Cards de Contato

- **Background**: Gradiente linear de `#F5E6D3` para `#FFFFFF`
- **Border**: `1px solid rgba(183, 139, 76, 0.2)`
- **Padding**: `48px`
- **Border-radius**: `12px`
- **Box-shadow**: `var(--shadow-md)`

---

## 📱 Layout e Grid

### Container Principal

- **Max-width**: `1200px`
- **Padding**: `32px` (desktop)
- **Margin**: `0 auto` (centralizado)

### Grid de Exercícios

- **Layout**: CSS Grid
- **Colunas**: `repeat(auto-fit, minmax(350px, 1fr))`
- **Gap**: `32px`
- **Responsivo**: 1 coluna em mobile

### Grid de Contatos

- **Layout**: CSS Grid
- **Colunas**: `repeat(auto-fit, minmax(250px, 1fr))`
- **Gap**: `32px`
- **Responsivo**: 1 coluna em mobile

---

## 🎯 Elementos Visuais Específicos

### Ícones

- **Biblioteca**: Font Awesome 6.4.0
- **Tamanho padrão**: 20px
- **Cor padrão**: `#B78B4C` (dourado)
- **Uso**: 
  - Ícones de seções: 28px
  - Ícones de exercícios: 20px
  - Ícones de contato: 20px
  - Ícone WhatsApp: 32px (desktop) / 28px (mobile)

### Logo

- **Arquivo**: `logo-branca.png.webp`
- **Posição**: Topo do cabeçalho, centralizado
- **Tamanho máximo**: 
  - Desktop: 100px altura, 300px largura
  - Mobile: 70px altura, 250px largura
- **Filtro**: Nenhum (logo branco sobre fundo dourado)

### Linhas Divisórias

- **Seções**: `border-bottom: 2px solid #B78B4C`
- **Cards**: `border-top: 1px solid rgba(183, 139, 76, 0.1)`
- **Itens de lista**: Bordas sutis em cards

### Gradientes

- **Cabeçalho**: `linear-gradient(135deg, #B78B4C 0%, #9A7239 100%)`
- **Card de Contato**: `linear-gradient(135deg, #F5E6D3 0%, #FFFFFF 100%)`

---

## 📱 Responsividade

### Breakpoints

- **Mobile**: `max-width: 375px`
- **Tablet**: `max-width: 768px`
- **Desktop**: `min-width: 1200px`

### Ajustes Responsivos

#### Mobile (≤ 768px)
- Padding do container: `24px` (reduzido de 32px)
- Título principal: `24px` (reduzido de 32px)
- Grid de exercícios: 1 coluna
- Grid de contatos: 1 coluna
- Títulos de seção: `22px` (reduzido de 28px)
- Botão WhatsApp: `56px` (reduzido de 60px)
- Logo: `70px altura, 250px largura`

#### Mobile Extra Pequeno (≤ 375px)
- Header content: Coluna única (flex-direction: column)
- Patient info: Largura 100%

### Estratégia de Design

- **Mobile-first**: Design pensado primeiro para mobile
- **Progressive Enhancement**: Melhorias para telas maiores
- **Touch-friendly**: Elementos com tamanho mínimo de 44px para toque

---

## ✨ Animações e Transições

### Transições Padrão

- **Duração**: `0.3s`
- **Timing**: `ease`
- **Propriedades animadas**:
  - Transform
  - Box-shadow
  - Background-color
  - Color

### Efeitos de Hover

- **Cards de exercícios**: Elevação (`translateY(-4px)`) + sombra aumentada
- **Botões**: Mudança de cor + leve elevação
- **Links**: Mudança de cor suave

### Estados Interativos

- **Focus**: Estados de foco para acessibilidade (não especificados, mas devem seguir padrões WCAG)
- **Active**: Estados ativos para feedback visual

---

## 🖼️ Elementos de Conteúdo

### Placeholders de Imagem

- **Removidos**: Não há placeholders visíveis na versão final
- **Estrutura preparada**: Espaço reservado para futuras ilustrações

### Vídeos

- **Links**: Botões estilizados com ícone do YouTube
- **Estilo**: Cards com background `#F8F9FA` e borda esquerda dourada
- **Comportamento**: Abrem em nova aba (`target="_blank"`)

---

## 🎨 Princípios de Design

### Hierarquia Visual

1. **Nível 1**: Cabeçalho com gradiente dourado (maior destaque)
2. **Nível 2**: Cards de diagnóstico e resumo (borda esquerda dourada)
3. **Nível 3**: Cards de exercícios (sombras médias)
4. **Nível 4**: Elementos de informação (backgrounds claros)

### Contraste

- **WCAG AA**: Todos os textos seguem padrões de contraste mínimo
- **Texto sobre dourado**: Branco para máximo contraste
- **Texto sobre branco**: Preto suave (`#212121`) ou cinza escuro (`#333333`)

### Espaçamento em Branco

- **Generoso**: Espaçamento amplo entre seções para respiração visual
- **Consistente**: Uso sistemático do sistema de espaçamento de 8px
- **Hierárquico**: Espaçamentos maiores para elementos mais importantes

### Consistência

- **Cores**: Uso consistente da paleta definida
- **Tipografia**: Hierarquia clara e consistente
- **Componentes**: Padrões visuais repetidos em toda a cartilha

---

## 🖨️ Compatibilidade de Impressão

### Media Query Print

- **Cores**: Mantidas para elementos importantes (cabeçalho)
- **Quebras de página**: Evitadas em cards e seções importantes
- **Sombras**: Removidas ou simplificadas
- **Backgrounds**: Mantidos para elementos críticos

---

## ♿ Acessibilidade

### Contraste

- **Textos**: Contraste mínimo WCAG AA garantido
- **Links**: Diferenciação clara do texto normal
- **Botões**: Contraste adequado entre texto e fundo

### Navegação

- **Estrutura semântica**: HTML5 semântico
- **Labels**: Elementos com labels apropriados
- **ARIA**: Labels ARIA onde necessário (botão WhatsApp)

### Interatividade

- **Estados de foco**: Visíveis para navegação por teclado
- **Áreas de toque**: Mínimo de 44px em mobile
- **Feedback visual**: Hover states claros

---

## 📊 Resumo da Identidade Visual

### Características Principais

1. **Paleta Dourada**: Tons dourados/marrom claro transmitem profissionalismo médico
2. **Tipografia Moderna**: Poppins e Inter para legibilidade e modernidade
3. **Espaçamento Generoso**: Layout limpo e respirável
4. **Sombras Sutis**: Profundidade sem poluição visual
5. **Bordas Arredondadas**: Suavidade e modernidade
6. **Gradientes Elegantes**: Apenas em elementos de destaque
7. **Responsividade Completa**: Adaptação perfeita a todos os dispositivos

### Personalidade da Marca

- **Profissional**: Visual médico confiável
- **Elegante**: Design refinado e sofisticado
- **Acessível**: Fácil de ler e navegar
- **Moderno**: Estilo contemporâneo e atualizado
- **Confiável**: Transmite segurança e credibilidade

---

## 📝 Notas de Implementação

### Variáveis CSS

Todas as cores, espaçamentos e valores são definidos como variáveis CSS em `:root` para fácil manutenção e consistência.

### Fontes Externas

- Google Fonts: Poppins e Inter
- Font Awesome: Ícones

### Performance

- Fontes pré-carregadas com `preconnect`
- CSS inline para evitar requisições adicionais
- Imagens otimizadas (formato webp)

---

**Última atualização**: 2025-01-27  
**Baseado em**: Site da Dra. Laice Cunha (https://dralaicecunha.com.br/)  
**Versão**: 1.0
