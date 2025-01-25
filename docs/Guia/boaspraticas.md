# Boas Práticas para Designers e Desenvolvedores

A acessibilidade digital garante que todas as pessoas, incluindo idosos e usuários com limitações temporárias ou permanentes, possam interagir com interfaces de forma eficiente. Designers e desenvolvedores devem aplicar diretrizes que tornem a experiência mais intuitiva e inclusiva.

Este tópico apresenta práticas essenciais para melhorar a acessibilidade, abordando contraste de cores e tipografia, navegação por teclado e em dispositivos móveis, descrições alternativas para imagens e legendas/transcrições para mídia.

---

## 8.1. Contraste de Cores e Tipografia Legível

Um bom contraste de cores e uma tipografia legível são essenciais para que todos os usuários possam ler e compreender o conteúdo sem esforço. Baixo contraste dificulta a leitura, especialmente para idosos, pessoas com baixa visão, daltonismo ou em condições de pouca iluminação.

### Contraste adequado:
- **Texto menor que 24px**: Deve ser pelo menos 4,5 vezes mais claro ou mais escuro que o fundo.
- **Texto grande (24px ou 18px em negrito)**: Pode ter um contraste menor, sendo 3 vezes mais claro ou mais escuro que o fundo.

Quanto maior a diferença, melhor será a legibilidade. Ferramentas online podem ajudar a verificar se a combinação de cores atende às normas de acessibilidade.

### Escolha da fonte:
- Prefira fontes **sem serifa** (como Arial ou Roboto), pois são mais fáceis de ler em telas.
- Evite fontes decorativas ou manuscritas.

### Tamanho e espaçamento:
- O tamanho mínimo recomendado para textos é **16px**, com espaçamento adequado entre letras e linhas para facilitar a leitura.

### Uso de cores:
- **Nunca use apenas cores para transmitir informações** (exemplo: erro exibido apenas em vermelho). Combine com ícones, padrões ou textos adicionais para garantir a compreensão por todos.

### Ferramentas para Teste:
- **WebAIM Contrast Checker** – Avalia se o contraste atende às normas de acessibilidade.
- **Contrast Ratio** – Calcula a relação de contraste entre texto e fundo.
- **Color Oracle** – Simula como pessoas com daltonismo percebem as cores.
- **Readability Test Tool** – Avalia a legibilidade do texto com base no tamanho e espaçamento.
- **Accessible Fonts Guide** – Guia prático para escolher fontes acessíveis.

---

## 8.2. Navegação por Teclado e Acessibilidade em Dispositivos Móveis

Interfaces acessíveis devem permitir que os usuários naveguem sem depender exclusivamente do mouse ou do toque na tela. Pessoas com limitações motoras, usuários de leitores de tela e quem utiliza apenas o teclado precisam de uma navegação eficiente.

### Práticas de navegação por teclado:
- **Suporte a teclado**: Todas as funcionalidades devem ser acessíveis pelo teclado, usando Tab para navegar e Enter/Espaço para acioná-las.
- **Foco visível**: Os elementos navegáveis devem ter um destaque visual claro (como borda ou mudança de cor) quando selecionados.
- **Evite armadilhas de teclado**: O usuário nunca deve ficar "preso" em um elemento sem possibilidade de continuar navegando.

### Práticas para dispositivos móveis:
- **Gestos acessíveis**: Ofereça alternativas a gestos complexos (como deslizar com vários dedos).
- **Tamanho dos elementos interativos**: Botões e links devem ter área mínima de 48x48 pixels.
- **Compatibilidade com tecnologias assistivas**: Garanta que leitores de tela consigam interpretar corretamente os elementos.

### Ferramentas para Teste:
- **WebAIM Keyboard Accessibility** – Guia para testar e melhorar a navegação pelo teclado.
- **Google Lighthouse** – Audita a acessibilidade, incluindo suporte a teclado.
- **WAVE Accessibility Tool** – Analisa páginas e aponta problemas de acessibilidade.
- **Google Mobile-Friendly Test** – Avalia responsividade e acessibilidade móvel.
- **axe DevTools** – Testa acessibilidade, incluindo interação por toque.
- **NVDA** (Windows), **VoiceOver** (macOS/iOS) e **TalkBack** (Android) – Leitores de tela para simulações.

---

## 8.3. Descrição Alternativa para Imagens (Textos Alternativos)

Imagens devem sempre ter uma descrição alternativa (alt text) para garantir que usuários com deficiência visual, leitores de tela e conexões lentas consigam compreender o conteúdo visual.

### Tipos de imagens e boas práticas

#### Imagens informativas
Use descrições objetivas que transmitam a mensagem da imagem.  

- **Exemplo ruim**: "Imagem de um gráfico".  
- **Exemplo bom**: "Gráfico de barras mostrando o crescimento das vendas em 2023, com aumento de 20% no último trimestre."

#### Imagens decorativas
Se a imagem não adiciona informação relevante, use o atributo `alt=""` para que seja ignorada por leitores de tela.

#### Botões e ícones gráficos
Descreva a função do elemento, não apenas a aparência.  

- **Exemplo ruim**: "Ícone de lupa".  
- **Exemplo bom**: "Botão para pesquisar produtos."

#### Diagramas e gráficos complexos
Para imagens com muitas informações, forneça uma descrição detalhada no conteúdo da página e inclua um resumo no atributo `alt`.


### Ferramentas para Teste:
- **WAVE Accessibility Tool** – Identifica imagens sem texto alternativo.
- **axe DevTools** – Analisa se todas as imagens possuem alt apropriado.
- **WebAIM Alt Decision Tree** – Guia interativo para decidir se uma imagem precisa de descrição.
- **NVDA**, **VoiceOver** e **TalkBack** – Teste com leitores de tela.

---

## 8.4. Implementação de Legendas e Transcrições para Mídia

Vídeos e áudios devem sempre incluir **legendas** e **transcrições** para garantir acessibilidade a pessoas surdas, com deficiência auditiva ou que preferem consumir conteúdo sem som.

### Boas práticas:
- **Legendas para vídeos**: Inclua diálogos, sons relevantes (ex.: "[aplausos]") e identificação dos falantes.
- **Transcrições para áudios**: Inclua todo o conteúdo falado e informações sonoras importantes.
- **Sincronização correta**: Legendas devem aparecer no momento exato do áudio correspondente.
- **Evite legendas automáticas sem revisão**: Revise para garantir precisão.
- **Opções de personalização**: Permita ajustes de tamanho, cor e fundo das legendas.

### Ferramentas para Teste:
- **YouTube Studio** – Criação e edição de legendas.
- **Amara** – Adição de legendas acessíveis.
- **VEED.IO** – Geração automática de legendas com opção de edição.
- **WAVE Accessibility Tool** – Detecta vídeos sem legendas.
- **axe DevTools** – Analisa acessibilidade geral de conteúdo multimídia.
- **Web Captioner** – Gera legendas ao vivo para falas.

Garanta que todos os conteúdos em vídeo e áudio sejam acessíveis, proporcionando uma experiência inclusiva para todos os usuários.
