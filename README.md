# [การประปานครหลวง](https://www.mwa.co.th)
![mwa](https://github.com/farmsarayu/HW2/blob/master/PNOHT600627001002301.jpg)

## ภาพรวม Process ของการประปาเขตบางเขน

> เริ่มจากการสูบน้ำดิบมาจากคลองประปา น้ำดิบที่ถูกสูบจะถูกส่งไปผสมกับสารเคมีในถังกวน(clarifier) มีสารเคมีทั้งหมด 5 ตัว สารส้ม(alum),ปูนขาว,คลอรีน คลอรีนเติมก่อนจะเป็น pre-lime เติมหลังเรียกว่า post-lime สารส้มกับปูนขาวนั้นทำหน้าที่ทำปฏิกิริยากับดินทำให้ดินหนักขึ้นและตกตระกอนจมลงไปไหลไปในถังเก็บsludge และน้ำที่ใสแล้วจะไหลไปสู่บ่อกรอง(filter) ในบ่อก็จะกรองน้ำได้ในระดับไมครอน วิธีการกรองก็จะมีพวกทรายหยาบ,ทรายละเอียดพวกแอนทาไซต์และก็นอซเซิล ในส่วนของบ่อกรองนี้จะมีการทำความสะอาดเมื่อการกรองประสิทธิภาพไม่ถึงวัดโดยใช้differntial pressure ระหว่างทางด้าน output กับ input ของบ่อกรอง ซึ่งการทำความสะอาดบ่อกรองเรียกว่าการ Back Wash หรือล้างกลับนั่นเอง โดยจะปิดท่าปล่อยน้ำดิบเข้าและเปิดประตูน้ำdrainออกแล้วทำการพ่นน้ำและลม น้ำที่ใช้สูบมาจากถังพักน้ำดี(reservoir) เพื่อให้โคลนที่ติดอยู่กับนอซเซิลลอยขึ้นมา และdrainออกสู่บ่อsludgeเหมือนกับถังclarifier จะปล่อยน้ำจนกว่าน้ำจะใส หลังจากนั้นจะหยุดการbackwashแล้วรอให้น้ำไหลออกจนหมด ปิดประตูdrainน้ำลง แลัวเริ่มปล่อยน้ำดิบมากรองต่อ หลังจากน้ำที่กรองแล้วนั้นจะถูกนำไปเก็บไว้ที่ถังreservior แล้วเมื่อต้องการจะใช้ทางฝั่งโรงสูบส่ง-สูบจ่าย(sunction well)ก็จะสูบแล้วส่งออกไป สูบส่งคือการที่สูบน้ำเพื่อส่งไปโรงจ่ายอื่น ส่วนสูบจ่ายคือการสูบน้ำมาเพื่อจ่ายในพื้นที่ที่โรงนั้นๆดูแลอยู่ ในแต่ละโรงสูบ-จ่ายจะมี Surge tower กันการ water hummer (ตอนปิดวาล์วน้ำทันทีจะมีน้ำกระชากตีกลับอาจส่งผลกระทบถึงใบพัดแตก) สูง 1 เมตรจะส่งไปได้ไกล 1 กิโลเมตร
**[เพิ่มเติมสำหรับระบบผลิต](http://www.hydrotek.co.th/watertreatment-plant/)**

## ฝ่ายต่างๆ
ส่วนออโตเมชัน
+ ดูแล 7 โรงสูบหลัก ตั้งแต่ผลิตยันจ่ายน้ำ 1.ระบบอัตโนมัติPLC 2.สวิต 3.ไซเบอออฟติก 4.ไฟอลาม 5.CCTV 6.เซิฟเวอร์ 7.สายLAN
อุปกรณ์มิเตอร์วัดของส่วนออโตเมชัน
+ ก็จะมีเครื่องวัดแรงดันไฟฟ้า,กระแสไฟฟ้า,ความต้านทานไฟฟ้า ที่ผมเคยเห็นในมหาลัยอยู่แล้ว ที่ผมยังไม่เคยเห็นก็มีหลายตัว เช่น ตัวที่ใช้วัดเกี่ยวกับสายLANว่ายาวกี่เมตร,ต่อกับอะไร,ช่องอะไร,อยู่channelไหน,IPอะไร ปากกาเช็คไฟไว้ไล่สายว่าสายไหนมีไฟวิ่งอยู่ มิเตอร์ที่สามารถบักทึกผลได้และพลอตกราฟได้ เลเซอร์ใช้ตรวจสายfiber opticว่าขาดไหม ที่ทำความสะอาดสาย fiber optic
ส่วนเครื่องมือวัด
+ ทำการ Calibrate เครื่องมือวัดอย่างสม่ำเสมอ พร้อมทั้งดูแลซ่อมแซมและปรับปรุงเครื่องมือวัดที่อยู่หน้างาน
>หน้าที่ที่ทำร่วมกัน
>+ การดับไฟ จะมีการดับไฟเพื่อซ่อมบำรุงอุปกรณ์ต่างๆที่ต้องปิดเครื่องถึงจะทำได้ ในช่วงเวลากลางคืนประมาณ 4ทุ่ม จะดับไฟกันปีละครั้ง

**เครือข่ายการเชื่อมโยงกันของระบบ**
## TRANSMITTER และประเภทของTRANSMITTER
>2wires กับ 4wires ต่างกันแบบผิวเผินคือจำนวนสาย ผลที่ได้รับนั้นเหมือนกัน แต่ถ้าลึกลงไปคือ 
+ 2 wire นั้นจะมีsupplyต่อเพื่อเลี้ยงระบบในแบบอนุกรมอยู่ด้วย แล้วจะส่งผลให้สัญญาณoutputที่ได้นั้นจะขี่มากับพลังงานที่จ่ายในระบบ 
+ 4wiresนั้นจะมีการต่อ supply แยกออกไปต่างหากเลย 2 สายอีก 2 สายก็เป็นสัญญาณoutputเลย 
>ส่วนข้อดีข้อเสียของทั้ง 2 ตัวนั้น 2wires เนื่องจากสัญญาณoutput กับ พลังงานจากsourceขี่กันมา หากสายส่งยาวๆจะมีvoltage dropและทำให้สัญญาณoutputผิดเพี้ยนไป ข้อดีคือเนื่องจากใช้แค่2สายจึงถูก ส่วน4wires ตัดปัญหาเรื่องvoltage dropเพราะสัญญาณแยกจากsource แต่จะโดนเรื่องราคาของสายที่มากกว่า 2wires
## LAN
>สายLANมี2ชนิดหัวสายเรียกว่าport RJ45 STP shield แพง,กันnoise UTP unshield ถูก,ไม่กันnoise การย้ำสายLANปกติ จะย้ำ2ข้างเหมือนกัน ในทีมนี้จะย้ำเป็นแบบB โดยเรียงสีดังนี้ ขาว-ส้ม ส้ม ขาว-เขียว น้ำเงิน ขาว-น้ำเงิน เขียว ขาว-น้ำตาล น้ำตาล 
## Fiber optic
>แทนสายLANสามารถส่งได้ไกลกว่า มี2โหมด มัลติโหมด ซิงเกิลโหมด Singlemode ขนาดของเส้นใยแก้วจะมีขนาดเล็กกว่า Multimode ทำให้แสงเดินทางได้เร็วกว่า และไกลกว่า  ถ้าระยะไม่เกิน 5 กม. ใช้ Multimode ดูจะเหมาะสมกว่า อีกอย่าง singlemode อุปกรณ์ราคาแพงกว่า
ลงทุนทีเดียวใช้สาย Single Mode ผมว่าคุ้มกว่าเพราะสามารถ Up Bandwidth ไปได้ถึง 1Gbps สบาย ๆ (ระยะทางขึ้นอยู่กับ Converter Type) ถ้า Multimode 1 Gbps ได้แค่ 500 เมตร
