# Documentação do Projeto: Landing Page - Corinthians

## 1. Objetivo da Atividade
Desenvolver uma landing page com tema livre para treinar habilidades de front-end básico (HTML/CSS), desenvolver repertório visual (IDV) e, principalmente, documentar a comunicação com a IA (Prompt Engineering / "Vibecode"). 

## 2. Tema e Escopo
* **Tema Principal:** Futebol Brasileiro.
* **Foco:** Uma vitória recente e fictícia do Corinthians.
* **Restrição Técnica:** Dados mockados diretamente no código. Proibido o uso de chamadas de API externas para forçar o foco na marcação e estilização.

## 3. Decisões de Design (IDV)
* **Estilo Visual:** Minimalista, limpo e direto. Evitar elementos visuais poluídos ou estética "tecnológica" excessiva.
* **Referência:** Site oficial do "Fiel Torcedor".
* **Paleta de Cores:**
  * **Fundo Principal:** Preto (`#000000`)
  * **Fundo Secundário:** Chumbo/Cinza Escuro (`#1A1A1A`)
  * **Texto Principal:** Branco (`#FFFFFF`) para alto contraste e legibilidade.
  * **Destaques (Botões/Links):** Dourado/Amarelo, remetendo à identidade premium do Fiel Torcedor.

## 4. Estrutura da Página e Decisões Técnicas
A página será construída utilizando **HTML5 Semântico** rigoroso e **CSS3 puro** (sem frameworks como Bootstrap ou Tailwind).

**Mapeamento de Seções:**
1. `<header>`: Cabeçalho com o título/logo fictício "Timão News".
2. `<main>`: Conteúdo principal da página.
   * `<section id="hero">`: Destaque principal com manchete de impacto sobre a vitória da semana passada e um parágrafo curto descrevendo o clima da partida.
   * `<section id="detalhes">`: Resumo da partida, contendo um placar fictício centralizado (ex: Corinthians 3 x 0 Rival) e uma lista semântica (`<ul>` ou `<dl>`) com os autores dos gols.
3. `<footer>`: Rodapé contendo um botão de Call to Action (CTA) "Cadastre-se no Fiel Torcedor" e os créditos de desenvolvimento do projeto.

## 5. Estratégia de Comunicação com a IA (Vibecode)
Para garantir que a IA gere um código que atenda às expectativas sem a necessidade de múltiplos retrabalhos, o prompt inicial foi estruturado utilizando as seguintes técnicas:
* **Definição de Papel:** Atribuir à IA a persona de um "desenvolvedor front-end sênior".
* **Restrições Claras:** Especificar o uso de HTML semântico, CSS puro e a proibição de APIs.
* **Direcionamento Visual:** Detalhar a paleta de cores em hexadecimal e o estilo minimalista.
* **Estrutura por Tópicos:** Listar exatamente as tags semânticas esperadas para cada bloco de conteúdo.

### 5.1. Prompt Inicial Registrado
> "Atue como um desenvolvedor front-end sênior. Crie uma landing page responsiva usando HTML5 semântico e CSS3 puro, sem frameworks e sem chamadas de API externas (dados mockados).
> 
> **Tema:** Uma vitória fictícia recente do Corinthians no campeonato brasileiro.
> 
> **Diretrizes de Design (IDV):** Estilo minimalista e limpo, inspirado no site do Fiel Torcedor. Evite elementos visuais excessivamente tecnológicos ou poluídos. 
> **Paleta de cores:** Fundos escuros (Preto `#000000` e Chumbo `#1A1A1A`), texto principal em Branco (`#FFFFFF`) e cor de destaque para botões e links em Dourado/Amarelo.
> 
> **Estrutura Obrigatória (Semântica):**
> 1. `<header>`: Título/Logo em texto "Timão News".
> 2. `<section>` principal (Hero): Manchete de impacto sobre a vitória da semana passada e um parágrafo curto descrevendo o clima da partida.
> 3. `<section>` de detalhes: Um placar fictício centralizado (ex: Corinthians 3 x 0 Rival) e uma lista com os autores dos gols.
> 4. `<footer>`: Um botão de CTA "Cadastre-se no Fiel Torcedor" e os créditos do projeto.
> 
> Entregue o código completo e estruturado para o index.html e o style.css (ou tudo em um único arquivo HTML, caso prefira)."