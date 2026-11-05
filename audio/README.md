แต่ GitHub ไม่สามารถสร้างไฟล์ MP3 เปล่าจากหน้าเว็บได้ แนะนำให้:
สร้างโฟลเดอร์ audio โดยสร้างไฟล์ชั่วคราว เช่น:
text
audio/README.md
กด Add file → Upload files
เลือกไฟล์เสียง MP3 จากเครื่อง
ตั้งชื่อไฟล์ให้ตรงกับ:
text
dua_h23.mp3
ตรวจสอบว่าไฟล์อยู่ที่:
text
audio/dua_h23.mp3
กด Commit changes ลง branch:
text
main
หลังจากนั้นลิงก์เสียงจะเป็น:
text
https://raw.githubusercontent.com/lbssalif-web/islamicvoip/main/audio/dua_h23.mp3
เมื่ออัปโหลดแล้ว ให้รอประมาณ 1–2 นาที จากนั้นเปิดเว็บใหม่ด้วย:
text
https://lbssalif-web.github.io/islamicvoip/?v=audio1
ถ้ายังไม่ได้ยิน ให้ลองเปิดลิงก์ MP3 โดยตรงก่อน หากเล่นได้ แปลว่าเว็บจะสามารถโหลดไฟล์เดียวกันได้ครับ.
