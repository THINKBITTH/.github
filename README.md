# 🌟 Think Bit — Company Bio

> 🧠 We build practical systems for complex documents and data-heavy workflows.

Think Bit คือทีมเทคโนโลยีที่โฟกัสการสร้างซอฟต์แวร์เพื่อ **“ทำให้งานยากกลายเป็นงานที่ทำได้จริง”**  
โดยเฉพาะงานที่เกี่ยวข้องกับ **ข้อมูลจำนวนมาก, เอกสารเชิงกฎหมาย/ภาษี, และกระบวนการหลังบ้านที่ต้องการความแม่นยำสูง**  
เราทำงานแบบ *product-minded* คิดจากปัญหาจริงขององค์กร แล้วออกแบบระบบที่เชื่อมต่อการทำงานตั้งแต่ต้นทางถึงปลายทางให้ไหลลื่น ✅ ตรวจสอบได้ 🔍 และขยายต่อได้ 🚀

---

## 🏗️ เราทำอะไร

### 📄 ระบบจัดการเอกสาร + OCR/AI Workflow
- 🧩 ออกแบบ pipeline ตั้งแต่รับไฟล์ → แยกหน้า → เก็บแบบมี metadata → OCR → ตรวจคุณภาพ → แจ้งผลแบบ real-time  
- ☁️ รองรับการทำงานบนคลาวด์แบบ serverless เช่น **Azure Functions / AWS Lambda** และสเกลตามปริมาณงาน  
- 🗂️ เก็บผลลัพธ์เชิงโครงสร้างลง **NoSQL** เพื่อให้ค้นหา/วิเคราะห์ต่อได้ทันที

### ✅ ระบบตรวจสอบความถูกต้องของข้อมูล (Validation Engine)
- 🧠 สร้างตัวตรวจสอบเอกสารตามประเภท + บริบทองค์กร (company-warehouse specific rules)  
- ➕ คำนวณค่าที่สัมพันธ์กัน เช่น **sum / running totals / ratios**  
- 🧾 ส่งผลลัพธ์แบบ per-field พร้อม `expected / actual / passed`  
- 🛡️ ไม่แก้ข้อมูลดิบ แต่ “ชี้จุดผิด” ให้ผู้ใช้แก้ได้ง่าย

### 🔌 API และ Backend สำหรับงานองค์กร
- 🛠️ พัฒนา API ด้วย **Node.js / TypeScript**, ORM (**Prisma / Drizzle**), ฐานข้อมูล **SQL Server + NoSQL**  
- 🧱 วางโครงสร้างโปรเจกต์แบบขยาย route ได้ในอนาคต (auth, master data, report ฯลฯ)  
- 🚢 รองรับ CI/CD และ deploy บน **AWS (Elastic Beanstalk, ECS/ALB)** และ **Azure**

### 🎨 Frontend/UX สำหรับการทำงานภายใน
- 🔎 UI ที่เน้นการค้นหา/กรอง/แสดงผลข้อมูลขนาดใหญ่แบบใช้งานง่าย  
- ⚛️ โครงสร้าง **React + TypeScript** และออกแบบ component ให้ reusable/maintainable  
- ⚡ รองรับ realtime notifications

---

## 💎 จุดเด่นของเรา
- 🧭 **เข้าใจปัญหาเชิงกระบวนการจริง**: ทำให้ระบบเวิร์กโฟลว์ขององค์กร “ดีขึ้นจริง”  
- 🔍 **ตรวจสอบได้และโปร่งใส**: ทุก step มี trace + expected vs actual + error reporting ชัดเจน  
- 🧩 **ขยายต่อได้ง่าย**: โครงสร้าง modular + rule-driven รองรับเอกสาร/ธุรกิจใหม่ได้เร็ว  
- 🤝 **ทำงานแบบคู่คิด**: ทำงานใกล้ชิดกับผู้ใช้/เจ้าของกระบวนการ เพื่อให้ผลลัพธ์ตรงงานจริง

---

## 🧰 เทคโนโลยีที่ใช้บ่อย

**Backend & Data**
- 🟦 Node.js, TypeScript, Python  
- 🔷 Azure Functions, AWS Lambda  
- 🗄️ SQL Server (RDS), Prisma/Drizzle ORM  
- 🟩 Cosmos DB, DynamoDB  

**Document AI**
- 🤖 Amazon Textract (Custom Queries/Adapter)  
- 🧠 Azure Form Recognizer  

**Infra & DevOps**
- ☁️ AWS Elastic Beanstalk  
- 🚦 ECS + ALB  
- 🪣 S3, SNS  
- 🔁 Git-based CI/CD  

**Frontend**
- ⚛️ React + Vite + TypeScript  
- 📱 Flutter  
- 🅰️ Angular  
- 🔔 Realtime via SignalR / WebPubSub  

---

## 🚀 วิสัยทัศน์
เราต้องการเป็นทีมที่ช่วยองค์กรปลดล็อกงานหลังบ้านที่ซับซ้อน  
ด้วยการเปลี่ยน **“เอกสารและข้อมูลที่กระจัดกระจาย”** ให้เป็นระบบดิจิทัลที่  
✅ เชื่อถือได้  
⚙️ อัตโนมัติได้  
📊 พร้อมต่อยอดเป็นการวิเคราะห์เชิงธุรกิจในระยะยาว

---

## 🤍 Contact / Collaboration
หากอยากคุยเรื่องการทำ OCR workflow, validation engine, หรือระบบหลังบ้านที่ซับซ้อน  
ยินดีร่วมออกแบบทางออกที่ “ใช้ได้จริงในองค์กร” ไปด้วยกันครับ ✨
