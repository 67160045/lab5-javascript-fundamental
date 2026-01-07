LAB 05 – JavaScript Explanation & Output
ไฟล์ explain.md นี้จัดทำขึ้นเพื่อแสดงผลลัพธ์จากการทำงานของโค้ด JavaScript
พร้อมอธิบายขั้นตอนการทำงานของโค้ดว่าเหตุใดจึงได้ผลลัพธ์ดังกล่าว
สามารถเปิดอ่านได้โดยตรงบน GitHub

Activity 1: Variables & Data Types ✅
Challenge: Create a Person Object
การทำงาน: ประกาศตัวแปร person แบบ Object เพื่อรวมกลุ่มข้อมูล เช่น firstName, lastName และ age

ผลลัพธ์: เมื่อเข้าถึง Property หรือแสดงผลผ่าน Console จะเห็นข้อมูลถูกจัดเก็บเป็นคู่ Key-Value ที่สัมพันธ์กัน

Key file: 01-variables.js

Activity 2: Functions & Arrow Functions ✅
Returning Objects
การทำงาน: สร้างฟังก์ชันที่รับพารามิเตอร์แล้วส่งค่ากลับ (Return) ออกมาเป็น Object ใหม่ทันที

ผลลัพธ์: ทำให้สามารถสร้างชุดข้อมูลที่มีโครงสร้างเหมือนกันได้หลายชุดอย่างรวดเร็ว

Function as Parameter (Callback)
การทำงาน: การส่งฟังก์ชันหนึ่งเข้าไปเป็น Argument เพื่อให้ฟังก์ชันหลักเรียกใช้งาน (Execute) ในภายหลัง

ผลลัพธ์: ช่วยให้โค้ดมีความยืดหยุ่น สามารถปรับเปลี่ยนพฤติกรรมการทำงานได้โดยไม่ต้องแก้ฟังก์ชันหลัก

Key file: 02-functions.js

Activity 3: Control Flow & Logic ✅
Short-Circuit Evaluation
การทำงาน: ใช้ตัวดำเนินการ && เพื่อตรวจสอบเงื่อนไขก่อนรันคำสั่งถัดไป หรือ || เพื่อกำหนดค่าเริ่มต้น (Default value)

ผลลัพธ์: โค้ดกระชับขึ้นและป้องกัน Error ในกรณีที่ตัวแปรไม่มีค่า

Form Validation
การทำงาน: ใช้ if-else ตรวจสอบเงื่อนไขข้อมูลนำเข้า (Input) เช่น ความยาวตัวอักษรหรือความถูกต้องของรูปแบบ

ผลลัพธ์: คืนค่า Boolean (True/False) เพื่อควบคุมการทำงานของระบบให้ปลอดภัย

Key file: 03-control-flow.js

Activity 4: Loops & Array Methods ✅
Chaining methods
การทำงาน: การนำ Method เช่น .filter() มาต่อด้วย .map() เพื่อประมวลผลข้อมูลเป็นทอดๆ ในบรรทัดเดียว

ผลลัพธ์: ข้อมูลใน Array ถูกคัดกรองและแปลงรูปแบบอย่างมีประสิทธิภาพโดยไม่รบกวนข้อมูลต้นฉบับ

Challenge: Student Grades
การทำงาน: วนลูปผ่าน Array ของนักเรียนแล้วใช้เงื่อนไขตัดเกรด (เช่น A, B, C) ตามคะแนนที่ระบุ

ผลลัพธ์: ได้รายการสรุปเกรดของนักเรียนทุกคนที่พร้อมนำไปแสดงผล

Key file: 04-loops.js

Activity 5: Integration ✅
Activity 5: Integration - Quiz Application

การทำงาน: นำความรู้เรื่อง Array of Objects มาเก็บโจทย์, ใช้ Loop วนคำถาม, และใช้ Function ตรวจคำตอบ

ผลลัพธ์: แอปพลิเคชันสามารถถามตอบ ตรวจสอบความถูกต้อง และสะสมคะแนนรวม (Score) ของผู้ใช้ได้

Key file: 05-integration.js
