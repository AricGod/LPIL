##Linux Shell Projet


###What is the "LPIL": 


LPIL的全称是：LinuxShell Projetc is not LinuxShell。此项目的目的是让大家能快速的安装与配置一些著名的Linux发行版。
当前共有`KaliLinux`和`ArchLinux`的快速设置的Shell scripts，我们正在计划开发适用于DebianLinux的Shell script。

对于这两个Shell script，当前`KaliLinuxShell（KLS）`已经基本完善了，所以我们会偶尔的会进行维护，基本不会再有太大的更新了。
但是由于ArchLinux的“Arch之道”，所以ArchLinux装好后会需要很多的设置。于是`ArchLinuxShell（ALS）`会有很多地方需要改进。

`Tips：ALS当前版本为1.0正式版。`

###How do I use this?: 
-----------------------
####首先，对于KaliLinux：

由于KaliLinux自带git，所以git clone是最方便的：
在您联网的时候，复制下面这些代码到终端：
```
git clone --depth=1 https://github.com/Guanrenfu/LPIL
cd LPIL
cd KLS
chmod +x KaliLinuxShell.sh
./KaliLinuxShell.sh
```
然后您无需操作，只需要等待完成即可～然后您就可以享受您的Kali了～

####对于ArchLinux：

当您安装ArchLinux完成后，先确认可以联网，然后在tty输入这些：

```
pacman -S --noconfirm git
pacman -S --noconfirm wqy-microhei
pacman -S --noconfirm fbterm
fbterm
```
此时会进入一个虚拟终端，前面输入的将被清空。现在tty就可以正常显示中文了，之后输入这些：
```
git clone --depth=1 https://github.com/Guanrenfu/LPIL
cd LPIL
cd ALS
chmod +x ArchLinuxShell.sh
./ArchLinuxShell.sh
```
好了，现在根据提示做，之后就完成了～


###LPIL FAQ：


>1、本项目由谁开发与负责？
>
>：本项目由本人全权负责，但除了大家的热心之外还有支持veners1995帮忙改写了多处代码。感谢大家的帮助！
>
>
>2、本项目的开发进展是什么？
>
>：KaliLinuxShell（KLS）基本完善，现在本人就是偶尔的修改下，也没有版本可言。
>ArchLinuxShell（ALS）现在只有快速配置的Shell，而且2015.6.14才发布了1.0正式版。ALS是接下来的重点开发目标。
>
>
>3、使用时我还需要注意什么？
>
>：LPIL scripts的部分操作可能需要您具有一定的权限，请确保这一点以保证配置的顺利完成
>
>
>4、接下来的目标是什么？
>
>：ALS我们将持续更新，然后本人还计划要开发DebianLinuxShell（DLS）系列。
>
>
>5、当前开发团队的规模有多大？
>
>：当前共有本人与@veners1995 在努力维护，同时@Arthur2e5也对本项目十分热情。
>
>
>6、此项目的协议是？
>
>：此项目遵循Apache协议。
>
>
