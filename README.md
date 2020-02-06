# TheEconomist2020

经济学人2020年期刊（pdf版）

来源于https://magazinelib.com/网址。

------

```bash
#初始建库
$ cd c:/MyGit/TheEconomist2020
jiangsu@JiangSu MINGW64 /c/MyGit/TheEconomist2020

…or create a new repository on the command line
echo "# TheEconomist2020" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin git@github.com:buaajs/TheEconomist2020.git
git push -u origin master

…or push an existing repository from the command line
git remote add origin git@github.com:buaajs/TheEconomist2020.git
git push -u origin master
```

```bash
#向Git库添加文件（如往TheEconomist2020库中添加The_Economist-20yymmdd.pdf文件）
jiangsu@JiangSu MINGW64 /c/MyGit/TheEconomist2020 (master)

#确保已经处在本地库工作目录下（/c/MyGit/TheEconomist2020）
#从远程库获取最新文件
$ git pull

#在工作目录中修改相应文件The_Economist-20yymmdd.pdf
#暂存文件（将文件的快照放入暂存区）
$ git add The_Economist-20yymmdd.pdf

#提交更新，找到暂存区域的文件，将快照永久性存储到Git仓库目录【本地库】。
$ git commit -m "Commit The_Economist-20yymmdd.pdf" 

#从本地库提交到远程库
$ git push origin master
```

```powershell
#删除Git库中已经存在文件(如：从TheEconomist2020库中删除The_Economist-20yymmdd.pdf文件)
jiangsu@JiangSu MINGW64 /c/MyGit/TheEconomist2020 (master)
$ git rm -r The_Economist-20yymmdd.pdf
$ git commit -m "Delete The_Economist-20yymmdd.pdf"
$ git push origin master
jiangsu@JiangSu MINGW64 /c/MyGit/TheEconomist2020 (master)
```

