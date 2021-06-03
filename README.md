<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>金立手机</title>
    <style>
      * {
        margin: 0;
        padding: 0;
      }
      .w-80 {
        width: 80%;
        margin: 0 auto;
      }
      .userRegList {
        height: 30px;
        line-height: 30px;
        margin-top: 10px;
        margin-bottom: 30px;
      }
      .regAndLog {
        display: flex;
        list-style: none;
        float: right;
        font-size: 12px;
        color: #9cadb7;
      }
      .regAndLog > li {
        float: left;
        margin-left: 10px;
      }
      .regAndLog > li > a {
        text-decoration: none;
        color: #9cadb7;
      }
      .regAndLog > li > a.font-red {
        color: #f00;
      }
      .d-flex {
        display: flex;
        width: 100%;
        border-bottom: 2px solid #e1e1e2;
        justify-content: space-between;
        align-items: center;
      }
      .nav {
        width: 300px;
      }
      .nav .navList {
        display: flex;
        justify-content: space-between;
      }
      .list-style-none {
        list-style: none;
      }
      .list-style-none .text {
        color: #999;
        text-decoration: none;
      }
      .searchBtn {
        outline: none;
        padding-left: 10px;
		margin-bottom: 10px;
      }
      .logo {
        position: relative;
        bottom: 30px;
      }
      .start-pro {
        width: 100%;
		
      }
      .start-pro-title {
        text-align: center;
        margin: 30px 0;
		color: #999;
      }
	  .pro-list{
		  width:100%;
		  display: flex;
		  justify-content:center;
		  list-style: none;
	  }
	  .host-pro{
		  padding-bottom: 40px;
		  border-top:1px solid transparent ;
		  background: #E1E1E2;
	  }
	  .more{
		  display: flex;
		  justify-content: flex-end;

	  }
	  .more>a{
		  color: #999999;
		  text-decoration: none;
	  }
	  .host-pro-list{
		  display: flex;
		  justify-content: space-between;
	  }
	  .big-img{
		  width: 24.5%;
	  }
	.small-img{
		width: 75%;
		display: flex;
		justify-content: space-between;
		flex-wrap: wrap;
	}
	.mb-2{
		margin-bottom: 2px;
	}
.small-pro-item{
	background: #fff;
	width: 33%;
	
}
.small-pro-title{
	text-align: center;
	font-weight: 700;
	color: #000;
}
.small-pro-text{
	text-align: center;
	color: #999;
}
.small-pro-price{
	text-align: center;
	color: #f99;
}
.host-small-img{
	width:100%;
	display: flex;
	justify-content: space-between;
	flex-wrap: wrap;
	margin:0 auto;
}
.footer{
	margin-top: 10px;
}
.ppdongtai{
	display: flex;
	justify-content: space-between;

}
.pptitle{
	margin: 30px 0;
	text-align: center;
}
.shouhou{
	background-color: #ffffff;
	width: 100%;
	margin-top: 150px;
	margin-bottom: 10px;
}
.shouhou-4{
	display: flex;
	width: 60%;
	justify-content: space-between;
	flex-wrap: wrap;
	margin:0 auto;
	text-align: center;
}
.four{
		float:left;	
}
.blue1{
	text-align:center;
	float:right;
	color: #006fa6;
}
.last{
	background-color: #ffffff;
	margin-top: 100px;
	margin-bottom: 100px;
}
.last-6{
	display: flex;
	justify-content: space-between;
	flex-wrap: wrap;
	margin top:50px;
	margin:0 auto;
	width: 60%;
}
.small_text{
	text-align: left;
	color: #ff5500;
	height:30px;
}
.text_1{
	text-align: left;
	color: #006fa6;
	height:30px;	
}
.f1{
position: fixed;
/*固定定位*/
right: 0;
bottom:50%;
}
    </style>
  </head>
  <body>
    <div class="container">
      <div class="w-80">
        <!-- 顶部用户注册 -->
        <div class="userRegList">
          <ul class="regAndLog">
            <li><a href="#" class="font-red">amigo账号登录</a></li>
            <li style="font-size: 12px">|</li>
            <li><a href="#"  class="font-red" >原账号登录</a></li>
            <li style="font-size: 12px">|</li>
            <li><a href="#">注册</a></li>
            <li><a href="#">购物车</a></li>
          </ul>
        </div>
        <!-- LOGO及导航部分 -->
        <div class="d-flex">
          <!-- LOGO -->
          <div class="logo"><img src="img/logo.jpg" ></div>
          <!-- 导航 -->
          <div class="nav">
            <ul class="navList list-style-none">
              <li><a href="#" class="text">首页</a></li>
              <li><a href="#" class="text">手机</a></li>
              <li><a href="#" class="text">配件</a></li>
              <li><a href="#" class="text">服务</a></li>
              <li><a href="#" class="text">下载</a></li>
              <li><a href="#" class="text">amigoOS</a></li>
            </ul>
          </div>
          <!-- 搜索 -->
          <div class="searchStyle">
            <input
              class="searchBtn"
              type="text"
              placeholder="请输入你想要的商品"
            />
          </div>
        </div>
      </div>
      <div class="projuct w-80">
        <div class="start-pro">
          <h1 class="start-pro-title">明星产品</h1>
          <ul class="pro-list">
            <li><img width="100%" height="100%" src="img/star1.jpg" ></li>
            <li><img width="100%" height="100%" src="img/star2.jpg" ></li>
		  	<li><img width="100%" height="100%" src="img/star3.jpg" ></li>
          </ul>
        </div>
      </div>
	  <div class="host-pro">
	  	<div class="host-pro-title">
	  		<h1 class="start-pro-title">热卖推荐</h1>
	  	</div>
		<div class="more w-80">
			<a href="#">
				...更多
			</a>
		</div>
		<div class="host-pro-list w-80">
			<div class="big-img">
					<img width="100%" height="100%" src="img/hot1.jpg" >
			</div>
			<div class="small-img">
				<div class="small-pro-item mb-2">
					<img width="100%" src="img/fu-cen1.jpg" >
					<h4 class="small-pro-title">金立K3</h4>
					<p class="small-pro-text">5000mAh大电池，微Q八开</p>
					<p class="small-pro-price">¥999</p>
				</div>
				<div class="small-pro-item mb-2">
					<img width="100%" src="img/fu-cen2.jpg" >
					<h4 class="small-pro-title">S10C</h4>
					<p class="small-pro-text">1600万柔光自拍</p>
					<p class="small-pro-price">¥1399</p>
				</div>
				<div class="small-pro-item mb-2">
					<img width="100%" src="img/fu-cen3.jpg" >
					<h4 class="small-pro-title">大金刚2</h4>
					<p class="small-pro-text">六寸全面屏</p>
					<p class="small-pro-price">¥1799</p>
				</div>
				<div class="small-pro-item">
					<img width="100%" src="img/fu-cen6.jpg" >
					<h4 class="small-pro-title">金刚3</h4>
					<p class="small-pro-text">5000mAh大电池，微Q开</p>
					<p class="small-pro-price">¥2199</p>
				</div>
				<div class="small-pro-item">
					<img width="100%"  src="img/fu-cen5.jpg" >
					<h4 class="small-pro-title">金立S6 plus</h4>
					<p class="small-pro-text">6020mAh超级续航、骁龙八核处理器</p>
					<p class="small-pro-price">¥2199起</p>
				</div>
				<div class="small-pro-item">
					<img width="100%"  src="img/fu-cen8.jpg" >
					<h4 class="small-pro-title">金立S9</h4>
					<p class="small-pro-text">双摄柔光自拍、5.5英寸1080P高清屏</p>
					<p class="small-pro-price">¥1699</p>
				</div>
			</div>
		</div>
	  </div>
	  <div class="host-pro">
	  	<div class="host-pro-title">
	  		<h1 class="start-pro-title">热卖推荐</h1>
	  	</div>
	  		<div class="more w-80">
	  			<a href="#">
	  				...更多
	  			</a>
	  		</div>
	  		<div class="host-pro-list w-80">
	  			
	  			<div class="host-small-img">
	  				<div class="small-pro-item mb-2">
	  					<img width="100%" src="img/pr1.jpg" >
	  					<h4 class="small-pro-title">线控自拍杆</h4>
	  					<p class="small-pro-text">迷你携带，线控美拍</p>
	  					<p class="small-pro-price">¥999</p>
	  				</div>
	  				<div class="small-pro-item mb-2">
	  					<img width="100%" src="img/pr2.jpg" >
	  					<h4 class="small-pro-title">USB充电器</h4>
	  					<p class="small-pro-text">高速传输</p>
	  					<p class="small-pro-price">¥999</p>
	  				</div>
	  				<div class="small-pro-item mb-2">
	  					<img width="100%" src="img/pr3.jpg" >
	  					<h4 class="small-pro-title">旅行充电器</h4>
	  					<p class="small-pro-text">高速充电</p>
	  					<p class="small-pro-price">¥999</p>
	  				</div>
	  				<div class="small-pro-item">
	  					<img width="100%" src="img/pr4.jpg" >
	  					<h4 class="small-pro-title">快充充电器</h4>
	  					<p class="small-pro-text">高速充电</p>
	  					<p class="small-pro-price">¥999</p>
	  				</div>
	  				<div class="small-pro-item">
	  					<img width="100%" src="img/pr5.jpg" >
	  					<h4 class="small-pro-title">HiFi耳机</h4>
	  					<p class="small-pro-text">HiFi魔音，震撼享受</p>
	  					<p class="small-pro-price">¥999</p>
	  				</div>
	  				<div class="small-pro-item">
	  					<img width="100%" src="img/pr6.jpg" >
	  					<h4 class="small-pro-title">贴膜</h4>
	  					<p class="small-pro-text">高清透光防油污</p>
	  					<p class="small-pro-price">¥999</p>
	  				</div>
	  			</div>
	  		</div>
	  </div>
	  <div class="footer w-80">
		  	<h1 class="pptitle">品牌动态</h1>
	  	<div class="ppdongtai">
	  		<div class="ppimg">
	  			<img width="100%" src="img/fu.jpg" >
	  		</div>
			<div class="ppimg">
				<img width="100%" src="img/shi1.jpg" >
			</div>
			<div class="ppimg">
				<img width="100%" src="img/shi2.jpg" >
			</div>
	  	</div>
	  </div>
    </div>

	<div class="shouhou">
		<div class="shouhou-4">
			<div class="four">
				<div class="four">
				<img src="img/s1_03.jpg">
				</div>
				<p class="blue1">7天<br/>退货保障</p>
			    
			</div>
			<div class="four">
				<div class="four">
				<img src="img/s2_03.jpg">
				</div>
				<p class="blue1">30天<br/>换货承诺</p>
			
			</div>
			<div class="four">
				<div class="four">
				<img src="img/s3_03.jpg">
				</div>
				<p class="blue1">99元起<br/>全场免运费</p>
			    
			</div>
			<div class="four">
				<div class="four">
				<img src="img/s4_03.jpg">
				</div>
				<p class="blue1">579家<br/>售后服务点</p>
			    
			</div>
		</div>		
	</div>
<HR style="border:1 dashed #332a3f" width="100%" color=#987cb9 SIZE=1>
	<div class="last">
		<div class="last-6">
			<div  class="last-text">
				<h3 class="small_text">关于金立</h3>
				<p  class="text_1">企业荣誉</p>
				<p  class="text_1">金立体验店</p>
				<p  class="text_1">专业代理商</p>
				<p  class="text_1">加入金立</p>
				<p  class="text_1">联系我们</p>
				<p  class="text_1">服务商需求</p>
			</div>
			<div  class="last-text">
				<h3 class="small_text">新闻资讯</h3>
				<p  class="text_1">公司新闻</p>
				<p  class="text_1">媒体报道</p>
				<p  class="text_1"></p>
				<p  class="text_1"></p>
				<p  class="text_1"></p>
				<p  class="text_1"></p>
			</div>
			<div  class="last-text">
				<h3 class="small_text">购物指南</h3>
				<p  class="text_1">购物流程</p>
				<p  class="text_1">支付方式</p>
				<p  class="text_1">配送说明及费用</p>
				<p  class="text_1">订单管理</p>
				<p  class="text_1">购物常见问题</p>
				<p  class="text_1">预置应用公示</p>
			</div>
			<div  class="last-text">
				<h3 class="small_text">售后服务</h3>
				<p  class="text_1">售后政策</p>
				<p  class="text_1">售后服务网点</p>
				<p  class="text_1">上网维修</p>
				<p  class="text_1">签收须知</p>
				<p  class="text_1">物流查询</p>
				<p  class="text_1"></p>
			</div>
			<div  class="last-text">
				<h3 class="small_text">关于我们</h3>
				<p  class="text_1">新浪微博</p>
				<p  class="text_1">腾讯微博</p>
				<p  class="text_1">QQ空间</p>
				<p  class="text_1"></p>
				<p  class="text_1"></p>
				<p  class="text_1"></p>
			</div>
			<div class="last-text">
				<img src="img/erwm.jpg">
				<p  class="text_1">扫一扫关注微信</p>
			</div>	
		</div>	
	</div>		
  </body>
  <div class="f1">
	  <div class="f2">
  	<img src="./img/1-1_03.jpg" >
	 </div>
	 <div class="f2">
	<img src="./img/2-2_03.jpg" >
	</div>
	<div class="f2">
	<img src="./img/3-3_03.jpg" >
	</div>
  </div>
</html>
