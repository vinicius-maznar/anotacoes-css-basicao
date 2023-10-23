# 🎨💡 Formas de Declaração no CSS

## 💭 **Conceito**
Como Desenvolvedor FrontEnd, é importante compreender as diferentes maneiras de declarar estilos em CSS. Aqui estão as formas fundamentais de declaração:

## 🎯 **Seletores Diretos**

- Os seletores diretos aplicam estilos a elementos específicos com base em seus nomes ou classes.
- Exemplo: `p { color: blue; }`, `.botao { background-color: #FF5733; }`.

## 🆔🔑 **Seletores de Classe e ID**

- Seletores de classe e ID permitem direcionar elementos com base em atributos `class` e `id`.
- Exemplo: `.destaque { font-weight: bold; }`, `#cabecalho { background-color: #333; }`.

## 🏢 **Seletores de Tipo**

- Seletores de tipo aplicam estilos a todos os elementos do mesmo tipo.
- Exemplo: `h1 { font-size: 24px; }`, `a { text-decoration: none; }`.

## 📝 **Seletores de Atributo**

- Seletores de atributo direcionam elementos com base em atributos específicos.
- Exemplo: `[href="https://www.example.com"] { color: green; }`.

## 🙅‍♂️📃 **Seletores Pseudo-Classe e Pseudo-Elemento**

- Pseudo-classes selecionam elementos em estados específicos (por exemplo, `:hover`).
- Pseudo-elementos estilizam partes específicas de um elemento (por exemplo, `::before`).
- Exemplo: `a:hover { color: red; }`, `p::before { content: "→"; }`.

## 💼 **Regras de Estilo Embutido**

- Regras de estilo embutido são definidas diretamente no elemento HTML usando o atributo `style`.
- Exemplo: `<div style="background-color: #FFFF00; padding: 10px;">Conteúdo</div>`.

## 🏛️ **Regras de Estilo Interno**

- Regras de estilo interno são definidas na seção `<style>` de um documento HTML.

📌

- Exemplo:
  ```html
  <style>
    p { color: purple; }
    .destaque { font-size: 18px; }
  </style>
    ```

📌
