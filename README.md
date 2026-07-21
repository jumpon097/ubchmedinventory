# UBCH Med Stock Redesign v2

เวอร์ชันนี้เพิ่มตราโรงพยาบาล โลโก้งานคลังยา มาสคอต และแบ่งรายการระบบเป็นส่วนตามประเภทบริการอย่างชัดเจน

## ไฟล์
- `index.html` หน้าเว็บไซต์หลัก
- `assets/hospital-logo.png` โลโก้โรงพยาบาล
- `assets/pharmacy-logo.png` โลโก้งานคลังยา
- `assets/mascot.png` มาสคอต
- `assets/favicon.png` ไอคอนเว็บไซต์

## ติดตั้งบน GitHub Pages
1. สำรองไฟล์เว็บไซต์เดิม
2. อัปโหลด `index.html` และโฟลเดอร์ `assets` ไปยัง root ของ repository
3. Commit การเปลี่ยนแปลง
4. เปิด GitHub Pages และกดรีเฟรชแบบไม่ใช้ cache (`Ctrl + F5`)

## จุดที่แก้ไขบ่อย
- ข่าวประชาสัมพันธ์: ค้นหา `NEWS_CSV_URL` ใน `index.html`
- รายการระบบและลิงก์: แก้ในตัวแปร `services`
- หมวดบริการ: แก้ในตัวแปร `categories`
- Messenger: ค้นหา `m.me/pharmacyubcc`

พัฒนาโดย ภก.จุมพล อุทธา
