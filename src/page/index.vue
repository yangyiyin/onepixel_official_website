<template>
    <div>
        <div class="top">
            <img class="top_bg" src="http://qiniu-pub.yixsu.com/one-pixel-web---cut_02.png"/>
            <div class="content">
                <img class="logo" src="http://qiniu-pub.yixsu.com/logo-white_03.png"/>

                <div id="nav" class="nav">
                    <div class="item"><a href="javascript:;" @click="goAnchor('#fuwu')">服务</a></div>
                    <div class="item">|</div>
                    <div class="item" ><a href="javascript:;" @click="goAnchor('#anli')">案例</a></div>
                    <div class="item">|</div>
                    <div class="item"><a href="javascript:;" @click="goAnchor('#guanyu')">关于</a></div>
                    <div class="item">|</div>
                    <div class="item"><a href="javascript:;" @click="goAnchor('#lianxi')">联系</a></div>
                    <div class="clear"></div>
                </div>
            </div>
        </div>
        <div v-bind:style="searchBarFixed" class="top2">
            <img width="5%" style="margin-left: 5%;margin-right: 2%;margin-top: 5px" src="http://qiniu-pub.yixsu.com/one-pixel-web---cut_04.png"/>
            <div class="nav" style="width: 70%;display: inline-block">
                <div class="item" style="color: #000"><a style="color: #000" href="javascript:;" @click="goAnchor('#fuwu')">服务</a></div>
                <div class="item" style="color: #000">|</div>
                <div class="item"  style="color: #000"><a style="color: #000" href="javascript:;" @click="goAnchor('#anli')">案例</a></div>
                <div class="item" style="color: #000">|</div>
                <div class="item" style="color: #000"><a style="color: #000" href="javascript:;" @click="goAnchor('#guanyu')">关于</a></div>
                <div class="item" style="color: #000">|</div>
                <div class="item" style="color: #000"><a style="color: #000" href="javascript:;" @click="goAnchor('#lianxi')">联系</a></div>
                <div class="clear"></div>
            </div>
        </div>
        <div class="body">
            <img id="fuwu" class="title_line" src="http://qiniu-pub.yixsu.com/one-pixel-web---cut_09.png"/>
            <img class="sub_title" src="http://qiniu-pub.yixsu.com/one-pixel-web---cut_13.png"/>
            <div class="block">
                <div class="con_item">
                    <img src="http://qiniu-pub.yixsu.com/one-pixel-web---cut_17.png"/>
                    <p style="font-size: 1em">产品原型设计</p>
                    <p style="font-size: 0.7em;color: #666">最初信息架构<br/>低保真原型<br/>应用界面布局<br/>快速原型<br/>产品原型</p>
                </div>
                <div class="con_item">
                    <img src="http://qiniu-pub.yixsu.com/one-pixel-web---cut_19.png"/>
                    <p style="font-size: 1em">产品视觉设计</p>
                    <p style="font-size: 0.7em;color: #666">GUI界面设计<br/>图标设计<br/>品牌形象设计<br/>设计规范制定<br/>前端H5页面开发</p>
                </div>
                <div class="con_item">
                    <img src="http://qiniu-pub.yixsu.com/one-pixel-web---cut_22.png"/>
                    <p style="font-size: 1em">网站设计和开发</p>
                    <p style="font-size: 0.7em;color: #666">企业及个人网站<br/>其他类型网站<br/>电子商务网站<br/>手机wap<br/>网页前端开发和测试</p>
                </div>
                <div class="con_item">
                    <img src="http://qiniu-pub.yixsu.com/one-pixel-web---cut_24.png"/>
                    <p style="font-size: 1em">App设计和开发</p>
                    <p style="font-size: 0.7em;color: #666">手机及平板app开发<br/>微信小程序开发<br/>微信公众号<br/>H5应用设计开发<br/>ios与安卓界面适配</p>
                </div>
                <div class="con_item">
                    <img src="http://qiniu-pub.yixsu.com/one-pixel-web---cut_26.png"/>
                    <p style="font-size: 1em">应用软件设计</p>
                    <p style="font-size: 0.7em;color: #666">客户端软件界面设计<br/>智能家电应用软件<br/>电视软件界面<br/>未来家电界面<br/>其他终端界面</p>
                </div>
                <div class="con_item" style="margin-right: 0">
                    <img src="http://qiniu-pub.yixsu.com/one-pixel-web---cut_29.png"/>
                    <p style="font-size: 1em">品牌形象VI设计</p>
                    <p style="font-size: 0.7em;color: #666">品牌logo及VI设计<br/>店铺海报等平面设计<br/>活动海报等创意设计<br/>二维动画<br/>产品拍摄及修图</p>
                </div>
                <div class="clear"></div>
            </div>
            <img class="sub_title" src="http://qiniu-pub.yixsu.com/one-pixel-web---cut_38.png"/>
            <div class="block">
                <div class="con_item2">
                    <img src="http://qiniu-pub.yixsu.com/one-pixel-web---cut_42.png"/>
                    <p style="font-size: 1em">定制App快速设计及开发</p>
                    <p style="font-size: 0.7em;color: #666">移动端快速开发，满足不同客户对移动端产品的不同需求。从用户的角度出发，为不同行业提供专业的App设计和开发。包括但不限于电商类、教育培训、医疗、餐饮、金融、旅游等</p>
                </div>
                <div class="con_item2">
                    <img src="http://qiniu-pub.yixsu.com/one-pixel-web---cut_44.png"/>
                    <p style="font-size: 1em">企业及个人网站解决方案</p>
                    <p style="font-size: 0.7em;color: #666">个性化定制，以专业的视角，商业设计的思维为企业和个人提供最具创意的网站，从交互的角度为品牌提供更舒适的体验感受，带来更好的效益</p>
                </div>
                <div class="con_item2" style="margin-right: 0">
                    <img src="http://qiniu-pub.yixsu.com/one-pixel-web---cut_46.png"/>
                    <p style="font-size: 1em">微信小程序及微信公众号</p>
                    <p style="font-size: 0.7em;color: #666">微信的营销互动传播日趋受到大众喜爱，我们从营销出发，为企业及个体户提供微信小程序的定制设计和开发，以及微信公众号的运营和推广服务</p>
                </div>
                <div class="con_item2" >
                    <img src="http://qiniu-pub.yixsu.com/one-pixel-web---cut_51.png"/>
                    <p style="font-size: 1em">智能家居应用设计及开发</p>
                    <p style="font-size: 0.7em;color: #666">随着智能家居的发展，越来越多的智能产品走入大众的生活。传统产品已经不能轻易满足用户，用户要求产品使用起来更加快捷简便。互联网使一切皆有可能</p>
                </div>
                <div class="con_item2">
                    <img src="http://qiniu-pub.yixsu.com/one-pixel-web---cut_52.png"/>
                    <p style="font-size: 1em">手机小游戏开发</p>
                    <p style="font-size: 0.7em;color: #666">近年来手机游戏的发展越来越快，因为现在的手机游戏操作简单，可以通过联网的方式进行多人对战，方便快捷简单好玩。做有特色和有影响力的产品一直是我们努力的方向</p>
                </div>
                <div class="con_item2" style="margin-right: 0">
                    <img src="http://qiniu-pub.yixsu.com/one-pixel-web---cut_53.png"/>
                    <p style="font-size: 1em">品牌形象设计</p>
                    <p style="font-size: 0.7em;color: #666">为个人和企业提供定制设计，包括logo、头像、企业VI体系、个人品牌、店铺活动页面、活动海报、店铺产品拍摄及修图、淘宝店铺和详情页设计等</p>
                </div>
                <div class="clear"></div>
            </div>
            <img id="anli" class="title_line" src="http://qiniu-pub.yixsu.com/one-pixel-web---cut_57.png"/>

            <div class="block">
                <div class="con_item3">
                    <img src="http://qiniu-pub.yixsu.com/one-pixel-web---cut_60.png"/>
                    <p style="font-size: 1em">VPN手机端App</p>
                    <p style="font-size: 0.7em;color: #666">ios及安卓端的VPN应用局部页面</p>
                </div>
                <div class="con_item3">
                    <img src="http://qiniu-pub.yixsu.com/one-pixel-web---cut_62.png"/>
                    <p style="font-size: 1em">ios手机端App定制</p>
                    <p style="font-size: 0.7em;color: #666">消费类app的ios端定制</p>
                </div>
                <div class="con_item3">
                    <img src="http://qiniu-pub.yixsu.com/one-pixel-web---cut_64.png"/>
                    <p style="font-size: 1em">叮咚活动页海报设计</p>
                    <p style="font-size: 0.7em;color: #666">针对不同主题的banner设计</p>
                </div>
                <div class="con_item3" style="margin-right: 0">
                    <img src="http://qiniu-pub.yixsu.com/one-pixel-web---cut_66.png"/>
                    <p style="font-size: 1em">小Y个人网站定制</p>
                    <p style="font-size: 0.7em;color: #666">个性化个人网站设计和开发</p>
                </div>
                <div class="con_item3">
                    <img src="http://qiniu-pub.yixsu.com/one-pixel-web---cut_72.png"/>
                    <p style="font-size: 1em">叮咚网页端页面设计</p>
                    <p style="font-size: 0.7em;color: #666">企业官方网站的个性化定制设计</p>
                </div>
                <div class="con_item3" >
                    <img src="http://qiniu-pub.yixsu.com/one-pixel-web---cut_73.png"/>
                    <p style="font-size: 1em">企业云管理平台</p>
                    <p style="font-size: 0.7em;color: #666">针对考勤、日志等开发的企业管理app</p>
                </div>
                <div class="con_item3">
                    <img src="http://qiniu-pub.yixsu.com/one-pixel-web---cut_74.png"/>
                    <p style="font-size: 1em">生活社区app</p>
                    <p style="font-size: 0.7em;color: #666">一站式小区生活类app</p>
                </div>
                <div class="con_item3" style="margin-right: 0">
                    <img src="http://qiniu-pub.yixsu.com/one-pixel-web---cut_75.png"/>
                    <p style="font-size: 1em">M-comics手机端</p>
                    <p style="font-size: 0.7em;color: #666">英文版漫画app手机端</p>
                </div>
                <div class="con_item3" >
                    <img src="http://qiniu-pub.yixsu.com/one-pixel-web---cut_80.png"/>
                    <p style="font-size: 1em">安卓手机主题设计</p>
                    <p style="font-size: 0.7em;color: #666">安卓市场个性化手机主题设计</p>
                </div>
                <div class="con_item3" >
                    <img src="http://qiniu-pub.yixsu.com/one-pixel-web---cut_81.png"/>
                    <p style="font-size: 1em">微学读书共享app</p>
                    <p style="font-size: 0.7em;color: #666">针对读书的分享软件,包括朋友圈和商城等</p>
                </div>
                <div class="con_item3">
                    <img src="http://qiniu-pub.yixsu.com/one-pixel-web---cut_82.png"/>
                    <p style="font-size: 1em">企业管理后台</p>
                    <p style="font-size: 0.7em;color: #666">web端企业管理后台,功能强大</p>
                </div>
                <div class="con_item3" style="margin-right: 0">
                    <img src="http://qiniu-pub.yixsu.com/one-pixel-web---cut_83.png"/>
                    <p style="font-size: 1em">社区网站设计</p>
                    <p style="font-size: 0.7em;color: #666">基于公司内部的社区网站</p>
                </div>
                <div class="clear"></div>
            </div>

            <img id="guanyu" class="title_line" src="http://qiniu-pub.yixsu.com/one-pixel-web---cut_88.png"/>
            <div class="block">
                <p  style="margin-bottom: 3%">壹像素工作室是我们努力用心打造的全新品牌。我们希望通过专业的服务使更多客户达成目标。我们有比大公司更加亲近的工作态度，有比小公司更专业的服务水平。用技术赢得市场，以用心取得信誉，我们竭诚为广大客户提供优质、高效、快捷的服务。期待你的到来。</p>
                <img width="100%" src="http://qiniu-pub.yixsu.com/one-pixel-web---cut_91.png"/>
            </div>

            <img id="lianxi" class="title_line" src="http://qiniu-pub.yixsu.com/one-pixel-web---cut_94.png"/>

            <div class="block">
                <img width="10%" src="http://qiniu-pub.yixsu.com/one-pixel-web---cut_97.png"/>
                <div style="margin-left: 3%;width: 40%;overflow:hidden;display: inline-block">
                    <p>邮箱:178340042@qq.com</p>
                    <p>手机:13567498217</p>
                    <p>QQ:178340042</p>
                    <p>微信:左方扫一扫</p>
                </div>
                <div style="display: inline-block;height: 100px;width: 1px;background-color: #999"></div>
                <img width="30%" style="float:right;" src="http://qiniu-pub.yixsu.com/one-pixel-web---cut_101.png"/>
            </div>

            <p class="bottom"><a href="http://www.beian.miit.gov.cn" target="_blank">浙ICP备18030959号-1</a></p>

        </div>
    </div>
</template>

<script>

    export default {
        data(){
            return {
                searchBarFixed:'display:none'
            }
        },
        components: {

        },
        created(){
        },
        mounted(){
            window.addEventListener('scroll', this.handleScroll)
        },
        methods: {
            goAnchor(selector) {

                var anchor = this.$el.querySelector(selector);

                document.documentElement.scrollTop = anchor.offsetTop;
            },
            handleScroll () {
                var scrollTop = window.pageYOffset || document.documentElement.scrollTop || document.body.scrollTop
                var offsetTop = document.querySelector('#nav').offsetTop
                if (scrollTop > offsetTop) {
                    this.searchBarFixed = 'display:block'
                } else {
                    this.searchBarFixed = 'display:none'
                }
            },
        },
    }
</script>

<style lang="less">
    @import '../style/mixin';
    *{
        padding: 0;
        margin: 0;
    }
    .clear{
        clear: both;
    }
    .top{
        max-height: 950px;
    }
    .top, .body{
        width: 100%;
    }
    .top_bg{
        width: 100%;
    }
    .top .content{
        width: 100%;
        position: absolute;
        /*left: 20.5%;*/
        z-index: 2;
        top: 0;
    }
    .logo{
        margin: 0 auto;
        margin-top: 3%;
        width: 10%;
        display: block;
    }
    .nav{
        width: 59%;
        margin: 0 auto;
        margin-top: 4%;

    }
    .nav .item{
        float: left;
        text-align: center;
        width: 14%;
        color: #ffffff;
        font-size: 1em;
    }
    .nav .item a{
        color: #fff;
    }

    .title_line{
        width: 80%;
        margin: 4% auto;
        display: block;
    }
    .sub_title{
        width: 30%;
        margin: 2% auto;
        display: block;
    }

    .block {
        width: 60%;
        margin: 0 auto;
    }
    .block .con_item{
        width: 12.6%;
        margin-right: 4.8%;
        float: left;
        text-align: center;

    }

    .block .con_item img{
        width: 50%;
        margin-left: 8%;
    }
    .block .con_item2{
        width: 28.3%;
        margin-right: 7.5%;
        float: left;
        margin-top: 2%;
        height: 250px
    }
    .block .con_item2 img{
        width: 100%;
    }

    .block .con_item3{
        width: 22%;
        margin-right: 4%;
        float: left;
        margin-top: 2%;
        height: 250px
    }
    .block .con_item3 img{
        width: 100%;
        max-height: 200px;
    }

    .bottom{
        text-align: center;
        margin-top: 20px;
        background: #999;

    }
    .top2{
        position: fixed;
        top: 0;
        z-index: 9;
        background: #fff;
        width: 100%;
        border-bottom: 1px solid #999;
        padding-bottom: 5px;
    }

</style>
