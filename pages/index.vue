<template>  
<html>
<div class="bg_page"> 



<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">
<link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Inconsolata">

<style>
.bg_page {
  background: linen;
  align-items: center;
  text-align: center;
}

.title {
  font-family:
    'Quicksand',
    'Source Sans Pro',
    -apple-system,
    BlinkMacSystemFont,
    'Segoe UI',
    Roboto,
    'Helvetica Neue',
    Arial,
    sans-serif;
  display: block;
  font-weight: 300;
  font-size: 60px;
  color: #FFFF;
  letter-spacing: 1px;
}

</style>

<!-- Links (sit on top) -->
<div class="w3-top">
  <div class="w3-row w3-padding w3-black">
    <div class="w3-col s3">
      <a href="#" class="w3-button w3-block w3-black">HOME</a>
    </div>
    <div class="w3-col s3">
      <a href="#about" class="w3-button w3-block w3-black">ABOUT</a>
    </div>
    <div class="w3-col s3">
      <a href="#menu" class="w3-button w3-block w3-black">RECOMMEND MENU</a>
    </div>
    <div class="w3-col s3">
      <a href="#where" class="w3-button w3-block w3-black">WHERE</a>
    </div>
  </div>
</div>

<!-- Header with image -->
<header <img src="/image/banner.jpg" alt="Cinque Terre" width="1500" height="500"> </header>

<!-- Add a background color and large text to the whole page -->
<div class="bg_page">

<!-- About Container -->
<div class="w3-container" id="about">
  <div class="w3-content" style="max-width:700px">
    <h5 class="w3-center w3-padding-64"><span class="w3-tag w3-wide">ABOUT KRUA KHUN TONG</span></h5>
    <p>ครัวคุณโต้ง ตำรับอาหารไทยพื้นเมือง  มีอาหารพื้นเมืองหลากหลาย กว่า 180 เมนู อยากให้ทุกท่านได้เข้ามาลิ้มลองรสชาติที่จัดจ้าน  กับบรรยากาศร้าน สบาย ๆ ใจกลางเมือง ให้อารมณ์การทานอาหารท่ามกลางธรรมชาติ และการบริการที่เป็นกันเอง รับรองว่าท่านจะได้รับความอร่อย และความสุขในการทานอาหาร แน่นอนครับ</p>
    <div class="w3-panel w3-leftbar w3-light-grey">
      <p><i>"ผมได้รับแรงบันดาลใจการทำอาหารมาจากแม่ครับ แม่ผมทำอาหารอร่อยมาก ผมจึงตั้งใจนำสูตรอาหารของแม่มารังสรรค์เป็นอาหารที่อร่อยและเป็นเอกลักษณ์ให้ทุกคนได้ทานครับ".</i></p>
      <p>Chef: Tong</p>
    </div>
    <img src="/image/1.jpg" style="width:100%;max-width:1000px" class="w3-margin-top">
    <p><strong>Opening hours:</strong> 11:00-22:00</p>
    <p><strong>Address:</strong>87/54 หมู่ 5 ถ.เอกวานิช ต.รัษฎา อ.เมือง จ.ภูเก็ต 83000</p>
  </div>
</div>

<!-- Menu Container -->
<div class="w3-container" id="menu">
  <div class="w3-content" style="max-width:700px">
 
    <h5 class="w3-center w3-padding-48"><span class="w3-tag w3-wide">THE RECOMMEND MENU</span></h5>

  <div class="w3-row-padding">
    <div class="w3-col l3 m6 w3-margin-bottom">
      <div class="w3-display-container">
        <img src="/image/f1.jpg"  style="width:100%">
        <p>ยำทะเลกรอบ</p>
      </div>
    </div>
    <div class="w3-col l3 m6 w3-margin-bottom">
      <div class="w3-display-container">
        <img src="/image/f2.jpg"  style="width:100%">
        <p>แกงส้มปลายอดมะพร้าว</p>
      </div>
    </div>
    <div class="w3-col l3 m6 w3-margin-bottom">
      <div class="w3-display-container">
        <img src="/image/f3.jpg"  style="width:100%">
        <p>แกงปูหมี่หุ้น</p>
      </div>
    </div>
    <div class="w3-col l3 m6 w3-margin-bottom">
      <div class="w3-display-container">
        <img src="/image/f4.jpg"  style="width:100%">
        <p>ปอเปี๊ยะห่อกล้วย</p>
      </div>
    </div>
  </div>

  <div class="w3-row-padding">
    <div class="w3-col l3 m6 w3-margin-bottom">
      <div class="w3-display-container">
        <img src="/image/f5.jpg"  style="width:100%">
        <p>หมูฮ้อง</p>
      </div>
    </div>
    <div class="w3-col l3 m6 w3-margin-bottom">
      <div class="w3-display-container">
        <img src="/image/f6.jpg"  style="width:100%">
        <p>ยำมะมุดปลาฉิ้งฉ้าง</p>
      </div>
    </div>
    <div class="w3-col l3 m6 w3-margin-bottom">
      <div class="w3-display-container">
        <img src="/image/f7.jpg" style="width:100%">
        <p>ผักเหมียงผัดไข่</p>
      </div>
    </div>
    <div class="w3-col l3 m6 w3-margin-bottom">
      <div class="w3-display-container">
        <img src="/image/f8.jpg"  style="width:100%">
        <p>กุ้งผัดกะปิสะตอ</p>
      </div>
    </div>
  </div>
   

    <img src="/image/con.jpg" style="width:100%;max-width:1000px;margin-top:32px;">
  </div>
</div>

<!-- Contact/Area Container -->
<div class="w3-container" id="where" style="padding-bottom:32px;">
  <div class="w3-content" style="max-width:700px">
    <h5 class="w3-center w3-padding-48"><span class="w3-tag w3-wide">WHERE TO FIND US</span></h5>
    <p>Find us at some address at some place.</p>
    <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3951.973320315746!2d98.37212241498135!3d7.897856007850743!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x305031c1d79df597%3A0x172496fa8a5454c!2z4LiE4Lij4Lix4Lin4LiE4Li44LiT4LmC4LiV4LmJ4LiHIEtydWEgS2h1biBUb25n!5e0!3m2!1sen!2sth!4v1602761110759!5m2!1sen!2sth" width="600" height="450" frameborder="0" style="border:0;" allowfullscreen="" aria-hidden="false" tabindex="0"></iframe>
    <p><strong>บริการจองโต๊ะ</strong> ท่านสามารถสอบถาม หรือเพิ่มข้อความอื่นๆได้ครับ:</p>
    
    <form>
      <p><input class="w3-input w3-padding-16 w3-border" id="myInput" type="text" placeholder="Name" onfocus="this.value=''" required name="Name"></p>
      <p><input class="w3-input w3-padding-16 w3-border" id="myInput" type="number" placeholder="How many people" onfocus="this.value=''" required name="People"></p>
      <p><input class="w3-input w3-padding-16 w3-border" id="myInput" type="datetime-local" placeholder="Date and time" onfocus="this.value=''" required name="date" value="2017-11-16T20:00"></p>
      <p><input class="w3-input w3-padding-16 w3-border" id="myInput" type="text" placeholder="Message / Special requirements" onfocus="this.value=''" required name="Message"></p>
      <button class="w3-button w3-black" id="myBtn" type="submit"  onclick="alert('จองสำเร็จ!')" >SEND MESSAGE</button>
     
    </form>
  </div>
</div>

<!-- End page content -->
</div>

<!-- Footer -->
<footer class="w3-center w3-light-grey w3-padding-30 w3-large">
  <p>&copy;Copyright 2020 Powered by Mr.P</p>
</footer>
</div>


<script>
  var input = document.getElementById("myInput");
input.addEventListener("keyup", function(event) {
  if (event.keyCode === 20) {
   event.preventDefault();
   document.getElementById("myBtn").click();
  }
});
</script>

  </html>
</template>