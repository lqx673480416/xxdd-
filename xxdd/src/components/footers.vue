<template>
    <div class="footerAll">
        <div class="footer">
                <a href="" class="one">
                    <img src="../assets/img/weibo2.png" alt="">
                </a>
                <a href="" class="two">
                    <img src="../assets/img/email2.png" alt="">
                </a>
                <div class="ft">
                    <p>2016-2019 Timing360.com</p>
                    <p>武汉氪细胞网络技术有限公司</p>
                </div>
                <p>鄂ICP备17013082号</p>
                <p>
                    <a href="http://www.beian.gov.cn/portal/registerSystemInfo?recordcode=42010202001767">
                        <img src="http://www.timing360.com/images/site/v3/ga.png" alt="" class="ga">
                        鄂公网安备 42010202001767号
                    </a>
                </p>
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
.footerAll{
    z-index: 99;
    position: flex;
    bottom: 10px;
    display: flex;
    justify-content: center;
    align-items: center;
}
    .footer{
        height: 20%;
        font-size: 12px;
        font-family: PingFangSC-Regular, PingFang SC;
        font-weight: 400;
        color: #233D63;
        line-height: 1.5;
        text-align: center;
        .two img{
            width: 20px; height: 20px;
            margin-left: 30px;
        }
        .one img{
            width: 20px; height: 20px;
        }   
        .ft{
            margin-top: 5px;
        }
    }
    a{
        color: black;
    }
</style>