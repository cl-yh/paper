<template>
    <div class="hello">
        <div class="paer-Herder">
            <img src="../assets/logo.png" alt />
            <div class="her-Column">
                <div>
                    <a href>首页</a>
                </div>
                <div>
                    <a href>项目</a>
                </div>
                <div>
                    <a href>优势</a>
                </div>
                <div>
                    <a href>流程</a>
                </div>
                <div>
                    <a href>估价</a>
                </div>
                <div>
                    <a href>联系</a>
                </div>
            </div>
        </div>
        <div class="swiper-container">
            <div class="swiper-wrapper">
                <div class="swiper-slide icon-Img1">
                    <div>选择我们·顺利毕业</div>
                    <div class=""></div>
                    <div>好文章成就好事业</div>
                    <div>以质量求生存,以信誉求发展</div>
                </div>
                <div class="swiper-slide icon-Img2">
                    <div>你想要的·我们都提供</div>
                    <div class=""></div>
                    <div>联系客服,免费代下论文文献,范文</div>
                </div>
                <div class="swiper-slide icon-Img3">、
                    <div>论文怎么写？不会写？重复率高？</div>
                    <div></div>
                    <div> 
                        时间紧？没精力？要求高？<br>
                        我们专注于专科，本科，硕士，博士毕业写作，论文降重，硕博级导师<br>
                        交给我们，让文字飞扬，让毕业so easy!
                    </div>
                </div>
            </div>
            <!-- 如果需要分页器 -->
            <div class="swiper-pagination icon-podd"></div>
        </div>
        <div>

        </div>
    </div>
</template>

<script>
import Swiper from "swiper";
import "swiper/dist/css/swiper.min.css";
export default {
    name: "HelloWorld",
    data() {
        return {};
    },
    methods:{

    },
    mounted(){
         var mySwiper = new Swiper ('.swiper-container', {
            // direction: 'vertical', // 垂直切换选项
            loop: true, // 循环模式选项
            // 如果需要分页器
            pagination: {
                el: '.swiper-pagination',
            },
            // 如果需要前进后退按钮
            navigation: {
                nextEl: '.swiper-button-next',
                prevEl: '.swiper-button-prev',
            },
        })        
    }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
a {
    text-decoration: none;
}
.paer-Herder {
    position: fixed;
    width: 100%;
    height: 0.5rem /* 74/75 */;
    background: black;
    opacity: 0.5;
    line-height: 0.5rem;
    z-index: 2;
}
img{
    float: left;
    width: 10%;
    height: 100%;
}
.her-Column {
    text-align: center;
    margin-left: 2.5rem;
    width: 50%;
    display: flex;
}
.her-Column div {
    flex: 1;
    font-size: 0.1rem /* 12/75 */;
}
.her-Column div a {
    padding: .175rem /* 10/75 */ .05rem /* 10/75 */;
     color: #ffffff ;
}
.her-Column div a:hover{
    border-top: .015rem solid #00dfb9;
    color: #00dfb9;
}
.swiper-slide{
    width: 100%;
    height:100vh;
   }

@media screen and (max-width: 650px) {
    .swiper-slide{
        width: 100%;
        height:7rem;
    }
 
}
.icon-Img1{
    background: url('http://www.paperred.cn/templets/Images/wallpaper1_3.jpg') 0 no-repeat;
    background-size: 100% 100%;
}
.icon-Img2{
    background: url('http://www.paperred.cn/templets/Images/wallpaper1_1.jpg') 0 no-repeat;
    background-size: 100% 100%;
}
.icon-Img3{
    background: url('http://www.paperred.cn/templets/Images/wallpaper1_2.jpg') 0 no-repeat;
    background-size: 100% 100%;
}
</style>
 <style>
   .icon-podd .swiper-pagination-bullet{
        width: .25rem /* 30/75 */;
        height: .025rem /* 8/75 */;
        border-radius: .02rem /* 2/75 */;
    }
</style>