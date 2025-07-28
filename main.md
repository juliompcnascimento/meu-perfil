# Tópicos da Página Principal

A página principal conterá as principais informações sobre mim e as seções de meu "currículo" profissional.


## Sumário

- [Tópicos da Página Principal](#tópicos-da-página-principal)


## Tópicos da Página Principal

- Apresentação contendo uma breve descrição sobre a carreira profissional e educacional como um todo.
- A seguir devem conter as sessões como que um currículo.
  - Formação:
    - Ensino médio-técnico integrado.
    - Ensino superior: graduação concluída e em curso.
    - Ensino de pós-gaduação pela Facuminas.
    - Outros cursos diversos.
  - Experiências:
    - Experiências profissionais como estágio e concurso.
    - Projetos diversos, como planilhas, aplicativos AppSheet, etc.
  - Habilidades:
    - Apresentar conteúdos que apresente domínio, como edição de planilhas (Google Sheets), usuário básico-intermediário de Linux, linguagens de programação que possui familiaridade, entre outras habilidades.
  - Sessão Pessoal:
    - Livros lidos.

## Dados para a Construção das Páginas

A página foi construída usando o *template* **Parallax** do site [Materialize CSS](https://materializecss.com/).

Para configurar e o usar as formatações do **Materialize CSS**, deve-se baixar o *template* acima além de outros arquivos. Veja a seguir.

1. Baixar o *template* em [materializecss.com/getting-started.html](https://materializecss.com/getting-started.html).
2. Estruturar a pasta do *Web Site* da seguinte forma:

```
 MyWebsite/
  |--css/
  |  |--materialize.css
  |
  |--fonts/
  |  |--roboto/
  |
  |--js/
  |  |--materialize.js
  |
  |--index.html
```

3. O arquivo `index.html` deve estar configurado da seguinte forma:

```html
<!DOCTYPE html>
<html>
  <head>
    <!--Import Google Icon Font-->
    <link href="https://fonts.googleapis.com/icon?family=Material+Icons" rel="stylesheet">
    <!--Import materialize.css-->
    <link type="text/css" rel="stylesheet" href="css/materialize.min.css"  media="screen,projection"/>

    <!--Let browser know website is optimized for mobile-->
    <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  </head>

  <body>

    <!--JavaScript at end of body for optimized loading-->
    <script type="text/javascript" src="js/materialize.min.js"></script>
  </body>
</html>
```

