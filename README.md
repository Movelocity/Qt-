# Qt-Miku-Parkour
用qt写一个简单跑酷小游戏，检验学习成果
文件直接下载后放在用Qt5打开ParkourProject.pro文件应该就能自动导入了。

引用了状态机和动画机的概念，自己设计了刚体rigidbody检测碰撞，碰撞检测效率可能有点慢，是一个一个像素找的，应该还要先排序一下比较好。
有对应的类 State, Animation, Rigidbody
这里像素和位移多用的是固定的，因为懒只在windows上面试过，其它系统可能还要调位移单位像素。
其实刷新率应该还能调整，动画为了衔接没有把spritesheet中的全部图用上，把定时器调快一点就能提高帧率了，不过移动速度（每步位移）也要相应调整

游戏画面看我github头像



QQ：209848539
