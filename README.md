# LFS_Demo
LFS_Demo


 - Operate Log
```
CoderDreamdeiMac:GitHub coderdream$ cd LFS_Demo/
CoderDreamdeiMac:LFS_Demo coderdream$ ls
README.md	test.jpg
CoderDreamdeiMac:LFS_Demo coderdream$ git lfs track "test.jpg"
Tracking "test.jpg"
CoderDreamdeiMac:LFS_Demo coderdream$ git add .gitattributes
CoderDreamdeiMac:LFS_Demo coderdream$ git add test.jpg
CoderDreamdeiMac:LFS_Demo coderdream$ git commit -m "Add jpg file"
[master 8e8a77c] Add jpg file
 2 files changed, 4 insertions(+)
 create mode 100644 .gitattributes
 create mode 100755 test.jpg
CoderDreamdeiMac:LFS_Demo coderdream$ git push origin master
Uploading LFS objects: 100% (1/1), 281 KB | 29 KB/s, done                       
Counting objects: 4, done.
Delta compression using up to 4 threads.
Compressing objects: 100% (3/3), done.
Writing objects: 100% (4/4), 475 bytes | 475.00 KiB/s, done.
Total 4 (delta 0), reused 0 (delta 0)
To github.com:CoderDream/LFS_Demo.git
   ecc3a7a..8e8a77c  master -> master
CoderDreamdeiMac:LFS_Demo coderdream$ git lfs track "Office.dmg"
Tracking "Office.dmg"
CoderDreamdeiMac:LFS_Demo coderdream$ git add Office.dmg
CoderDreamdeiMac:LFS_Demo coderdream$ git commit -m "Add design file"
[master b6cbe60] Add design file
 1 file changed, 3 insertions(+)
 create mode 100755 Office.dmg
CoderDreamdeiMac:LFS_Demo coderdream$ git push origin master
Uploading LFS objects: 100% (1/1), 246 MB | 1.3 MB/s, done                      
Counting objects: 3, done.
Delta compression using up to 4 threads.
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 464 bytes | 464.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0)
To github.com:CoderDream/LFS_Demo.git
   8e8a77c..b6cbe60  master -> master
CoderDreamdeiMac:LFS_Demo coderdream$ 
```