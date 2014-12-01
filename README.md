sparklingchild
==============

Theme child Sparkling

/*
  ==========
  List
  ==========
*/  
  
01.style.css

02.functions.php

03.footer.php

/*
  ==========
  01.style.css
  ==========
*/

Não usar @import url("style.css");

Carregar stylesheet do tema pai atráves do arquivo de functions.php

/*
  ==========
  02.functions.php
  ==========
*/

Usar add_action('wp_enqueue_scripts', 'sparkling_child_load_parent_styles');

Para carregar a folha de estilo do tema pai.

/*
  ==========
  .03footer.php
  ==========
*/

No arquivo functions.php, criar uma nova function para alterar direitos autorais no rodápe.


