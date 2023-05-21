# INT107 COMPUTING PLATFORM TECHNOLOGY 2022
## LINUX LAB EXERCISES [^1]
[^1]: Initially released on 21.05.2023 by Olarn Rojanapornpun

1. Check whether the system date and time are correct.\
ตรวจสอบว่าวันและเวลาในระบบถูกต้องหรือไม่(ตรงกับเวลาปัจจุบันหรือไม่)

2. What are the day of the year and the day of the week of **September 11, 2001**?\
วันที่ 11 กันยายน 2001 เป็นวันที่เท่าไหร่ของปี และเป็นวันอะไร

3. What is option `-t` in command `mount` for?\
option '-t' ในคำสั่ง mount มีไว้เพื่ออะไร

4. What is the _last word_ of the _second line_ of the file `/etc/services`?\
คำสุดท้ายของบรรทัดที่สองของไฟล์ /etc/services คืออะไร

5. What is the _first word_ of line _584_ of the file `/etc/services`?\
คำแรกของบรรทัดที่ 584 ของไฟล์ /etc/services คืออะไร

6. What is the last _modified time_ of directory `/etc`?\
เวลาแก้ไขสุดท้ายของ directory /etc คืออะไร

7. Write a command that will list every files and directories in `/etc` that begin with vowel letter(`a`, `e`, `i`, `o`, `u`) and are **3 characters long**.\
เขียนคำสั่งที่จะแสดงรายชื่อ files and directories ใน `/etc` ที่ขึ้นต้นด้วยอักษรเสียงสระ(a, e, i, o, u) และมีความยาวสามตัวอักษร 

8. Create a directory called `Exercise1` under current _user home directory_.\
สร้าง directory ชื่อ Exercise1 ไว้ใน home directory ของ user ปัจจุบัน(/home/s65???)

9. Copy `who` program to `Exercise1` directory.\
ให้ก๊อปปี้ไฟล์โปรแกรม who มาไว้ใน directory ที่ชื่อ 'Exercise1' (ต้องค้นหาตำแหน่งของ ไฟล์นี้)

10. Copy the file called `fstab` to 'Exercise1' directory.\
ให้ก๊อปปี้ไฟล์ที่ชื่อ 'fstab' มาไว้ใน directory ที่ชื่อ 'Exercise1' (ต้องค้นหาตำแหน่งของไฟล์นี้)

11. Rename the file `fstab` in `Exercise1` to `fstab.bak`.\
เปลี่ยนชื่อไฟล์ 'fstab' ที่อยู่ใน directory 'Exercise1' เป็นชื่อ 'fstab.bak'

12. Create a directory called `Exercise2` under current _user home directory_.\
สร้าง directory ชื่อ Exercise2 ไว้ใน home directory ของ user ปัจจุบัน(/home/s65???)

13. Copy _every files_ in the directory `Exercise1` to the directory `Exercise2`\
ก๊อปปี้ทุกไฟล์ที่อยู่ใน directory ที่ชื่อ Exercise1 ไปไว้ใน Exercise2

14. Delete the directory `Exercise1`.\
ลบ directory 'Exercise1'

15. Create a directory called `Exercise3` under current _user home directory_.\
สร้าง directory ชื่อ Exercise3 ไว้ใน home directory ของ user ปัจจุบัน

16. Create a new file called `MyData` in the directory `Exercise3`.\
สร้างไฟล์ใหม่ชื่อ MyData ใน Exercise3

17. Enter your full name in the file `MyData`.\
พิมพ์ชื่อและนามสกุลของตนเองเป็นบรรทัดแรกของไฟล์ MyData

18. **Append** line _56-197_ in `/etc/services` to `MyData`.\
เพิ่มข้อมูลบรรทัดที่ 56-197 ที่อยู่ในไฟล์ /etc/services ไว้ในไฟล์ MyData

19. Write a command to display any line in `/etc/services` that contains the word `smtp`, ignoring case.\
เขียนคำสั่งที่จะแสดงทุกบรรทัดในไฟล์ /etc/services ที่มีคำว่า smtp ไม่สนใจว่าเป็นตัวเล็กหรือตัวใหญ่

20. What is the free space of `/dev/sda1` in `MB`?\
disk /dev/sda1 มีที่ว่างเหลืออยู่เท่าไหร่

21. Create a symbolic link to `MyData` in your _user home directory_ under the name `DataFile`.\
สร้าง symbolic link ชี้ไปที่ไฟล์ MyData ชื่อ 'DataFile' ให้อยู่ใน home directory ของคุณ

22. Edit `PATH` variable so that the system will search for executable files in `Exercise3` directory first.\
กำหนด PATH variable ให้หาใน Exercise3 เป็นที่แรก

23. Create a script file called `bash` in `Exercise3`. When this script is executed, it displays the sentence "Opening another bash shell.". Then `/bin/bash` is called. After this bash shell is terminated, the sentence "Goodbye.." is displayed.\
สร้าง script file ชื่อ 'bash' ใน 'Exercise3' directory. Script นี้จะแสดงประโยค "Opening another bash shell." แล้วเรียกโปรแกรม '/bin/bash' หลังจากออกจาก bash ตัวนี้แล้ว(คำสั่ง exit หรือ CTRL+D) จะแสดงข้อความ 'Goodbye..".

24. Change file permission of `bash` in `Exercise3` so that you and every users in group `int107` can execute this file.\
เปลี่ยน file permission ให้ user ของคุณ และคนที่อยู่ในกลุ่ม 'int107' สามารถ execute ไฟล์นี้ได้

25. Check which `bash` will be executed when a command `bash` is used.\
ตรวจสอบว่าโปรแกรมไหนจะถูกเรียกเมื่อใช้คำสั่ง 'bash'.

26. Test your `bash` script.
ทดสอบ 'bash' script ว่าทำอย่างที่กำหนดหรือไม่

27. What is the command to change the standard permission of a new file/directory? Suppose you want the new directory to have `rwxr-x---` permission, what is the command to accomplish this task?\
ถ้าจะให้ directory ที่สร้างใหม่(ในอนาคต) มี permission rwxr-x--- จะต้องใช้คำสั่งใด

28. How many files and directories are there in the directory `/etc` (do not count ., .., and files/directories in sub-directories)?\
มีไฟล์และไดเรกทอรี่รวมทั้งหมดเท่าไหร่ ใน directory /etc ไม่นับไฟล์และไดเรกทอรี่ใน sub-directories และไม่นับ . และ ..

