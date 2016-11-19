clear 清屏,但是可以看到以前的问题
gh-pages(如果把代码提交到分支上。该ithub会给你个地址可以直接访问这个项目)
--创建分支  git branch gh-pages
--切换分支  git checkout gh-pages
--创建文件  touch index.html
--写入内容  echo worldhello > index.html
           git add . 
           git commit -m'shiz'
           git push origin gh-pages
--删除分支 切换到其他分支进行删除  git branch -d gh-pages
--查看分支  git branch