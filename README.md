
# step1 : create new repo
*no env at this computer,create a new env*
```
git add AxureDesign.rp
git commit -m "add first"
git branch -M main
git remote add origin https://github.com/zhucm/axuredesign.git
git push -u origin main
```
# step2 : update commit to remote
*commit update content to remote*

```
git add AxureDesign.rp
git commit -m "update at 2022-04-3"
git push origin main

# 添加所有更新的文件，不包括新增文件
git add -u
git commit -m "注释"
git push origin main
```

# step3 : get clone from other computer(Windows 10)
*now , I want modify it at another windows 10 computer,no env in this computer*
```
git clone https://github.com/zhucm/axuredesign
```

# step4 : get update from other computer(Mac)
*when I go back home, I want get update from remote, which modified at windows 10, pull means fetch and merge*
```
git pull https://github.com/zhucm/axuredesign main
```

# step5 : redo step2 and step4
*before update ,please close the application if any one use it. Or it may be show error: unlink of file 'xxxx' failed ,Should I try again...*
