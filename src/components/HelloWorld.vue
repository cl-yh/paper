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
                <div class="swiper-slide icon-Img1 paer-Img1">
                    <div class="paer-cen">
                        <div class="inoc-top">选择我们·顺利毕业</div>
                        <div class="paer-acti"></div>
                        <div class="inoc-bottom">
                            好文章成就好事业
                            <br />以质量求生存,以信誉求发展
                        </div>
                    </div>
                </div>
                <div class="swiper-slide icon-Img2 paer-Img2">
                   <div class="paer-cen paer-posi">
                       <div class="paer-seven"></div>
                       <div class="paer-right">
                            <div class="inco1-top">论文怎么写？不会写？重复率高？</div>
                            <div class="paer-acti2"></div>
                            <div class="inoc1-bottom">
                                时间紧？没精力？要求高？
                                <br />我们专注于专科，本科，硕士，博士毕业写作，论文降重，硕博级导师
                                <br />交给我们，让文字飞扬，让毕业so easy!
                            </div>
                       </div>
                   </div>
                </div>
                <div class="swiper-slide icon-Img3 paer-Img3">
                    <div class="paer-cen"> 
                        <div class="inco2-top">你想要的·我们都提供</div>
                        <div class="paer-acti2"></div>
                        <div class="inco2-bottom">联系客服,免费代下论文文献,范文</div>
                    </div>
                </div>
            </div>
            <!-- 如果需要分页器 -->
            <div class="swiper-pagination icon-podd"></div>
        </div>
        <div class="paer-serve">
            <div class="serv-top">
                <div class="serv-cata"></div>
                <div class="serv-rama">服务项目</div>
            </div>
            <ul class="sere-ul sere-loop">
                <li class="sere-li">
                    <i class="one"></i>
                    <i class="two"></i>
                    <div class="sere-imgAll sere-img1"></div>
                    <div class="sere-boop">本硕写作</div>
                    <div class="">
                        硕博导师团队<br/>
                        一对一服务
                    </div>
                </li>
                <li class="sere-li">
                    <i class="one"></i>
                    <i class="two"></i>
                     <div class="sere-imgAll sere-img2"></div>
                    <div class="sere-boop">意见修改</div>
                    <div>
                        专业改内容意见<br/>
                        保证质量免费售后
                    </div>
                </li>
                <li class="sere-li">
                    <i class="one"></i>
                    <i class="two"></i>
                    <div class="sere-imgAll sere-img3"></div>
                    <div class="sere-boop">改重降重</div>
                    <div>
                        降低重复率<br/>
                        不通过退款
                    </div>
                </li>
                <li class="sere-li">
                    <i class="one"></i>
                    <i class="two"></i>
                    <div class="sere-imgAll sere-img4"></div>
                    <div class="sere-boop">格式排版</div>
                    <div>
                        按要求格式调整<br/>
                        内容布局排版
                    </div>
                </li>
                <li class="sere-li">
                    <i class="one"></i>
                    <i class="two"></i>
                    <div class="sere-imgAll sere-img5"></div>
                    <div class="sere-boop">外文翻译</div>
                    <div>
                        目录摘要翻译<br/>
                        多国翻译中英互译
                    </div>
                </li>
                <li class="sere-li">
                    <i class="one"></i>
                    <i class="two"></i>
                    <div class="sere-imgAll sere-img6"></div>
                    <div class="sere-boop">PPT制作</div>
                    <div>
                        制作答辩PPT<br/>
                        简历制作定制设计
                    </div>
                </li>
                <li class="sere-li">
                    <i class="one"></i>
                    <i class="two"></i>
                    <div class="sere-imgAll sere-img7"></div>
                    <div class="sere-boop">职称评审</div>
                    <div>
                        高通过率<br/>
                        免费协助解答
                    </div>
                </li>
                <li class="sere-li">
                    <i class="one"></i>
                    <i class="two"></i>
                    <div class="sere-imgAll sere-img8"></div>
                    <div class="sere-boop">学术不端查重</div>
                    <div>
                        正品支持验证<br/>
                        与学校结果一致
                    </div>
                </li>
            </ul>

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
    methods: {},
    mounted() {
        var mySwiper = new Swiper(".swiper-container", {
            // direction: 'vertical', // 垂直切换选项
            loop: true, // 循环模式选项
            // 如果需要分页器
            pagination: {
                el: ".swiper-pagination"
            },
            // 如果需要前进后退按钮
            navigation: {
                nextEl: ".swiper-button-next",
                prevEl: ".swiper-button-prev"
            }
        });
    }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.sere-boop{
    display: block;
    margin-top: 70px;
    font-size: 16px;
    font-weight: normal;
    text-align: center;
}   
.sere-imgAll{
    display: block;
    position: relative;
    margin: 0 auto;
    height: 73px;
    width: 72px;
}
.sere-imgAll{
    margin-top: 43px;
}
.sere-imgAll:hover{
    -webkit-transition: all .5s ease-in-out .4s;
    -moz-transition: all .5s ease-in-out .4s;
    -ms-transition: all .5s ease-in-out .4s;
    -o-transition: all .5s ease-in-out .4s;
    transition: all .5s ease-in-out .4s;
}
.sere-img1{
    background: url('../assets/words.png') no-repeat -248px -366px;
}
.sere-li:hover .sere-img1{
    background: url("../assets/words.png") no-repeat -168px -366px;
}
.sere-img2{
    background: url("../assets/words.png") no-repeat -411px -291px
}
.sere-li:hover .sere-img2{
    background: url("../assets/words.png") no-repeat -337px -291px
}
.sere-img3{
    background:url("../assets/words.png") no-repeat -415px -364px
}
.sere-li:hover .sere-img3{
    background: url("../assets/words.png") no-repeat -327px -362px
}
.sere-img4{
    background: url("../assets/words.png") no-repeat -244px -439px
}
.sere-li:hover .sere-img4{
    background: url("../assets/words.png") no-repeat -164px -439px
}
.sere-img5{
    background:url("../assets/words.png") no-repeat -580px -291px
}
.sere-li:hover .sere-img5{
    background: url("../assets/words.png") no-repeat -500px -291px
}
.sere-img6{
    background:url("../assets/words.png") no-repeat -583px -364px
}
 .sere-li:hover .sere-img6{
    background: url("../assets/words.png") no-repeat -495px -364px
}
.sere-img7{
    background: url("../assets/words.png") no-repeat -583px -445px
}
.sere-li:hover .sere-img7{
    background: url("../assets/words.png") no-repeat -503px -445px
}
.sere-img8{
    background: url("../assets/words.png") no-repeat -601px -532px
}
.sere-li:hover .sere-img8{
    background: url("../assets/words.png") no-repeat -521px -532px
}
.sere-li:hover .sere-imgAll{
    -webkit-transition: all .5s ease-in-out .4s;
    -moz-transition: all .5s ease-in-out .4s;
    -ms-transition: all .5s ease-in-out .4s;
    -o-transition: all .5s ease-in-out .4s;
    transition: all .5s ease-in-out .4s;
}
.sere-li{
    width: 200px;
    height: 300px;
    margin: 0 8px;
    background: url('../assets/bg_green.png') no-repeat 0px 400px;
    overflow: hidden;
    display: inline-block;
    padding-right: 5px;
    padding-left: 5px;
}
.sere-li:hover{
    background-position: 0px 0px;
    -webkit-transition: all .5s ease-in-out .3s;
    -moz-transition: all .5s ease-in-out .3s;
    -ms-transition: all .5s ease-in-out .3s;
    -o-transition: all .5s ease-in-out .3s;
    transition: all .5s ease-in-out .3s;
}
i{
    display: block;
    position: absolute;
    width: 156px;
    height: 156px;
    margin-left: 22px;
    background: url('../assets/words.png') no-repeat 0px -363px;
    /* -webkit-transition: all .5s ease-in-out 0s; */
    -moz-transition: all .5s ease-in-out 0s;
    -ms-transition: all .5s ease-in-out 0s;
    -o-transition: all .5s ease-in-out 0s;
    transition: all .5s ease-in-out 0s;
}
.sere-ul{
    padding-top: 60px;
    max-width: 1000px;
    padding-left: 0;
    margin-left: -5px;
    list-style: none;
    text-align: center;
}
.sere-ul{
  margin:auto;
}
.serv-cata{
    display: block;
    margin: 0 auto;
    margin-bottom: 20px;
    width: 320px;
    height: 31px;
    background: url('../assets/words.png') no-repeat 0px -294px;
}
.serv-rama{
    font-size: 24px;
    letter-spacing: 3px;
}
.serv-top{
    width: 100%;
    text-align: center;
}
.serv-top{
    width: 100%;
    text-align: center;
    -webkit-transition: all .5s ease-in-out 0s;
    -moz-transition: all .5s ease-in-out 0s;
    -ms-transition: all .5s ease-in-out 0s;
    -o-transition: all .5s ease-in-out 0s;
    transition: all .5s ease-in-out 0s;
}
.paer-serve{
    width: 100%;
    height: calc(100vh - 105px);;
    background: url('../assets/wallpaper2.jpg') 50% bottom;
    font-size: .1rem;
    padding-top: 105px;
}
.paer-Img1,
.paer-Img2,
.paer-Img3 {
    color: #ffffff;
    text-align: center;
    font-size: 0.1rem;
}
.inoc-top {
    font-size: 0.2rem;
}
.inco1-top{
    font-size: 36px;
    color: White;
}
.inco2-top{
    font-size: 66px;
    color: White;
}
.inco2-bottom{
     width: 100%;
    margin-top: 32px;
    font-size: 33px;
    line-height: 25px;
    color: #ccc;
    text-align: center;
    -webkit-transition: all .5s linear 0s;
    -moz-transition: all .5s linear 0s;
    -ms-transition: all .5s linear 0s;
    -o-transition: all .5s linear 0s;
    transition: all .5s linear 0s;
    z-index: 10;
}

.paer-acti2{
    display: block;
    width: 339px;
    height: 66px;
    margin-bottom: 5px;
    background: url("../assets/words.png") no-repeat;
    margin: 0 auto;
}
.paer-posi{
    position: relative;
    margin: 14% auto;
}
.paer-right{
    position: absolute;
    text-align: center;
    width: 100%;
    margin-top: 45px;
}
.inoc1-bottom{
    font-size: 16px;
    line-height: 25px;
    color: #ccc;
}
.paer-seven{
    position: absolute;
    left: 500px;
    width: 123px;
    height: 231px;
    background: url("../assets/words.png") no-repeat -377px 0;
    -moz-opacity: 0;
    -webkit-transition: all .5s ease-in-out 0s;
    -moz-transition: all .5s ease-in-out 0s;
    -ms-transition: all .5s ease-in-out 0s;
    -o-transition: all .5s ease-in-out 0s;
    transition: all .5s ease-in-out 0s;
}
.inoc-bottom {
    width: 100%;
    color: #ccc;
    font-size: 0.11rem /* 16/75 */;
    line-height: 0.15rem /* 30/75 */;
    text-align: center;
    -moz-opacity: 0;
    -webkit-transition: all 0.6s ease-in-out 0.3s;
    -moz-transition: all 0.6s ease-in-out 0.3s;
    -ms-transition: all 0.6s ease-in-out 0.3s;
    -o-transition: all 0.6s ease-in-out 0.3s;
    transition: all 0.6s ease-in-out 0.3s;
    z-index: 10;
}
.paer-cen {
    transform: translate(0, 130%);
}
.paer-acti {
    width: 3.35rem /* 630/75 */;
    height: 0.4rem /* 66/75 */;
    margin: 0 auto;
    margin-top: 0.12rem /* 20/75 */;
    margin-bottom: 0.07rem /* 10/75 */;
    background: url("../assets/words.png") no-repeat 0.01rem -5rem;
    -webkit-transition: all 0.3s ease-in-out 0s;
    -moz-transition: all 0.3s ease-in-out 0s;
    -ms-transition: all 0.3s ease-in-out 0s;
    -o-transition: all 0.3s ease-in-out 0s;
    transition: all 0.3s ease-in-out 0s;
}
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
.paer-Herder img {
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
    padding: 0.175rem /* 10/75 */ 0.05rem /* 10/75 */;
    color: #ffffff;
}
.her-Column div a:hover {
    border-top: 0.015rem solid #00dfb9;
    color: #00dfb9;
}
.swiper-slide {
    width: 100%;
    height: 100vh;
}
.icon-Img1 {
    background: url("http://www.paperred.cn/templets/Images/wallpaper1_3.jpg") 0
        no-repeat;
    background-size: 100% 100%;
}
.icon-Img2 {
    background: url("http://www.paperred.cn/templets/Images/wallpaper1_1.jpg") 0
        no-repeat;
    background-size: 100% 100%;
}
.icon-Img3 {
    background: url("http://www.paperred.cn/templets/Images/wallpaper1_2.jpg") 0
        no-repeat;
    background-size: 100% 100%;
}

@media screen and (max-width: 650px) {
    .swiper-slide {
        width: 100%;
        height: 7rem;
    }
    .paer-acti {
        width: 5rem /* 630/75 */;
        height: 0.6rem /* 66/75 */;
        margin: 0 auto;
        margin-top: 0.12rem /* 20/75 */;
        margin-bottom: 0.07rem /* 10/75 */;
        background: url(/static/img/words.e8d21c2.png) no-repeat 0.01rem -6.7rem;
        -webkit-transition: all 0.3s ease-in-out 0s;
        transition: all 0.3s ease-in-out 0s;
        background-size: 6.69rem /* 24.8/75 */ 7.3rem /* 20.6/75 */;
        -webkit-transition: all 0.3s ease-in-out 0s;
        -moz-transition: all 0.3s ease-in-out 0s;
        -ms-transition: all 0.3s ease-in-out 0s;
        -o-transition: all 0.3s ease-in-out 0s;
        transition: all 0.3s ease-in-out 0s;
    }
    .inoc-bottom {
        line-height: 0.4rem;
    }
    .paer-cen {
        transform: translate(0, 100%);
    }
}
</style>
 <style>
.icon-podd .swiper-pagination-bullet {
    width: 0.25rem /* 30/75 */;
    height: 0.025rem /* 8/75 */;
    border-radius: 0.02rem /* 2/75 */;
}
</style>