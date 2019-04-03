<!DOCTYPE html>
<html>

<head>
	<meta charset="utf-8">
	<title>Simon的个人简历</title>
	<script src="https://libs.baidu.com/jquery/1.9.1/jquery.min.js"></script>
	<style>
		* {
			margin: 0px;
			padding: 0px;
			font-family: "PingFang SC", "Hiragino Sans GB", "Microsoft YaHei", "WenQuanYi Micro Hei", sans-serif;
		}

		a {
			color: #006CCA;
			text-decoration: none;
			line-height: 50px;
		}

		#gyw,
		#zpj {
			background: #fff;
			border-radius: 8px;
			padding: 0px 10px;
			width: 74px;
			height: 60px;
			margin-top: 30px;
			box-shadow: 0px 2px 10px #006cca;
		}

		ul {
			list-style-type: none;
		}

		body {
			background: -webkit-linear-gradient(left top, #4AB5FE, #006CCA);
			background: -o-linear-gradient(bottom right, #4AB5FE, #006CCA);
			background: -moz-linear-gradient(bottom right, #4AB5FE, #006CCA);
			background: linear-gradient(bottom right, #4AB5FE, #006CCA);
			height: 6319px;
			/* width: 1920px; */
			margin: 0px auto;
		}

		.content {
			width: 1200px;
			height: 100%;
			margin: 0px auto;
			position: relative
		}

		.content .left {
			z-index: 9;
			width: 200px;
			color: #000;
			margin-top: 30px;
			padding-top: 300px;
			font-weight: 200;
			font-size: 24px;
			line-height: 70px;
			position: fixed;
		}

		.content .right {
			position: absolute;
			left: 250px;
			width: 100%;
			display: block;
			margin-top: 30px;
			color: #fff;
		}

		.content .right .tx {
			margin: 0px auto;
			height: 150px;
			width: 100%;
			position: relative;
		}

		.content .right .tx>span {
			border-radius: 50%;
			width: 100px;
			height: 100px;
			background: #fff;
			position: absolute;
			left: 50px;
			margin-left: -50px;
		}

		.content .right .tx>p {
			font-size: 12px;
			color: #fff;
			position: absolute;
			top: 88px;
			left: 28%;
			margin-left: -181px;
			text-align: center;
		}

		.content .right .zl {
			width: 100%;
			/* background: red; */
			/* position: absolute; */
			margin-top: 10px;
			height: 500px;
		}

		.title {
			font-size: 20px;
		}

		.content .right .zl .czjl {
			width: 463px;
			position: relative;
			float: left;
		}

		#dx {
			position: absolute;
			left: 160px;
			line-height: 12px;
			top: 20px;
		}

		#sx {
			position: absolute;
			left: 160px;
			line-height: 12px;
			top: 171px;
		}

		#gz_1 {
			position: absolute;
			left: 160px;
			line-height: 12px;
			top: 300px;
		}

		.czjl .t {
			width: 7px;
			background: #fff;
			border-radius: 3.5px;
			position: absolute;
			left: 125px;
		}

		.czjl>div {
			position: relative;
			margin-top: 50px;
		}

		.czjl .d {
			width: 20px;
			height: 20px;
			position: absolute;
			border-radius: 50%;
			background: #fff;
			left: 119px;
		}

		.czjl .t_1 {
			height: 20px;
		}

		.czjl .t_2 {
			height: 114px;
			top: 62px;
		}

		.czjl .t_3 {
			height: 100px;
			top: 214px;
		}

		.czjl .t_4 {
			height: 30px;
			top: 352px;
		}


		.czjl .d_1 {
			top: 30px;
		}

		.czjl .d_2 {
			top: 185px;
		}

		.czjl .d_3 {
			top: 322px;
		}

		.content .right .zl .wd {
			float: left;
			margin-left: 100px;
		}

		.content .right .zl .wd>ul {
			float: left
		}

		.content .right .zl .wd>.wd_xm>li {
			text-align: justify;
			width: 80px;
			height: 90px;
			font-size: 20px;
		}

		.content .right .zl .wd>.wd_xx {
			margin-left: 30px;
		}

		.content .right .zl .wd>.wd_xx>li {
			height: 90px;
		}

		.content .right .zl .wd>.wd_xm>li>span {
			display: inline-block;
			padding-left: 100%;
		}

		.jn {
			width: 564px;
			height: 100px;
			float: left;
		}

		.icon {
			width: 500px;
			height: 200px;
		}

		.icon>li {
			float: left;
			height: 36px;
			width: 36px;
			border: 1px solid #000;
			margin: 30px 20px 0px 50px;
			font-size: 10px;
			text-align: center;
			line-height: 30px;
		}

		.xm {
			float: left;
		}

		.xm>a {
			color: #fff;
			margin-top: 20px;
			display: block;
		}

		#aqc {
			width: 350px;
			margin-top: 20px;
			line-height: 24px;
			text-align: justify;
		}

		#zp {
			/* padding-top: 960px; */
			width: 1200px;
			overflow: hidden;
			position: absolute;
			top:1000px;
		}

		#zp>img {
			width: 1200px;
		}

		.dt {
			height: 460px;
			width: 225px;
			position: absolute;
			top: 157px;
			right: 216px;
			z-index: 9

		}
		.head {
			background:url(./img/lh.png) no-repeat;
			background-size:120px 17px;
			height: 20px;
			width: 181px;
			position: absolute;
			top: 157px;
			right: 216px;
			z-index: 9

		}

		.dt .img {
			height: 451px;
			width: 210px;
			z-index: 1;
			border-radius:26px;
		}
		.dt .dt_img li{
		display:none;
		}
	</style>
</head>

<body>
	<div class="bg">
		<div class="content">
			<ul class="left">
				<li>
					<p id="gyw"><a href="#tx">关于我</a></p>
				</li>
				<li>
					<p id="zpj"><a href="#zpj_m">作品集</a></p>
				</li>
			</ul>
			<ul class="right">
				<li id="grxx">
					<div class="tx" id="tx">
						<span></span>
						<p style="top:40px;font-size:24px;font-weight:600">Simon</p>
						<p>设计爱好者，熟悉iOS、Android设计规范，对细节追求完美</p>
					</div>
					<div class="zl">
						<div class="czjl">
							<p class="title">成长经历</p>
							<div>
								<div id="dx">
									<p>上海财经大学浙江学院</p><br>
									<p>本科-物流管理</p><br>
									<p>2012.9-2016.6</p>
								</div>
								<div class="t_1 t"></div>
								<div class="d_1 d"></div>
								<div class="t_2 t"></div>
								<div class="d_2 d"></div>
								<div id="sx">
									<p>天天快递有限公司</p><br>
									<p>实习-调度专员</p><br>
									<p>2016.6-2016.11</p>
								</div>
								<div class="t_3 t"></div>
								<div class="d_3 d"></div>
								<div id="gz_1">
									<p>浙江康宏物流有限公司、</p><br>
									<p>杭州亿晟网络科技有限公司</p><br>
									<p>物流专员、UI设计师</p><br>
									<p>2016.11-2019.3</p>
								</div>
								<div class="t_4 t"></div>
							</div>
						</div>
						<div class="wd">
							<ul class="wd_xm">
								<li>我的名字<span></span></li>
								<li>年龄<span></span></li>
								<li>籍贯<span></span></li>
								<li>居住地<span></span></li>
								<li>联系方式<span></span></li>
							</ul>
							<ul class="wd_xx">
								<li>俞齐栋</li>
								<li>25岁</li>
								<li>杭州余杭</li>
								<li>杭州余杭</li>
								<li><span></span>15757979720</li>
								<li style="margin-top:-50px;"><span></span>1120616477@qq.com</li>
							</ul>
						</div>
					</div>
					<div class="jn">
						<p class="title">职业技能</p>
						<ul class="icon">
							<li><span>PS</span></li>
							<li><span>AI</span></li>
							<li><span>AE</span></li>
							<li><span>Axure</span></li>
							<li><span>Sketch</span></li>
							<li><span>H5</span></li>
							<li><span>CSS</span></li>
						</ul>
					</div>
					<div class="xm">
						<p class="title">项目经历</p>
						<a href="http://www.aqc520.com" target="_blank">阿其车网上商城</a>
						<p id="aqc">阿其车是专注于营运货车汽车后市场的APP，运营模式是B2C
							结合O2O，项目持续半年左右，从0开始建站，参与了第一版app的修改，第二版的原型图设计，参与了网页UI的布局，以及一些线上门店的运营效果图，设计一部分公司VI宣传物料。</p>
					</div>
				</li>
			</ul>
			<div id="zp">
				<img src="./img/BM.jpg"
					alt="">
				<div class="dt" id="zpj_m">
					<ul class="dt_img">
						<li style="display:block"><img src="./img/登录@2x.jpg" alt="" class="img"></li>
						<li><img src="./img/首页@2x.jpg" alt="" class="img"></li>
						<li><img src="./img/个人中心@2x.jpg" alt="" class="img"></li>
						<li><img src="./img/电台@2x.jpg" alt="" class="img"></li>
						<li><img src="./img/设置@2x.jpg" alt="" class="img"></li>
						<li><img src="./img/播放@2x.jpg" alt="" class="img"></li>
						<li><img src="./img/歌单@2x.jpg" alt="" class="img"></li>
						<li><img src="./img/歌单列表@2x.jpg" alt="" class="img"></li>
					</ul>
				</div>
				<div class="head"></div>
			</div>
		</div>
	</div>
</body>

</html>
<script>
		$(function () {
			// 自适应li数量
			for (var i = 0; i < $('.dt_img>li').length; i++) {
				$('.dt_img>li').eq(i).attr('index', i)
			}
			// 向后滚动效果
			function tab() {
				$('.dt_img>li').fadeOut(0);
				$('.dt_img>li').eq(now).fadeIn(0);
			}
			var now = 0;
			// // 圆点功能
			// $('.banner_zsq>li').click(function () {
			// 	// 防止点击重复执行变换
			// 	if (now == $(this).index()) return;
			// 	now = $(this).index();
			// 	tab();
			// })
			// // 向后变换
			// $('.right').click(function () {
			//     now++;
			//     // 防止now的值超出li数量
			//     if (now >= $('#ul_radius>li').length) { now = 0 };
			//     tab();
			// })
			// // 向前变换
			// $('.left').click(function () {
			//     now--;
			//     // 防止now的值低于第一个li编号
			//     if (now <= -1) { now = $('#ul_radius>li').length - 1 };
			//     tab();
			// })
			// 设置定时向后变换
			var time = setInterval(function () {
				now++;
				if (now >= $('.dt_img>li').length) { now = 0 };
				tab();
			}, 5000);
			// 鼠标悬停停止自动变换
			$('.dt').hover(function () {
				clearInterval(time);
			},
				// 鼠标离开自动开始变换
				function () {
					time = setInterval(function () {
						now++;
						if (now >= $('.banner_zsq>li').length) { now = 0 };
						tab();
					}, 5000);
				})
		})
	</script>
