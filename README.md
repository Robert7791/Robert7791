- 👋 Hi, I’m @Robert7791
This my plugin for ZPS. Thank you!

//Description of my plugin//
How does it work? 
Very simple.
In configs/register system.cfg you write data from the database, in scripting/zpbank_and_lvl_save_in_mysql.smarty you also write data from the database.
Compile.

In game
When player come in game, he can register or not register on server. If he will register on server, plugin save his nikcname with ammo/lvl/exp in Mysql base and when he will come on server again, plugin set his ammo/level/xp from Mysql. If player won`t register, plugin don`t save his nickname with ammo/lvl/exp, and player loses his progress.
