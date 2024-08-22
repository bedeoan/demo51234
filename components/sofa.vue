<template>
  <div>
    <div class="container">
      <img width="100%" src="/images/image4.webp" />
      <div class="toparea">
        <div>
          Lorem Ipsum is simply dummy text of the printing and typesetting
          industry.One other line.......
          Lorem Ipsum is simply dummy text of the 
        </div>
        <button class="btn mt-2">Shop here</button>
      </div>
      <div class="bottom font-bold">
        <div class="kitchen">Kitchen</div>
        <div>Living</div>
        <div class="dining">Dining</div>
      </div>
    </div>
  </div>
</template>

<style>
.container {
  position: relative;
  width: 100%;
  max-width: 400px;
}

.container img {
  width: 100%;
  height: auto;
}

.container .toparea {
  width:80%;
  position: absolute;
  top: 10%;
  left: 5%;
  color: white;
  font-size: 12px;
  border: none;
}
.container .bottom {
  width:80%;
  position: absolute;
  bottom: 10%;
  left: 70%;
  color: white;
  font-size: 12px;
  border: none;
}

.btn {
  font-size: 1cqw;
  padding: 0.5cqw;
  background-color: white;
  color: black;
}
.kitchen {
    margin-left: 5px;
}
.dining {
    margin-left: 10px;
}
</style>
