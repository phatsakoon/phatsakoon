index.html
<!DOCTYPE html >
<!-- สร้างโดย CodingNepal - www.codingnepalweb.com -->
<!DOCTYPE html >
< html  lang =" th " >
< หัว>
    < meta  charset =" UTF-8 " >
    < meta  name =" viewport " content =" width=device-width, initial-scale=1.0 " >
    < title >แอพตอบคำถามสุดเจ๋ง | CodingNepal </ title >
    <!-- <link rel="stylesheet" href="style.css"> -->
    < ?!= รวม('สไตล์') ? >
    <!-- ลิงก์ FontAweome CDN สำหรับไอคอน -->
    < link  rel =" stylesheet " href =" https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css "/>
</ head >
< ร่างกาย>
    <!-- ปุ่มเริ่มแบบทดสอบ -->
    < div  class =" start_btn " > < button >เริ่มทำแบบทดสอบ</ button > </ div >

    <!-- หน้าคำชี้แจง -->
    < div  class =" info_box " >
        < div  class =" info-title " > < span >คำเจอแบบทดสอบ</ span > </ div >
        < div  class =" info-list " >
            < div  class =" info " > 1. คุณทำแบบทดสอบทดสอบ< span > 15 วินาที</ span >ต่อ 1 ข้อ. </ div >
            < div  class =" info " > 2. เหมาะที่จะเล่นเบื่อๆ แล้วเปลี่ยนลุยใหม่ได้. </ div >
            < div  class =" info " > 3. ถามตอบไขปริศนาใหม่ </ div >
            < div  class =" info " > 4. ทำข้อสอบให้ครบทุกข้อ. </ div >
            < div  class =" info " > 5. เมื่อทำคะแนนคะแนนละ 1 คะแนน. </ div >
        </ div >
        < div  class =" ปุ่ม " >
            < button  class =" quit " >ออก</ ปุ่ม>
            < button  class =" restart " >สอบสอบ</ button >
        </ div >
    </ div >

    <!-- หน้าคำถาม -->
    < div  class =" Quiz_box " >
        < header >
            < div  class =" title " >แบบทดสอบก่อนเรียน</ div >
            < div  class =" ตัวจับเวลา " >
                < div  class =" time_left_txt " >เหลือเวลา</ div >
                < div  class =" timer_sec " > 15 </ div >
            </ div >
            < div  class =" time_line " > </ div >
        </ header >
        < ส่วน>
            < div  class =" que_text " >
                <!--ปราการที่นี่ -->
            </ div >
            < div  class =" option_list " >
                <!--เชิญแวะที่นี่ -->
            </ div >
        </ ส่วน>

        <!-- ในที่สุดของหน้าคำถาม -->
        < ส่วนท้าย>
            < div  class =" total_que " >
                <!-- นิ่วข้อที่และผู้เชี่ยวชาญทั้งหมด -->
            </ div >
            < button  class =" next_btn " >ข้อถัดไป</ ปุ่ม>
        </ ส่วนท้าย>
    </ div >

    <!-- หน้ารายงานผล -->
    < div  class =" result_box " >
        < div  class =" ไอคอน " >
            < i  class =" fas fa-crown " > </ i >
        </ div >
        < div  class =" complete_text " >คุณทำข้อสอบครบทุกข้อแล้ว! </ div >
        < div  class =" score_text " >
            <!-- รายงานผลการทดสอบ+ที่นี่ -->
        </ div >
        < div  class =" ปุ่ม " >
            < button  class =" restart " >เริ่มสอบใหม่</ button >
            < button  class =" quit " >สิ้นสุด</ ปุ่ม>
        </ div >
    </ div >
< ?!= รวม('คำถาม') ? >
< ?!= รวม('สคริปต์') ? >
</ body >
</ html >
</ html >
