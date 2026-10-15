# Spec de Desenvolvimento: Landing Page "Timão News"

## 1. Visão Geral
Este documento especifica os requisitos para a criação de uma landing page responsiva, focada em uma notícia de vitória fictícia do Sport Club Corinthians Paulista. O objetivo é aplicar conhecimentos de HTML5 e CSS3 puro.

## 2. Estrutura de Arquivos Exigida
O projeto deve estritamente seguir a seguinte estrutura de diretórios e arquivos:
```text
/ (raiz do projeto)
├── index.html
└── css/
    └── style.css
```

## 3. Requisitos Técnicos
*   **HTML:** Utilizar HTML5 Semântico (`<header>`, `<main>`, `<section>`, `<footer>`, etc.).
*   **CSS:** CSS3 puro, sem o uso de frameworks (como Tailwind ou Bootstrap).
*   **Responsividade:** O layout deve se adaptar a dispositivos móveis e desktops utilizando Media Queries flexíveis (Mobile First recomendado).
*   **Dados:** Todo o conteúdo deve ser *mockado* (inserido estaticamente no HTML). Nenhuma API externa deve ser consumida.
*   **Fontes:** Recomenda-se o uso de uma fonte sem serifa limpa (ex: Roboto, Helvetica, Arial) importada via Google Fonts.

## 4. Identidade Visual (IDV) e Paleta de Cores
O design deve ser minimalista, limpo e escuro, inspirado na estética do portal "Fiel Torcedor".

*   **Cor de Fundo Principal:** Preto (`#000000`)
*   **Cor de Fundo Secundária/Containers:** Chumbo/Cinza Escuro (`#1A1A1A`)
*   **Cor do Texto Principal:** Branco (`#FFFFFF`)
*   **Cor de Destaque (Ações/Botões/Links):** Dourado/Amarelo (`#D4AF37` ou similar, remetendo a ouro/glória).

## 5. Estrutura de Conteúdo (Wireframe Lógico)

### 5.1 `index.html`
O documento deve conter as seguintes áreas lógicas:

1.  **`<header>`**
    *   Deve conter a marca ou título: "Timão News".
2.  **`<main>`**
    *   **`<section id="hero">`**: Manchete principal em `<h1>` anunciando a vitória heroica da semana passada. Um parágrafo curto (`<p>`) com a linha de apoio descrevendo a festa da torcida.
    *   **`<section id="match-details">`**: 
        *   Um placar centralizado e em destaque (ex: Corinthians 3 x 0 Adversário Fictício).
        *   Uma lista semântica (`<ul>` ou `<dl>`) listando os autores dos gols e os minutos.
3.  **`<footer>`**
    *   Um botão de CTA (Call to Action) chamativo com o texto "Cadastre-se no Fiel Torcedor".
    *   Créditos do desenvolvedor em texto menor.

## 6. Instruções para o Bot Desenvolvedor
1. Leia esta especificação completamente.
2. Gere o código finalizado para `index.html` e `css/style.css` garantindo a ligação correta (`<link rel="stylesheet" href="css/style.css">`).
3. Assegure que as cores de contraste atendam a requisitos básicos de acessibilidade visual.
4. Mantenha o código indentado e comentado onde achar necessário.