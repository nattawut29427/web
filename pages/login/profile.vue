<template>
  <HeaderLogin/>
  
  <div>
    <div class="navbar h-[230px] bg-white"></div>
    <img src="/pic/banner.jpg" class="w-full h-[400px] object-cover" />
  </div>

  <div class="flex justify-between">
    <div class="ml-[262px] flex items-center">
      <img
        src="https://i.pinimg.com/564x/1c/56/d1/1c56d1e6e3f002f4109a1f59e56cf292.jpg"
        class="rounded-full w-[250px] h-[250px] mt-[-100px] border-[15px] border-white"
      />
      <div class="">
        <div class="text-3xl text-pink-800 font-bold ml-[20px] flex">
          ออยเอง
          <img src="/pic/Edit_light (1).png" class="w-7 h-7 mt-2 ml-2" />
        </div>
        <div class="ml-4 mt-2 flex">
          <img src="/pic/Group_add_light.png" class="w-7 h-7" />
          <div class="ml-2">ผู้ติดตาม 12K</div>
        </div>
      </div>
    </div>

    <div class="flex items-center">
      <div
        class="btn text-base  w-fit mr-[262px] rounded-3xl pr-6 bg-[#AEC8FC] text-[#1A37A7] hover:bg-D_Blue font-bold"
      >
        <p class="pl-1">แก้ไขโปรไฟล์</p>
      </div>
    </div>
  </div>

  <div class="navbar h-[130px] bg-white"></div>
  <div class="flex justify-between h-auto">
    <div class="w-[860px] ml-[262px] rounded-xl bg-[#AEC8FC]">
      <div class="text-[#1A37A7] text-3xl  font-bold p-2 pb-0 ml-5 flex justify-between">
        ร้าน ออยเองงง
        <img src="/pic/Edit_light.png" class="w-7 h-7 mt-2 mr-2 cursor-pointer" />
      </div>
      <div class="w-[760px] ml-[28px] mt-4 rounded-xl mb-7 bg-white">
        <div class="w-5/6 pl-5 p-4 text-sm">
          <p>- ของทุกชิ้นใช่เอง สภาพดีเหมือนใหม่เเน่นอน</p>
          <p>- สามารถนัดรับได้เเถวหน้า มอ</p>
          <p>- หรือจัดส่ง EMS Flash Express</p>
          <p>- ของดีราคาถูกสมเหตุสมผล</p>
          <p></p><br>
          <p></p><br>
        </div>
      </div>
    </div>
    <div class="w-[500px] h-auto mr-[262px] rounded-xl bg-[#AEC8FC]">
      <div class="text-[#1A37A7] text-[29px] ml-4 font-bold p-2 flex justify-between">
        ช่องทางการติดต่อ
        <img src="/pic/Edit_light.png" class="w-7 h-7 mt-2 mr-2" />
      </div>
      <div class="w-[375px] h-[172px] ml-[28px] pl-5 p-3 rounded-xl bg-white">
        <div class="flex items-center justify-between mb-4 w-full">
          <div class="flex items-center  gap-2">
            <p><Icon name="i-logos-facebook" class="text-[30px]"/></p>
            <h1 class="text-[#3563E9] text-xl">: Facebook</h1>
          </div>
          <a
            class="btn btn-xs w-10 h-7 rounded-full bg-Light text-white hover:bg-D_Blue font-bold"
            ><p><Icon name="i-icon-park-outline-link-two" class="text-[20px]"/></p></a
          >
        </div>

        <div class="flex items-center justify-between w-full mb-4">
          <div class="flex items-center gap-2">
            <p><Icon name="i-logos-instagram-icon" class="text-[30px]"/></p>
            <h1 class="text-[#3563E9] text-xl">: Instargram</h1>
          </div>
          <button
            class="btn btn-xs w-10 h-7 rounded-full bg-Light text-white hover:bg-D_Blue font-bold"
            ><p><Icon name="i-icon-park-outline-link-two" class="text-[20px]"/></p></button
          >
        </div>

        <div class="flex items-center justify-between w-full">
          <div class="flex items-center gap-2">
            <p><Icon name="i-logos-tiktok-icon" class="text-[30px]"/></p>
            <h1 class="text-[#3563E9] text-xl">: Tiktok</h1>
          </div>
          <a
            class="btn btn-xs w-10 h-7 rounded-full bg-Light text-white hover:bg-D_Blue font-bold"
            ><p><Icon name="i-icon-park-outline-link-two" class="text-[20px]"/></p></a
          >
        </div>
      </div>
      
    </div>
  </div>
  <Cardme :hname="'สินค้าของฉัน'" class="m-0"/>
</template>


