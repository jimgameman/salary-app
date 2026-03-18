# แบ่งเงินเดือน — วิธีติดตั้ง

## ไฟล์ที่มี
- `index.html` — ตัวแอปหลัก
- `manifest.json` — ข้อมูล PWA
- `sw.js` — Service Worker (ใช้ออฟไลน์ได้)

---

## วิธีใช้บนโทรศัพท์ (PWA)

### iPhone / iPad
1. เปิด `index.html` ใน Safari
2. กดปุ่ม Share (กล่องมีลูกศรขึ้น)
3. เลือก **"Add to Home Screen"**
4. กด **Add** — แอปจะปรากฎหน้าจอหลักเหมือน app จริง

### Android
1. เปิด `index.html` ใน Chrome
2. กดเมนู ⋮ (สามจุด)
3. เลือก **"Add to Home screen"**
4. กด **Add**

---

## วิธีเปิดไฟล์บนมือถือ

**ง่ายที่สุด:** อัปโหลด `index.html` ขึ้น Google Drive หรือ iCloud แล้วเปิดใน browser

**หรือ** ใช้ VS Code + Live Server บน PC แล้วเข้าผ่าน IP ของเครื่อง

---

## หมายเหตุ
- ข้อมูลบันทึกใน localStorage ของ browser (ไม่ออนไลน์ ไม่มีใครเห็น)
- ใช้ได้ออฟไลน์หลังจากเปิดครั้งแรกแล้ว
- รองรับ Dark Mode อัตโนมัติ
