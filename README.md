# The money plan

เว็บวางแผนการเงินส่วนตัว (รายรับ รายจ่าย ออม/ลงทุน + แดชบอร์ด) ไฟล์เดียว ไม่มี build step

- repository นี้เก็บเฉพาะ **โค้ดเว็บ** ไม่มีข้อมูลการเงิน
- ข้อมูลจริงเก็บเป็น `data.json` ใน repository **Private** แยกต่างหาก (เช่น `money-plan-data`) เว็บอ่าน/เขียนผ่าน fine-grained token ที่จำกัดสิทธิ์ Contents: Read and write เฉพาะ repository นั้น
- token เก็บในเบราว์เซอร์ของแต่ละเครื่องเท่านั้น
