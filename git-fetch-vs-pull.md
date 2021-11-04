# Git Fetch vs Pull 

git fetch สามารถดึงข้อมูลจาก repository เดียวหรือหลาย repository พร้อมกัน
git pull ดึงข้อมูลจาก remote repository มาไว้บน local repository ใน branch ปัจจุบัน

![fetch vs pull](./images/fetch-vs-pull.png)

```git fetch``` เป็นคำสั่งที่บอกให้ git ในเครื่องคอมพิวเตอร์ของเราดึงข้อมูล meta-data ล่าสุดจาก origin repository แต่ไม่ได้ทำการถ่ายโอนไฟล์ใดๆ เป็นเหมือนการตรวจสอบเพื่อดูว่ามีการเปลี่ยนแปลงใดๆ บน origin repository หรือไม่ 
```git pull``` เป็นคำสั่งที่บอกให้ git ในเครื่องคอมพิวเตอร์ของเราตรวจสอบการเปลี่ยนแปลงบน origin repository แล้วดึงไฟล์ที่เปลี่ยนแปลงมาเก็บใน local repository

**ข้อควรจำ**: ```git pull``` เป็นคำสั่งที่รวมเอา  ```git fetch``` ตามด้วย ```git merge FETCH_HEAD``` เข้าไว้ในคำสั่งเดียว

### เมื่อใดควรใช้ git fetch ###




### เมื่อใดควรใช้ git pull ###


