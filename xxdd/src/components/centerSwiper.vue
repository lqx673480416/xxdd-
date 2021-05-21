<template>
    <div class="centerAll">
        <!-- <titlep></titlep> -->
        <swipers>
            <div class="swiper-slide alls" v-for="(item) in centerMsg" :key="item.id">
                <div class="all">
                    <span>{{item.title}}</span>
                    <p>{{item.msg}}</p>
                    <img :src="item.centerimg" alt="">
                </div>
                
            </div>
        </swipers>
    </div>
</template>

<script>
// import titlep from "../components/title-p"
import swipers from "../components/swipers"
import 'swiper/css/swiper.min.css'
export default {
    data() {
        return {
            
        }
    },
    props:['centerMsg'],
    mounted() {
        
    },
    components:{
        swipers,
    }
}
</script>

<style lang="less" scoped>
    .centerAll{
        height: 60%;
    }
    .all{
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
        span{
            display: block;
            margin-top: 30px;
            font-size: 18px;
            font-weight: bold;
            letter-spacing: 2px;
        }
        p{
            color: gray;
            font-size: 15px;
            margin-top: 8px;
        }
        img{
            margin-top: 5px;
            width: 250px; height: 320px;
        }
    }
</style>