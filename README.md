# Godot-Project 《勇者传说》
跟着B站学习游戏引擎-自用

## 07 蹬墙跳的实现
- 关于godot 4.4.1 的is_on_wall( ) 必须要按住方向键才能为TRUE 的bug对player节点添加RayCast2D 进行碰撞检测的第二个标准 var reall_is_on_wall = is_on_wall( ) and RayCast2D.is_colliding( )在蹬墙跳的实例中可以在添加一个wall_jump_coyotetimer 来实现宽松判定丝滑的蹬墙跳
<img width="1133" height="748" alt="556cc74c61b91e9ca52366c26f90d4c1" src="https://github.com/user-attachments/assets/1c2125ce-2423-4607-930e-21cbf3b3b70d" />
<img width="1095" height="303" alt="a0ac9822086a0eadca73058d172888dd" src="https://github.com/user-attachments/assets/72077c64-4359-4a0b-8fdb-52ae75e89a0c" />


## 勇者传说大概30号前完工哦！！
