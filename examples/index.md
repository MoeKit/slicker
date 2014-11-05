# 示例

---






````iframe:1800

<h2>简陋</h2>

<link rel="stylesheet" href="../slick/slick.css" />
<style>
	.single-item {
		width:300px;
	}
	.single-item div{
		background:blue;
		color:#fff;
		text-align:center;
	}
	.single-item div h3 {
		text-align:center;
	}
</style>
<div class="slider single-item">
					<div><h3>1</h3></div>
					<div><h3>2</h3></div>
					<div><h3>3</h3></div>
					<div><h3>4</h3></div>
					<div><h3>5</h3></div>
					<div><h3>6</h3></div>

<span class="next" data-action="next">下一个</span>
<span class="pre" data-action="prev">上一个</span>
				</div>


<h2>一淘</h2>

<ul class="clearfix etao" style="width:230px;height:300px;padding:0;">
    <li style="float:left;">
        <a href="http://1111.etao.com/?spm=1002.1.18.30.apMQW0&amp;partnerid=4831" title="双11一淘到底">
            <img src="http://gtms04.alicdn.com/tps/i4/TB1AQKUGFXXXXb2XFXX9D_A6FXX-230-300.jpg" alt="双11一淘到底">
        </a>
    </li>
       <li style="float:left;">
        <a href="http://temai.etao.com/?spm=1002.1.18.31.apMQW0" title="一淘特卖">
            <img src="http://gtms01.alicdn.com/tps/i1/TB1REaIGFXXXXXgXpXXl04i7pXX-228-298.gif" alt="一淘特卖">
        </a>
    </li>  
</ul>


<style>
	.items{

	}
	.item {
		width:186px;
		height:160px;
		background-color:#4DC7A0;
		margin-right:10px;
	}
	.item h4 {
		color:#fff;
		font-weight:400;
		font-size:20px;
		font-family:"Lato","Helvetica Neue","Helvetica",Helvetica,Arial,sans-serif;
		text-align:center;
	}
</style>

<h2>多图</h2>

<div class="items">
    <div class="item"><h4>1</h4></div>
    <div class="item"><h4>2</h4></div>
    <div class="item"><h4>3</h4></div>
    <div class="item"><h4>4</h4></div>
    <div class="item"><h4>5</h4></div>
    <div class="item"><h4>6</h4></div>
    <div class="item"><h4>7</h4></div>
    <div class="item"><h4>8</h4></div>
    <div class="item"><h4>9</h4></div>
    <div class="item"><h4>10</h4></div>
    <div class="item"><h4>11</h4></div>
    <div class="item"><h4>12</h4></div>
    <p style="text-align:center;">    
	    <a href="#" data-action="prev">prev</a>
	    <a href="#" data-action="next">next</a>
    </p>
</div>




<h2>文字垂直滚动通告</h2>

<ul class="demo4">
	<li>白雪 阳光下泡沫1最近加入本栈</li>
	<li>所有的红包以及微信活动请来这边,切勿私自发帖,谢谢合作 </li>
	<li>京东30-20券，QQ钱包新人绑卡专享！详解</li>
	<li>10本装 广博 软抄 笔记本 A5 26页 包邮</li>
	<li>曼秀雷敦 复方薄荷脑鼻用吸入剂 1.5元包邮手慢无</li>
</ul>


<h2>文字水平滚动通告</h2>
<style>
	.demo4,.demo5 {
		width:500px;
		border:1px dashed #ececec;
		padding-left:0;
		font-size:12px;
	}
</style>
<ul class="demo5">
	<li>白雪 阳光下泡沫1最近加入本栈</li>
	<li>所有的红包以及微信活动请来这边,切勿私自发帖,谢谢合作 </li>
	<li>京东30-20券，QQ钱包新人绑卡专享！详解</li>
	<li>10本装 广博 软抄 笔记本 A5 26页 包邮</li>
	<li>曼秀雷敦 复方薄荷脑鼻用吸入剂 1.5元包邮手慢无</li>
</ul>




<script>
seajs.use(['index','jquery'],function(Slicker,$){
    //console.log(Slicker);
    var slicker = new Slicker('.single-item',{
    	autoplay:true,
    	dots: true,
    	dotsClass: 'slick-dots-wrap',
    	fade: false,
    	vertical: false
    });
    console.log(slicker);
    //slicker.autoPlay();
    /*setInterval(function(){
    	slicker.next();
    },2000);*/
    //$('.single-item').slick();

    new Slicker('.etao',{
    	slide:'li',
    	autoplay:true,
    	dots: true,
    	fade:true
    });

    new Slicker('.items',{
    	dots:true,
    	slidesToShow:5,
    	slidesToScroll:4
    });

    new Slicker('.imgs',{
    	slide:'img',
    	dots:true,
    	slidesToShow:5,
    	slidesToScroll:4
    });

    new Slicker('.demo4',{
    	slide:'li',
    	autoplay:true,
    	vertical:true
    });

    new Slicker('.demo5',{
    	slide:'li',
    	autoplay:true,
    	speed:200
    });
});
</script>
````



