# ExcelDateDifGenerateCode

ExcelDateDifGenerateCode is a web-based tool designed to help you generate the DATEDIF formula for Excel effortlessly. This utility supports multiple input methods and date formats, making it versatile for different user needs.

## Features

- **Input Flexibility**:
  - Separate fields for day, month, and year (as Excel cell references).
  - Single field for a complete date (DD/MM/YYYY or Excel cell reference).
- **Year Format Options**:
  - Choose between AD (Gregorian calendar) and BE (Buddhist calendar).
- **Unit Selection**:
  - Support for DATEDIF units like `Y`, `M`, `D`, `MD`, `YM`, and `YD`.
- **Responsive Design**:
  - Built using Bootstrap for compatibility across devices.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/ExcelDateDifGenerateCode.git
   ```
2. Navigate to the project directory:
   ```bash
   cd ExcelDateDifGenerateCode
   ```
3. Open `index.html` in your preferred web browser.

## Usage

1. Select the input method:
   - Separate fields for day, month, and year (input Excel cell references, e.g., `A1`, `B1`, `C1`).
   - A single field for the complete date (input Excel cell reference, e.g., `D1`, or a date in `DD/MM/YYYY` format).
2. Choose the year format:
   - AD (e.g., 1990)
   - BE (e.g., 2533)
3. Select the desired unit for the DATEDIF formula:
   - Years (`Y`)
   - Months (`M`)
   - Days (`D`)
   - Days ignoring months and years (`MD`)
   - Months ignoring years (`YM`)
   - Days ignoring years (`YD`)
4. Click **Generate DATEDIF Code** to create the formula.
5. Copy the generated code to your Excel sheet.

## Example Output

If you input the following:
- Day: `A1`
- Month: `B1`
- Year: `C1`
- Year Format: `BE`
- Unit: `Y`

The generated formula will be:
```excel
=DATEDIF(DATE(C1-543, B1, A1), TODAY(), "Y")
```

## Technologies Used

- HTML
- JavaScript
- Bootstrap 5

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request.

## License

This project is licensed under the MIT License. See the LICENSE file for details.

## Author

[@mamazaki](https://github.com/mamazaki)

---

Feel free to customize this README file for your GitHub repository as needed.


# ExcelDateDifGenerateCode

ExcelDateDifGenerateCode เป็นเครื่องมือบนเว็บที่ช่วยคุณสร้างสูตร DATEDIF สำหรับ Excel ได้อย่างง่ายดาย เครื่องมือนี้รองรับหลายรูปแบบการป้อนข้อมูลและรูปแบบวันที่ ทำให้สะดวกต่อการใช้งานในหลากหลายความต้องการ

## คุณสมบัติ

- **ความยืดหยุ่นในการป้อนข้อมูล**:
  - ช่องแยกสำหรับวัน เดือน และปี (ใช้เป็นการอ้างอิงเซลล์ใน Excel เช่น `A1`, `B1`, `C1`)
  - ช่องเดียวสำหรับวันที่ครบถ้วน (DD/MM/YYYY หรือการอ้างอิงเซลล์ Excel เช่น `D1`)
- **รูปแบบปีที่เลือกได้**:
  - พ.ศ. (ปีพุทธศักราช)
  - ค.ศ. (ปีคริสต์ศักราช)
- **ตัวเลือกหน่วยการคำนวณ**:
  - ปี (`Y`)
  - เดือน (`M`)
  - วัน (`D`)
  - วัน (ไม่รวมเดือนและปี) (`MD`)
  - เดือน (ไม่รวมปี) (`YM`)
  - วัน (ไม่รวมปี) (`YD`)
- **การออกแบบที่ตอบสนองต่อการใช้งาน**:
  - สร้างด้วย Bootstrap รองรับการใช้งานบนอุปกรณ์หลากหลาย

## วิธีการติดตั้ง

1. คัดลอกโครงการนี้โดยใช้คำสั่ง:
   ```bash
   git clone https://github.com/yourusername/ExcelDateDifGenerateCode.git
   ```
2. เข้าไปยังโฟลเดอร์ของโปรเจกต์:
   ```bash
   cd ExcelDateDifGenerateCode
   ```
3. เปิดไฟล์ `index.html` บนเบราว์เซอร์ที่คุณต้องการ

## วิธีการใช้งาน

1. เลือกรูปแบบการป้อนข้อมูล:
   - ช่องแยกสำหรับวัน เดือน และปี (ป้อนการอ้างอิงเซลล์ Excel เช่น `A1`, `B1`, `C1`)
   - ช่องเดียวสำหรับวันที่ครบถ้วน (ป้อนการอ้างอิงเซลล์ Excel เช่น `D1` หรือรูปแบบวันที่ DD/MM/YYYY)
2. เลือกรูปแบบปี:
   - พ.ศ. (เช่น 2533)
   - ค.ศ. (เช่น 1990)
3. เลือกหน่วยที่ต้องการสำหรับสูตร DATEDIF:
   - ปี (`Y`)
   - เดือน (`M`)
   - วัน (`D`)
   - วันไม่รวมเดือนและปี (`MD`)
   - เดือนไม่รวมปี (`YM`)
   - วันไม่รวมปี (`YD`)
4. คลิก **Generate DATEDIF Code** เพื่อสร้างสูตร
5. คัดลอกสูตรที่สร้างและวางใน Excel

## ตัวอย่างผลลัพธ์

หากคุณป้อนข้อมูลดังนี้:

- วัน: `A1`
- เดือน: `B1`
- ปี: `C1`
- รูปแบบปี: `พ.ศ.`
- หน่วย: `Y`

สูตรที่สร้างจะเป็น:

```excel
=DATEDIF(DATE(C1-543, B1, A1), TODAY(), "Y")
```

## เทคโนโลยีที่ใช้

- HTML
- JavaScript
- Bootstrap 5

## การมีส่วนร่วม

ยินดีต้อนรับทุกการมีส่วนร่วม! กรุณาคัดลอกโครงการและส่งคำขอ Pull Request เพื่อเพิ่มฟีเจอร์หรือแก้ไขปัญหา

## ใบอนุญาต

โครงการนี้ได้รับอนุญาตภายใต้ใบอนุญาต MIT ดูไฟล์ LICENSE สำหรับข้อมูลเพิ่มเติม

## ผู้พัฒนา

[@mamazaki](https://github.com/mamazaki)

---

คุณสามารถปรับแต่ง README นี้ให้เหมาะสมกับโครงการของคุณเพิ่มเติมได้ตามต้องการ

