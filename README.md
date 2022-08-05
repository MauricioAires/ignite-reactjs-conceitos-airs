

<img src=".github/cover-reactjs.png" alt="ignite">

<h1 align="center">
  🚀 Conceitos ReactJS 🚀

</h1>


<h2 align="center">
  Sobre 🤓
</h2>

<p>
  Nesse desafio, foi criado uma aplicação para treinar o que aprendi até agora no ReactJS

O principal objetivo desse projeto é uma pequena aplicação de atividades a fazer, para treinar um pouco mais sobre manipulação do estado no React.

- Adicionar uma nova tarefa
- Remover uma tarefa
- Marcar e desmarcar uma tarefa como concluída

</p>

<h2 align="center">
  🔍 Revisão Relâmpago ⚡
</h2>
<ul>
<li>
  <Strong>Componentes</Strong>: Unidades isoláveis e funcionais de JSX e estilização
  
  ```javascript
  function Header() {
      return (
        <header>
          Conteúdo do Cabeçalho
        </header>
      )
    }
  ```
</li>
<li>
  <Strong>Propriedades</Strong>: Valores passados como parâmetros, de um componente a outro
  
  ```javascript
  function App() {
    return <Header title="ReactJS" />
  }
  ```
  ```javascript
  function Header(props) {
      return <header>{props.title}</header>
    }
  ```
</li>
<li>
  <Strong>Estado e imutabilidade</Strong>: O estado de um componente é o valor de determinadas variáveis internas, de acordo com o contexto. Esses valores, por sua vez <em>só</em> devem ser alterados com as funções 'setNomeDoEstado' (imutabilidade)
  
  ```javascript
    import React, { useState } from 'react';

    function App() {
      const [title, setTitle] = useState('');

      return <Header title={title} />
    }
  ```
</li>
</ul>

