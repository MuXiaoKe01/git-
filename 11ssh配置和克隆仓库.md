
![image](https://github.com/user-attachments/assets/c2615aea-970e-42e6-8f6b-51f7d0768800)

ssh-keygen -t rsa -b 4096 在.ssh文件下使用该命令，创建密钥。产生对应名字的公钥和私钥。复制公钥。浏览器打开github网站，点击右上角头像，点击settings。点击页面左侧的ssh and GPG keys ,点击new ssh key按钮，将公钥内容复制到key里面，并输入任意的title,点击 add ssh key按钮。

在.ssh文件夹中修改文件config,添加以下内容

Host github.com

 HostName github.com
 
 PreferredAuthentications publickey
 
 IdentityFile ~/.ssh/test


git clone ssh地址

![image](https://github.com/user-attachments/assets/63ef7580-1fd5-49d4-a37e-50a99420c80d)

git pull 从远程拉取到本地

git push 从本地拉取到远程


