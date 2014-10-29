# 示例

---




## single item

````iframe
<link rel="stylesheet" href="../slick/slick.css" />
<style>
	.single-item {
		width:300px;
	}
	.single-item div{
		background:blue;
		color:#fff;
	}
</style>
<div class="slider single-item">
					<div><h3>1</h3></div>
					<div><h3>2</h3></div>
					<div><h3>3</h3></div>
					<div><h3>4</h3></div>
					<div><h3>5</h3></div>
					<div><h3>6</h3></div>
				</div>
<span class="next">下一个</span>
<span class="pre">上一个</span>
<script>
seajs.use(['index','jquery'],function(Slicker,$){
    //console.log(Slicker);
    var slicker = new Slicker('.single-item',{
    	autoplay:true
    });
    console.log(slicker);
    //slicker.autoPlay();
    /*setInterval(function(){
    	slicker.next();
    },2000);*/
    //$('.single-item').slick();
});
</script>
````
