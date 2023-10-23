# 🎨📂 Regras de Estilo em Arquivos Externos CSS

Como Desenvolvedor FrontEnd, é fundamental entender como criar e aplicar regras de estilo em arquivos CSS externos para manter seu código organizado. Aqui estão os pontos-chave:

## 📄🖥️ **Criação de Arquivos CSS Externos**

- Para criar um arquivo CSS externo, você cria um arquivo de texto com extensão ".css".
- Recomenda-se manter seu CSS separado do HTML para facilitar a manutenção.
- Um exemplo de arquivo CSS externo:

📌

  ```css
  /* styles.css */
  body {
    font-family: Arial, sans-serif;
    background-color: #f0f0f0;
  }
```

📌

## 📜 Regras de Estilo Internas

Dentro da tag `<style>`, você pode definir várias regras de estilo, como seletores, propriedades e valores. Isso permite estilizar elementos HTML de forma flexível.

## 🌟 Vantagens da Tag `<style>`

- A tag `<style>` permite estilos internos, o que significa que as regras de estilo são aplicadas apenas ao documento HTML em que estão definidas.
- É útil para estilos específicos de uma página ou seção.
- É uma alternativa quando não se deseja usar um arquivo CSS externo.

## 🚫 Limitações

- A tag `<style>` pode aumentar o tamanho do documento HTML, especialmente se houver muitas regras de estilo.
- Pode tornar o código HTML menos organizado quando há uma quantidade significativa de estilos.

## 🏁 Conclusão

A tag `<style>` é uma ferramenta valiosa para incorporar estilos diretamente em um documento HTML. Ela oferece flexibilidade e controle sobre a aparência de elementos HTML em uma página web, embora deva ser usada com moderação para manter a organização do código.
