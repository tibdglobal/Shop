# Scan & Shop by TIBD

หน้าร้านลูกค้าของ บริษัท ทีไอบีดี จำกัด (ขายหน้างานที่บริษัท ชำระผ่าน ChillPay)

- เว็บ: https://tibdglobal.github.io/Shop/ · หน้าแบรนด์ `?brand=genio` `?brand=tracetaste` `?brand=phromprung`
- ไฟล์ `index.html` สร้างอัตโนมัติจาก `apps-script/Customer.html` ในโปรเจกต์ร้านค้า QR (`node tools/build-shop.js <โฟลเดอร์นี้>`) อย่าแก้ไฟล์นี้ตรง ๆ
- ข้อมูลสินค้า ออเดอร์ และการชำระเงินอยู่ที่ระบบหลังบ้าน (Google Apps Script) repo นี้ไม่มีรหัสหรือข้อมูลลูกค้า
