# 示例

---




## single item

````iframe
<link rel="stylesheet" href="../slick/slick.css" />
<div class="slider single-item">
					<div><h3>1</h3></div>
					<div><h3>2</h3></div>
					<div><h3>3</h3></div>
					<div><h3>4</h3></div>
					<div><h3>5</h3></div>
					<div><h3>6</h3></div>
				</div>

<script>
seajs.use(['index','jquery'],function(Slicker,$){
    console.log(Slicker);
    new Slicker('.single-item');
    //$('.single-item').slick();
});
</script>
````
