<template>
  <div>
    <div class="floor_wrap" id="floor_wrap">
      <div class="floor">
        <div class="floor_name">
          <span class="floor_title">美丽人生</span>
          <span class="floor_sub_title">FASHION & BEAUTY"</span>
        </div>
        <div class="floor_con">
          <div class="floor_con_left">
            <a href="#">
              <img
                class="ad"
                src="https://img.alicdn.com/tps/i4/TB1fJ2m08r0gK0jSZFnSuvRRXXa.jpg"
                alt=""
              />
              <div class="ad_position">
                <p class="ad_left_title">女装新品</p>
                <p class="ad_right_title">
                  <span class="ad_t"></span>
                  <span class="ad_t"></span>
                </p>
              </div>
            </a>
          </div>
          <div class="floor_con_right">
            <ul>
              <li>
                <a href="#">
                  <img
                    src="https://gw.alicdn.com/bao/uploaded/i3/1964144719/O1CN01stJKqJ1kjLhQvkNXE_!!0-item_pic.jpg"
                    alt=""
                  />
                  <p class="goods_info">
                    自然堂弹嫩紧致套装补水保湿化妆护肤品旗舰店官方专柜正品水乳套
                  </p>
                  <p class="goods_price">133</p>
                </a>
              </li>
              <li>
                <a href="#">
                  <img
                    src="https://gw.alicdn.com/bao/uploaded/i3/1964144719/O1CN01stJKqJ1kjLhQvkNXE_!!0-item_pic.jpg"
                    alt=""
                  />
                  <p class="goods_info">
                    自然堂弹嫩紧致套装补水保湿化妆护肤品旗舰店官方专柜正品水乳套
                  </p>
                  <p class="goods_price">133</p>
                </a>
              </li>
              <li>
                <a href="#">
                  <img
                    src="https://gw.alicdn.com/bao/uploaded/i3/1964144719/O1CN01stJKqJ1kjLhQvkNXE_!!0-item_pic.jpg"
                    alt=""
                  />
                  <p class="goods_info">
                    自然堂弹嫩紧致套装补水保湿化妆护肤品旗舰店官方专柜正品水乳套
                  </p>
                  <p class="goods_price">133</p>
                </a>
              </li>
              <li>
                <a href="#">
                  <img
                    src="https://gw.alicdn.com/bao/uploaded/i3/1964144719/O1CN01stJKqJ1kjLhQvkNXE_!!0-item_pic.jpg"
                    alt=""
                  />
                  <p class="goods_info">
                    自然堂弹嫩紧致套装补水保湿化妆护肤品旗舰店官方专柜正品水乳套
                  </p>
                  <p class="goods_price">133</p>
                </a>
              </li>
              
               
            </ul>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
  <style lang="scss">
* {
  margin: 0;
  padding: 0;
}
li {
  list-style: none;
}
a {
  text-decoration: none;
  color: #333;
}
body {
  background: #f5f5f5;
  color: #fff;
}
.floor_wrap {
  width: 800px;
  margin: 0 auto;
}
.floor {
  margin-bottom: 10px;
}

.floor_name {
  height: 50px;
  line-height: 50px;
}

.floor_sub_title {
  font-size: 14px;
  margin-left: 10px;
}
.floor_con {
  width: 800px;
  height: 500px;
  display: flex;
  justify-content: space-between;
}
.floor_con_left {
  width: 235px;
  height: 500px;
  position: relative;
}

.ad_position {
  position: absolute;
  left: 0;
  bottom: 20%;
  display: flex;
  width: 140px;
  height: 60px;
  background: rgba(0, 0, 0, 0.5);
}
.ad_left_title {
  width: 60px;
  height: 60px;
  background: rgba(0, 0, 0, 0.7);
  color: #fff;
}
.ad_right_title {
  flex: 1;
  color: #fff;
}
.floor_con_left img {
  width: 235px;
  height: 500px;
}
.floor_con_right {
  width: 750px;
  height: 500px;
}
.floor_con_right ul {
  display: flex;
  flex-wrap: wrap;
  justify-content: space-between;
}
.floor_con_right ul li {
  width: 220px;
  height: 200px;
  background: #fff;
  margin-bottom: 10px;
  text-align: center;
}
.floor_con_right ul li img {
  width: 185px;
  height: 185px;
}
.goods_info {
  font-size: 14px;
  width: 135px;
  height: 40px;
  margin: 12px auto;
  overflow: hidden;
}
.goods_price {
  color: red;
}
</style>