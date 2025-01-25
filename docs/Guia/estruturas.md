# Estruturas e Padrões de Acessibilidade

## 7.1. Uso Correto de HTML Semântico

O **HTML semântico** organiza o conteúdo de forma lógica e compreensível tanto para navegadores quanto para tecnologias assistivas, como leitores de tela. 

- Tags como `<header>`, `<main>`, `<footer>`, `<article>` e `<section>` tornam o código mais legível e ajudam na navegação.  
- Seu uso correto melhora a experiência de todos os usuários, especialmente aqueles com deficiência visual, permitindo que compreendam a hierarquia e a função de cada elemento no site.  
- **Evite** o uso de tags genéricas como `<div>` e `<span>` para funções estruturais.

---

## 7.2. Estruturação de Páginas

A organização clara da página é essencial para garantir acessibilidade.

- **Cabeçalhos**:  
  Devem seguir uma hierarquia lógica, começando com `<h1>` e descendo gradualmente. Isso facilita a navegação, especialmente com leitores de tela.

- **Listas**:  
  Use `<ul>` para listas não ordenadas, `<ol>` para listas ordenadas e `<dl>` para listas de definições. Elas estruturam o conteúdo de forma acessível.

- **Links**:  
  Textos de links devem ser descritivos, indicando claramente o destino. Evite expressões genéricas como “clique aqui”.

- **Formulários**:  
  - Cada campo deve ser claramente identificado com `<label>`.  
  - Erros devem ser apresentados com mensagens claras.  
  - Atributos como `aria-required` e `aria-describedby` melhoram a usabilidade para usuários com deficiência.

---

## 7.3. Acessibilidade em Mídia

Os recursos multimídia devem ser acessíveis para todos os usuários. Aqui estão as práticas recomendadas para diferentes tipos de mídia:

### Imagens
- Inclua descrições nos atributos `alt` para explicar o conteúdo visual.
- Para imagens decorativas, use `alt=""` para que sejam ignoradas por leitores de tela.

### Vídeos
- **Legendas sincronizadas** são essenciais para usuários surdos ou com dificuldades auditivas.
- **Transcrições completas** devem ser fornecidas para permitir acesso ao conteúdo em formato textual.
- **Áudio-descrição** deve ser adicionada para narrar informações visuais importantes que não estão disponíveis no áudio principal.
- Certifique-se de que os controles do player de vídeo sejam acessíveis, permitindo uso fácil por todos os usuários.

### Áudios
- Forneça **transcrições** detalhadas para todo o conteúdo em áudio.
- Garanta que os controles do player de áudio sejam fáceis de operar, mesmo para usuários com deficiências motoras.
- Considere o impacto do uso de sons contínuos ou intensos para usuários sensíveis, como aqueles com autismo.



---

## 7.4. Acessibilidade Móvel

Em dispositivos móveis, o design deve ser **responsivo** e **intuitivo**.

- Diretrizes de acessibilidade, como **WCAG** e **WAI-ARIA**, ajudam a criar experiências inclusivas.
- **Botões e áreas de toque**:  
  Devem ser grandes o suficiente para evitar erros.
- **Contraste adequado**:  
  Garante a legibilidade do conteúdo.
- O atributo **viewport** no HTML é útil para ajustar o zoom e o layout em diferentes tamanhos de tela.
- Ferramentas como **VoiceOver (iOS)** e **TalkBack (Android)** podem ser usadas para testar a acessibilidade em dispositivos móveis.
