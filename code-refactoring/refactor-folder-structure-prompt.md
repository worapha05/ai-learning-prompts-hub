📍 **Nav:** [`🏠 AI Learning Prompts Hub`](../README.md)

---

# ♻️ Directory Restructuring & File Cleanup Prompt

- **Topic:** Refactor โครงสร้างโฟลเดอร์ย่อย จัดหมวดหมู่เนื้อหาตามระดับความยาก และ Reformat ไฟล์ทั้งหมด
- **Category:** Directory & Code Refactoring

---

## 🎯 Context & Goal

ใช้สำหรับสั่ง AI ให้ช่วยทำความสะอาด (Cleanup) โครงสร้างโฟลเดอร์ ย้ายไฟล์เรียนรู้เข้าตามระดับ `01-beginner`, `02-intermediate`, `03-expert` พร้อมทั้งจัด Format โค้ด/เอกสาร และสร้าง Script ช่วยย้ายไฟล์ให้อัตโนมัติ

---
### 1. 🚀 Master Refactor Prompt (Prompt หลัก)
```text
ช่วย refactor โครงสร้างโฟลเดอร์ด้านล่างนี้ ให้ทุก sub-folder มีโครงสร้างมาตรฐานเหมือนกันทั้งหมด:

## โครงสร้างเป้าหมายในทุก sub-folder
- `01-beginner/`
- `02-intermediate/`
- `03-expert/`
- `README.md`
- `.gitignore`

## ข้อกำหนดและเงื่อนไข
1. **Cleanup & Re-structure:** ลบหรือย้ายไฟล์ที่ไม่ควรอยู่ระดับ root ของ sub-folder (เช่น `node_modules`, `package.json`, `package-lock.json`, `tsconfig.json`, `eslint.config.mjs`, โฟลเดอร์ `scripts`) ออกจากระดับนอก ให้เหลือเฉพาะโครงสร้างเป้าหมายเท่านั้น
2. **Content Categorization by Level:** จัดวางโค้ด/เนื้อหาการเรียนรู้ ตัวอย่างโปรเจกต์ หรือไฟล์ Config ต่างๆ ให้อยู่ในระดับที่ถูกต้องตามความเหมาะสม (`01-beginner/`, `02-intermediate/`, `03-expert/`) ไม่มากองไว้ด้านนอก
3. **Format Code & Documentation (Clean & Scannable):**
   - รีฟอร์แมต (Format) เนื้อหาในทุกไฟล์ ทั้งไฟล์โค้ด (.js, .ts, .py ฯลฯ) และไฟล์สอน/เอกสาร (.md, .txt) ให้สะอาด อ่านง่าย
   - จัด Indent (ย่อหน้า), เว้นวรรค (Spacing), และเว้นบรรทัด (Line Breaks) ระหว่างบล็อกโค้ด/หัวข้ออย่างเหมาะสม ไม่กระจุกตัวหรือติดกันเป็นพืด
4. **Output Target:** แสดงผลลัพธ์เป็น Directory Tree ที่สะอาด อ่านง่าย พร้อม Bash / PowerShell Script สำหรับสั่งรันจัดโครงสร้างและไฟล์อัตโนมัติ
5. **Feasibility Check & Impact Analysis:** หากมีไฟล์/โฟลเดอร์ใดที่ไม่ควรลบทิ้ง (เช่น หากลบ `package.json` หรือ `tsconfig.json` แล้วโปรเจกต์จะทำงานไม่ได้) ให้ระบุสาเหตุ ผลกระทบ และแนะนำวิธีจัดเก็บที่ถูกต้องลงในแต่ละระดับความยาก
6. **Auto-Fix & Bug Prevention (Every File/Folder):** 
   - เพิ่มกระบวนการตรวจสอบและแก้ไข Bug หรือ Error ที่อาจเกิดขึ้นระหว่างการย้าย/ลบ/สร้างไฟล์ทุกไฟล์ในสคริปต์ (เช่น ติด Permission Denied, ไฟล์ถูก Process อื่นล็อกไว้, หรือปัญหา Path ไม่ถูก)
   - ปรับแต่งไฟล์ `.gitignore` ในแต่ละ sub-folder ให้ครอบคลุมไฟล์ขยะหรือโฟลเดอร์ที่ไม่ควร Push ขึ้น Git (เช่น `node_modules`, `.env`, build outputs)
7. **Validation & Self-Correction:** ตรวจสอบความถูกต้องของ Directory Tree, สคริปต์ และเนื้อหาไฟล์อีกครั้งหลังทำเสร็จ หากพบข้อผิดพลาด จุดขัดแย้ง หรือ Format ที่ยังไม่อ่านง่าย ให้แก้ไขให้เรียบร้อยก่อนส่งผลลัพธ์สุดท้าย
```
### 2. 🔄 Follow-up & Refinement Prompts (Prompt ตามเก็บรายละเอียด)
#### 📌 Iteration 1: ย้ำการ Reformat และจัดระดับเนื้อหา (Reinforce Formatting & Levels)
```text
แก้ format ของทุกไฟล์ ไม่ว่าจะโค้ดไฟล์ ไฟล์สอน แก้ให้อ่านง่าย มีเว้นว่าง
แก้ให้ทุกเนื้อหาสอนอยู่ตามระดับของมัน beginner intermediate expert
แก้ปัญหาที่อาจเกิดขึ้นของทุกไฟล์ด้วย
```
#### 📌 Iteration 2: ตรวจสอบความสมบูรณ์ครั้งสุดท้าย (Validation Check)
```text
ไฟล์ไม่มีปัญหาหลังแก้ไขใช่ไหม
```
