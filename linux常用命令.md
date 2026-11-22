ls (List)
作用：列出目录内容
说明：用于查看当前目录下的文件和文件夹。常用参数-l查看详细信息（如权限，大小，时间）， -a查看包含隐藏文件在内的所有文件
cd（Change Directory）
作用：切换当前工作目录
说明：用于进入指定的文件夹。例如cd /home进入home 目录， cd .. 返回上一级目录， cd ~ 回到当前用户的家目录
pwd (Print Working Directory)
作用：显示当前工作目录的绝对路径
说明：当前你不确定自己当前在哪个文件夹下时，输入pwd即可显示完整的路径（例如 /home/user/projects）
mkdir (Make Directory)
作用：创建新目录（文件夹）
说明：例如mkdir test 创建一个名为test的文件夹。加上 -p参数可以递归创建多级目录 （如 mkdir -p a/b/c）
rm (Remove) 
作用：删除文件或目录
说明:(谨慎使用) rm 文件名 删除文件； rm -r 目录名 递归删除目录及其内容 rm -f 强制删除不提示。 注意， Linux 下没有回收站， 删除后通常难以恢复
cp (Copy)
作用：复制文件或目录
说明：例如 cp file1.txt file2.tet 将file1 复制为 file2. 如果要复制文件夹， 需要加上 -r 参数（如 cp -r dir1 dir2）
mv (Move)
作用：移动文件或目录， 或者重命名
说明：例如 mv file.txt /tmp/ 将文件移动到/tmp目录。如果是在同一目录下操作， mv oldname.txt newname.txt 就起到了重命名的作用
cat (Concatenate)
作用：查看文件内容或连接文件
说明：常用于直接在终端显示文本文件的全部内容， 例如 cat README.MD, 也可以用于合并文件或创建新文件
grep (Global Regular Expression Print)
作用：在文本中搜索指定的字符串或模式
说明：非常强大的文本搜索工具。例如 grep "error" log.txt 会在 log.txt 中查找包含“error” 的行。常与管道符 | 结合使用， 如 ls -1 | grep ".txt"
chmod (Change Mode)
作用：修改文件或目录的访问权限
说明：用于控制谁可以读 （r）, 写 （w）, 执行 （x） 文件。例如 chmod +x script.sh 赋予脚本可执行权限；chmod 755 file 通过数字方式设置权限
在Git Bash 或 Linux 终端中， 你可以使用 man 命令行 （例如 man ls） 来查看该命令的详细帮助手册
