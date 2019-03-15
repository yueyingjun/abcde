## git 上传流程

1.  下载并安装 git for windows

2.  需要在github上面注册用户名和账号

3.  登陆 github，并且创建新的仓库

4.  给仓库起名字

5. create 创建一个空的仓库

6. 双击打开 git bash  这个应用

7. 在该界面输入相关的命令

8. 设置本地git的用户名和邮箱

    ```
     git config --global user.name "xxx"
     git config --global user.email "xxx"

    ```
    
9. 进入到你的工作目录

    ```
      d:
      
      cd a
    ```
    
10. 用git命令 去管理你的工作目录

   ``` 
     git init
   ```
11. 需要继续输入git命令

    ```  
    git add .
    git commit -m "xxxxx"
    
    
    ```
    
12. 回到你的github的空的仓库，拷贝你的空的仓库的地址

   ``` 
   git remote add origin https://github.com/yueyingjun/abcde.git
   ```

13. 输入命令进行上传

    ``` 
     git push origin master
    ```
   
14. 提示输入用户名和密码(github上面注册的时候的用户名和密码)


15. 等待上传(....)


16. 上传成功

17. 在你的当前的仓库页面，点击 setting

18. 找到 GitHub Pages -> Source-> master branch  -> 自定刷新页面

19. 会看到生成一个预览的地址

20. 在当前地址后面跟上你的文件的路径或者是名字就OK

  