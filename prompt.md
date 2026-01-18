# 🎨 Prompt para Gerar Cartilha com Estilo Visual da Dra. Laice Cunha

## 📋 Prompt Completo para Ferramentas de IA (ChatGPT, Claude, etc.)

Use este prompt em ferramentas de IA para gerar uma cartilha de fisioterapia com o estilo visual do site da Dra. Laice Cunha:

```
Você é um especialista em design de interfaces web modernas e responsivas, especializado em criar materiais educativos médicos e cartilhas de fisioterapia.

CONTEXTO DO PROJETO:
- Aplicação web Flask para geração de cartilhas de fisioterapia
- Estilo visual baseado no site da Dra. Laice Cunha (https://dralaicecunha.com.br/)
- Especialidade: Ortopedia e Traumatologia, foco em tornozelo e pé
- Estilo: Moderno, limpo, profissional, médico, elegante

ESTRUTURA DA CARTILHA (MANTER):
A cartilha deve conter as seguintes seções:
1. Cabeçalho com informações do paciente e médico
2. Diagnóstico
3. Exercícios de fisioterapia (com descrições, imagens/ilustrações, séries e repetições)
4. Orientações gerais
5. Contatos e informações da clínica
6. Rodapé com dados profissionais

ESTILO VISUAL DA DRA. LAICE CUNHA (APLICAR):

CORES PRINCIPAIS:
- Cor primária médica: Tons de azul/verde médico profissional (similar ao site)
  - Primary: #0066CC ou #0052A3 (azul médico confiável)
  - Primary Dark: #004080 (azul escuro para contraste)
  - Primary Light: #E6F2FF (azul claro suave)
  - Accent: #00A6A6 (verde-azulado médico, se aplicável)
- Background: #FFFFFF (branco limpo) e #F8F9FA (cinza muito claro para seções alternadas)
- Texto: #1A1A1A (preto suave) para títulos, #4A4A4A (cinza escuro) para corpo
- Texto secundário: #6B7280 (cinza médio)
- Destaques: #0066CC (azul médico) para links e CTAs

TIPOGRAFIA:
- Fonte principal: 'Inter', 'Roboto', ou 'Poppins' (Google Fonts) - fontes modernas e limpas
- Títulos: Weight 600-700 (semi-bold a bold)
- Corpo: Weight 400 (regular)
- Destaques: Weight 500 (medium)
- Hierarquia clara com tamanhos: h1 (32-40px), h2 (24-28px), h3 (20-22px), body (16px)

ELEMENTOS DE DESIGN:
- Layout limpo e espaçado (padding generoso)
- Cards com bordas arredondadas suaves (border-radius: 12-16px)
- Sombras sutis e elegantes (box-shadow: 0 2px 8px rgba(0,0,0,0.08))
- Linhas divisórias suaves entre seções
- Ícones médicos/fisioterapia (use Font Awesome ou SVG)
- Espaçamento consistente (margens de 24px, 32px, 48px)
- Botões com estilo médico profissional (bordas arredondadas, padding generoso)

COMPONENTES ESPECÍFICOS:
1. Cabeçalho da Cartilha:
   - Logo ou nome da clínica/médico no topo
   - Informações do paciente em card destacado
   - Data de geração
   - Visual limpo e profissional

2. Seção de Exercícios:
   - Cada exercício em card individual
   - Número do exercício destacado
   - Título do exercício em negrito
   - Descrição clara e objetiva
   - Área para ilustração/imagem (placeholder ou espaço reservado)
   - Informações de séries/repetições em destaque
   - Ícones relacionados (pé, tornozelo, movimento)

3. Orientações:
   - Lista organizada e clara
   - Ícones para cada orientação
   - Destaque para informações importantes

4. Contatos:
   - Card de contato elegante
   - Informações organizadas (telefone, email, endereço)
   - Botão de agendamento (se aplicável)

SOLICITAÇÃO:
Crie um design completo de frontend para uma cartilha de fisioterapia em formato HTML/CSS, seguindo o estilo visual do site da Dra. Laice Cunha, mas mantendo a estrutura funcional de uma cartilha de exercícios.

REQUISITOS DE DESIGN:
1. Layout responsivo (mobile-first)
2. Paleta de cores médica profissional (baseada no site da Dra. Laice)
3. Tipografia moderna e legível (Inter, Roboto ou Poppins)
4. Componentes com:
   - Cards elegantes com sombras suaves
   - Botões profissionais com hover states
   - Animações sutis e elegantes
   - Estados de hover e focus bem definidos
   - Feedback visual para todas as ações
5. Acessibilidade completa (contraste WCAG AA, labels, ARIA)
6. Microinterações suaves (transições de 0.3s)
7. Visual médico profissional e confiável

ENTREGÁVEIS:
1. HTML completo e válido (estrutura semântica HTML5)
2. CSS inline ou em tag <style> (com variáveis CSS para cores e espaçamentos)
3. JavaScript mínimo necessário (se houver interatividade)
4. Comentários explicando seções importantes
5. Design system completo com:
   - Variáveis CSS (:root) para cores, fontes, espaçamentos
   - Componentes reutilizáveis (cards, botões, seções)
   - Breakpoints responsivos (mobile: 375px, tablet: 768px, desktop: 1200px)
   - Espaçamento consistente (sistema de 8px)
6. Estrutura da cartilha completa com:
   - Cabeçalho profissional
   - Seções de exercícios (mínimo 5 exercícios de exemplo)
   - Orientações gerais
   - Informações de contato
   - Rodapé

ESTILO VISUAL ESPECÍFICO:
- Gradientes suaves apenas em elementos de destaque (botões principais)
- Bordas arredondadas moderadas (12-16px, não exagerado)
- Sombras sutis e elegantes (evitar sombras pesadas)
- Espaçamento generoso (não compacto)
- Ícones médicos/fisioterapia (Font Awesome ou SVG inline)
- Cores que transmitam confiança e profissionalismo médico
- Visual limpo, sem poluição visual
- Hierarquia visual clara (o que é mais importante se destaca)

DETALHES TÉCNICOS:
- Use Google Fonts para tipografia
- Inclua Font Awesome para ícones (ou SVG inline)
- Código otimizado e bem comentado
- Compatível com impressão (media queries para print)
- Performance otimizada (CSS inline, sem dependências externas pesadas)

EXEMPLO DE ESTRUTURA DE EXERCÍCIO:
Cada exercício deve ter:
- Card com borda sutil e sombra leve
- Número do exercício em círculo ou badge
- Título em negrito
- Descrição passo a passo
- Espaço para ilustração (placeholder com cor de fundo suave)
- Box destacado com séries/repetições
- Ícone relacionado ao tipo de exercício

Por favor, forneça o código HTML completo, pronto para uso, sem markdown, sem ```html, apenas o código puro e funcional.
```

---

## 🎯 Como Usar Este Prompt

### Passo 1: Copiar o Prompt
1. Copie todo o conteúdo entre os três backticks (```) acima
2. Cole em ChatGPT, Claude, Gemini ou outra ferramenta de IA

### Passo 2: Personalizar (Opcional)
Você pode adicionar informações específicas antes de enviar:

```
[COLE O PROMPT ACIMA AQUI]

INFORMAÇÕES ESPECÍFICAS PARA ESTA CARTILHA:
- Nome do paciente: [NOME]
- Diagnóstico: [DIAGNÓSTICO]
- Número de exercícios: [QUANTIDADE]
- Foco: Tornozelo e pé / [OUTRA ÁREA]
- Informações de contato: [DADOS]
```

### Passo 3: Receber e Aplicar
1. Receba o código HTML completo da IA
2. Salve em um arquivo HTML (ex: `cartilha_template.html`)
3. Teste localmente abrindo no navegador
4. Ajuste cores/fontes se necessário

---

## 🎨 Paleta de Cores Sugerida (Baseada no Estilo Médico Profissional)

```css
:root {
  /* Cores Primárias - Estilo Médico Profissional */
  --primary: #0066CC;           /* Azul médico confiável */
  --primary-dark: #004080;      /* Azul escuro */
  --primary-light: #E6F2FF;     /* Azul claro suave */
  --accent: #00A6A6;            /* Verde-azulado médico */
  
  /* Cores de Fundo */
  --bg-primary: #FFFFFF;        /* Branco limpo */
  --bg-secondary: #F8F9FA;      /* Cinza muito claro */
  --bg-card: #FFFFFF;           /* Fundo de cards */
  
  /* Cores de Texto */
  --text-primary: #1A1A1A;      /* Preto suave */
  --text-secondary: #4A4A4A;    /* Cinza escuro */
  --text-muted: #6B7280;        /* Cinza médio */
  --text-light: #9CA3AF;        /* Cinza claro */
  
  /* Cores de Destaque */
  --success: #10B981;           /* Verde sucesso */
  --warning: #F59E0B;           /* Amarelo atenção */
  --error: #EF4444;             /* Vermelho erro */
  --info: #0066CC;              /* Azul informação */
  
  /* Sombras */
  --shadow-sm: 0 1px 2px rgba(0,0,0,0.05);
  --shadow-md: 0 4px 6px rgba(0,0,0,0.08);
  --shadow-lg: 0 10px 15px rgba(0,0,0,0.1);
  
  /* Espaçamentos */
  --spacing-xs: 8px;
  --spacing-sm: 16px;
  --spacing-md: 24px;
  --spacing-lg: 32px;
  --spacing-xl: 48px;
  
  /* Bordas */
  --radius-sm: 8px;
  --radius-md: 12px;
  --radius-lg: 16px;
}
```

---

## 📝 Checklist de Aplicação

Após receber o código da IA, verifique:

- [ ] HTML válido e semântico
- [ ] Cores aplicadas corretamente (estilo médico profissional)
- [ ] Fontes carregando (Google Fonts)
- [ ] Responsividade testada (mobile, tablet, desktop)
- [ ] Estrutura da cartilha completa (cabeçalho, exercícios, orientações, contato)
- [ ] Cards de exercícios bem formatados
- [ ] Espaçamento consistente
- [ ] Sombras e bordas aplicadas
- [ ] Ícones funcionando
- [ ] Compatibilidade de impressão (se necessário)
- [ ] Acessibilidade (contraste, labels)

---

## 💡 Dicas de Personalização

### Para Ajustar Cores:
Procure por `:root` no CSS e modifique as variáveis de cor conforme necessário.

### Para Adicionar Mais Exercícios:
Copie a estrutura de um card de exercício e ajuste o conteúdo.

### Para Modificar Fontes:
Altere a importação do Google Fonts e a propriedade `font-family` nas variáveis CSS.

### Para Ajustar Espaçamentos:
Modifique as variáveis `--spacing-*` no `:root`.

---

## 🚀 Exemplo de Uso Rápido

1. **Copie o prompt completo** (conteúdo entre ```)
2. **Cole no ChatGPT/Claude** com a mensagem: "Gere uma cartilha de fisioterapia usando este prompt:"
3. **Receba o HTML completo**
4. **Salve como `cartilha.html`**
5. **Abra no navegador para visualizar**
6. **Ajuste conforme necessário**

---

**Última atualização:** 2025-01-27
**Baseado em:** Site da Dra. Laice Cunha (https://dralaicecunha.com.br/)
**Estrutura original:** PROMPT_DESIGN_FRONTEND.md

