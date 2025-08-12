# Godot-Project 《勇者传说》
跟着B站学习游戏引擎-自用

## 07 蹬墙跳的实现
- 关于godot 4.4.1 的is_on_wall( ) 必须要按住方向键才能为TRUE 的bug对player节点添加RayCast2D 进行碰撞检测的第二个标准 var reall_is_on_wall = is_on_wall( ) and RayCast2D.is_colliding( )在蹬墙跳的实例中可以在添加一个wall_jump_coyotetimer 来实现宽松判定丝滑的蹬墙跳


