# Chord Generator - 24-Fret Fretboard & Chord Suggester

เครื่องมือสร้างคอร์ดและลำดับคอร์ดแบบ Interactive สำหรับกีตาร์ 24 เฟรต

<img width="1920" height="945" alt="image" src="https://github.com/user-attachments/assets/f996a8b5-ae93-456a-986c-77c251561e92" />

## ฟีเจอร์หลัก

### 1. Fretboard 24 เฟรต
- แสดง Fretboard แบบ Interactive พร้อม 24 เฟรต
- คลิกเลือกโน้ตบน Fretboard เพื่อสร้างคอร์ด
- รองรับ E Standard Tuning (E, A, D, G, B, E)

### 2. Chord Detection & Suggestions
- ตรวจจับคอร์ดอัตโนมัติเมื่อเลือก 3 โน้ตขึ้นไป
- แสดงคำแนะนำคอร์ดหลายแบบ (Voicings)
- แสดงรูปแบบคอร์ดบน Fretboard แบบ Mini Fretboard

### 3. Chord Progression Builder
- สร้างลำดับคอร์ดได้สูงสุด 7 คอร์ด
- ลากและวางคอร์ดเพื่อจัดเรียงลำดับ
- แสดงรูปแบบคอร์ดแต่ละตัว

### 4. Segment Composer & Playback
- สร้าง Segment หลายๆ อันเพื่อจัดโครงสร้างเพลง
- ลากคอร์ดจาก Palette หรือ Progression มาวางใน Segment
- **ฟีเจอร์ใหม่: เลือกความยาวบาร์แบบเศษส่วน**
  - Double-click ที่คอร์ดใน Segment เพื่อเลือกความยาวบาร์
  - รองรับเศษส่วน: 1/1, 1/2, 1/3, 1/4, ... 1/32
  - รองรับหลายบาร์: 2, 3, 4, ... 8 bars
  - แสดงผลแบบ Fraction Label (เช่น "1/4", "1/2", "1 bar", "2 bars")

### 5. Group Management
- จัดกลุ่มคอร์ดหลายตัวเข้าด้วยกัน
- Duplicate และ Ungroup ได้
- Drag & Drop ทั้งกลุ่ม

### 6. Audio Playback
- Preview ลำดับคอร์ดด้วยเสียง
- ปรับ Tempo (BPM) ได้
- รองรับ Time Signature ต่างๆ (4/4, 3/4, 2/4, 6/8)
- Metronome (Click Track)

## วิธีใช้งาน

### สร้างคอร์ด
1. คลิกเลือกโน้ตบน Fretboard (อย่างน้อย 3 โน้ต)
2. ระบบจะแสดงคำแนะนำคอร์ดอัตโนมัติ
3. คลิกปุ่ม "+" เพื่อเพิ่มคอร์ดเข้า Progression

### สร้าง Segment
1. ลากคอร์ดจาก Chord Palette หรือ Progression มาวางใน Segment
2. Double-click ที่คอร์ดเพื่อเลือกความยาวบาร์ (1/1, 1/2, 1/3, ... 1/32)
3. คลิก Preview เพื่อฟังเสียง

### จัดกลุ่มคอร์ด
1. Shift-click เพื่อเลือกคอร์ดหลายตัว
2. คลิกปุ่ม "Group" เพื่อจัดกลุ่ม
3. Double-click ที่กลุ่มเพื่อแก้ไข

## เทคโนโลยีที่ใช้

- HTML5, CSS3, JavaScript (Vanilla)
- Tailwind CSS
- Web Audio API
- Firebase (สำหรับเก็บข้อมูล)

## License

MIT License
