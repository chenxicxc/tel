[# tel](https://www.cnblogs.com/mq0036/p/18755134
https://blog.csdn.net/wzcool273509239/article/details/145731842
vs2022修改nuget包默认存放位置的方法
找到一下三个文件
C:\Users\NueXini\AppData\Roaming\NuGet\NuGet.Config
C:\Program Files (x86)\NuGet\Config\Microsoft.VisualStudio.FallbackLocation.config
C:\Program Files (x86)\NuGet\Config\Microsoft.VisualStudio.Offline.config

在packageSources节或fallbackPackageFolders节下添加下面的节

  <config>
	<add key="globalPackagesFolder" value="E:\cxc\.nuget" />
  </config>


https://www.cnblogs.com/cdaniu/p/18052959
vs2022修改android设备管理默认存放位置的方法
1、进入C:\Users\chenxicheng\.android目录下把avd文件夹复制到其他盘
2、删除*.avd文件夹
3、修改*.ini文件中path=* 的路径)
