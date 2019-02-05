---
layout: template_d1
title: Happy Birthday
description: Wishing you a very happy birthday
image: /assets/images/d1/happy_birthday_1_thumb.jpg
categories: happy_birthday
---
<link href="/assets/css/d1/bdy.css" rel="stylesheet" type="text/css">
<link href="/assets/css/d1/setting.css" rel="stylesheet" type="text/css">
<div style="overflow-x: hidden; overflow-y: scroll;">

<script>
      $(function() {
  for (var i=0; i < 8; i++) {
    $('.balloons').append("<div class='balloon balloon" + i + "'></div>");
  }
});

WebFont.load({
  google: {
    families: ["Poppins:300,400,400i,700,900"]
  },
  custom: {
    families: ["segoepr"],
    urls: ["https://www.studiolunter.com/fonts/segoepr.css"]
  }
});
      //# sourceURL=pen.js
    </script>    
<div class="pyro">
    <div class="before"></div>
    <div class="after"></div>
</div>
<div class="container">
    <div class="cake">
      <div class="fire"></div>
      <div class="candle"></div>
      <div class="html"></div>
      <div class="css"></div>
      <div class="js"></div>
      <h1 class="ball">happy birthday <br> <span id="receivername"></span></h1>
        <p class="name">From <span id="sendername"></span></p>
  </div>
</div>
<div class="balloons"></div>

</div>