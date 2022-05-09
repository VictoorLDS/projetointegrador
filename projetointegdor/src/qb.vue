<script>    function darkMode() {
        var element = document.body;
        var content = document.getElementById("DarkModetext");
        element.className = "dark-mode";
        content.innerText = "Dark Mode is ON";
      }
      function lightMode() {
        var element = document.body;
        var content = document.getElementById("DarkModetext");
        element.className = "light-mode";
        content.innerText = "Dark Mode is OFF";
      }</script>

<template>
  <nav>
    <div id="titulo"><h1>Info NFL</h1></div>
    <a href=""><div id="qb"><h2>QB</h2></div></a>
    <a href=""><div id="rb"><h2>RB</h2></div></a>
    <a href=""><div id="wr"><h2>WR</h2></div></a>
    <a href=""><div id="ol"><h2>OL</h2></div></a>
    <a href=""><div id="te"><h2>TE</h2></div></a>
    <a href=""><div id="dl"><h2>DL</h2></div></a>
    <a href=""><div id="safety"><h2>S</h2></div></a>
    <a href=""><div id="edge"><h2>EDGE</h2></div></a>
    <a href=""><div id="lb"><h2>LB</h2></div></a>
    <a href=""><div id="cb"><h2>CB</h2></div></a>
  </nav>
  <main>
      <div id="qbtitulo">QB</div>
      <div id="quarterback">Quarterback</div>
  </main>
</template>

<style>
#qbtitulo{
    position: absolute;
width: 132px;
height: 92px;
left: 96px;
top: 193px;

font-family: 'League Gothic';
font-style: normal;
font-weight: 400;
font-size: 96px;
line-height: 115px;

color:#000;
}
quarterback{
    position: absolute;
width: 352px;
height: 46px;
left: 254px;
top: 222px;

font-family: 'League Gothic';
font-style: normal;
font-weight: 400;
font-size: 48px;
line-height: 58px;

color: #ACA7A7;
}
</style>
