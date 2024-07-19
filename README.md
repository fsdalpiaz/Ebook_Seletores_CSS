# Ebook_Seletores_CSS
Ebook generated with AI and managed by human. Get ready to know about some CSS selectors

# eBook: Principais Seletores CSS com Exemplos Reais
## Introdução
CSS (Cascading Style Sheets) é uma linguagem essencial para a estilização de páginas web. Dominar seus seletores é fundamental para aplicar estilos de forma eficiente e precisa. Este eBook apresenta os principais seletores CSS com exemplos práticos, explicados de maneira simples.

## 1. Seletor de Elemento
O seletor de elemento aplica estilos a todas as ocorrências de um determinado elemento HTML.  

css

/* Aplica uma cor azul a todos os parágrafos */
p {
  color: blue;
}
Exemplo Real:
-----------------------------------
html

<!DOCTYPE html>
<html>
<head>
  <style>
    p {
      color: blue;
    }
  </style>
</head>
<body>
  <p>Este é um parágrafo estilizado com CSS.</p>
  <p>Outro parágrafo que será azul.</p>
</body>
</html>  

## 2. Seletor de Classe
O seletor de classe aplica estilos a elementos que possuem um atributo class específico.
----------------------------
css

/* Aplica um fundo amarelo a todos os elementos com a classe "highlight" */
.highlight {
  background-color: yellow;
}  
Exemplo Real:
---------------------------------
html


<!DOCTYPE html>
<html>
<head>
  <style>
    .highlight {
      background-color: yellow;
    }
  </style>
</head>
<body>
  <p class="highlight">Este parágrafo está destacado.</p>
  <p>Este parágrafo não está destacado.</p>
</body>
</html>
3. Seletor de ID
O seletor de ID aplica estilos a um elemento único com um atributo id.
--------------------------------
css

/* Aplica uma cor vermelha ao elemento com o ID "header" */
#header {
  color: red;
}
Exemplo Real:
-------------------------------
html

<!DOCTYPE html>
<html>
<head>
  <style>
    #header {
      color: red;
    }
  </style>
</head>
<body>
  <h1 id="header">Este é o cabeçalho da página.</h1>
  <p>Texto normal da página.</p>
</body>
</html>

## 4. Seletor de Atributo
O seletor de atributo aplica estilos a elementos que possuem um atributo específico.

css
Copiar código
/* Aplica um estilo itálico aos links que abrem em uma nova aba */
a[target="_blank"] {
  font-style: italic;
}
Exemplo Real:

html
Copiar código
<!DOCTYPE html>
<html>
<head>
  <style>
    a[target="_blank"] {
      font-style: italic;
    }
  </style>
</head>
<body>
  <a href="https://www.example.com" target="_blank">Link externo</a>
  <a href="https://www.example.com">Link interno</a>
</body>
</html>
5. Seletor Descendente
O seletor descendente aplica estilos a elementos que são descendentes de outro elemento.

css
Copiar código
/* Aplica um tamanho de fonte maior aos parágrafos dentro de divs */
div p {
  font-size: 18px;
}
Exemplo Real:

html
Copiar código
<!DOCTYPE html>
<html>
<head>
  <style>
    div p {
      font-size: 18px;
    }
  </style>
</head>
<body>
  <div>
    <p>Parágrafo dentro de uma div.</p>
  </div>
  <p>Parágrafo fora de uma div.</p>
</body>
</html>
6. Seletor de Pseudo-Classe
Pseudo-classes permitem estilizar elementos com base em seu estado.

css
Copiar código
/* Altera a cor dos links quando o mouse passa sobre eles */
a:hover {
  color: green;
}
Exemplo Real:

html
Copiar código
<!DOCTYPE html>
<html>
<head>
  <style>
    a:hover {
      color: green;
    }
  </style>
</head>
<body>
  <a href="https://www.example.com">Passe o mouse sobre este link.</a>
</body>
</html>
7. Seletor de Pseudo-Elemento
Pseudo-elementos permitem estilizar partes específicas de um elemento.

css
Copiar código
/* Adiciona conteúdo antes de um parágrafo */
p::before {
  content: "Nota: ";
  font-weight: bold;
}
Exemplo Real:

html
Copiar código
<!DOCTYPE html>
<html>
<head>
  <style>
    p::before {
      content: "Nota: ";
      font-weight: bold;
    }
  </style>
</head>
<body>
  <p>Este parágrafo tem uma nota antes dele.</p>
</body>
</html>
Conclusão
Conhecer e utilizar corretamente os seletores CSS é crucial para criar páginas web bem estilizadas e funcionais. Experimente aplicar esses seletores em seus próprios projetos para ver o impacto direto na aparência de suas páginas.
