#Welcome to use MarkDown
# Git配置
##ignore
  - 忽略HB创建的文件；
  - git add -f(强制添加.gitignore忽略文件)
  - git reset HEAD
  - git check-ignore -v .project(查看.gitignore策略生效行号)
##Github Mode
 - cerat repository 添加.gitignore的类型文件；
##换行  
- 提交时转换为LF，检出时转换为CRLF，默认设置不用修改，git是Linux配置；
  - git config --global core.autocrlf true 
- 允许提交包含混合换行符的文件 
  - git config --global core.safecrlf false
  
  - **CR:** carriage return回车，光标到首行，‘\r’=return
  - **LF:** line feed换行，光标下移一行，‘\n’=newline
    - **linux: line feed \n**
    - **windows: line feed \r\n**
    - **MAC OS: line feed \r**
    
##别名


##凭证





















