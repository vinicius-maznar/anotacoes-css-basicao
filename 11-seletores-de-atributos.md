# 👉🎯 Seletores de Atributos em CSS

Os seletores de atributos em CSS permitem selecionar elementos HTML com base em atributos específicos. Eles oferecem uma maneira flexível de aplicar estilos com base em características dos elementos. Abaixo estão os pontos-chave sobre seletores de atributos:

## 🤷‍♂️ O que é um Seletor de Atributo?
- Um seletor de atributo é usado para selecionar elementos HTML com base nos valores de seus atributos.
- Permite direcionar elementos com atributos específicos, independentemente do valor do atributo.

## 📝 Sintaxe de um Seletor de Atributo
- Para selecionar elementos por atributo, você usa colchetes [] com o nome do atributo ou o atributo com um valor específico.
- Exemplo: `input[type="text"] { border: 1px solid #ccc; }` estiliza campos de texto.

## 🌟 Seleção de Atributos com Valores Específicos
- É possível selecionar elementos com atributos que tenham valores específicos, como IDs, classes ou valores personalizados.
- Exemplo: `a[target="_blank"] { text-decoration: underline; }` estiliza links com `target="_blank"`.

## 🕵️ Seleção de Atributos que Contêm um Valor
- Você pode selecionar elementos com atributos que contenham um valor específico, independentemente do valor completo.
- Exemplo: `[href*="example.com"] { color: #FF6600; }` estiliza links que contenham "example.com" no atributo "href".

## ✅ Seleção de Atributos que Iniciam com um Valor
- É possível selecionar elementos com atributos que comecem com um valor específico.
- Exemplo: `[src^="https://"] { border: 2px solid #008CBA; }` estiliza elementos com atributos "src" que começam com "https://".

## 🛡️ Seleção de Atributos que Terminam com um Valor
- Você pode selecionar elementos com atributos que terminam com um valor específico.
- Exemplo: `[src$=".jpg"] { max-width: 100%; }` estiliza elementos com atributos "src" que terminam com ".jpg".

## 🔍👇 Seleção de Atributos com Valores Exatos
- Você pode selecionar elementos com atributos que tenham um valor exato, sem considerar outros caracteres.
- Exemplo: `[type="button"] { background-color: #333; }` estiliza botões com o atributo "type" igual a "button".

## 📌

Os seletores de atributos em CSS são uma ferramenta poderosa para estilizar elementos com base em características específicas, como atributos HTML. Eles fornecem flexibilidade e precisão ao aplicar estilos em páginas da web.

## 📌
