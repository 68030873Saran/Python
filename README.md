# คำอธิบายข้อมูล (Data Description)

โฟลเดอร์นี้อธิบายข้อมูลที่ใช้ในโครงงาน **IT Salary Analysis**

## 1. แหล่งที่มาและสิทธิ์การใช้ข้อมูล

| หัวข้อ | รายละเอียด |
| --- | --- |
| ชื่อชุดข้อมูล | Video Game Sales |
| แหล่งที่มาเดิม |[ https://www.kaggle.com/datasets/parulpandey/2020-it-salary-survey-for-eu-region ](https://www.kaggle.com/datasets/gregorut/videogamesales)|
| ประเภทข้อมูล |ชุดข้อมูลนี้ประกอบด้วยรายชื่อวิดีโอเกมที่มียอดขายมากกว่า 100,000 ชุด โดยได้มาจากการดึงข้อมูลจากเว็บไซต์vgchartz.com|

## 2. ไฟล์ในโฟลเดอร์นี้

| ตำแหน่งไฟล์ | คำอธิบาย |
| --- | --- |
| `Downloads\Python\Game_data` | ไฟล์ดิบตามที่ดาวน์โหลดมา **ห้ามแก้ไขด้วยมือ** มี  16,598 แถว 11 คอลัมน์ |
| `Downloads\Python\DATA_GAME_clean` | ข้อมูลที่ล้างแล้ว 2,490 แถว 8 คอลัมน์  |



## 3. ยอดขายวิดีโอเกม (Video Game Sales) ของ `DATA_GAME_clean`

ข้อมูลหลังจากทำความสะอาดแล้วมีทั้งหมด 2,490 แถว ตารางต่อไปนี้แสดงชื่อคอลัมน์ ชนิดข้อมูล คำอธิบาย 
| คอลัมน์ |  | ชนิดข้อมูล | คำอธิบาย / ค่าที่เป็นไปได้ |  |
| --- | --- | --- | --- | ---: |
| `age` | Age | ตัวเลข | อายุของผู้ตอบแบบสอบถาม หน่วยเป็นปี | 0 |
| `gender` | Gender | ข้อความ | เพศของผู้ตอบแบบสอบถาม ได้แก่ Male, Female และ Diverse (กลุ่ม Diverse มี 2 รายการ) | 3 |
| `city` | City | ข้อความ | เมืองที่ทำงาน ได้แก่ Berlin, Munich, Frankfurt และ Other | 0 |
| `position` | Position | ข้อความ | ชื่อตำแหน่งงานที่ผู้ตอบแบบสอบถามกรอกด้วยตนเอง มีทั้งหมด 135 รูปแบบ | 2 |
| `exp_total_years` | Total years of experience | ตัวเลข | จำนวนปีของประสบการณ์ทำงานทั้งหมด | 0 |
| `exp_germany_years` | Years of experience in Germany | ตัวเลข | จำนวนปีของประสบการณ์ทำงานในประเทศเยอรมนี | 44 |
| `seniority` | Seniority level | ข้อความ | ระดับตำแหน่งงาน ได้แก่ Junior, Middle, Senior, Lead, Head และ Other | 0 |
| `main_tech` | Your main technology / programming language | ข้อความ | เทคโนโลยีหรือภาษาโปรแกรมหลักที่ใช้งาน กรอกด้วยตนเองและอาจมีรูปแบบการสะกดต่างกัน เช่น Python และ python | 109 |
