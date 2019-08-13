第一步当然是建工程省略

添加 dll 动态链接库到工程

![鼠标右键工程属性](https://img.hacpai.com/file/2019/08/鼠标右键工程属性-b9cfd471.png)


1、添加工程的头文件目录：工程—属性—配置属性—c/c++—常规—附加包含目录：加上头文件存放目录。
![引入头文件](https://img.hacpai.com/file/2019/08/引入头文件-7b1f0c27.png)

2、添加文件引用的lib静态库路径：工程—属性—配置属性—链接器—常规—附加库目录：加上lib文件存放目录。 
![添加lib目录](https://img.hacpai.com/file/2019/08/添加lib目录-e093c9ad.png)

然后添加工程引用的lib文件名：工程—属性—配置属性—链接器—输入—附加依赖项：加上lib文件名。
![添加具体lib名称](https://img.hacpai.com/file/2019/08/添加具体lib名称-e66d1384.png)

3、添加工程引用的dll动态库：把引用的dll放到工程的可执行文件所在的目录下。
![添加具体dll文件到可执行目录](https://img.hacpai.com/file/2019/08/添加具体dll文件到可执行目录-ba5a0654.png)
