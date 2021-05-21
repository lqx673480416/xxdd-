<template>
    <div class="top">
        <div class="imgs">
            <img src="../assets/img/xxdd.jpg" alt="">
        </div>
        <div class="p">
            <p>内容精准输送到千万Timing学习用户</p>
        </div>
        <div class="b">
            <div class="btn">
                <a href="">立即下载</a>
            </div>
        </div>
        
    </div>
</template>

<script>
export default {
    data() {
        return {
            
        }
    },
}
</script>

<style lang="less" scoped>
@top-main-color: #5AC3BE;
@top-main-fontcolor: #FFFFFF;
    .top{
        height: 28%;
        background-color: @top-main-color;
        .imgs{
            display: flex;
            justify-content: center;
            img{
                width: 80px;
                height: 80px;
                border-radius: 18px;
                border: 2px solid white;
                margin-top: 25px;
            }
        }
        .p{
            display: flex;
            justify-content: center;
            p{
            margin-top: 20px;
            text-align: center;
            font-size: 16px;
            color: @top-main-fontcolor;
            
        }
        
        
        }
        .b{
            display: flex;
            justify-content: center;
            .btn{
            width: 100px;
            height: 32px;
            border: 1px solid white;
            font-size: 16px;
            text-align: center;
            line-height: 32px;
            border-radius: 15px;
            // margin-left: 155px;
            margin-top: 10px;
                a{
                    color: @top-main-fontcolor;
                }
            }
        }
    }
</style>