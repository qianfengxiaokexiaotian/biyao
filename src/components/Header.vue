<template>
	
		
    <div class="hello">
		  	
		    <div class="header_q">
			    <div class="list">
			           <input type="text" placeholder="输入你想要的商品" id="app_txt1">
			    </div>
			   
			    
		    	 <div class="header_bottom">
				    	<p>
				    		<a>推荐</a>
				    		<a>男装</a>
				    		<a>怒撞</a>
				    		<a>眼镜</a>
				    		<a>配饰</a>
				    		<a>婴童</a>
				    	</p>
		         </div>
		    </div>
		    
		    
		    <div class="lunbo">
		    	
		    	
		    	
		    	
		    	
		    	
		    	
		    	
		    	
		    	
		    	
		    	
		    </div>
		    
		    
		    
		    
		    
		    
		    
		    
		    
		    
		    
		    
		    
		    
		    
		    
		    
		    
		    
		    
		    
		    
		    
		    
		    
		    
		    
		    
		    
		    
		    
		    
		    
		    
		    
		    
		    
		    
		    
     </div>
</template>

<script>	
	
		export default {
		  name: 'common-header',
		  data () {
		    return {
		     
		    }
		  }
		}
	
</script>

<style scoped>
	
ul,li{list-style: none;}
	
	.hello{
				width: 100%;
				height: 100%;
				background: white;
				display: flex;
				position: absolute;
				align-items: center;
				justify-content: space-between;
		}
	
	
	
	.list{
			position: absolute;
			width: 100%;
			height: 3rem;
			background: white;
			display: flex;
			align-items: center;
			top: 0;
		    padding-left: 1rem;
		    padding-right: 1rem;
		    
		    
		}
	
	#app_txt1{
			position: absolute;
			width:78%;
			height: 1.8rem;
			background: #f2f2f2;
			border: none;
			text-decoration: none;
			font-size: 0.8rem;
			padding-left: 2rem;
		}
	
	
	
	.header_bottom{
			position: absolute;
			display: flex;
			justify-content: space-between;
			align-items: center;
          	width: 100%;	
          	height: 2.5rem;
          	bottom: 0;
          	background: white;
		}






	.header_bottom>p{
			text-align: center;
			align-items: auto;
			flex-direction: row;
		
		}
	.header_bottom>p>a{
			text-align: center;
			margin-left: 1.7rem;
			text-align: center;
			font-size: 1rem;
			width: 2rem;
		}
	
	
	.header_q{
			position: absolute;
			display: flex;
			height: 5.5rem;
			width: 100%;
			background: gray;
			top: 0;
		    border-bottom: 1px solid black;
		}
	
	
	
	
	
	.lunbo{
			width: 100%;
			height: 8rem;
			background: white;
			position: absolute;
			display: flex;
			justify-content: space-around;
			border-bottom: 1px solid black;
			top: 5.5rem;
	}
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
</style>