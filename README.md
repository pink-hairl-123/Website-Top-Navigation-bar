# Website-Top-Navigation-bar
guide you make a website top Navigation bar

网站万能导航栏，改一下颜色和文字，不需要的代码注释掉即可，以后要用直接放出来！

html5+css代码

<div class="aa">

        <p>西安网站建设 | 西安网站制作 | 西安网站设计 | 小程序开发 | 胸弟网络 - 网站建设十余年经验，更值得信赖！</p>

    </div>



    <div class="a1">

        <div class="a2"><img src="imgs/logo1.png" alt=""></div>

        <div class="a3">

            <p>网站建设咨询热线 :</p>

            <p>029-000000</p>

            <p>029-000000</p>

        </div>

        <div class="a4">

            <br>

            <img src="imgs/icophone.gif" alt=""><br>

            &nbsp;<img src="imgs/t2.png" alt="">

        </div>

    </div>



    <!-- 头部 -->



    <div class="b">

        <div class="b1">

            <ul>

                <li><a href="#">网站首页</a></li>

                <li><a href="#">关于我们</a>

                    <ul>

                        <li><a href="#">公司简介</a></li>

                        <li><a href="#">公司环境</a></li>

                        <li><a href="#">成熟团队</a></li>

                        <li><a href="#">合作企业</a></li>

                        <li><a href="#">公司优势</a></li>

                    </ul>

                </li>

                <li><a href="#">网站建设</a>

                    <ul>

                        <li><a href="#">成品超市</a></li>

                        <li><a href="#">基础套餐</a></li>

                        <li><a href="#">双模套餐</a></li>

                        <li><a href="#">三模套餐</a></li>

                        <li><a href="#">商城套餐</a></li>

                        <li><a href="#">营销套餐</a></li>

                    </ul>

                </li>

                <li><a href="#">成功案例</a>

                    <ul>

                        <li><a href="#">企业官网</a></li>

                        <li><a href="#">营销型网站</a></li>

                        <li><a href="#">各类商城</a></li>

                        <li><a href="#">政府 院校 协会</a></li>

                        <li><a href="#">系统开发</a></li>

                        <li><a href="#">手机网站</a></li>

                        <li><a href="#">集团网站</a></li>

                        <li><a href="#">外语网站</a></li>

                        <li><a href="#">响应式(H5)</a></li>

                    </ul>

                </li>

                <li><a href="#">建站学院</a>

                    <ul>

                        <li><a href="#">网站优化</a></li>

                        <li><a href="#">网络营销</a></li>

                        <li><a href="#">网站运营</a></li>

                        <li><a href="#">网站安全</a></li>

                        <li><a href="#">网站建设</a></li>

                    </ul>

                </li>

                <li><a href="#">服务项目</a>

                    <ul>

                        <li><a href="#">网站建设</a></li>

                        <li><a href="#">网站优化</a></li>

                        <li><a href="#">网站托管</a></li>

                        <li><a href="#">微信开发</a></li>

                        <li><a href="#">小程序</a></li>

                        <li><a href="#">相关服务</a></li>

                    </ul>

                </li>

                <li><a href="#">小程序</a></li>

                <li><a href="#">网站优化</a></li>

                <li><a href="#">挑选网站</a></li>

                <li class="b2"><a href="#">联系我们</a>

                    <ul>

                        <li><a href="#">联系方式</a></li>

                        <li><a href="#">在线留言</a></li>

                        <li><a href="#">支付方式</a></li>

                    </ul>

                </li>

            </ul>

        </div>

    </div>


    * {
    margin: 0;
    padding: 0;
    text-decoration: none;
    list-style: none;
}



body {
    height: 3000px;
}

.aa {
    width: 100%;
    height: 31px;
}

.aa p {
    width: 1200px;
    height: 31px;
    border-color: antiquewhite;
    font-size: 12px;
    color: red;
    margin: auto;
    line-height: 31px;
    font-weight: 700;
}

.a1 {
    width: 1200px;
    height: 101px;
    margin: auto;
}

.a1 .a2 {
    width: 200px;
    height: 101px;
    float: left;
}

.a1 .a4 {
    width: 35px;
    height: 101px;
    float: right;
    line-height: 31px;
}

.a3 {
    width: 187px;
    height: 101px;
    float: right;
    line-height: 33.5px;
}

.a3 p:nth-child(1) {
    color: orange;
    font-size: 12px;
}

.a3 p:nth-child(2) {
    color: red;
    font-size: 20px;
}

.a3 p:nth-child(3) {
    color: burlywood;
}

/* 完成 */

.b {
    width: 100%;
    height: 50px;
    background-color: #1e1c1d;
    position: sticky;
    top: 0;
}

.b a {
    color: white;
}

.b .b1 {
    width: 1200px;
    height: 50px;
    background-color: #1e1c1d;
    color: white;
    font-size: 18px;
    line-height: 50px;
    margin: auto;
}

.b1 li {
    float: left;
    position: relative;
}

.b1 .b2 {
    border-right: 0;
}

.b1>ul>li>a {
    display: block;
    width: 116px;
    height: 50px;
    border-right: 1px solid #3b393e;
    text-align: center;
}

.b1>ul>li>a:hover {
    background-color: red;
}

.b div>ul>li ul {
    position: absolute;
    width: 116px;
    display: none;
}

div>ul>li>ul li a {
    display: block;
    width: 116px;
    line-height: 40px;
    font-size: 14px;
    background-color: #3b393e;
    opacity: 0.6;
    text-align: center;
}

.b div>ul>li>ul>li a:hover {
    background-color: black;
    opacity: 1;
    color: red;
}

.b div>ul>li:hover ul {
    display: block;

}


/* 完成 */
