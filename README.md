# Qt-Miku-Parkour
用qt写一个简单跑酷小游戏
文件直接下载后放在用Qt5打开ParkourProject.pro文件应该就能自动导入了。

引用了状态机和动画机的概念，自己设计了刚体rigidbody检测碰撞，碰撞检测效率可能有点慢，是一个一个像素找的，应该还要先排序一下比较好。

游戏贴图来自MMD模型，通过绿色背景加PS抠图导出。

有对应的类 State, Animation, Rigidbody

这里像素和位移多用的是固定的，只在windows上面试过，其它系统可能还要调位移单位像素。

其实刷新率应该还能调整，动画为了衔接没有把spritesheet中的全部图用上，把定时器调快一点就能提高帧率了，不过移动速度（每步位移）也要相应调整

# 启动界面
![main](https://github.com/Movelocity/Qt-Miku-Parkour/blob/main/mainpage.png)

# 游戏界面
![play](https://github.com/Movelocity/Qt-Miku-Parkour/blob/main/playground.png)

QQ：209848539
