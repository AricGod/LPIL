##Linux Shell Projet


###What is the "LPIL"?: 


LPIL的全称是：LinuxShell Projetc is not LinuxShell。此项目的目的是让大家能快速的安装与配置一些著名的Linux发行版。
当前共有`KaliLinux`和`ArchLinux`的快速设置的Shell，我们正在计划开发DebianLinux的Shell。

对于这两个Shell，当前`KaliLinuxShell（KLS）`已经基本完善了，所以我们会偶尔的会进行维护，基本不会再有太大的更新了。
但是由于ArchLinux的“Arch之道”，所以ArchLinux装好后会需要很多的设置。于是`ArchLinuxShell（ALS）`会有很多地方需要改进。

`Tips：ALS当前版本为1.0正式版。`

###How do I use this?: 


####首先，对于KaliLinux：

由于KaliLinux自带git，所以git clone是最方便的：
在您联网的时候，复制下面这些代码到终端：
```
git clone https://github.com/Guanrenfu/LPIL
cd LPIL
cd KLS
chmod +x KaliLinuxShell.sh
./KaliLinuxShell.sh
```
然后您无需操作，只需要等待完成即可～然后您就可以享受您的Kali了～

####对于ArchLinux：

当您安装ArchLinux完成后，先确认可以联网，然后这么做：

```
pacman -S --noconfirm git
git clone https://github.com/Guanrenfu/LPIL
cd LPIL
cd ALS
chmod +x ArchLinuxShell.sh
./ArchLinuxShell.sh
```
好了，现在根据提示做，之后就完成了～


###LPIL FAQ：


1、本项目由谁开发与负责？


：本项目由本人全权负责，但除了大家的热心之外还有支持veners1995帮忙改写了多处代码。感谢大家的帮助！


2、本项目的开发进展是什么？

：KaliLinuxShell（KLS）基本完善，现在本人就是偶尔的修改下，也没有版本可言。
ArchLinuxShell（ALS）现在只有快速配置的Shell，而且2015.6.14才发布了1.0正式版。ALS是接下来的重点开发目标。


3、接下来的目标是什么？


：ALS还有一个重大的Bug没有解决（在ArchLinux运行中文注释会乱码），然后本人还计划要开发DebianLinuxShell（DLS）系列。


4、当前开发团队的规模有多大？


：很不幸的是，当前的开发团队只有我一个人在努力的开发与维护。如果您愿意帮忙的话我将会很欢迎的。


5、此项目是否开源？


：没错，但是此项目将遵循Apache协议。


6、当前有什么问题没有？


：除了ALS在ArchLinux运行会乱码之外暂时没什么问题了。这个问题的临时解决方案就是先记住每个选项的意思，然后再在ArchLinux下运行。




#####最后感谢veners1995的帮忙，当前很大部分代码都是此人帮忙写的。再次感谢！！
