1.จงวิจารณ์คำกล่าวอ้างต่อไปนี้
  ตามคำกล่าวที่อ้างมาทั้ง2กระบวนการมีความแตกต่างกันแต่มีจุดมุ่งหมายเดียวกันคือการพัฒนาซอฟแวร์ให้สำเร็จตามเป้าหมาย
แต่ที่มีความแตกต่างกันเป็นเพราะวิธีการในการดำเนินงาน agile มีกระบวนการทำที่รวดเร็วทำไปเรื่อยๆแล้วส่งให้ลูกค้าตรวจสอบ
อยู่เป็นระยะเพื่อเน้นความพึงพอใจของลูกค้า ส่วน waterfall นั้นจะมีการใช้เวลาในการพัฒนาซอฟแวร์ที่นานเพราะ
เหมาะสำหรับซอฟแวร์ที่ต้องการความแน่นอนชัดเจนไม่คลุมเครือ จะทำการพัฒนาจนสำเร็จและจะไม่กลับมาทำซ้ำอีก ดังนั้นไม่ว่าจะเป็น
กระบวนการไหนก็ย่อมมีจุดประสงค์เดียวกัน แต่วิธีการต่างกันนั่นเอง

2.จงวิจารณ์คำกล่าวอ้างต่อไปนี้
  สำหรับการทำ version control ในปัจจุบัน ไม่ว่าจะ Git หรือ SVN/CVS ไม่ว่าจะแบบไหนก็ยังมีผู้คนใช้งานอยู่
git นั้นมีความปลอดภัยในการเก็บcodeที่สูงเพราะหากลบไปแล้วถ้าเราต้องการกู้ก็ยังสามารถทำได้ แต่ทั้งนี้ขึ้นอยู่กับปัจจัยหลายอย่าง
เช่น วิธีการนำไปใช้ จำนวนคนในทีม ปริมาณงานที่ต้องแก้ไขร่วมกันหรืออื่นๆ 

3.ถ้าต้องการสร้าง branch
$ git checkout -b feature1
$ git push origin <branch>
กรอก user หรือ E-mail
กรอกPassword

4.คำสอนจากรุ่นพี่โปรแกรมเมอร์
  ถ้าโชคร้าย อาจจะเกิด conflict หรือข้อขัดแย้งของการเปลี่ยนแปลง ดังนั้น คุณจะต้องทำการแก้ไขข้อขัดแย้งเหล่านั้นด้วยตัวเอง
ต่อจากนั้นให้ทำการบันทึกการเปลี่ยนแปลงด้วยคำสั่ง git add <filename> แต่ก่อนที่จะ merge การเปลี่ยนแปลง 
สามารถตรวจสอบความแตกต่างของสิ่งที่แก้ไข ด้วยคำสั่ง git diff <source_branch> <target_branch>

5.จงแสดงผลลัพธ์ที่ได้จาการรัน Ruby
   abcde"a".."e"

6.จงวิจารณ์คำกล่าวอ้างต่อไปนี้
  เทคโนโลยี Desktop Application ไม่สามารถตอบสนองความต้องการการบริหารจัดการได้ โดยเฉพาะการทำธุรกิจที่ต้องปรับเปลี่ยนไปตลอดเวลา ข้อมูลมีการเคลื่อนไหวตลอดเวลา 
  เพื่อตอบสนองภาวะตลาดที่แปรเปลี่ยน ระบบ Client-Server Application ตัวโปรแกรมมีความซับซ้อน การแก้ไข การ Upgrade ทำได้ยุ่งยาก อย่างกรณี หากต้องการ Upgrade หรือเพิ่มคุณสมบัติเพิ่มเติมให้กับ Application ที่ตัวเซิร์ฟเวอร์ต้องหยุดระบบทั้งหมด และเมื่อ Upgrade ที่เซิร์ฟเวอร์แล้ว ก็จำเป็นต้อง Upgrade ที่ Client ด้วย หากระบบมีผู้ใช้งานจำนวนมาก จะยิ่งเพิ่มความยุ่งยากมากขึ้น จากตัวอย่างปัญหาเหล่านี้ ถูกจัดการด้วยเทคโนโลยี Web Application (เว็บแอพพลิเคชั่น) เพราะ Web Application สามารถตอบสนองปัญหาข้างต้นได้เป็นอย่างดี และสามารถแทนที่ Desktop Application ที่เป็น Client-Server Application ได้เป็นอย่างดี

7.อธิบายกลไกของ MVC ใน Rails
 user จะมีการเรียกหาข้อมูลที่ต้องการผ่าน Rails router เพื่อรอการตอบกลับจาก index และจะส่ง HTML กลับมาที่หน้า Browser
 
8.ยกตัวอย่าง framework
  PHP กับ Rails
PHP ถูกใช้สร้างเว็บใหญ่ๆ อย่าง Facebook และ Ruby สร้าง Twitter
Ruby ถูกจัดว่ามี usability มากกว่าใครเพื่อน และโปรแกรมเมอร์ก็มีความสุขกับการเขียนโปรแกรมเสียด้วย
PHP มีอัตราจ้างงานสูงที่สุด และจำนวนโปรแกรมเมอร์ใน LinkedIn ก็มีมากกว่า 2 ภาษารวมกันเกือบ 10 เท่า
สรุป PHP มีการใช้งานที่ง่ายสะดวกเข้าใจได้ง่ายเพราะเป็นพื้นฐาน ส่วน Rails จะมี Library น้อยกว่าภาษาอื่น

9.Heroka คืออะไร
  Heroku เป็น Platform as a Service (Paas) ที่ให้เราใช้งานได้ฟรี (มีแบบเสียเงินด้วย) โดยรองรับภาษาโปรแกรมที่หลากหลาย เช่น Ruby, PHP, Node.js, Python, Java, Clojure, Scala และยังสามารถสร้าง buildpack สำหรับภาษาอื่นๆได้ เช่น Lua ที่รันอยู่บน OpenResty ได้อีกด้วย
มีบทบาทกับการพัฒนา web application ที่สามารถใช้งานได้สะดวก ลดเวลาในการพัฒนาแอปโดยตั้งเป้าหมายไปที่การพัฒนาแอปเลย ไม่ต้องมาตั้งค่าเครื่องเซิร์ฟเวอร์เองให้เปลืองเวลา เพราะอาจจะไม่มีทรัพยากรณ์มากพอ ทั้งในด้านบุคคลและอื่นๆ อยากจะมุ่งเน้นไปที่พัฒนาโปรแกรมเพียงอย่างเดียว

10.ทำไมสาขาวิชาวิทยาการสารสนเทศจึงบรรจุวิชานี้เข้ามาในหลักสูตร
  เพื่อให้ได้ความรู้เบื้องต้นเกี่ยวกับวิศวกรรมซอฟต์แวร์ กระบวนการพัฒนาซอฟต์แวร์ การบริหารโครงการซอฟต์แวร์กระบวนการวิศวกรรมความต้องการ แบบจำลองระบบ การออกแบบ การสร้างซอฟต์แวร์ การทดสอบ การตรวจสอบความถูกต้อง ตัวชี้วัดซอฟต์แวร์ การประกันคุณภาพซอฟต์แวร์ การจัดการและควบคุมการเปลี่ยนแปลงในการพัฒนางานด้านซอฟต์แวร์ การบำรุงรักษาซอฟต์แวร์
