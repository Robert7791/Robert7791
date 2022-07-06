<p>- 👋 Hi, I&rsquo;m @Robert7791<br />This my plugin for ZPS. Thank you!</p>
<p>//Description of my plugin//</p>
<p>How does it work?</p>
<p>Very simple.<br />In configs/register system.cfg you will write data from the database, in scripting/zpbank_and_lvl_save_in_mysql.sma you will also write data from the database.</p>
<p>Compile.</p>
<p>&lt;In game&gt;</p>
<p>When player come in game, he can register (/reg) or not register on server. If he will register on server, plugin save his nickname with ammo/lvl/exp in Mysql base and when he will come on server again, plugin set his ammo/level/xp from Mysql. If player won`t register, plugin don`t save his nickname with ammo/lvl/exp, and player loses his progress.</p>
<p>----------</p>
<h3 dir="auto">Changelog:</h3>
<div class="snippet-clipboard-content position-relative overflow-auto">
<pre class="notranslate"><code class="notranslate">1.0:
    - First Release
1.1:
    - Fixed connection to mysql, now in plugin you don`t need to write your information from mysql server, it takes information from registration system <br />  
    - Add UTF-8 support<br />    
    - Fixed some parametrs
1.2:
    - Fixed some parametrs
<br /></code></pre>
</div>


