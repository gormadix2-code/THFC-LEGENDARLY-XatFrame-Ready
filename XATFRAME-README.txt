THFC LEGENDARLY — XatFrame package
==================================

ไฟล์นี้เป็นหน้า HTML แบบ standalone สำหรับนำไปโฮสต์ แล้วนำ URL ของ index.html
ไปใส่ในช่อง XatFrame ของ XatSpace (ไม่ใช่นำ ZIP ไปวางในช่อง XatFrame)

ไฟล์สำคัญ
- index.html       หน้า XatFrame
- images/          รูปหน้าปก รูปโปรไฟล์ และรูป Latest Work

วิธีเผยแพร่ให้ได้ URL สาธารณะ (ตัวอย่าง GitHub Pages)
1. แตกไฟล์ ZIP
2. สร้าง GitHub repository ใหม่ และอัปโหลด index.html กับโฟลเดอร์ images ทั้งหมด
   โดยให้ index.html อยู่ที่ root ของ repository
3. ไปที่ Settings > Pages
4. เลือก Deploy from a branch, เลือก branch main และ folder /(root) แล้ว Save
5. รอให้ GitHub Pages เผยแพร่ จากนั้นเปิด URL ที่ได้และตรวจว่ารูปทั้งหมดแสดงครบ
   URL จะมีลักษณะ https://ชื่อผู้ใช้.github.io/ชื่อ-repository/
6. ใช้ URL หน้าเว็บนั้นเป็น XatFrame URL ในหน้าแก้ไข XatSpace

วิธีใส่ใน XatSpace
1. เข้าหน้าแก้ไข XatSpace ของบัญชี xat
2. เปิดช่อง XatFrame แล้ววาง URL สาธารณะ HTTPS ของหน้า index.html
3. บันทึกและ Preview
4. หากไม่มีช่อง XatFrame หรือระบบแจ้งสิทธิ์ไม่พอ อาจต้องมี ME power ตามเงื่อนไขของ xat

ข้อควรรู้
- ต้องใส่ URL ของหน้า HTML ที่เปิดได้โดยตรง ไม่ใช่ URL ของไฟล์ ZIP หรือหน้า GitHub repository
- อย่าลบหรือย้ายโฟลเดอร์ images เพราะหน้าเว็บอ้างอิงรูปด้วย path images/...
- YouTube player แสดงอยู่ในหน้า XatFrame และผู้ชมต้องกดเล่นเองตามข้อจำกัด autoplay ของเบราว์เซอร์
- การฝัง YouTube จะทำงานได้เมื่อวิดีโอนั้นอนุญาตให้ฝัง (embedding)
- Facebook และ TeamSpeak 3 เป็นชื่อรายการในหน้าเว็บเดิม หากต้องการให้กดไปยังบัญชีจริง ต้องใส่ URL ปลายทางของคุณ
- XatFrame เป็น URL หน้าเว็บภายนอก ไม่ใช่การวาง HTML/CSS ลงในช่อง About Me
- ตรวจข้อกำหนด XatFrame และกฎของ xat ก่อนเผยแพร่จริง
