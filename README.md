# 📋 แบบสอบถามความพึงพอใจต่อระบบศูนย์รวมบริการเอกสาร LAMS Document Hub

> **คณะศิลปศาสตร์และวิทยาการจัดการ มหาวิทยาลัยสงขลานครินทร์ วิทยาเขตสุราษฎร์ธานี**  
> 🌐 **เว็บไซต์ทางการ (Live Web App)**: [https://thanachai-p.github.io/lams-survey/](https://thanachai-p.github.io/lams-survey/)

---

## 🏛️ เกี่ยวกับโครงการ (Overview)

เว็บแอปพลิเคชันแบบสอบถามความพึงพอใจของผู้รับบริการ (อาจารย์, บุคลากร, นักศึกษา และผู้ใช้ทั่วไป) ต่อการใช้งาน **ระบบศูนย์รวมบริการเอกสารอิเล็กทรอนิกส์ LAMS Document Hub** เพื่อนำข้อเสนอแนะและผลการประเมินไปพัฒนาและยกระดับคุณภาพการให้บริการอย่างต่อเนื่อง

---

## ✨ คุณสมบัติเด่น (Features)

- **🎨 Anti-AI-Slop & Human-Crafted UX**: ดีไซน์สะอาด ภูมิฐาน สไตล์ Digital Governance ตามอัตลักษณ์ของคณะศิลปศาสตร์และวิทยาการจัดการ ม.อ.สุราษฎร์ธานี
- **📱 Responsive & Touch-Optimized**: รองรับการใช้งานสมบูรณ์แบบบนสมาร์ตโฟน แท็บเล็ต และคอมพิวเตอร์ (Touch Target ขั้นต่ำ 44×44px)
- **♿ Accessibility Standards (WCAG 2.1 AA/AAA)**: 
  - ออกแบบตามเกณฑ์ Semantics (`role="radiogroup"`, `role="radio"`, `aria-checked`)
  - รองรับโหมดลดการเคลื่อนไหว (`@media (prefers-reduced-motion: reduce)`)
  - ค่า Contrast Ratio สูง อ่านง่ายสบายตา
- **🏆 Personal Recap Card (สรุปผลการประเมิน)**:
  - แสดงคะแนนเฉลี่ยตัวเลขชัดเจน `X.X / 5` พร้อมป้ายระดับความพึงพอใจ
  - สรุปคะแนนประเมินรายข้อ 7 รายการสไตล์ Digital Governance ปราศจากรูปดาวพาณิชย์
- **🔒 Privacy by Design & Security Hardening**:
  - ประเมินแบบไม่ระบุตัวตน 100% (Anonymous)
  - ป้องกัน XSS ผ่าน DOM TextContent Rendering
  - ป้องกัน Spreadsheet Formula Injection Guard (`toSheetText`)
  - เชื่อมต่อ Google Sheet แบบ Write-Only ผ่าน Google Apps Script Web App

---

## 🛠️ สถาปัตยกรรมเทคโนโลยี (Tech Stack)

- **Frontend**: Single-File HTML5, Tailwind CSS (CDN), Lucide Icons, Google Fonts (`Prompt`)
- **Backend / Database**: Google Sheets + Google Apps Script Web App (Serverless Endpoint)
- **Hosting**: GitHub Pages

---

## 📄 ลิขสิทธิ์ (License)

© 2026 คณะศิลปศาสตร์และวิทยาการจัดการ มหาวิทยาลัยสงขลานครินทร์ วิทยาเขตสุราษฎร์ธานี  
All rights reserved.
