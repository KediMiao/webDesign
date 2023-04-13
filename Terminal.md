
MacBook-Air:~ miao$ ls 

MacBook-Air:Story miao$ ls -a    all the hiden files

MacBook-Air:~ miao$ cd Documents

MacBook-Air:Documents miao$ cd ~

option can move the pointer

MacBook-Air:~ miao$ cd ..

MacBook-Air:Desktop miao$ mkdir fileName    create folder

MacBook-Air:Desktop miao$ touch Text2.txt   create file

MacBook-Air:Desktop miao$ open Text2.txt    open file

MacBook-Air:Desktop miao$ open -a Wechat Text2.txt   Using Wechat to open file

MacBook-Air:Desktop miao$ rm Text2.txt  delete file

MacBook-Air:Desktop miao$ pwd     whole directory     
/Users/miao/Desktop

MacBook-Air:Desktop miao$ rm *   remove everything

MacBook-Air:Desktop miao$ rm -r remove whole directory


***************** LOCAL GIT*********************************

MacBook-Air:Story miao$ git init
Initialized empty Git repository in /Users/miao/Desktop/Story/.git/



MacBook-Air:Story miao$ git status       check file's status
On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        text1.txt

nothing added to commit but untracked files present (use "git add" to track)
  
  
MacBook-Air:Story miao$ git commit -m "Complete the first text"
[master (root-commit) 71e5130] Complete the first text
 1 file changed, 1 insertion(+)
 create mode 100644 text1.txt
  
  
  
MacBook-Air:Story miao$ git log
commit 71e5130a8bf771c8e07cf17cc4f6ebb408e20d23 (HEAD -> master)
Author: cordellM <k.miao@wustl.edu>
Date:   Thu Apr 13 16:27:09 2023 -0700

    Complete the first text
  
  
MacBook-Air:Story miao$ git add text2.txt
MacBook-Air:Story miao$ git add text3.txt
MacBook-Air:Story miao$ git add .
  
  this will add all new files to git in this folder
  
  
  
MacBook-Air:Story miao$ git diff text3.txt
diff --git a/text3.txt b/text3.txt
index 6c9ba5d..851c75c 100644
--- a/text3.txt
+++ b/text3.txt
@@ -1 +1 @@
-Hello everyone, it is me Kenny! HIHIHI
\ No newline at end of file
+=
\ No newline at end of file
  
 
MacBook-Air:Story miao$ git checkout text3.txt       roll back, very useful
Updated 1 path from the index
  
  






