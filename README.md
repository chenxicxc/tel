https://www.cnblogs.com/mq0036/p/18755134</br>
https://blog.csdn.net/wzcool273509239/article/details/145731842</br>
vs2022修改nuget包默认存放位置的方法</br>
找到一下三个文件</br>
C:\Users\NueXini\AppData\Roaming\NuGet\NuGet.Config</br>
C:\Program Files (x86)\NuGet\Config\Microsoft.VisualStudio.FallbackLocation.config</br>
C:\Program Files (x86)\NuGet\Config\Microsoft.VisualStudio.Offline.config</br>
</br>
在packageSources节或fallbackPackageFolders节下添加下面的节</br>
</br>
  &lt;config&gt;</br>
  &nbsp;&nbsp;&nbsp;&nbsp;&lt;add key="globalPackagesFolder" value="E:\cxc\.nuget" /&gt;</br>
  &lt;/config&gt;
</br>
</br>
https://www.cnblogs.com/cdaniu/p/18052959</br>
vs2022修改android设备管理默认存放位置的方法</br>
1、进入C:\Users\chenxicheng\.android目录下把avd文件夹复制到其他盘</br>
2、删除*.avd文件夹</br>
3、修改*.ini文件中path=* 的路径</br>
</br>
  
