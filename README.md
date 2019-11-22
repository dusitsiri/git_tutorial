# Git Tutorial Command Line

## Terminology (คำศัพท์ที่ควรรู้)

1. local = คอมพิวเตอร์ของเรา
2. remote = 

## git version
- ใช้ในการตรวจสอบว่าได้ทำการติดตั้ง git version ใดลงบนเครื่อง local ของเรา

command:
```git version
 git --version
```
result: 
```
git version 2.23.0.windows.1
```
---

## git config
- ใช้ในการ Setup ชื่อและอีเมล์สำหรับใช้งาน Git
```git config
git config --global user.name "YOURNAME"
git config --global user.email "your@email.com"
```
Note: ```YOURNAME ให้ใส่ชื่อ username ของตัวเอง your@email.com ให้ใส่ email ของตัวเอง```

---

## git init
- ใช้ในการสร้างไฟล์ตั้งต้นของ git เพื่อใช้ในการกำหนด repository ของ project
```git init
git init
```

---

## how to edit main branch without touch it directly.
![edit branch without touching](https://github.com/dusitsiri/git_tutorial_command_line/blob/master/Edit_branch_without_touch_directly/merge.png)