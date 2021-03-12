<template>
  <div id="app">
   <div >
      <b-navbar toggleable="lg" type="dark" variant="info">
        <b-navbar-brand href="#">Movie</b-navbar-brand>

        <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

        <b-collapse id="nav-collapse" is-nav>
          <b-navbar-nav>
            <b-nav-item href="#">Link</b-nav-item>
            <b-nav-item href="#" disabled>Disabled</b-nav-item>
          </b-navbar-nav>

          <!-- Right aligned nav items -->
          <b-navbar-nav class="ml-auto">
            <b-nav-form>
              <b-form-input size="sm" class="mr-sm-2" placeholder="Search"></b-form-input>
              <b-button size="sm" class="my-2 my-sm-0" type="submit">Search</b-button>
            </b-nav-form>

            <b-nav-item-dropdown text="Lang" right>
              <b-dropdown-item href="#">EN</b-dropdown-item>
              <b-dropdown-item href="#">ES</b-dropdown-item>
              <b-dropdown-item href="#">RU</b-dropdown-item>
              <b-dropdown-item href="#">FA</b-dropdown-item>
            </b-nav-item-dropdown>

            <b-nav-item-dropdown right>
              <!-- Using 'button-content' slot -->
              <template #button-content>
              </template>
            </b-nav-item-dropdown>
          </b-navbar-nav>
    </b-collapse>
  </b-navbar>

<br><br><br><br>

<b-card-group deck style="justify-content: center;">
  <b-card
    title="Vincenzo"
    img-src="../static/Vincenzo1.jpg"
    img-alt="Image"
    img-top
    tag="article"
    style="max-width: 20rem;"
    class="mb-2"
  >
    <b-card-text>
      ซีรีส์เล่าเรื่องราวของ Vincenzo Cassano (รับบทโดย ซงจุงกิ) ทนายความและที่ปรึกษามาเฟียที่เดินทางกลับจากอิตาลีมายังเกาหลีหลังขัดแย้งกับองค์กร การกลับมาของเขาทำให้เขาได้พบกับ ทนายความสาว ฮงชายอง (รับบทโดย จอนยอบิน) ซึ่งเป็นทนายความที่ทำทุกหนทางเพื่อชนะคดี และพวกเขาได้มาร่วมกันสร้างความชอบธรรมตามวิถีวายร้าย
      ซึ่งในซีรีส์จะนำเสนอเรื่องราวของฮีโร่ด้านมืดที่กำจัดเหล่าคนร้ายที่กฎหมายไม่สามารถทำอะไรได้
    </b-card-text>

    <b-button href="javascript:alert('เพิ่มสินค้าแล้ว');" variant="primary" >เพิ่มเข้ารถเข็น</b-button>
  </b-card>
  <b-card
    title="StartUp"
    img-src="../static/StartUp.jpg"
    img-alt="Image"
    img-top
    tag="article"
    style="max-width: 20rem;"
    class="mb-2"
  >
    <b-card-text>
      เรื่องราวของหญิงสาวที่ใฝ่ฝันอยากจะประสบความสำเร็จเหมือนสตีฟ จ็อบส์ และชายหนุ่มผู้เป็นรักแรกของเธอ ซอดัลมี (แบซูจี) เป็นทายาทรุ่นที่สองของตระกูลใหญ่ เธอตัดสินใจลาออกจากมหาวิทยาลัยและเริ่มต้นทำงานพาร์ทไทม์ เพื่อหาเงิน 90 ล้านวอนมาลงทุนทำธุรกิจของตัวเอง ซอดัลมีตกหลุมรักนัมโดซาน (นัมจูฮยอก) ชายหนุ่มผู้ก่อตั้งบริษัทซัมซานเทค
    </b-card-text>

    <b-button href="javascript:alert('เพิ่มสินค้าแล้ว');" variant="primary">เพิ่มเข้ารถเข็น</b-button>
  </b-card>
  <b-card
    title="Sisyphus"
    img-src="../static/Sisyphus.jpg"
    img-alt="Image"
    img-top
    tag="article"
    style="max-width: 20rem;"
    class="mb-2"
  >
    <b-card-text>
      เรื่องราวของวิศวกรอัจฉริยะ ที่กำลังคิดค้นนวัตกรรมเปลี่ยนโลก และเธอที่มาจากโลกอนาคต เขาทั้งสองต้องร่วมมือกันผ่านภารกิจเฉียดตาย เพื่อช่วยเหลือโลกใบนี้ การเดินทางข้ามเวลาครั้งนี้จะเป็นอย่างไร น่าสนุกแค่ไหน ติดตามได้ใน
      ดูซีรีส์เกาหลี Sisyphus: The Myth (2021) รหัสลับข้ามเวลา ซับไทย
    </b-card-text>

    <b-button href="javascript:alert('เพิ่มสินค้าแล้ว');" variant="primary">เพิ่มเข้ารถเข็น</b-button>
  </b-card>
</b-card-group>

<b-card-group deck style="justify-content: center;">
  <b-card
    title="Memories Of The Alhambra"
    img-src="../static/Alhambra.jpg"
    img-alt="Image"
    img-top
    tag="article"
    style="max-width: 20rem;"
    class="mb-2"
  >
    <b-card-text>
      ยูจินอู (ฮยอนบิน) เป็นซีอีโอของบริษัทด้านการลงทุน เขามีความรู้สึกที่ดีในการทำงาน จิตวิญญาณที่รักการผจญภัยที่แข็งแกร่งและความปรารถนาดีสำหรับผู้ชนะ ยูจินอูกำลังผ่านช่วงเวลาที่ลำบากในเรื่องของความรู้สึกเนื่องมาจากการทรยศต่อเพื่อนของเขา
      เขาไปที่ประเทศสเปนและได้เข้าพักในหอพักเก่าที่มี จองฮีจู (พัคชินฮเย) เป็นผู้ดูแล ที่นั่นเขาได้มีส่วนร่วมในเรื่องแปลกๆ
    </b-card-text>

    <b-button href="javascript:alert('เพิ่มสินค้าแล้ว');" variant="primary">เพิ่มเข้ารถเข็น</b-button>
  </b-card>
  <b-card
    title="Crash Landing On You"
    img-src="../static/01.jpg"
    img-alt="Image"
    img-top
    tag="article"
    style="max-width: 20rem;"
    class="mb-2"
  >
    <b-card-text>
      ยุนเซรี (รับบทโดย ซนเยจิน) ทายาทตระกูลร่ำรวยที่ระหว่างเล่นร่มร่อน (Paragliding) เกิดกระแสลมแรง จึงเป็นเหตุให้ต้องลงจอดฉุกเฉินแล้วมาตกลงในเขตพื้นที่ในประเทศเกาหลีเหนือ
      ซึ่งทำให้เธอได้พบกับ รีจองฮยอก (รับบทโดย ฮยอนบิน) เจ้าหน้าที่ทหารเกาหลีเหนือที่ พยายามซ่อนตัวและปกป้องเธอระหว่างที่เธออยู่ในประเทศของเขา​ แล้วเกิดตกหลุมรักเธอในที่สุด
    </b-card-text>

    <b-button href="javascript:alert('เพิ่มสินค้าแล้ว');" variant="primary">เพิ่มเข้ารถเข็น</b-button>
  </b-card>
  <b-card
    title="KingDom"
    img-src="../static/Kingdom.jpg"
    img-alt="Image"
    img-top
    tag="article"
    style="max-width: 20rem;"
    class="mb-2"
  >
    <b-card-text>
      ในยุคโชซอนเมื่อ องค์รัชทายาท อีชาง (รับบทโดย จูจีฮุน) สงสัยถึงอาการป่วยขององค์พระราชา เมื่อพระมเหสีไม่อนุญาตให้องค์รัชทายาทเข้าไปในตำหนักของพระราชบิดาของพระองค์เอง องค์รัชทายาทจึงตัดสินใจปลอมตัวออกไปนอกพระราชวัง และพยายามค้นหาความจริงที่อยู่เบื้องหลังอาการป่วยของพระราชบิดา ในขณะเดียวกันก็ได้พบว่าเกิดโรคประหลาดกำลังแพร่กระจายจนทำให้คนกลายเป็นอสูรกาย พระองค์จึงร่วมมือกับ ซอบี (รับบทโดย แบดูนา) แพทย์สาวสามัญชนที่คอยช่วยเหลือชาวบ้านจากเรื่องราวร้ายแรงครั้งนี้ และนอกจากนี้องค์ราชทายาทยังต้องต่อสู้กับ โจฮักจู (รับบทโดย รยูซึงรยง) ข้าหลวงในพระราชวังที่คอยชักใยแผนการชั่วร้ายเพื่อจะได้มาซึ่งอำนาจเหนือกว่าราชวงศ์
    </b-card-text>

    <b-button href="javascript:alert('เพิ่มสินค้าแล้ว');" variant="primary">เพิ่มเข้ารถเข็น</b-button>
  </b-card>
</b-card-group>

<b-card-group deck style="justify-content: center;">
  <b-card
    title="Her private Life"
    img-src="../static/her-private-life.jpg"
    img-alt="Image"
    img-top
    tag="article"
    style="max-width: 20rem;"
    class="mb-2"
  >
    <b-card-text>
      ซองด็อกมี (พัคมินยอง) เธอทำงานเป็นคนดูแลภาพวาดอยู่ที่หอศิลป์ นอกจากนี้เธอยังเป็นแฟนคลับตัวยงของสมาชิกไอดอล ชีอัน และแอบดูแลเว็บไซต์แฟนคลับที่เกี่ยวกับเขา เนื่องจากความรักที่เธอมีต่อไอดอลคนนี้มาก เธอจึงมีปัญหาในเรื่องส่วนตัวหลายครั้งอยู่มาวันหนึ่ง ไรอัน (คิมแจอุค) เขาได้เริ่มทำงานเป็นผู้อำนวยการคนใหม่ของอาร์ตแกลอรี่ที่ ซองด็อกมีทำงานอยู่ ในอดีตเขาเคยเป็นจิตรกรที่มีชื่อเสียง ไรอัน ไม่ได้เป็นคนที่ชอบสนใจคนอื่นมากนัก แต่เขาก็รู้ว่าซองด็อกมี 
      เป็นแฟนคลับของ ชีอัน และยังเป็นคนดูแลเว็บไซต์แฟนคลับด้วย 
      เขาจึงเริ่มสนใจ ซองด็อกมี มากขึ้น
    </b-card-text>

    <b-button href="javascript:alert('เพิ่มสินค้าแล้ว');" variant="primary">เพิ่มเข้ารถเข็น</b-button>
  </b-card>
  <b-card
    title="Vagabond"
    img-src="../static/vagabond.jpg"
    img-alt="Image"
    img-top
    tag="article"
    style="max-width: 20rem;"
    class="mb-2"
  >
    <b-card-text>
    </b-card-text>

    <b-button href="javascript:alert('เพิ่มสินค้าแล้ว');" variant="primary">เพิ่มเข้ารถเข็น</b-button>
  </b-card>
  <b-card
    title="What's Wrong With Secretary Kim"
    img-src="../static/02.jpg"
    img-alt="Image"
    img-top
    tag="article"
    style="max-width: 20rem;"
    class="mb-2"
  >
    <b-card-text>
      
    </b-card-text>

    <b-button href="javascript:alert('เพิ่มสินค้าแล้ว');" variant="primary">เพิ่มเข้ารถเข็น</b-button>
  </b-card>
</b-card-group>

  </div>
  </div>
</template>

<script>
export default {
  name: 'App'
}
</script>

<style>

</style>
