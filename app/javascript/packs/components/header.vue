<template>
  <nav class="navbar navbar-expand-lg navbar-light bg-light">
  <div class="container">
    <h1><a class="navbar-brand" href="/">みんなのペット自慢</a></h1>

    <ul class="navbar-nav">
      <li class="nav-item">
        <a class="nav-link twitter-link" href="users/auth/twitter">Twitterログイン</a>
      </li>
    </ul>
  </div>
</nav>
</template>

<style scoped>
  h1 {
    font-family: 'ヒラギノ丸ゴ ProN','Hiragino Maru Gothic ProN',sans-serif;
    border-bottom: solid 3px skyblue;
    position: relative;
  }
  
  h1:after {
    position: absolute;
    content: " ";
    display: block;
    border-bottom: solid 3px #ffc778;
    bottom: -3px;
    width: 30%;
  }
  
  .twitter-link {
    padding: 0.5em 1em;
    margin: 2em 0;
    font-weight: bold;
    color: #6091d3;/*文字色*/
    background: #FFF;
    border: solid 3px #6091d3;/*線*/
    border-radius: 10px;/*角の丸み*/
  }
</style>

