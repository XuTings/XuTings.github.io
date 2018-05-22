<!DOCTYPE html>
<html>
	<head>
		<meta charset="utf-8" />
		<title>西蜴首页</title>
		<link href="css/demo.css" rel="stylesheet" type="text/css" />
		<link href="css/easyui.css" rel="stylesheet" type="text/css" />
		<link href="css/icon.css" rel="stylesheet" type="text/css" />
		<link href="css/market_Home page.css" rel="stylesheet" type="text/css"/>
		<link rel="stylesheet" href="css/goods.css"/>
        <script type="text/javascript" src="js/jquery-2.1.4.min.js"></script>
        <script src="js/jquery.animate-colors-min.js"></script>
	</head>
	<body>
		<!----------------------------------------head------------------------------------------>
		<div id="head">
			<ul class="head_left">
				<li><a href="#" onclick="logIn()">亲，请登录</a></li>
				<li><a href="#" onclick="resister()">免费注册</a></li>
			</ul>
			<ul class="head_right">
				<li><a href="seller center.html">个人中心</a></li>
				<li><a href="site map.html">网站导航</a></li>
				<li><a href="about our.html">关于我们</a></li>
			</ul>
		</div>
		
	    <!----------------------------------------logo------------------------------------------>
	    <div id="logo">
	    	<div class="logo">
	  
	    	</div>
	    	<div class="logo_left">
	    		<ul>
	    			<li style="width: 5%;border-bottom: 3px solid #000;"><a href="market_Home page.html">首页</a></li>
	    			<li><a href="mobile phones used.html">最新二手</a></li>
	    			<li><a href="lost and found.html">失物招领</a></li>
	    			<li><a href="barter.html">以物换物</a></li>
	    			<li>|</li>
	    			<li><a href="post message.html">发布闲置</a></li>
	    			<li><a href="my leave unused.html">我的闲置</a></li>
	    		</ul>
	    	</div>
	    	<input class="easyui-searchbox searchbox" data-options="prompt:'请输入关键字',searcher:doSearch" style="width:300px"></input>
	    </div>
	    <!----------------------------------------tbody------------------------------------------>
	    <div style="margin-bottom: 0px;"></div>
	    <div id="tbody">
	    	<!--slideImg-->
	    	<div id="slideImg">
	    		<div class="slideImg_map">
	    			<ul>
	    				<li><a href="#">手机/数码/电脑办公</a></li>
	    				<li><a href="#">运动/健身器材</a></li>
	    				<li><a href="#">图书音像</a></li>
	    				<li><a href="#">服装</a></li>
	    				<li><a href="#">美妆/个人护理</a></li>
	    				<li><a href="#">食品</a></li>
	    				<li><a href="#">摩托/汽车/自行车</a></li>
	    				<li><a href="#">失物招领</a></li>
	    				<li><a href="#">电影票</a></li>
	    				<li><a href="#">以物换物</a></li>
	    			</ul>
	    		</div>
	    		<div class="slideImg_back">
	    			<a href="#"><img src="img/dao1.jpg"/></a>
	    			<a href="#"><img src="img/dao2.jpg"/></a>
	    			<a href="#"><img src="img/dao3.jpg"/></a>
	    			<a href="#"><img src="img/dao4.jpg"/></a>
	    			<a href="#"><img src="img/dao5.jpg"/></a>
	    		</div>
	    		<div class="slideImg_a">
	    			<ul>
	    		        <li><a href="#" onmousemove="switchImg(0)" style="background: #000;"></a></li>
	    		        <li><a href="#" onmousemove="switchImg(1)"></a></li>
	    	    	    <li><a href="#" onmousemove="switchImg(2)"></a></li>
	    		        <li><a href="#" onmousemove="switchImg(3)"></a></li>
	    		        <li><a href="#" onmousemove="switchImg(4)"></a></li>
	    	       </ul>
	    		</div>
	    	</div>
	    </div>



		<!----------------------------------------goods----------------------------------------------------------------------------------------------------------------------->

		<div class="easyui-accordion" style="width:100%">
			<a href="#" class="a_goods">
			<div class="div_goods">
				<div class="div_goods_img" style="background: url(img/一卡通.jpg) no-repeat center center;"><img src="img/1.jpg"></div>
				<div class="div_goods_content"><span>666元</span><br>
					<span>超级超级美丽好看的裙子以及很好看的衣服简直好看的不得了</span>
				</div>
			</div>
		</a>
	    <a href="#" class="a_goods">
			<div class="div_goods">
				<div class="div_goods_img" style="background: url(img/一卡通.jpg) no-repeat center center;"><img src="img/2.jpg"></div>
				<div class="div_goods_content"><span>666元</span><br>
					<span>超级超级美丽好看的裙子以及很好看的衣服简直好看的不得了</span>
				</div>
			</div>
		</a>
	    <a href="#" class="a_goods">
			<div class="div_goods">
				<div class="div_goods_img" style="background: url(img/一卡通.jpg) no-repeat center center;"><img src="img/3.jpg"></div>
				 <div class="div_goods_content"><span>666元</span><br>
				<span>超级超级美丽好看的裙子以及很好看的衣服简直好看的不得了</span></div>
			</div>
		</a>
	   <a href="#" class="a_goods">
			<div class="div_goods">
				<div class="div_goods_img" style="background: url(img/一卡通.jpg) no-repeat center center;"><img src="img/4.jpg"></div>
				 <div class="div_goods_content"><span>666元</span><br>
				<span>超级超级美丽好看的裙子以及很好看的衣服简直好看的不得了</span>
				 </div>
			</div>
		</a>

			<a href="#" class="a_goods">
			<div class="div_goods">
				<div class="div_goods_img" style="background: url(img/一卡通.jpg) no-repeat center center;"><img src="img/5.jpg"></div>
				 <div class="div_goods_content"><span>666元</span><br>
				<span>超级超级美丽好看的裙子以及很好看的衣服简直好看的不得了</span>
				 </div>
			</div>
		</a>
			<a href="#" class="a_goods">
			<div class="div_goods">
				<div class="div_goods_img" style="background: url(img/一卡通.jpg) no-repeat center center;"><img src="img/5.jpg"></div>
				 <div class="div_goods_content"><span>666元</span><br>
				<span>超级超级美丽好看的裙子以及很好看的衣服简直好看的不得了</span>
				 </div>
			</div>
		</a>
			<a href="#" class="a_goods">
			<div class="div_goods">
				<div class="div_goods_img" style="background: url(img/一卡通.jpg) no-repeat center center;"><img src="img/5.jpg"></div>
				 <div class="div_goods_content"><span>666元</span><br>
				<span>超级超级美丽好看的裙子以及很好看的衣服简直好看的不得了</span>
				 </div>
			</div>
		</a>
			<a href="#" class="a_goods">
			<div class="div_goods">
				<div class="div_goods_img" style="background: url(img/一卡通.jpg) no-repeat center center;"><img src="img/5.jpg"></div>
				 <div class="div_goods_content"><span>666元</span><br>
				<span>超级超级美丽好看的裙子以及很好看的衣服简直好看的不得了</span>
				 </div>
			</div>
		</a>
			<a href="#" class="a_goods">
			<div class="div_goods">
				<div class="div_goods_img" style="background: url(img/一卡通.jpg) no-repeat center center;"><img src="img/5.jpg"></div>
				 <div class="div_goods_content"><span>666元</span><br>
				<span>超级超级美丽好看的裙子以及很好看的衣服简直好看的不得了</span>
				 </div>
			</div>
		</a>
			<a href="#" class="a_goods">
			<div class="div_goods">
				<div class="div_goods_img" style="background: url(img/一卡通.jpg) no-repeat center center;"><img src="img/5.jpg"></div>
				 <div class="div_goods_content"><span>666元</span><br>
				<span>超级超级美丽好看的裙子以及很好看的衣服简直好看的不得了</span>
				 </div>
			</div>
		</a>
			<a href="#" class="a_goods">
			<div class="div_goods">
				<div class="div_goods_img" style="background: url(img/一卡通.jpg) no-repeat center center;"><img src="img/5.jpg"></div>
				 <div class="div_goods_content"><span>666元</span><br>
				<span>超级超级美丽好看的裙子以及很好看的衣服简直好看的不得了</span>
				 </div>
			</div>
		</a>
			<a href="#" class="a_goods">
			<div class="div_goods">
				<div class="div_goods_img" style="background: url(img/一卡通.jpg) no-repeat center center;"><img src="img/5.jpg"></div>
				 <div class="div_goods_content"><span>666元</span><br>
				<span>超级超级美丽好看的裙子以及很好看的衣服简直好看的不得了</span>
				 </div>
			</div>
		</a>
			</div>
	    <!----------------------------------------foot------------------------------------------>
	    <div id="foot">
	    	<div>
	    			<a href="about our.html">关于西蜴</a>
	    			<a href="customer service.html">联系我们</a>
	    			<a href="consociation.html">合作招商</a>
	    			<a href="feedback.html">反馈及意见</a>
	    	</div>
	    	<div>
	    		<span>公司名称：四川绵阳青鸾科技</span>
	    	</div>
			<div>
				<span>地址：四川绵阳涪城区</span>
			</div>
			<div>
				<span>联系电话：66666666</span>
			</div>
	    </div>
	    <!----------------------------------------side------------------------------------------>
	    <div id="side">
	    	<ul>
	    		<li><a href="#" onclick="scrollToTop()">顶部</a></li>
	    		<li><a href="shopping trolley.html">购物车</a></li>
	    		<li><a href="feedback.html">消息</a></li>
	    		<li><a href="#" onclick="closeSide()">关闭</a></li>
	    	</ul>
	    </div>
	    <!----------------------------------------load------------------------------------------>
	    <div id="dlg1" class="easyui-dialog" style="width:400px" data-options="closed:true,modal:true,border:'thin',buttons:'#dlg1-buttons'">
         <form id="fm" method="post" novalidate style="margin:0;padding:20px 50px">
            <h3>密码登录</h3>
            <div style="margin-bottom:10px">
                <input class="easyui-textbox" required="true" label="学 &nbsp&nbsp号:" data-options="prompt:'请输入学号',validType:'length[10,10]'" style="width:100%">
            </div>
            <div style="margin-bottom:10px">
                <input class="easyui-textbox" required="true" type="password" label="密 &nbsp&nbsp码:" data-options="validType:'length[6,16]'" style="width:100%">
            </div>
            <div style="margin-bottom:20px">
			    <input class="easyui-textbox" label="验证码:" required="ture" validType="verification['#dlg1 .get']" labelPosition="left"  style="width:50%;">
			    <a href="#" class="get" onclick="getVerification()">获取验证码</a>
		    </div>
		    <div style="margin-bottom:20px">
		    	<a href="#" onclick="" style="margin-left:20px">支付宝登录</a>
			    <a href="#" onclick="findPassword()" style="margin-left:20px">忘记密码</a>
			    <a href="#" onclick="resister()" style="margin-left:20px">免费注册</a>
		    </div>
         </form>
        </div>
        <div id="dlg1-buttons">
            <a href="javascript:void(0)" class="easyui-linkbutton c6" iconCls="icon-ok" onclick="" style="width:90px">登录</a>
            <a href="javascript:void(0)" class="easyui-linkbutton" iconCls="icon-cancel" onclick="javascript:$('#dlg1').dialog('close');" style="width:90px">取消</a>
        </div>
	    <!----------------------------------------resister------------------------------------------>
	    <div id="dlg2" class="easyui-dialog" style="width:400px" data-options="closed:true,modal:true,border:'thin',buttons:'#dlg2-buttons'">
         <form id="fm" method="post" novalidate style="margin:0;padding:20px 50px">
            <h3>注册</h3>
            <div style="margin-bottom:10px">
                <input class="easyui-textbox" required="true" label="学  &nbsp&nbsp&nbsp&nbsp&nbsp号:" data-options="prompt:'请输入学号',validType:'length[10,10]'" style="width:100%">
            </div>
            <div style="margin-bottom:10px">
                <input class="easyui-textbox" id="password" required="true" type="password" label="密&nbsp&nbsp&nbsp&nbsp&nbsp 码:" data-options="prompt:'6-16位',validType:'length[6,16]'" style="width:100%">
            </div>
            <div style="margin-bottom:10px">
                <input class="easyui-textbox" required="true" label="确认密码:" type="password" validType="equalTo['#password']" style="width:100%">
            </div>
             <div style="margin-bottom:10px">
                <input class="easyui-textbox" required="true" label="手机号码:"  validType="mobile" style="width:100%">
            </div>
		    <div style="margin-bottom:20px">
		    	<input class="easyui-textbox" label="验证码:" required="ture" validType="verification['#dlg2 .get']" labelPosition="left"  style="width:50%;">
			    <a href="#" class="get" onclick="getVerification()">获取验证码</a>
		    </div>
         </form>
        </div>
        <div id="dlg2-buttons">
            <a href="javascript:void(0)" class="easyui-linkbutton c6" iconCls="icon-ok" onclick="" style="width:90px">注册</a>
            <a href="javascript:void(0)" class="easyui-linkbutton" iconCls="icon-cancel" onclick="javascript:$('#dlg2').dialog('close');i=0;" style="width:90px">取消</a>
        </div>
	    <!----------------------------------------forget------------------------------------------>
        <div id="dlg3" class="easyui-dialog" style="width:400px" data-options="closed:true,modal:true,border:'thin',buttons:'#dlg3-buttons'">
         <form id="fm" method="post" novalidate style="margin:0;padding:20px 50px">
            <h3>找回密码</h3>
            <div style="margin-bottom:10px">
                <input class="easyui-textbox" required="true" label="学  &nbsp&nbsp&nbsp&nbsp&nbsp号:" data-options="prompt:'请输入学号',validType:'length[10,10]'" style="width:100%">
            </div>
            <div style="margin-bottom:10px">
                <input class="easyui-textbox" id="password2" required="true" type="password" label="新的密码:" data-options="prompt:'6-16位',validType:'length[6,16]'" style="width:100%">
            </div>
            <div style="margin-bottom:10px">
                <input class="easyui-textbox" required="true" label="确认密码:" type="password" validType="equalTo['#password2']" style="width:100%">
            </div>
             <div style="margin-bottom:10px">
                <input class="easyui-textbox" required="true" label="手机号码:"  validType="mobile" style="width:100%">
            </div>
		    <div style="margin-bottom:20px">
		    	<input class="easyui-textbox" label="验证码:" required="ture" validType="verification['#dlg3 .get']" labelPosition="left"  style="width:50%;">
			    <a href="#" class="get" onclick="getVerification()">获取验证码</a>
		    </div>
         </form>
        </div>
        <div id="dlg3-buttons">
            <a href="javascript:void(0)" class="easyui-linkbutton c6" iconCls="icon-ok" onclick="" style="width:90px">修改并登录</a>
            <a href="javascript:void(0)" class="easyui-linkbutton" iconCls="icon-cancel" onclick="javascript:$('#dlg3').dialog('close');i=0" style="width:90px">取消</a>
        </div>
	</body>
	<script src="js/jquery.min.js" type="text/javascript"></script>
	<script src="js/jquery.easyui.min.js" type="text/javascript"></script>
	<script type="text/javascript" src="js/main.js"></script>
	<script type="text/javascript">
		localStorage.privates=false;
		var n=0;//定时器
		function switchImg(index){
			for(m=0;m<$(".slideImg_back img").length;m++){
			   if(m==index){
			   	 $(".slideImg_back img")[index].style.display="block";
			   	 $(".slideImg_a ul li a")[index].style.background="black";
			   }else{
			   	 $(".slideImg_back img")[m].style.display="none";
			   	 $(".slideImg_a ul li a")[m].style.background="none";
			   }
			}
			n=index;
		}
		//定时器
		setInterval(function(){
			switchImg(n);
			n++;
			if(n==$(".slideImg_back img").length)   n=0;
		},5000);
	</script>
</html>
