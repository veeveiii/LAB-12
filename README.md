#ใบงานที่ 12
##การเขียนโปรแกรมกราฟฟิกส์ด้วย GDI+ (3)
##กล่าวนำ
ใบงานนี้ มีวัตถุประสงค์ เพื่อให้นักศึกษา ได้รู้จักกับ GDI+ ซึ่งจะช่วยให้นักษาสามารถ
* โหลดภาพชนิดต่างๆ เพื่อมาแสดงบนฟอร์มได้
* จัดการกับภาพโดยวิธีการง่ายๆ เช่น พลิกภาพ หมุนภาพ และเขียนข้อความลงบนภาพได้

###การโหลดภาพเพื่อแสดงบน Form
Project นี้จะโหลดภาพจากไฟล์ (ชนิดใดก็ได้) มาแสดงผลบน Form 
* สร้าง Project ใหม่เป็น Visual C#
* แก้ไข code เพื่อโหลดและแสดงภาพบน Form 
</p align = "center">
<img src="https://github.com/Desktop-Programming-Lab-2559/LAB-12/blob/master/imgs/lab12-1.png">
</p> 

**หมายเหตุ** ในบรรทัดที่ 23 หากนักศึกษาต้องการแสดงไฟล์อื่น ก็ให้ใส่ path พร้อมชื่อ แต่ต้องใส่ \\ แทน \ เนื่องจาก ในภาษา C# นั้น เครื่องหมาย \ จะเป็น escape character เช่นเดียวกับภาษา c และ c++
###ผลการทดลอง
![](https://scontent.fbkk2-3.fna.fbcdn.net/v/t34.0-12/15139374_1142402579213325_386260577_n.png?oh=d4d5477f53953cc2afdcce69e51a18da&oe=58313A4B)
<hr>

##การ Zoom ภาพ
การ Zoom ภาพ คือการกำหนดให้ขนาดของพื้นที่แสดงผลต่างไปจากขนาดที่แท้จริงของภาพ (Zoom in, Zoom out) นอกจากนี้เรายังสามารถเลือกส่วนของภาพที่จะแสดงได้อีกด้วย

### การ Zoom out  
คือการกำหนดให้ Rectangle ปลายทาง เล็กกว่าขนาดจริงของภาพ
 </p align = "center">
<img src="https://github.com/Desktop-Programming-Lab-2559/LAB-12/blob/master/imgs/lab12-2.png">
</p> 

###ผลการทดลอง
![](https://scontent.fbkk2-3.fna.fbcdn.net/v/t34.0-12/15134443_1142402555879994_1208909059_n.png?oh=db282793ed25bde5fdae9bb225f67766&oe=583100E0)
<hr>

### การ Zoom in  
คือการกำหนดให้ Rectangle ปลายทาง โตกว่า Rectangle ของภาพ ในที่นี้จะเลือกภาพมาแสดง
 
</p align = "center">
<img src="https://github.com/Desktop-Programming-Lab-2559/LAB-12/blob/master/imgs/lab12-3.png">
</p> 

###ผลการทดลอง
![](https://scontent.fbkk2-2.fna.fbcdn.net/v/t34.0-12/15086282_1142402569213326_1564139677_n.png?oh=bfb802801be00b163fa44f9ee4502e69&oe=58313046)
<hr>

### การพลิกและหมุนภาพ
 </p align = "center">
<img src="https://github.com/Desktop-Programming-Lab-2559/LAB-12/blob/master/imgs/lab12-4.png">
</p> 
![](https://scontent.fbkk2-2.fna.fbcdn.net/v/t34.0-12/15129824_1142402572546659_2006171975_n.png?oh=c25deb7d82f2237e366a97f41fca78e4&oe=5830E8F0)

## การเขียนข้อความลงในภาพ
 </p align = "center">
<img src="https://github.com/Desktop-Programming-Lab-2559/LAB-12/blob/master/imgs/lab12-5.png">
</p> 

###ผลการทดลอง
![](https://scontent.fbkk2-2.fna.fbcdn.net/v/t34.0-12/15151068_1142402575879992_589378849_n.png?oh=1e79fbd4f815d0e57444c2002bb9c9ae&oe=58311E0D)
<hr>
##แบบฝึกหัด
ให้วาดตัวการ์ตูน Doraemon โดยใช้คำสั่งต่างๆ ทางด้านกราฟฟิกส์ พร้อมทั้งใส่ชื่อ นามสกุล และรหัสนักศึกษาของตนเองลงไปด้วย (ห้ามใช้วิธีการใส่รูปภาพ)
###ผลการทดลอง
![](https://scontent.fbkk2-2.fna.fbcdn.net/v/t34.0-12/15058726_1142410425879207_965776540_n.png?oh=fde4c6ca6007570625a05d62312171b4&oe=58317149)
<hr>
<hr>
Ailada Samingkaew 57030249
<hr>
<hr>
**[ตัวอย่างงานวาดภาพ Doraemon ของรุ่นพี่](https://github.com/Desktop-Programming-Lab-2559/LAB-12/blob/master/Doraemon.md)**
