## 为知笔记批量导出为Html文件

- 作用

  批量将为知笔记导出为html形式
  
  ![](./resource/2018-04-10-21-51-31.png)
  
- todo

    导出附件
    
    加密文件解压
    
- 使用
    
    ```
    java -jar wiz-export-1.0-SNAPSHOT.jar -i 索引文件位置 -d 数据文件位置 -t html存储目录  
    
    ```
  
ps:

如果不熟悉java的话可以直接用下面的命令下载编译好的jar包
    
wget "https://raw.github.com/zuochangan/wiz-export/master/bin/wiz-export-1.0-SNAPSHOT.jar"
           

### 为知笔记索引位置的确定

默认在家目录下的.wiznote/登录用户/data下


### 为知笔记数据文件位置的确定

默认在家目录下的.wiznote/登录用户/data/notes下


**如果不在的话，可以通过lsof看下Wiznote应用当前打开的文件句柄找找看.**

