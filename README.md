<p align="center">  
  
  <a href="#">
    <img src="https://github.com/ChinaIceF/My-TODOs/blob/main/assets/readme/my-todos.png?raw=true" alt="head-image"  >
  </a>
  
  <h2 align="center">My-TODOs</h2>
  <p align="center">基于 PyQt-SiliconUI 编写的跨平台桌面待办小工具</p>


### 如何使用
* 在右侧下载最新的 Release，解压并运行即可
* 如果你需要开机自启，请参照网上的方法将本应用添加到自启

#### 如果无法运行
由于平台的多样性，这里提供的软件包可能无法适配所有平台，但您可以通过下载源代码并自行打包解决问题，以`Pyinstaller`为例，在项目目录命令行中输入：
```
Pyinstaller start.py --noconsole
```
编译完成后，你需要移动`options.ini` `todos.ini` `./icons/icons.dat`到可执行文件所在目录，这可能因为平台不同有不同情况，因此还需结合您的报错信息动态调整

### 调试与开发
如果你要进行调试源代码，你需要下载 [PyQt-Silicon](https://github.com/ChinaIceF/PyQt-SiliconUI/) 中的 `siui` 包并放置在工作目录后再进行调试工作

### 第三方资源
本项目使用了部分来自 [FlatIcon](https://flaticon.com) 的图标。 

### License
本项目采用 GPL v3.0 license，转载时需注明项目链接

### 赞助
如果你喜欢本项目的话，可以扫描下方的二维码赞助我，为爱发电，您的支持与鼓励就是我最大的动力  


<a href="#">
 <img src="https://github.com/ChinaIceF/My-TODOs/blob/main/assets/readme/payments.png?raw=true" alt="payments"  >
</a>
