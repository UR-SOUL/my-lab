---
name: Laboratório Químico Virtual
colors:
  surface: '#f9f9f9'
  surface-dim: '#dadada'
  surface-bright: '#f9f9f9'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f3f3f4'
  surface-container: '#eeeeee'
  surface-container-high: '#e8e8e8'
  surface-container-highest: '#e2e2e2'
  on-surface: '#1a1c1c'
  on-surface-variant: '#44474c'
  inverse-surface: '#2f3131'
  inverse-on-surface: '#f0f1f1'
  outline: '#74777d'
  outline-variant: '#c4c6cc'
  surface-tint: '#525f71'
  primary: '#000000'
  on-primary: '#ffffff'
  primary-container: '#0f1c2c'
  on-primary-container: '#778598'
  inverse-primary: '#bac8dc'
  secondary: '#006d3b'
  on-secondary: '#ffffff'
  secondary-container: '#62fb9f'
  on-secondary-container: '#00723e'
  tertiary: '#000000'
  on-tertiary: '#ffffff'
  tertiary-container: '#1a1c1a'
  on-tertiary-container: '#828481'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d6e4f9'
  primary-fixed-dim: '#bac8dc'
  on-primary-fixed: '#0f1c2c'
  on-primary-fixed-variant: '#3a4859'
  secondary-fixed: '#66fea2'
  secondary-fixed-dim: '#43e188'
  on-secondary-fixed: '#00210e'
  on-secondary-fixed-variant: '#00522b'
  tertiary-fixed: '#e2e3df'
  tertiary-fixed-dim: '#c6c7c3'
  on-tertiary-fixed: '#1a1c1a'
  on-tertiary-fixed-variant: '#454745'
  background: '#f9f9f9'
  on-background: '#1a1c1c'
  surface-variant: '#e2e2e2'
typography:
  display-lg:
    fontFamily: Inter
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Inter
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
  headline-lg-mobile:
    fontFamily: Inter
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  title-md:
    fontFamily: Inter
    fontSize: 20px
    fontWeight: '500'
    lineHeight: 28px
  body-lg:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  body-sm:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  label-caps:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '700'
    lineHeight: 16px
    letterSpacing: 0.05em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  base: 8px
  xs: 4px
  sm: 12px
  md: 24px
  lg: 40px
  xl: 64px
  container-max: 1280px
  gutter: 24px
---

## Brand & Style
O objetivo deste design system é transmitir precisão científica, clareza pedagógica e um ambiente de experimentação seguro. A personalidade da marca é **profissional, tecnológica e focada**, projetada para estudantes e pesquisadores que buscam uma interface que não interfira na cognição, mas que guie o usuário através de processos complexos.

O estilo visual adotado é o **Moderno/Corporativo com toques de Glassmorphism**. Utilizamos superfícies limpas e brancas para as áreas de trabalho, contrastando com um azul marinho profundo que evoca autoridade e seriedade acadêmica. Elementos de vidro e transparências sutis são aplicados para simular o ambiente de laboratório (vidraria e reatores), criando uma experiência imersiva e tátil dentro do ambiente digital.

## Colors
A paleta de cores foi selecionada para maximizar o foco e a legibilidade.

- **Primária (#0D1B2A):** Azul marinho profundo, utilizado para cabeçalhos, navegação principal e tipografia de alto nível. Transmite estabilidade e profundidade.
- **Acento/Sucesso (#3DDC84):** Verde vibrante, reservado para ações positivas, conclusões de experimentos bem-sucedidas e indicadores de "estado ativo".
- **Superfície (#FFFFFF):** Branco puro para o fundo das áreas de experimentação, garantindo que as cores das substâncias químicas sejam representadas com fidelidade.
- **Neutro/Bordas (#E0E1DD):** Um cinza azulado claro para divisores e estados desabilitados, mantendo a harmonia com o tom primário.

## Typography
A tipografia utiliza a família **Inter**, escolhida por sua legibilidade excepcional em telas e sua natureza sistemática. 

A hierarquia é rigorosa: usamos pesos mais pesados (Bold/SemiBold) para títulos e dados numéricos críticos, enquanto o corpo do texto permanece em peso regular para facilitar a leitura prolongada de manuais e procedimentos. O uso de `label-caps` é destinado a metadados técnicos e categorias de elementos químicos.

## Layout & Spacing
Este design system utiliza um **grid fluido de 12 colunas** para desktop e um grid de **4 colunas para mobile**. O sistema de espaçamento é baseado em uma unidade base de **8px**, garantindo proporções matemáticas consistentes.

Os painéis laterais (drawers) e áreas de controle ocupam colunas fixas (ex: 3 colunas para o menu de ferramentas), enquanto a área central de visualização do laboratório é totalmente fluida para permitir a observação detalhada de moléculas e reações. As margens de segurança para dispositivos móveis são fixadas em 16px.

## Elevation & Depth
A profundidade é comunicada através de **camadas tonais e sombras ambientes suaves**. 

1.  **Nível 0 (Fundo):** Superfície branca sólida.
2.  **Nível 1 (Cartões e Painéis):** Elevação sutil com bordas de 1px em `#E0E1DD` e uma sombra difusa de baixa opacidade para separar as instruções da área de trabalho.
3.  **Nível 2 (Componentes Interativos):** Elementos como menus suspensos e modais de erro/aviso utilizam um leve efeito de *backdrop-blur* (glassmorphism) para manter o contexto visual do laboratório ao fundo, enquanto priorizam a informação em primeiro plano.

## Shapes
As formas neste design system seguem o padrão **Rounded (Arredondado)**. 

- **Botões e Inputs:** Raio de 0.5rem (8px).
- **Painéis e Modais:** Raio de 1rem (16px) para suavizar a interface profissional e torná-la mais convidativa ao aprendizado.
- **Elementos de Vidraria:** Os ícones e representações de frascos devem ter curvas orgânicas que remetam ao vidro soprado, mantendo a precisão técnica.

## Components

### Botões
- **Primário:** Preenchimento total em `#0D1B2A` com texto branco. Estado de hover com leve clareamento.
- **Acento:** Preenchimento em `#3DDC84` para ações de "Misturar", "Aquecer" ou "Concluir".
- **Ghost:** Apenas contorno para ações secundárias, mantendo a leveza visual.

### Controles Deslizantes (Sliders)
Essenciais para temperatura e concentração. Devem possuir um "track" fino em cinza claro e um "thumb" (alça) circular e generoso em azul marinho. O valor numérico deve ser exibido em tempo real acima do polegar em um tooltip persistente.

### Painéis e Drawers
Os menus laterais utilizam um fundo levemente acinzentado ou branco com sombra direcional. Eles servem para organizar o inventário de substâncias e a lista de equipamentos.

### Vidraria (Ícones e Representações)
Estilo de contorno (outline) com traço de 1.5px. Devem parecer "transparentes", permitindo que a cor do reagente interno (em tons vibrantes de química orgânica) seja o foco visual.

### Cards de Substâncias
Devem exibir a fórmula molecular em negrito, o nome da substância e um pequeno ícone de perigo (pictogramas GHS) quando aplicável, organizados em uma estrutura de lista clara dentro dos drawers.