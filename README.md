[中文](README.md)
[English](README_EN.md)
# LXC-DOCKER-KernelSU_Action

## 说明 
- 有的工作流是用谷歌的 clang 14 编译器
- 有的工作流是用从clang官方源码编译的 clang 18 编译器
- 其中zyc clang 18 和 阿菌•未霜 clang 18可以任选，阿菌•未霜 clang 18 带BOLT等优化


## 步骤
1. fork本仓库到你的仓库，先打开config.env，编辑变量，Commit changes
2. 上方菜单选择Actions，选择All workflows，不同工作流的区别看名字就知道了，选择自己想运行的工作流
3. 然后点击 run workflow,再确认一次，就启动了，等待完成
4. 从下方Artifacts 下载编译好的内核


## 提示
- 如果编译不过，请采用clang 14 编译
- 上方菜单选择Actions，选择All workflows，可以看到所有工作流
- config.env文件里有对应的变量说明


## 感谢
- [AnyKernel3](https://github.com/osm0sis/AnyKernel3)
- [AOSP](https://android.googlesource.com)
- [KernelSU](https://github.com/tiann/KernelSU)
- [xiaoxindada](https://github.com/xiaoxindada)
- [xiaoleGun](https://github.com/xiaoleGun/KernelSU_Action)
- [wu17481748](https://github.com/wu17481748/LXC-DOCKER-KernelSU_Action)
- [qiuqiu](https://github.com/lateautumn233)

