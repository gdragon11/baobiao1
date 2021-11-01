<template>
    <div>
        <div class="toubu">
            <h3>购物车</h3>
            <router-link class="clgwc" to="/">返回</router-link>
        </div>
        <ul>
            <li class="neirong" v-for="(item) in list" :key="item.id">
                <div class="nrbk">
                    <span class="left"><img :src="item.img" alt=""></span> 
                    <div class="right">
                        <h4 class="r_text">{{item.name}}</h4><br>
                        <div class="r_jieshao">{{item.slogan}}</div>
                        <div class="r_jiaqian">￥{{item.price}}</div>
                        <div class="r_div">
                            <button class="jia" @click="item.num++">+</button>
                            <button class="shuliang">{{item.num}}</button>
                            <button class="jian" @click="$store.dispatch('jianjian',item.id)">-</button>
                        </div>
                    </div>
                </div>
            </li>
            <!-- <button @click="ad">123</button> -->
        </ul>
    </div>
</template>
<script>
import {mapState} from "vuex"
export default {
    computed:{
        ...mapState(['list3','list']),
    },
    data(){
        return {
            
        }
    },
    methods:{
                
    },
    created(){

    },
}
</script>
<style lang="scss" scoped>
li{
    list-style: none;
    display: flex;
}
.shuliang{
    width: 20px;
    height: 20px;
    position: relative;
    top: .55rem;
    right: -.13rem;
    border: 1px solid darkblue;
    background: white;
}
.jia{
    position: relative;
    top: .55rem;
    right: 0;
    width: .2rem;
    background: white;
    border-radius: 40%;
    height: .2rem;
    border: 1px solid lawngreen;
}
.jian{
    position: relative;
    top: .55rem;
    right: -.25rem;
    background: white;
    width: .2rem;
    border-radius: 40%;
    height: .2rem;
    border: 1px solid lawngreen;
}
.jr{
    position: absolute;
    bottom: 30px;
    right: 20px;
    width: 100px;
    height: 25px;
    border: 1px solid red;
    color: red;
    background: seashell;
}
.r_jieshao{
    margin: .05rem 0 .04rem;
    font-size: .14rem;
    width: 2.24rem;
    height: .19rem;
    color: rgba(0,0,0,.47);
    overflow: hidden;
    white-space: nowrap;
    text-overflow: ellipsis;
}
.r_jiaqian{
    color:red;
    float: left;
    margin: .2rem 0;
}
.right{
    width: 2.24rem;
    height: 1.42rem;
    // background: royalblue;
    float: left;
    margin-top: -10px;
    position: relative;
}
.r_text{
    // width: 4.2rem;
    text-overflow: ellipsis;
    overflow: hidden;
    float: left;
    margin-left: .04rem;
}
.toubu{
  width: 100%;
  height: .5rem;
  background:#ff6704;
}
.toubu>h3{
  text-align: center;
  line-height: .5rem;
}
.clgwc{
    position: absolute;
    top: 15px;
    left: 30px;
}
.neirong{
    width: 3.43rem;
    height: 1.54rem;
    margin: 0 auto;
    // background: red;
    padding: 0 .15rem;    
    margin: .1rem 0;
}
.left{
    height: .94rem;
    width: .94rem;
    // margin-right: .2rem;
    float: left;
}
.left>img{
    height: .94rem;
    width: .94rem;
}
.nrbk{
    width: 3.18rem;
    height: 1.42rem;

    
    margin: 0 auto;
    padding-top: .16rem;
    background: azure;
}
</style>