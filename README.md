# SSH密钥生成

一、SSH的密钥使用命令生成本地.ssh文件，生成方式有2种:<br>
        1.不加邮箱地址 :  ssh-keygen -t rsa<br>
        2.添加邮箱地址 ： ssh-keygen -t rsa -C "xxx@qq.com"<br>
        在C盘目录生成.ssh文件,目录位置: C:\Users\Administrator<br>
 二、github上添加密钥<br>
        1、使用命令切换到ssh目录: cd ~/.ssh   <br>
        2、显示文件：ls  <br>
        3、打开id.rsa.pub文件： cat id.rsa.pub <br>
        4、copy内容到github上，在右上角个人图标点击向下箭头->settings->SSH And GPG KEYS --->new SSH KEY
    





