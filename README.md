#  *THAILAND JIBI.*
 **THAILAND JIBI.** เป็นโปรแกรมสำหรับการเรียนรู้ ศึกษา หาข้อมูล อีกทั้งยังสามารถเป็นไกด์ในการท่องเที่ยว ที่เกี่ยวกับจังหวัดและอำเภอต่างๆในประเทศไทยได้อีกด้วย.
 
> วัตถุประสงค์
1. เพื่อให้ทราบถึงข้อมูลภายในจังหวัดของแต่ละภาคในประเทศไทย. 
2. เพื่อเป็นแนวทางในการศึกษาข้อมูลของจังหวัดและอำเภอต่างๆในประเทศไทย.
3. เพื่อเป็นไกด์สำหรับการท่องเที่ยวในตัวจังหวัดและอำเภอในประเทศไทย.
4. เพื่อเป็นแนวทางสำหรับผู้ที่สนใจในการพัฒนา GUI เกี่ยวกับข้อมูลของภูมิภาค จังหวัด และอำเภอต่างๆในประเทศไทย.

 > โปรแกรม THAILAND JIBI.
 ###### ตัวอย่างหน้าตาของโปรแกรม
 ![1](https://user-images.githubusercontent.com/45451711/49216402-8f39b780-f3fd-11e8-822f-dcb0490132d1.JPG)
 
 ###### อธิบายโปรแกรม 1
 
 ![2](https://user-images.githubusercontent.com/45451711/49216695-45050600-f3fe-11e8-8d2a-d92732a38f2e.jpg)

> ปุ่ม ถัดไป(Next) เป็นปุ่มสำหรับการไปต่อในหน้าถัดไป

```

การใช้คำสั่ง code.


if (JOptionPane.showConfirmDialog(this,"ยินดีต้อนรับ  :  " +tfname.getText()+"\n"+"ฉันมาจาก      :  " +tfcountry.getText(),"ยินดีต้อนรับ (Welcome) ",JOptionPane.OK_CANCEL_OPTION)==JOptionPane.OK_OPTION){
            
            new Thailandjibi().setVisible(true);
            this.setVisible(false);
        }

```
###### อธิบายโปรแกรม 2
![3](https://user-images.githubusercontent.com/45451711/49217391-0708e180-f400-11e8-8fe9-47959c1b278f.jpg)

> ปุ่ม ยกเลิก(Cancel) เป็นปุ่มสำหรับการยกเลิกโปรแกรม แต่จะมีข้อความเด้งขึ้นมาถามด้วยว่าจะยกเลิกโปรแกรมจริงหรือไม่ ดังรูป

```

การใช้คำสั่ง code.


if (JOptionPane.showConfirmDialog(this,"คุณต้องการยกเลิกใช่หรือไม่?" +"\n"+ "( Do you want to cancel? )","Cancel ?",JOptionPane.YES_NO_OPTION)==JOptionPane.YES_OPTION){
            System.exit(0);
        }

```
###### อธิบายโปรแกรม 3
![4](https://user-images.githubusercontent.com/45451711/49217769-150b3200-f401-11e8-982b-d1a8dd73c37d.JPG)

> เมื่อกด ถัดไป(Next) จะปรากฎหน้าต่าง ดังรูป และมีให้เลือกภูมิภาคต่างๆ เมื่อกดจะเด้งไปยังหน้าถัดไป ส่วนทางซ้ายมือจะเป็นปุ่ม ย้อนกลับ(Back) ไปยังหน้าลงชื่อเข้าใช้อีกรอบ

```

การใช้คำสั่ง code. (ภูมิภาค)

new N().setVisible(true);
        this.setVisible(false);

```
###### และเมื่อเรากดแต่ละภูมิภาค ก็จะปรากฎหน้าต่าง ดังรูป
![5](https://user-images.githubusercontent.com/45451711/49218285-9f07ca80-f402-11e8-8c70-5e809406742b.JPG)

![6](https://user-images.githubusercontent.com/45451711/49218312-a929c900-f402-11e8-81bf-1fbe769ce8aa.JPG)

![7](https://user-images.githubusercontent.com/45451711/49218327-b3e45e00-f402-11e8-9213-2939d2f8d489.JPG)

![8](https://user-images.githubusercontent.com/45451711/49218344-bba40280-f402-11e8-8ac6-15c83dadfef6.JPG)

![9](https://user-images.githubusercontent.com/45451711/49218356-c3fc3d80-f402-11e8-8109-2765c6b6e5fe.JPG)

![10](https://user-images.githubusercontent.com/45451711/49218366-ca8ab500-f402-11e8-84b0-6c11cedaebf0.JPG)

> เมื่อกด เสร็จสิ้น(Finish) จะเป็นการจบจากโปรแกรม ก่อนที่จะออกโปรแกรม จะมีหน้าต่างข้อความขึ้นมาถามว่าต้องการออกจริงๆหรือไม่ เป็นอันเสร็จสิ้น.

```

การใช้คำสั่ง code. (เสร็จสิ้น)

if (JOptionPane.showConfirmDialog(this, "ขอบคุณ แล้วพบกันใหม่" +"\n"+ "(Thank you for using ,See you.)" ," Finish ",JOptionPane.OK_CANCEL_OPTION)==JOptionPane.OK_OPTION){
            System.exit(0);
        }

```

###### ผู้พัฒนาโปรแกรม
 - นายกรกช กันทะปัญญา  60022123
 - นายทัตพงศ์ รัตนวิชัย  60020660


