**DADS5001 AS03**

By บุลวัชร์  เจริญยืนนาน 6610422013

ชุดข้อมูลพฤติกรรมการใช้จ่ายของนักศึกษาจำนวน 1000 คนจากมหาวิทยาลัยแห่งหนึ่งในต่างประเทศ  
แหล่งข้อมูล : https://www.kaggle.com/datasets/sumanthnimmagadda/student-spending-dataset  
ตัวอย่าง Code :https://github.com/Pomaccel/DADS5001-Data-Analytics-and-Data-Science-Tools-and-Programming/blob/main/6610422013_AS03.ipynb

**อธิบายชุดข้อมูล**  
ชุดข้อมูลนี้แสดงพฤติกรรมการใช้จ่ายของนักศึกษาจำนวน 1000 คนจาก ชั้นปีที่ 1 (Freshman),ชั้นปีที่ 2 (Freshman), ชั้นปีที่ 3 (Junior) และชั้นปีที่ 4 (Senior) โดยประกอบด้วย เพศชาย(Male), เพศหญิง(Female) และ ไม่ใช่ทั้งสองเพศ(Non-binary) จากแต่ละที่คณะที่แตกต่างกันซึ่งประกอบด้วย  
คณะจิตวิทยา (Psychology) ,เศรษฐศาสตร์ (Economics) ,วิทยาการคอมพิวเตอร์ (Computer Science) ,วิศวกรรม(Engineering) และ ชีววิทยา(Biology) รวมไปถึงรูปแบบวิธีการชำระเงินแบบต่างๆ ประกอบด้วย เงินสด (Cash), บัตรเครดิตหรือบัตรเดบิต(Credit/Debit Card) และ แอพชำระเงินผ่านมือถือ

**ข้อมูลที่ต้องการศึกษา**
- ยอดเงินที่นักศึกษาใช้จ่ายในการชำระเงินค่าอาหาร ของนักศึกษาแต่ละชั้นปีในแต่ละคณะ
- รูปแบบการชำระเงินที่นักศึกษานิยมใช้กัน

**เลือกกราฟ สำหรับการวิเคราะห์ข้อมูล**
![newplot (4)](https://github.com/Pomaccel/DADS5001-Data-Analytics-and-Data-Science-Tools-and-Programming/assets/158060569/7902496a-a459-48e6-8bbb-f304eef7e3ba)

**กราฟสำหรับใช้ในการวิเคราะห์**
เลือกใช้กราฟแท่งในการวิเคราห์ข้อมูล ปริมาณยอดเงินที่ใช้จ่าย โดยทำการพร็อตโดยแกน X แทนข้อมูลชั้นปีที่นักศึกษากำลังศึกษาอยู่ และ แกน Y แทน จำนวนยอดเงินที่นักศึกษาใช้ไปหลังจากนั้นทำการแยกข้อมูลออกเป็นกลุ่มย่อย โดยแยกเป็นคณะที่นักศึกษากำลังศึกษาอยู่ และรูปแบบการชำระเงินที่นักศึกษากลุ่มนั้นใช้

**ผลลัพธ์ที่ได้จากกราฟเบื้องต้น**
- นักศึกษาปี 4 คณะเศรษฐศาสตร์ มีการใช้เงินในการชำระค่าอาหารมากที่สุด และมีการใช้จ่ายโดยใช้บัตรเครดิตหรือบัตรเดบิตมากที่สุดเช่นกัน
- นักศึกษาปี 4 ชีววิทยา มีอัตราการใช้แอพชำระเงินผ่านมือถือ ค่อนข้างน้อย เมื่อเทียบกับ การชำระเงินผ่านบบัตรเครคิตและเงินสด 

