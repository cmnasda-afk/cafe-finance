# SHIFT × Easy Space — Finance Dashboard

ระบบ Dashboard การเงินสำหรับ SHIFT KKC + EASY SPACE — auto-sync จาก Google Sheets, แสดงรายรับ-รายจ่าย, VAT, หัก ณ ที่จ่าย, รายงานรายเดือน/รายปี

## ฟีเจอร์

- 🔄 **Auto-sync** จาก Google Sheets ทั้ง 3 ไฟล์ (CORS proxy fallback 4 ชั้น)
- 📊 **Dashboard** กำไรเดือนนี้, MoM%, Top 5 หมวด, รายรับ/รายจ่ายแยกประเภท
- 📋 **รายการ** filter เดือน/ประเภท/สถานะ + ค้นหา + Export CSV
- 📈 **รายงาน** สรุปรายเดือน 12 เดือน + YoY% + VAT + หัก ณ ที่จ่าย
- 🌐 **รวมทุกร้าน** มุมมองรวม + แยกตามร้าน
- ⚠️ **Auto duplicate detection** ตรวจซ้ำข้ามชีตอัตโนมัติ
- ⌨️ **Keyboard shortcuts** (1/2/3 แท็บ, ←/→ เดือน, S sync)
- 📱 **Responsive** ใช้งานบนมือถือได้

## เปิดใช้งาน

แค่เปิด `index.html` — ไม่ต้องลงอะไร

- **Local:** ดับเบิลคลิกไฟล์
- **Online:** เปิด URL ที่ deploy ไว้

## โครงสร้าง

ไฟล์เดียว — HTML + CSS + JS + (option) seed data ฝังในไฟล์เดียว ใช้ Chart.js + SheetJS จาก CDN (lazy-loaded)
