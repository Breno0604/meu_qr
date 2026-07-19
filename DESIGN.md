---
name: QR Code
description: Ferramenta QR Code de precisão — leitura e geração instantâneas, sem cadastro, sem dados na nuvem.
colors:
  primary: "#0040a0"
  primary-deep: "#003380"
  neutral-bg: "#f5f5f7"
  neutral-surface: "#ffffff"
  neutral-border: "#d1d1d6"
  neutral-muted: "#8e8e93"
  neutral-text: "#1d1d1f"
  neutral-text-secondary: "#3a3a3c"
  neutral-text-tertiary: "#515154"
  neutral-hover: "#e8e8ed"
  critical: "#c6201a"
  critical-deep: "#a31b16"
  success: "#34c759"
typography:
  body:
    fontFamily: "-apple-system, BlinkMacSystemFont, 'Helvetica Neue', 'Segoe UI', Roboto, Arial, sans-serif"
    fontSize: "0.9375rem"
    fontWeight: 400
    lineHeight: 1.5
  display:
    fontFamily: "-apple-system, BlinkMacSystemFont, 'Helvetica Neue', 'Segoe UI', Roboto, Arial, sans-serif"
    fontSize: "1.5rem"
    fontWeight: 600
    lineHeight: 1.25
    letterSpacing: "-0.02em"
  headline:
    fontFamily: "-apple-system, BlinkMacSystemFont, 'Helvetica Neue', 'Segoe UI', Roboto, Arial, sans-serif"
    fontSize: "1.25rem"
    fontWeight: 600
    lineHeight: 1.3
    letterSpacing: "-0.02em"
  title:
    fontFamily: "-apple-system, BlinkMacSystemFont, 'Helvetica Neue', 'Segoe UI', Roboto, Arial, sans-serif"
    fontSize: "1rem"
    fontWeight: 500
    lineHeight: 1.4
  label:
    fontFamily: "-apple-system, BlinkMacSystemFont, 'Helvetica Neue', 'Segoe UI', Roboto, Arial, sans-serif"
    fontSize: "0.8125rem"
    fontWeight: 500
    lineHeight: 1.4
  caption:
    fontFamily: "-apple-system, BlinkMacSystemFont, 'Helvetica Neue', 'Segoe UI', Roboto, Arial, sans-serif"
    fontSize: "0.75rem"
    fontWeight: 400
    lineHeight: 1.4
rounded:
  sm: "6px"
  md: "10px"
  lg: "12px"
  xl: "16px"
  app: "20px"
spacing:
  xs: "4px"
  sm: "8px"
  md: "16px"
  lg: "24px"
  xl: "32px"
components:
  button-primary:
    backgroundColor: "{colors.primary}"
    textColor: "{colors.neutral-surface}"
    rounded: "{rounded.md}"
    padding: "10px 20px"
  button-primary-hover:
    backgroundColor: "{colors.primary-deep}"
    textColor: "{colors.neutral-surface}"
    rounded: "{rounded.md}"
    padding: "10px 20px"
  button-secondary:
    backgroundColor: "{colors.neutral-hover}"
    textColor: "{colors.neutral-text}"
    rounded: "{rounded.md}"
    padding: "10px 20px"
  button-secondary-hover:
    backgroundColor: "{colors.neutral-border}"
    textColor: "{colors.neutral-text}"
    rounded: "{rounded.md}"
    padding: "10px 20px"
  button-danger:
    backgroundColor: "{colors.critical}"
    textColor: "{colors.neutral-surface}"
    rounded: "{rounded.md}"
    padding: "10px 20px"
  button-danger-hover:
    backgroundColor: "{colors.critical-deep}"
    textColor: "{colors.neutral-surface}"
    rounded: "{rounded.md}"
    padding: "10px 20px"
  input-text:
    backgroundColor: "{colors.neutral-surface}"
    textColor: "{colors.neutral-text}"
    rounded: "{rounded.lg}"
    padding: "12px 16px"
  card:
    backgroundColor: "{colors.neutral-surface}"
    textColor: "{colors.neutral-text}"
    rounded: "{rounded.xl}"
    padding: "32px 28px"
  tab:
    backgroundColor: "transparent"
    textColor: "{colors.neutral-text-tertiary}"
    rounded: "{rounded.md}"
    padding: "10px 0"
  tab-active:
    backgroundColor: "{colors.neutral-surface}"
    textColor: "{colors.neutral-text}"
    rounded: "{rounded.md}"
    padding: "10px 0"
---

# Design System: QR Code

## 1. Overview

**Creative North Star: "O Relojoeiro Suíço"**

Precisão alemã com alma japonesa. Funcionalidade como estética. Este sistema visual existe para desaparecer na tarefa — o usuário lê ou gera um QR Code e segue com a vida. Cada elemento é um instrumento calibrado, não uma decoração.

O app rejeita propagandas, pop-ups, cadastros e dados na nuvem. Rejeita interfaces cluttered com muitas opções. Rejeita o design genérico de "app de QR Code" que parece todos os outros. A identidade é construída sobre silêncio funcional: o design fala menos para que o usuário faça mais.

**Key Characteristics:**
- Silêncio funcional — elementos existem apenas quando precisam existir
- Precisão milimétrica — cada pixel tem um propósito
- Feedback sutil — confirmação visual sem drama
- Confiabilidade mecânica — a interface transmite que funciona

## 2. Colors

Paleta técnica e contida. Uma cor de ação primária, neutros precisos, sem floreios cromáticos.

### Primary
- **Azul Técnico** (#0040a0): Ação primária, links, indicadores de estado ativo. Usado com moderação — menos de 10% da superfície. Raridade é o ponto.
- **Azul Profundo** (#003380): Estado hover do primário. Transição suave, sem salto cromático.

### Neutral
- **Cinza Pedra** (#f5f5f7): Fundo principal. Neutro frio sem temperatura — não é cream, não é azulado. É cinza.
- **Superfície** (#ffffff): Containers, cards, inputs. Elevação por contraste com o fundo.
- **Cinza Grafite** (#d1d1d6): Bordas, divisores, secundário. Estrutura visual sem peso.
- **Cinza Silêncio** (#8e8e93): Placeholders, texto desabilitado. Presente mas não compete.
- **Texto Primário** (#1d1d1f): Corpo, títulos. Alta contraste, sem negociação.
- **Texto Secundário** (#3a3a3c): Descrições, status. Hierarquia clara.
- **Texto Terciário** (#515154): Labels, badges. Hierarquia menor.
- **Hover** (#e8e8ed): Estado hover de listas e itens interativos. Feedback tátil.

### Critical
- **Vermelho Crítico** (#c6201a): Ações destrutivas, erros, alertas. Nunca decorativo.
- **Vermelho Profundo** (#a31b16): Estado hover do crítico.

### Success
- **Verde Confirmação** (#34c759): Feedback de sucesso, flash de leitura. Uso pontual.

### Named Rules
**The 10% Rule.** O azul primário é usado em ≤10% de qualquer tela. Sua raridade é o ponto. Se tudo é azul, nada é azul.

## 3. Typography

**Display Font:** Sistema (SF Pro / system-ui)
**Body Font:** Sistema (SF Pro / system-ui)

**Character:** Uma família, múltiplos pesos. A tipografia é um instrumento, não uma voz. Sem pareamento serif/sans, sem display fonts, sem personalidade visual. A personalidade está na precisão, não no traço.

### Hierarchy
- **Display** (600, 1.5rem / 24px, -0.02em): Título principal do app. Aparece uma vez.
- **Headline** (600, 1.25rem / 20px, -0.02em): Títulos de seção. Hierarquia clara.
- **Title** (500, 1rem / 16px): Títulos de componente, labels de card.
- **Body** (400, 0.9375rem / 15px, 1.5): Texto corrido, descrições, resultados.
- **Label** (500, 0.8125rem / 13px): Botões, tabs, badges. Ações interativas.
- **Caption** (400, 0.75rem / 12px): Timestamps, contadores, metadata.

### Named Rules
**The Instrument Rule.** A tipografia nunca chama atenção para si mesma. Se o usuário percebe a fonte, algo está errado. A hierarquia é feita por peso e tamanho, nunca por estilo decorativo.

## 4. Elevation

Híbrido: plano por padrão, sombras sutis em containers importantes. A profundidade é comunicada por contraste de cor (Cinza Pedra vs. Superfície), não por sombras decorativas.

### Shadow Vocabulary
- **Ambient** (`box-shadow: 0 2px 20px rgba(0,0,0,0.04), 0 1px 3px rgba(0,0,0,0.02)`): Container principal (app card). Presença sutil, não dramática.
- **Interactive** (`box-shadow: 0 1px 3px rgba(0,0,0,0.04)`): Cards ativos, tabs selecionados. Estado, não decoração.
- **Tooltip** (`box-shadow: 0 4px 20px rgba(0,0,0,0.15)`): Toast, tooltip. Camada superior, comunicar urgência.

### Named Rules
**The Flat-By-Default Rule.** Superfícies são planas em repouso. Sombras aparecem apenas como resposta a estado (hover, elevação, foco). Nunca como ornamento.

## 5. Components

Componentes refinados e contidos. Cada interação tem feedback claro sem drama. A elegância está na simplicidade mecânica.

### Buttons
- **Shape:** Arredondamento médio (10px radius). Nem quadrado, nem pill.
- **Primary:** Azul Técnico (#0040a0) com texto branco. Padding 10px 20px. Transição 0.2s ease.
- **Hover / Focus:** Escurece para Azul Profundo (#003380). Scale 0.97 no active. Sem bounce.
- **Secondary:** Cinza Hover (#e8e8ed) com texto escuro. Mesma geometria.
- **Danger:** Vermelho Crítico (#c6201a). Usado apenas para ações destrutivas.
- **Disabled:** Opacidade 0.4. Cursor not-allowed. Sem transform.

### Inputs
- **Style:** Borda 1.5px Cinza Grafite (#d1d1d6), fundo levementeacinzentado (#fafafa). Radius 12px.
- **Focus:** Borda muda para Azul Técnico (#0040a0). Fundo fica branco. Transição suave.
- **Placeholder:** Cinza Silêncio (#8e8e93). Contraste adequado, não desbotado.

### Tabs
- **Style:** Container com fundo Cinza Pedra (#f5f5f7). Tabs internas com radius 10px.
- **Active:** Fundo branco com sombra sutil. Texto escuro.
- **Inactive:** Texto cinza médio. Hover escurece levemente.

### Cards / Containers
- **Corner Style:** Radius 16px (containers), 20px (app principal).
- **Background:** Superfície (#ffffff) sobre Cinza Pedra (#f5f5f7).
- **Shadow Strategy:** Ambient shadow no container principal. Cards internos sem shadow.
- **Border:** Sem borda visível. Profundidade por contraste de cor.
- **Internal Padding:** 32px 28px (app), 24px (seções internas).

### Toast
- **Style:** Fundo escuro (#1d1d1f), texto branco. Radius 12px. Posição fixa inferior.
- **Animation:** Slide up + fade in (0.35s ease). Desaparece após 2.8s.

### Scan Overlay
- **Style:** Linha animada Azul Técnico com gradiente. Bordas de referência translúcidas.
- **Feedback:** Flash verde (#34c759) na leitura bem-sucedida. Duração 0.2s.

## 6. Do's and Don'ts

### Do:
- **Do** manter o azul primário em ≤10% da superfície — raridade comunica importância
- **Do** usar sistema de fontes (SF Pro / system-ui) — confiabilidade mecânica
- **Do** aplicar sombras apenas em estado interativo — flat-by-default
- **Do** manter transições em 200ms — feedback sem espera
- **Do** usar alta contraste no texto (#1d1d1f em fundo claro) — legibilidade não negocial
- **Do** implementar modo alto contraste para acessibilidade — preto absoluto, branco absoluto
- **Do** manter border-radius consistente (10px para interativos, 12-20px para containers)
- **Do** dar feedback visual em cada interação (hover, active, focus) — o usuário sabe que clicou

### Don't:
- **Don't** usar propagandas, pop-ups ou cadastros — anti-referência direta do PRODUCT.md
- **Don't** criar interfaces cluttered com muitas opções — simplicidade radical
- **Don't** enviar dados para servidores — privacidade por padrão
- **Don't** usar design genérico de "app de QR Code" — cada elemento deve ser intencional
- **Don't** usar gradient text (background-clip: text) — decorativo, nunca significativo
- **Don't** usar glassmorphism como padrão — blur decorativo é proibido
- **Don't** colocar sombras em todo lugar — sombras são para estado, não ornamento
- **Don't** usar fontes display em labels ou botões — instrumentos, não vozes
- **Don't** animar propriedades de layout — motion é para estado, não decoração
- **Don't** criar modais como primeiro pensamento — inline/progressive primeiro
- **Don't** usar cores saturadas em estados inativos — confunde a hierarquia
- **Don't** inventar affordances padrão — scrollbars custom, controles estranhos
