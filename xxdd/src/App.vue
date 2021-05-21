<template>
  <div id="app">
    <headers></headers>
    <centerSwiper :centerMsg="centerMsg"></centerSwiper>
    <footers></footers>
  </div>
</template>

<script>
import headers from './components/headers';
import centerSwiper from './components/centerSwiper'
import footers from './components/footers'
export default {
  data() {
    return {
      centerMsg:[
        {
          title: "学习直播",
          msg: "随时开直播，用知识攒人气",
          centerimg: require("./assets/img/zhibo.jpg"),
          id:"0"
        },
        {
          title: "我的答疑室",
          msg: "实时对话答疑，高效接收反馈",
          centerimg: require("./assets/img/dayi.jpeg"),
          id:"1"
        },
        {
          title: "学习小卖部",
          msg: "助您打造专业付费内容体系",
          centerimg: require("./assets/img/xmb.jpg"),
          id:"2"
        },
        {
          title: "学习小组",
          msg: "时刻关注学院动态，灵活调整教学方案",
          centerimg: require("./assets/img/xz.jpg"),
          id:"3"
        },
      ]
    }
  },

  components:{
    headers,centerSwiper,footers
  }
}
</script>

<style lang="less">
  *{
    margin: 0px; padding: 0px;
  }
  html{
    font-size: 20.8688px;
    height: 100%;
  }
  body{
    height: 100%;
  }
  #app{
    height: 100%;
  }
  a{
    text-decoration: none;
  }
  li{
    list-style: none;
  }
</style>

