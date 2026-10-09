# COJ Installation Dashboard

หน้า GitHub Pages สำหรับแสดง [COJ Installation Dashboard](https://script.google.com/macros/s/AKfycby16rsDsTEay1piZz7s5txF0CbuGfd53kQQc1VskHQNXHAQBau-5SdFwsQoc-ougXzGTQ/exec) ใน iframe พร้อมไอคอนติดตั้งคอมพิวเตอร์

## เผยแพร่ด้วย GitHub Pages

ที่ **Settings → Pages** เลือก **Deploy from a branch**, สาขา **main**, โฟลเดอร์ **/(root)** แล้วกด **Save** หน้าเว็บจะอยู่ที่ `https://wonbinaaa.github.io/COJ-Installation-Dashboard/`

ไฟล์ `index.html` มีลิงก์ **เปิดหน้าเต็ม** เผื่อเบราว์เซอร์บางตัวไม่แสดง iframe และใช้ `?embed=1` เพื่อเปิดการฝังเฉพาะหน้าที่ร้องขอ

## โค้ด iframe สำหรับคัดลอก

```html
<iframe
  title="แดชบอร์ดแผนติดตั้งคอมพิวเตอร์"
  src="https://script.google.com/macros/s/AKfycby16rsDsTEay1piZz7s5txF0CbuGfd53kQQc1VskHQNXHAQBau-5SdFwsQoc-ougXzGTQ/exec?embed=1"
  style="width:100%;height:80vh;min-height:600px;border:0"
  loading="eager">
</iframe>
```

รีโพนี้เก็บเฉพาะหน้าฝังและไอคอน ข้อมูลรายการติดตั้งยังอ่านและบันทึกใน Google Sheets ผ่าน Google Apps Script
