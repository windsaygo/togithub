...用命令行模式创建一个新的仓库

echo "# togithub" >>readme.md //创建一个说明文档

git init //初始化一个git仓库。有相关的配置

git add readme.md  //把readme.md文件放到一个什么区域来着

git commit -m "第一次提交" //提交到云服务器？

git remote add origin git@github.com:windsaygo/togithub.git //远程连接什么的

git push -u origin master //估计是上传代码