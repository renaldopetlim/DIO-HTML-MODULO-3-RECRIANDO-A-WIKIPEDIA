# Módulo 3 - Campeonato Mundial de Fórmula 1 de 2025
Este repositório contém a estrutura HTML e a estilização CSS para uma página informativa sobre o Campeonato Mundial de Fórmula 1 de 2025.

## 📌 Tecnologias Utilizadas:
- HTML5
- CSS3
- Google Fonts

## 📁 Estrutura do Projeto:
### Arquivos Principais:
- `index.html` → Estrutura da página.
- `style.css` → Estilização do site.

## Estrutura do HTML:
A página contém os seguintes elementos principais:
- **Header:** Contém a logo, wordmark, tagline e barra de pesquisa.
- **Aside:** Menu lateral com links para diferentes seções do conteúdo.
- **Main:** Artigos com informações detalhadas sobre o campeonato.
- **Tabelas:** Apresentação de equipes, pilotos e calendário de corridas.
- **Footer:** Informações sobre edição e propósito da página.

## 🎨 Estilização (CSS)
- Uso da fonte `PT Serif` via Google Fonts.
- Layout responsivo utilizando `grid` e `flexbox`.
- Cores suaves e estruturadas para melhor legibilidade.
- O código CSS é dividido por seções, separadas por comentários `/* --""-- */`, para facilitar a manutenção e leitura do código.

### Cabeçalho (`#header`)
- Configurado como `fixed` para manter-se visível durante a rolagem.
- Contém uma logo e uma caixa de pesquisa com um botão.

### Layout Principal (`#main`)
- Utiliza `grid-template-columns` para dividir a tela entre a barra lateral (`.aside`) e o conteúdo principal (`.article`).
- A barra lateral possui links organizados em uma estrutura de grade.
- O conteúdo principal possui estilos específicos para títulos, textos e tabelas.

### Rodapé (`#footer`)
- Contém informações de rodapé com um tamanho de fonte reduzido.

Link: https://f1-2025.netlify.app/
